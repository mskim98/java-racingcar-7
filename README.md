# java-racingcar-precourse

---

## 기능요구사항

1. [] 정보 입력 받아 출력(이름, 횟수)
    1. "," 기준 파싱
    2. 5자 이하 검사
    3. 출력 확인
2. [] 랜덤 횟수 출력
    1. 전진하는 조건(0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우)
3. [] 경주 게임을 완료한 후 누가 우승자 확인(우승자는 한 명 이상)
    1. 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분

## 에러 핸들링

1. [] 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료