# immer 사용하기
- 불변성 유지하면서 상태 업데이트 하기
- spread 연산의 복사: 얕은 복사 (shallow copy)
- 상태의 객체나 배열의 구조가 복잡한 경우 간단하게 처리 가능하게 해줌

# 프로젝트 생성
  - yarn create react-app react-immer
  - cd react-immer
- 라이브러리 설치
  - yarn add immer

# immer 사용법
- immer produce from "immer";
- const nextState = produce(수정하고자하는상태명, 상태를업데이트하도록하는함수정의);