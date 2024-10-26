# javascript-racingcar-precourse

> 초간단 자동차 경주 게임

## 입력

-   [ ] 자동차 이름 입력
-   [ ] 자동차 전진 횟수 입력

## 기능

-   [ ] 자동차 이름 구분
-   [ ] 전진 : 무작위 숫자 구해서 4 이상인지 구분
-   [ ] 최종 우승자 선별

## 출력

-   [ ] 1턴 마다 진행 상황 출력
-   [ ] 최종 우승자 출력
-   [ ] 예외 상황시 [ERROR] 메시지 출력

## 예외

-   [ ] 자동차 이름이 5자 초과일 때
-   [ ] 횟수 입력시 숫자 외 문자를 입력받았을 때
-   [ ] 자동차 이름 입력시 공백이 포함되어 있을 때

## 추가 요구사항

1. depth 2까지 허용
2. 3항 연산자 금지
3. 함수는 한 가지 일만 하도록 최대한 작게 분리
4. Jest로 테스트 코드 활용

---

### 실행 결과 예시

```
경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
pobi,woni,jun
시도할 횟수는 몇 회인가요?
5

실행 결과
pobi : -
woni :
jun : -

pobi : --
woni : -
jun : --

pobi : ---
woni : --
jun : ---

pobi : ----
woni : ---
jun : ----

pobi : -----
woni : ----
jun : -----

최종 우승자 : pobi, jun
```
