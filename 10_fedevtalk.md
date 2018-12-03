# FEDevtalk 10 회

## 세션 상세

## 1. Say Hello to Storybook : 스토리북을 통한 React UI 컴포넌트 개발

#### 발표자 진겸 님

### 개요

React 는 View 라이브러리 입니다. 그렇기 때문에 View 외에 우리는 그동안 아쉬운 부분들을 해결하기 위해 여러가지 다른 라이브러리들을 같이 써왔지만 view 외적인 것에 도움을 주었었습니다. 예를 들어 app 이 복잡해질수록, state management 를 하기 힘들어지며 이를 아주 깔끔하게 도와주는 패턴인 Redux 나 Mobx 등이 있지만 이는 앱의 “state”, 즉 data flow 를 다듬어 줄 뿐이지 결코 “View”의 개발 자체를 쉽게 해주지는 않습니다.

유저의 인터렉션이 제대로 specify 되지 않은 상태에서, 각종 예외처리를 앱을 설계해가면서 정의하면 구조를 뒤바꿔야 한는 경우가 심심치않게 있는데요, 실제 앱의 구조에서 리액트의 tree 형식의 구조 때문에, 그리고 top-down state 의 흐름도 때문에 각 컴포넌트의 state 를 따로 실제 view 단위로 모듈화 하여 테스팅 하기가 쉽지 않습니다.

따라서 수많은 로직과 state 로 연결이 되어있는 앱을 normalize 하여 스캐폴딩을 해주는 Storybook 을 소개합니다. Storybook 은 커져가는 리액트 컴포넌트를 page 혹은 module 별로 원하는데로 잘라 아예 isolated 된 environment 에서 ui testing 을 할 수 있게금 해주는 툴입니다.

Storybook 은 개발적인 이점을 줄 뿐만 아니라, 개발자와 PM 그리고 Designer 의 중요한 연결고리가 됩니다. Storybook 을 도입함으로써 협업시 얻을 각종 장점들에 대해서도 소개를 해드립니다.

### 목차

- 기존 React 앱을 개발할때의 각종 문제점
- Storybook 의 소개와 작동 방식
- 설치 및 실행 방법 / 직접 실행
- 현재 사용중인 라이브러리 및 데모
- Storybook driven development (개발과 협업)
- 사용사례(+ 실제로 제가 사용하고 있는 방법)
- TDD 와의 비교
- Storybook 의 미래 (from the main contributor)

### 발표자 소개

- Google Developer Group Korea, Organizer 2016
- CodersHigh, Software Engineer 2017.01 - 2017.06
- Foreseer, Software Engineer 2017.06 - 2017.10

### 발표 영상
- https://www.youtube.com/watch?v=jc9xKzdkYDg&index=6&t=0s&list=PLsFtzQAC8dDcv76FW0MDTTYVgnVrsW3sW

</br>

## 2. TypeScript 와 Flow: 자바스크립트 개발에 정적 타이핑 도입하기

#### 발표자 [안희종](https://ahnheejong.name/) 님 (하이퍼커넥트)

### 개요

프론트엔드 개발에 정적 타이핑을 도입하길 바라는 사람과 성공 사례가 점점 기하급수적으로 늘고 있습니다. 정적 타이핑이 제공하는 장점은 무엇인지, 어떤 선택지가 있는지, 그 중 가장 훌륭한 옵션은 무엇이고 왜 그런지, 마지막으로 기존 코드베이스를 옮겨오는 방법과 주의할 점으로는 무엇이 있는지 등에 대해 이야기합니다.

### 목차

- 동기부여
- 선택지
- 타입스크립트의 장점
- 도입 방법
- 시행착오
- 요약

### 발표자 소개

- 스포카 웹 프론트엔드 프로그래머 2017.01 ~ 2017.09
- 하이퍼커넥트 웹 FE 개발자 2017.10 ~ 현재

### 발표 영상
- https://www.youtube.com/watch?v=H16gTwa2J7g&index=7&t=0s&list=PLsFtzQAC8dDcv76FW0MDTTYVgnVrsW3sW

</br>

## 3. 통합검색 레이어 페이지

#### 발표자 유원홍 님 (네이버 FE 플랫폼)

### 개요

통합검색에서 제공하는 컨텐츠가 증가하여 UX 와 성능 문제가 발생하고 있습니다. 새로운 통합검색 JS 플랫폼이 어떤 기능을 제공하여 과거의 문제를 개선 했는지 설명합니다.

### 목차

- 애니매이션 구현 프로세스, 성능 최적화
- 페이지 성능 최적화
- FE 개발 환경의 개선

### 발표 영상
- https://www.youtube.com/watch?v=WdF3yytaYqw&index=5&t=0s&list=PLsFtzQAC8dDcv76FW0MDTTYVgnVrsW3sW
