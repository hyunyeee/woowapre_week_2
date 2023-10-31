# 기능 명세서

## ⚡ 구현할 기능 목록

- [ ] 경주할 자동차 이름 및 시도할 횟수를 입력받는다.

  ```
  경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
  pobi,woni,jun
  시도할 횟수는 몇 회인가요?
  5
  ```

- [ ] 각 차수별 실행 결과를 출력한다.

  ```
  실행 결과
  pobi : -
  woni :
  jun : -
  ```

- [ ] 우승자 안내 문구를 출력한다. (단독 / 공동)

  ```
  최종 우승자 : pobi, jun
  ```

- [ ] 사용자가 잘못된 값을 입력한 경우 예외를 발생시킨 후 종료한다.
  ```
  [ERROR] 숫자가 잘못된 형식입니다.
  ```