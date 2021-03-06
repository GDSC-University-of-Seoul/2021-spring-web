
# 1. Web과 Web Browser의 동작원리

## 1-1. 웹의 동작 원리

사용자가 사용하는 웹 페이지는 웹 서버에서 관련 데이터를 가져와 웹 브라우저를 통해 사용자에게 제공되는 형태로 이루어집니다.
그렇다면 웹은 어떻게 찾으려는 정보가 저장된 웹 서버에 정확히 접근하고 어떻게 데이터에 대한 요청(Request)과
반응(Response)을 전송할 수 있을까요?

사용자가 브라우저를 통해 찾고 싶은 웹 페이지의 URL을 입력하면 다음의 과정을 거쳐 사용자가 원하는 웹 페이지가 출력됩니다.

1. 사용자가 웹 페이지의 URL의 도메인 네임에 기반해 DNS 서버에서 도메인 네임을 IP 주소로 변환합니다.
2. 웹 페이지 URL 정보와 IP 주소를 통해 HTTP 프로토콜을 사용하여 HTTP 요청(Request) 메세지를 생성합니다.
3. HTTP 요청 메세지는 TCP 프로토콜과 네트워크(인터넷)를 통해 웹 서버측으로 전송됩니다.
4. 웹 서버측 HTTP 를 통해 요청 메세지에서 URL 정보로 추출합니다.
5. 웹 서버에서 URL 정보를 기반으로 해당하는 데이터를 검색한 후 HTTP 프로토콜을 사용해
   HTTP 응답(Response) 메세지를 생성한 다음 사용자 측으로 전송합니다.
6. 웹 브라우저는 응답 메세지에 저장된 데이터를 통해 웹 페이지를 렌더링하여 사용자에게 제공합니다.

> - HTTP : 클라이언트와 서버가 서로 통신할 수 있기 위한 통신 규약
> - DNS : URL의 도메인 네임을 통해 IP 주소로 변환하는 서버
> - TCP : 네트워크에서 데이터를 전달하기 위한 통신 규약

## 1-2. 웹 브라우저 기본 구조

웹 브라우저는 웹 서버와 양방향으로 통신하고 HTML 문서나 파일을 출력하는 GUI 기반의 응용 소프트웨어입니다.
웹 브라우저를 통해 사용자는 데이터 요청 메세지를 손쉽게 작성할 수 있고 웹 서버에서 전송받은 데이터에
기반해 웹 페이지를 렌더링하여 요청한 정보를 손쉽게 확인할 수 있습니다.

브라우저는 기본적으로 위와 같은 구조로 이루어져 있습니다.

- 사용자 인터페이스 : 사용자에게 요청한 페이지를 보여주는 영역
- 브라우저 엔진 : 사용자 인터페이스와 렌더링 엔진 사이의 동작을 제어
  - Webkit : 애플에서 제작한 레이아웃 엔진 (Safari)
  - Gecko : 모질라 재단에서 제작한 레이아웃 엔진 (Firefox)
  - Blink : Webkit에서 파생된 레이아웃 엔진 (Chrome, Opera)
- 렌더링 엔진 : 전달받은 데이터에 기반해 웹 페이지를 렌더링
- 통신 : 웹 서버와의 양방향 통신을 위해 HTTP를 통한 네트워크 호출
- 자바스크립트 해석기 : 자바스크립트 코드를 해석하고 실행
  - 스파이더 몽키 (FireFox)
  - V8 (Chrome)
  - Webkit (Safari)
- UI 백엔드 : 웹 요소에 기본 스타일을 적용하는 UI 장치
- 자료 저장소 : 브라우저에서 사용하는 데이터를 저장하는 계층 ex) 쿠키

## 1-3. 웹 브라우저 렌더링 동작

웹 브라우저의 렌더링은 요청 받은 내용을 브라우저 화면에 표시하는 작업입니다. 이를 위해 렌더링 엔진은 웹 서버에서
전달받은 HTML, CSS 문서를 파싱한 후 DOM 트리에 파싱한 내용을 반영합니다. DOM 트리가 업데이트되는 동안 요소를
표시할 순서와 문서의 시각적인 구성 요소로 올바른 순서로 내용을 그려내기 위해 렌더 트리를 구축합니다.

상세한 동작 과정은 다음과 같습니다.

- 1. HTML/CSS 파싱 : 파서를 통해 HTML/CSS 문서를 파싱하여 웹 페이지의 구조와 적용할 스타일을 설정합니다.
- 2. DOM 트리 구축 : 파싱한 HTML 정보를 기반으로 DOM 트리를 구축합니다.
- 3. 렌더 트리 구축 : DOM 트리에서 렌더링할 요소들을 표시합니다.
- 4. 렌더 트리 배치 : 렌더 트리의 요소들에 대한 크기와 위치 정보를 계산
- 5. 렌더 트리 그리기 : 렌더 트리 탐색 후 렌더러의 paint 메서드를 호출합니다. 그리기에는 UI 백엔드의 기본 요소를 사용합니다.

<참고 자료>

1. [TCP SCHOOL.com - 웹의 동작 원리](http://www.tcpschool.com/webbasic/works)
2. [MDN Web Docs - 웹의 동작 방식](https://developer.mozilla.org/ko/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
3. [Wikipedia - 웹 브라우저](https://ko.wikipedia.org/wiki/%EC%9B%B9_%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80)
4. [Naver D2 - 브라우저는 어떻게 동작하는가?](https://d2.naver.com/helloworld/59361)

# 2. Redux/MobX/Context API를 통한 React 상태 관리

## 2-1. 상태 관리 라이브러리

React 에서는 **컴포넌트 내부의 데이터를 관리**하기 위해 '상태(state)'라는 개념을 도입하여 사용하고 있습니다.
컴포넌트의 상태를 관리하기 위해서 가장 간단히 사용할 수 있는 방법은 `useState`나 `useReducer` 와 같은
상태관리 Hooks을 사용하는 것입니다.

하지만 프로젝트의 규모가 커지게 되면 컴포넌트의 개수가 많아지기 때문에 **관리해야하는 상태의 개수가 점점 늘어나게 됩니다.**
또한 **컴포넌트의 로직이 복잡해지면서** State 관리 동작과 컴포넌트의 controller 동작을 함께 관리하기 어려워집니다.
이러한 문제를 해결하기 위해 상태 관리 라이브러리가 탄생하게 되었습니다. 현재까지 사용되고 있는 상태 관리 라이브러리는
Redux, MobX, Context API 등이 있고 최근 떠오르고 있는 강자로 Recoil 이 있습니다.
이번 포스팅에서는 Redux, MobX, Context API 에 대해 알아보고 각각의 라이브러리에 어떠한 장점이 존재하는지 알아보겠습니다.

## 2-2. Redux

### Redux 소개

Redux는 현재 가장 많이 사용되고 있는 상태 관리 라이브러리입니다. Redux를 사용하면 컴포넌트의 상태들을 전역적으로 관리할 수 있기
때문에**상태에 대한 파일을 따로 관리**할 수 있습니다. 또한 기존에 컴포넌트 간에 상태를 공유하기 위해서는 props를 통해
여러 컴포넌트를 거쳐가면서 상태를 전달하였지만 Redux를 사용하면 여러 개의 컴포넌트를 거치지 않고 서로 연관된 컴포넌트끼리만
상태를 전달할 수 있습니다. 또한 `redux-thunk`나 `redux-saga`와 같은 **미들웨어를 통해 기능을 확장**해나가기
유용합니다.

### Redux 구성

Redux는 `useReducer` 와 유사하게 액션, 리듀서, 스토어를 통해 상태를 관리합니다. 각 역할을 살펴보면 액션(Action)은
상태 변경을 설명하는 정보, 스토어(Store)는 모든 상태와 리듀서를 포함하여 관련된 함수를 저장하는 저장소, 리듀서(Reducer)는
액션에 기반해 상태를 변경하는 함수입니다. 이후 컴포넌트는 `useSelector` 와 같은 Hooks을 사용해 스토어를
구독(Subscribe)하여 저장된 상태값에 접근할 수 있습니다.

### Redux 동작 방식

1. 웹 페이지에서 사용자에 의해 특정 이벤트가 발생하면 이벤트와 관련된 액션 객체를 스토어로 전송(dispatch)합니다.
2. 스토어는 액션 객체에 기반해 관련된 리듀서 동작을 실행합니다.
3. 리듀서에 의해 상태값을 갱신합니다.
4. 상태값이 변경되었으므로 웹 페이지에서 리렌더링을 수행하여 변경된 상태를 사용자에게 제공합니다.

## 2-3. MobX

### MobX 소개

MobX는 Redux와 더불어 인기있는 상태 관리 라이브러리입니다. Redux와 마찬가지로 React에 종속되지 않은 라이브러리로
MobX 단일로 사용할 수도 있고 React 이외에 Vue, Angular 등이랑 함께 사용할 수 있습니다.
**MobX는 클래스형 컴포넌트를 기준으로 작성**되어있기 때문에 객체지향적이지만 Hooks와 연계하여 사용하기 위해서는 추가적인
모듈이 필요하다는 단점 또한 존재합니다. 이외에도 MobX는 **불변성을 유지할 필요없이** state를 관리할 수 있다는 장점이 존재합니다.

### MobX 구성

MobX는 컴포넌트를 관찰할 상태(Observable State), 기존의 상태값과 연산에 기반하여 만들어지는 값인
파생(Derivation), 상태의 변화에 따른 부가적인 변화인 반응(Reaction), 마지막으로 상태를 변경시키는 액션(Action)으로
구성되어 상태를 관리합니다.

### MobX 동작 방식

1. 특정 이벤트에 의해 이벤트와 관련된 액션이 발생합니다.
2. 액션에 의해 상태가 변화합니다.
3. 상태가 변화하면 상태를 관찰하고 있는 동작이나 연산들을 수행하고 결과를 반환합니다.

## 2-3. Context API

### Context API 소개

Context는 React 내에서 **전역적으로 데이터를 공유**할 수 있도록 고안된 방법입니다. Context는 React 라이브러리에서
제공되는 기능이기 때문에 **추가적인 모듈 설치가 필요하지 않습니다.** 전역적으로 데이터를 공유할 수 있다는 특징을 이용하여 상태값을
여러 컴포넌트를 거치지 않고 연관된 컴포넌트에 전달할 수 있기 때문에 손쉽게 상태 관리를 수행할 수 있습니다.
하지만 Context를 선언한 **부모 컴포넌트가 렌더링 되면 Context를 상속받는 하위 컴포넌트가 불필요하게 리렌더링 되는 문제점**이
존재하기 때문에 계속해서 업데이트가 발생하는 환경에는 적합하지 않습니다.

<참고자료>

1. [Redux 공식 문서 - Redux 소개](https://ko.redux.js.org/tutorials/fundamentals/part-1-overview)
2. [야무의 React 러닝 가이드 - Redux 라이브러리](https://xn--xy1bk56a.run/react-master/lecture/rd-redux.html#redux-%E1%84%89%E1%85%B3%E1%84%90%E1%85%A9%E1%84%8B%E1%85%A5-%E1%84%80%E1%85%AE%E1%84%8C%E1%85%A9)
3. [벨로퍼트와 함께하는 모던 리액트 - 리덕스 모듈 만들기](https://react.vlpt.us/redux/04-make-modules.html)
4. [MobX 공식 문서 - MobX 소개](https://mobx.js.org/getting-started)
5. [velopert.log - MobX 시작하기](https://velog.io/@velopert/MobX-1-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-9sjltans3p)
6. [우아한형제들 기술 블로그 - React에서 MobX 경험기](https://woowabros.github.io/experience/2019/01/02/kimcj-react-mobx.html)
7. [React 공식 문서 - Context](https://ko.reactjs.org/docs/context.html)
8. [mementomori.log - React 상태 관리 Tool 사용 & 비교](https://velog.io/@mementomori/React-%EC%83%81%ED%83%9C-%EA%B4%80%EB%A6%AC-Tool-%EC%82%AC%EC%9A%A9-%EB%B9%84%EA%B5%90-Redux-VS-MobX-VS-Context-API)
