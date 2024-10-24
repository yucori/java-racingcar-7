# java-racingcar-precourse
# 자동차 경주 게임

## 기능 목록

1. **자동차 이름 입력**
    - 사용자로부터 쉼표(,)로 구분된 자동차 이름을 입력받는다.
    - 자동차는 2대 이상 입력하여야 한다.
    - 이름은 5자 이하만 가능하며 공백은 이름으로 사용할 수 없다.
    - 중복된 이름을 등록할 수 없다.
    - 입력된 이름이 유효하지 않을 경우 `IllegalArgumentException`을 발생시키고 프로그램을 종료한다.

2. **이동 횟수 입력**
    - 사용자에게 몇 번 이동할 것인지 입력받는다.
    - 이동 횟수는 1 이상이어야 하며, 유효하지 않을 경우 `IllegalArgumentException`을 발생시키고 프로그램을 종료한다.

3. **자동차 경주 진행**
    - 입력받은 횟수만큼 자동차 경주를 진행한다.
    - 각 턴마다 자동차는 무작위로 전진하거나 멈춘다.
    - 무작위 값이 0~9 사이에서 생성되며, 4 이상일 경우 자동차가 전진한다.

4. **경주 결과 출력**
    - 각 자동차의 현재 위치를 이름과 함께 출력한다.
    - 전진한 횟수만큼 "-" 기호를 사용하여 표시한다.

5. **우승자 계산 및 출력**
    - 경주가 끝나면 가장 멀리 전진한 자동차를 우승자로 결정한다.
    - 우승자가 여러 명일 경우 쉼표(,)로 구분하여 출력한다.
    - 최종 우승자를 출력한다.
