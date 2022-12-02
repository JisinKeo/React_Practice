리액트를 이용한 작은 프로젝트


url : https://jisinkeo.github.io/React_Practice/


<h3>관련 개념 정리</h3>

<b>JSX</b>

JavaScript + XML

JavaScript에 HTML태그를 끼얹은 문법
HTML 태그 안에서 중괄호를 사용해서 JS를 쓸 수 있다.

const count = 1;
const title = < h1>{count}번째 고양이</ h1>;

위 title 변수에 담은 h1 태그는 리액트 엘리먼트라고 부른다.

<b>Babel</b>

최신 문법을 브라우저가 이해할 수 있는 JavaScript로 통역

브라우저는 JSX를 이해하지 못한다.

<b>컴포넌트</b>

여기저기 재사용 가능한 UI 코드 조각

<b>상태</b>

컴포넌트 안에서 자유롭게 변경할 값이 필요할 때

useState함수로 상태를 추가할 수 있다.

const [상태명, 상태변경함수명] = React.useState(초기값)

컴포넌트 안에서 만들 수 있다.

<b>리스트</b>

배열로 반복되는 UI 그리기

웹사이트를 만들 때 정말 많이 쓴다.
배열에서 map을 돌면서 리액트 UI를 반환한다.

<b>폼</b>

사용자 입력 다루기

사용자 입력값을 직접 다루기 위해 value를 상태로 관리한다.

<b>로컬스토리지</b>

리액트 문법 X, 브라우저 기능 O

브라우저에 데이터 저장하기

간단한 데이터 저장이 필요할 때는 localStorage를 사용한다.