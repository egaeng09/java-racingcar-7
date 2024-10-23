# java-racingcar-precourse

> ## 구현 기능 목록
> * 경주할 자동차 이름 입력 받기
>   - "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)" 출력
>   - camp.nextstep.edu.missionutils.Console의 readLine()을 통해 입력
>   - 자동차 이름은 쉼표(,)를 기준으로 구분
>   - 자동차 이름은 5자 이하 제한
>   - "시도할 횟수는 몇 회인가요?" 출력
>   - 잘못된 값 입력 시 예외 발생
> * 자동차 경주
>   - "실행 결과" 출력
>   - 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우 전진
>    camp.nextstep.edu.missionutils.Randoms의 pickNumberInRange()
>   - 사용자가 입력한 횟수만큼 반복
>   - 이름 : "-" * 이동 횟수 출력
> * 결과 출력
>   - "최종 우승자 : "과 함께 우승자 이름 출력
>   - 우승자는 한 명 이상일 수 있으며, 여러 명일 경우 쉼표(,)를 통해 구분