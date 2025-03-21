# 형식 맞추기

<br>

## 목적
개발자의 일차적 의무 - 소통<br>
기능 부분은 유지보수를 통해 변경될 확률이 **매우** 높음<br>
하지만 가독성 있는 코드는 바뀔 코드의 품질에 막대한 영향을 끼침

## 권장하는 형식
- > 적절한 행 길이<br><br>
200행 내외의 파일로도 커다란 시스템을 구축할 수 있음<br>
큰 파일보다 작은 파일이 이해하기 쉽다.
- > 신문 기사처럼 작성<br><br>
설명 가능한 명칭으로 시작, 고차원 개념부터 서술하여 세세한 함수와 내역으로 마무리.
- > 빈 행으로 개념 분리<br><br>
코드 리딩 시 빈 행 바로 다음 줄에 눈이 멈춘다.<br>
**빈 행은 새로운 개념**을 시작한다는 시각적 단서다.
- > 팀 규칙
    >> 코드 스타일은 규칙적이여야 한다.<br>
    하나의 소스 파일에서 구현된 형식이 다른 소스 코드에서도 보일 것이란 신뢰를 주어라
## 밀집도
- > 세로 밀집도<br><br>
    > **고차원 함수에서 저차원 함수 순으로, 중요한 개념 먼저**<br><br>
    >> 수직 거리<br>
    연관 있는 코드는 가까이 있어야 한다<br><br>
    >> 변수 선언<br>
    변수는 사용하는 위치에서 가까운 곳에서 선언되어야한다<br>
    만약 루프 제어 변수를 선언한다면, 루프문 내부에서 선언하는 등<br><br>
    >> 인스턴스 변수<br>
    자바의 경우 클래스 맨 처음에 인스턴스 변수를 선언한다.<br>
    정말 중요한건, 누구나 알만한 위치에 선언하는 것이다.<br><br>
    >> 종속 함수<br>
    종속 함수는 세로로 가깝게, 호출하는 함수를 먼저 배치한다.<br><br>
    >> 개념적 유사성<br>
    비슷한 일을 한다면 근처에 배치한다.<br><br>
- > 가로 밀집도<br>
    >> 공백을 적절하게 배치하여 밀접한 개념과 느슨한 개념을 표현한다<br><br>
    >> 스코프에 따른 들여쓰기는, 설령 비어있더라도 지킨다.<br>
    