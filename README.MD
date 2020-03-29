github와 vscode 연결

node.js 
https://nodejs.org/en/

webpack 과 webpack-dev-server 설치

폴더 생성

npm init 으로 프로젝트 시작

개발모듈 설치
npm install react react-dom 설치

npm install babel-core, babel-loader, babel-preset-es2015 babel-preset-react babel-loader@7 설치

npm install --save-dev webpack webpack-dev-server react-hot-loader 설치

npm install webpack-cli -D 설치

webpack.config.js 생성

public 디렉토리에 index.html 생성

src 디렉토리에 components 디렉토리 생성

components 디렉토리에 App.js 생성

src 디렉토리에 index.js 생성

package.json에 개발 프로젝트 생성 코드 추가     "dev-server": "webpack-dev-server"

react-hot-loader 용도 => 코드변경을 실시간 적용하면서 state값을 유지하도록 함

react-hot-loader 적용 방법

강의의 방법이 버전업이 되면서 변경됨

webpack.config.js에서 

babel-loader에 플러그인으로 적용

plugins: ["react-hot-loader/babel"]

index.js에 ReactDOM.render 내용도 변경됨

https://gist.github.com/velopert/c5b1f5f748d9aa8b78f729a321682230 참조

react 서버 실행
D:\workspace\react>npm run dev-server
