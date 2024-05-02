# 경비ㆍ보안 근무자 관리 시스템 README
  이미지
  배포 후 아이디, 패스워드
  
# 프로젝트 소개
- 경비ㆍ보안 근무자의 근태를 확인할 수 있는 Application 입니다.
- 순찰 구역을 언제, 어디, 어떻게 돌았는 지 확인할 수 있습니다.
- 사진의 Meta data를 추출하여, 부정 순찰을 방지할 수 있습니다.
- Tesseract, OpenCV를 이용하여, 순찰 구역 텍스트를 추출하여, 어느 곳을 돌았는 지 확인 할 수 있습니다.

# 팀원 구성



# 개발 환경

|Front|Back|DataBase|
|:-:|:-:|:-:|
|JSP|JAVA-17|MariaDB|
|HTML/CSS|Python3|DBeaver|
|Javascript(JQuery)|Tesseract||


# 채택한 기술

- OpenCV
  - 테서렉트의 텍스트 추출 능력을 향상 시키기 위하여 grayscale을 사용하였습니다.
  - 가우시안 블러와 Canny를 사용하여 배경 영역 및 텍스트 영역을 구분하였습니다.
- Tesseract
  - 텍스트 인식을 위해 사용했습니다.

# 브랜치 전략 (GITHUB FLOW)
- 한정된 시간, 빠르게 개발하기 위하여 GitHub Flow 전략을 채택하였습니다.
- 충돌이 많이 나서 각자 코딩하기엔 적합하지 않으나, 학원이라는 공간에서 같이 코딩하기에 사용하기 적합한 전략이라 판단하여 채택했습니다.
- 충돌 해결 능력이 많이 향상되었습니다.


# Code Convention
- JAVA (CamelCase)
  - 변수 선언 시 명사
  - 함수 선언시 동사+명사
  - Class 선언 시 파스칼 케이스
- Python, MariaDB (Snake_Case)
- 변수 선언은 Field 영역에 선언

# 프로젝트 구조


# 역할 분담

# 개발 기간


