# 우아한 테크 코스 <br> 온라인 과제 1주차 Java Baseball
## 프로젝스 설명
컴퓨터가 만든 3자리의 숫자를 맞추는 야구게임이다. 
사용자가 숫자를 입력하면 그에 따른 결과가 출력되고, 이를 토대로 숫자를 맞출 수 있다.
컴퓨터의 숫자를 정확하게 맞추면 게임이 종료된다.

## 기능 목록  
### 1. 컴퓨터 난수 생성  
* 3자리의 난수를 생성한다.
* 각 자리 수가 1~9 사이에 포함되는 지 검증한다.

### 2. 사용자로부터 입력 받기
* 숫자를 입력한 것인지 검증한다.
* 3자리 수인지 검증한다.

### 3. 결과 검사
* 볼/스트라이크/포볼/낫싱을 검증한다.
* 같은 수가 같은 자리에 있는 지 검증한다.
* 같은 수가 다른 자리에 있는 지 검증한다.
* 결과에 따라, 스트라이크와 볼 값을 갱신한다.

### 4. 결과 출력 및 게임 진행
* 결과를 출력한다.
* 컴퓨터의 숫자를 맞추었다면 게임 시작 및 종류 여부를 출력한다.
* 컴퓨터의 숫자를 맞추지 못했다면 다시 사용자로부터 숫자를 입력받는다.