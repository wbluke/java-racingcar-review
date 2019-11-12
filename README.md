# java-racingcar
- 요구사항: https://techcourse.woowahan.com/s/1aKh56So/ls/vyt2vo7Y

## 객체지향 생활 체조

- 규칙 1: 한 메서드에 오직 한 단계의 들여쓰기만 한다.
- 규칙 2: else 예약어를 쓰지 않는다.
- 규칙 3: 모든 원시값과 문자열을 포장한다.
- 규칙 4: 한 줄에 점을 하나만 찍는다.
- 규칙 5: 줄여쓰지 않는다(축약 금지).
- 규칙 6: 모든 엔티티를 작게 유지한다.
- 규칙 7: 2개 이상의 인스턴스 변수를 가진 클래스를 쓰지 않는다.
- 규칙 8: 일급 콜렉션을 쓴다.
- 규칙 9: 게터/세터/프로퍼티를 쓰지 않는다.

## 기능 구현 목록

- 경주할 자동차 이름을 입력 받기
```text
- 자동차의 이름은 쉼표를 기준으로 구분한다.
- 이름 앞뒤 공백을 제거하여 글자 수를 측정
- 자동차의 수가 2대 미만일 경우 예외 처리
- 이름이 5자를 초과하는 경우 예외 처리
```

- 시도할 횟수 입력 받기
```text
- 정수 입력이 아닐 경우 예외 처리
- 0 이하의 정수일 경우 예외 처리
```

- 실행 결과 출력
```text
- 0에서 9 사이에서 random 값을 구한 후 random 값이 4 이상일 경우 전진하고, 3 이하의 값이면 멈춘다.
- 추가) 자동차 게임이 진행 중임을 표시하기 위해 매 회 사이에 정지 시간을 두자.
- 추가) 콘솔 상의 비교 편의성을 위해 이름의 출력은 공백을 더해 5칸으로 맞추자.
```

- 우승자 출력