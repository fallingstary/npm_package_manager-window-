<h1><img src="https://em-content.zobj.net/thumbs/160/microsoft/319/star_2b50.png" height="30px"/> npm package manager for window</h1>

![npm](https://img.shields.io/badge/npm-efefef?style=for-the-badge&logo=npm&logoColor=f3212d)

<h3> Now, explain about npm </h3>

* npm 패키지 매니저
1. 여러 환경에서 프로젝트를 배포하거나 공유할 때 매우 유용하다.
2. 필요한 기능을 빠르게 찾고 추가할 수 있다.

* npm 설치 및 세팅, 사용법
1. nodejs 설치 (https://nodejs.org/ko)
2. cmd 활성화
3. node -v로 node 설치 여부(버전 확인)
4. vscode에서 터미널 활성화한 후 다음 명령어로 해당 폴더에 package.json파일 생성 : $ npm init -y
5. 다음 명령어로 npm.lock 파일과 모듈 설치 : $ npm install
-> 만약에 package.json 파일을 가지고 있더라면, package.json안에 있던 패키지들이 자동으로 설치
6. 끝

* npm 명령어로 pakage.json 파일 사용법
1. npm install 패키지명 : 해당 패키지 설치
2. npm ci 패키지명 : 해당 패키지를 현 버전(package-lock)으로 설치
3. npm update : 설치된 패키지들을 업데이트
4. npm rm 패키지명 : 설치된 패키지들을 삭제
5. npm dedupe : npm 중복된 패키지들 정리
6. npm root : node_modules 설치 경로
7. npm test or start : package.json의 script 부분에 아래와 같이 입력하여 간단하게 실행가능. 하지만 입력하지 않았다면 node server.js가 실행
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "node index.js"
    },
8. npm stop : npm으로 실행이 되어진 상태를 종료
9. npm restart : npm을 다시 시작
10. npm search : 패키지 검색
