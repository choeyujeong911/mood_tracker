# mood_tracker
환자 본인의 정동을 매일 기록하고 연도별로 모아 꺾은선 그래프를 그립니다.<br/>
환자는 본인의 계정을 가지고 로그인하여 정보를 열람할 수 있습니다.<br/>

참고 블로그<br/>
https://velog.io/@dojun527/AWS-EC2-Django-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%B0%B0%ED%8F%AC%ED%95%98%EA%B8%B0

AWS의 EC2 인스턴스와 IAM 관련 모든 키 및 정보<br/>
로컬 컴퓨터 C:\User\youje\.ssh\<br/>

로컬 컴퓨터의 서버 컴퓨터 SSH 접속 명령어<br/>
$ ssh -i "C:\Users\youje\.ssh\mood-tracker-key-pair.pem" ec2-user@52.64.187.169

서버 컴퓨터의 장고 프로젝트 내 실행 명령어<br/>
$ python3 manage.py runserver 0:8000

사용자 컴퓨터의 브라우저 접속 주소<br/>
~~52.64.187.169:8000~~
