# Embedded-System-Programming
2020-1 ESP2
# 임베디드 시스템 프로그래밍2



## 1장 라즈베리파이,리눅스,파이썬

1. Raspnerry Pi 기능 및 용도 + 원격접속 방법

2. Linux 소개

   1. Linux는 다중 사용자 운영체제 각각의 사용자는 유일한 username을 가진다.

   2. superuser라고 불리는 특권을 가진 사용자: root

   3. superuser는 시스템의 거의 모든 자원에 대한권한을 가진다.

      - superuser 권한 획득하기

        주로 sudo 명령을 사용하는 것을 권장한다.

3. 파일 시스템 사용

4. 
![image-20200320175053093](https://user-images.githubusercontent.com/43948697/77149952-179e0900-6ad6-11ea-8f8f-73f4b4738810.png)


- 루트 디렉토리 
  - 최상위 디렉토리로 / 로 표시
- 절대 경로
  - /home/cam/book/wonderland
- 현재 디렉토리와 상대경로
  - 사용자가 현재 위치한 디렉토리(pwd명령 )



5. 홈 디렉토리

   - 각각의 사용자에게 할당된 디렉토리
   - Debian/Ubuntu 등에서는 "/home/username"
   - 자신의 홈 디렉토리 찾기/이동하기
     - $ cd
       - 매개변수 없는 cd 명령은 자신의 홈 디렉토리로 이동
       - HOME 환경 변수는 자신의 홈 디렉토리 이름을 값으로 가짐
       - ex) $ echo $HOME
     - ~
       - 디렉토리명이 들어갈 자리에 있는 ~는 자신의 홈 디렉토리 명으로 대체
     - echo 명령은 입력된 값을 **그대로 ** 화면에 출력
     - .
       - 항상 현재 디렉토리를 나타냄
       - ./readme.txt 와 readme.txt 는 동일
     - ..
       - 현재 디렉토리의 부모디렉토리
       - cd ..
     - ~
       - Shell은 ~를 항상 사용자의 홈 디렉토리명으로 대체한다.

6. 명령어 정리
   ![image-20200320180100943](https://user-images.githubusercontent.com/43948697/77149954-18cf3600-6ad6-11ea-9edf-ee7c87b02a37.png)
   ![image-20200320180212466](https://user-images.githubusercontent.com/43948697/77149956-18cf3600-6ad6-11ea-8328-a43461a442fb.png)
   ![image-20200320180230134](https://user-images.githubusercontent.com/43948697/77149957-1967cc80-6ad6-11ea-8b58-a61038672a64.png)
   ![image-20200320180257938](https://user-images.githubusercontent.com/43948697/77149958-1a006300-6ad6-11ea-8a52-69bc35e33f53.png)
