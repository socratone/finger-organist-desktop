## 가톨릭 성가 반주기 (데스크탑 버전)

[finger-organist](https://github.com/socratone/finger-organist.git)에서 빌드한 파일을 일렉트론을 이용해서 데스크탑앱으로 바꿉니다.<br />
빌드한 파일은 포함되어 있지 않습니다.<br />
필요한 파일은 아래와 같습니다.<br />

### 파일 구조

`dist` electron으로 빌드한 앱이 생성되는 폴더<br />
`public` 리액트에서 build한 파일을 담는 폴더<br />
`main.js` 일렉트론 빌드 명령을 내리면 이 파일을 토대로 앱이 만들어진다. 일렉트론과 관련된 설정은 여기서 한다. 이 프로젝트에서는 앱에서 파일 불러오는 문제를 해결하려고 별도의 서버를 열었다.<br />
`server.js`<br />
`package.json` electron.js를 구동하기 위한 중요한 설정들이 들어있다.<br />
