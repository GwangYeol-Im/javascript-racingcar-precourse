# 🏎️ 프리코스 2주차 미션 - 자동차 경주 게임

## 🎯 학습 목표

- 메소드와 모듈 분리에 좀 더 초점을 맞추고, 객체 지향에 대해 공부한다.

## 🎯 모듈 목록

- index.js (프로그램의 흐름을 명시)
- racing_car_game.js (RacingCarGame class)
- winner.js (Winner class)
- render.js (Render class)
- car.js (Car class)
- util.js (Util class)

## 🎯 기능 목록

- 브라우저가 onload 되면, 유저로부터 자동차 이름의 인풋 값을 받는다.
- 인풋 값의 적절성 확인 후에 올바르지 않은 인풋에 대해서는 경고창을 띄운다.
  - 전체 문자열의 양 끝 값을 검사한다. (letter 유효성 검사)
  - 이름이 될 수 있는 문자의 제한은 어디까지? (영어, 한글, 숫자 등...)
  - 쉼표는 최소 한 개 이상 있어야 한다. (비교 대상 필요)
  - 쉼표로 나누어진 각 원소의 길이는 5자 이하이다.
  - 경고창에 유저가 올바른 값을 유추할 수 있도록 유도하는 설명이 필요하다.
- 유저로부터 횟수의 인풋 값을 받는다.
- 횟수 값의 적절성 확인 후에 올바르지 않은 인풋에 대해서는 경고창을 띄운다.
  - 횟수는 0보다 큰 양의 정수만 해당한다.
- RacingGame class 에 이름과 횟수를 넣어 생성된 객체를 이용해 프로그램을 실행한다.
  - Car class 로부터 이름 인풋 값을 받아 생성된 객체들을 배열에 담아 둔다.
  - randomMoveForward() 를 이용해 배열을 순회하며 각 객체의 위치는 랜덤으로 전진한다.
  - 위 메소드가 끝나면 횟수를 1회 차감한다.
  - 중간 집계를 브라우저에 렌더링한다.
  - 횟수의 값이 0이 될 때까지 위 과정을 반복하고, 0이 되면 결과를 도출한다.
    - Winner 객체를 이용해 최대 거리를 구하고, 우승자를 가리어 브라우저에 렌더링한다.

## ✔️ 이슈

## 💻 프로그램 실행 결과

![실행이미지](images/result.gif)
