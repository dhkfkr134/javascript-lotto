# 로또 프로그램 - 기능 문서

[공통 요구사항] : 에러문구는 "[ERROR]"로 시작해야 한다.

## 입력
    - cost : 비용 ex)14000
        [요구사항] : 1000원으로 나누어 떨어지지 않으면 예외처리
    - winningNumbers : 당첨번호 ex) [1,2,3,4,5,6] / ','를 구분자로 한다.
        [요구사항] : 로또번호가 1 ~ 45 사이의 숫자가 아니라면 예외처리
        [요구사항] : 당첨번호가 6개가 아니라면 예외처리
    - bounusNumber : 보너스번호 ex) 7
## 기능
    - 로또 자동발행 기능
    - 당첨확인 기능
    - 수익률 계산 기능
    - 사용자 입출력 기능
        [요구사항] : 발행한 로또 개수와 번호를 출력할때, 로또의 숫자들은 오름차순으로 정렬한다.

## 클래스
    - App
        - 프로그램
    - Controller
        - 프로그램에서 기능들을 연결하는 컨드롤러
    - Lotto
        - 로또번호를 담은 객체
    - Display
        - 출력 및 입력의 역할
    - WinningNumbers
        - 당첨번호를 담은 객체