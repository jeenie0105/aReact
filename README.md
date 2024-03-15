# nodejs 프로젝트 작업하려면

일일이 모두 작업
src : 노드의 views : *.html , public : script, css 폴더
jQuery 같은 라이브러리
파일명.js $("div")

# 리액트 파일

src : *.js, *.jsx(javascript x(ht)ml)
클래스형 컴포넌트 => 함수형 컴포넌트

# 함수

```
function hello(파라미터) {
    return "hello"
}
```

# 컴포넌트(함수)

자주 사용되는 html 페이지를 부품화 한 것

# HMR 시스템

자동으로 프로그램을 갱신하는 시스템( live server, nodemon )
컴포넌트 => App.jsx에 배치 => index.js => index.html

# MPA(정적, static) & SPA(동적, dynamic)

nodejs를 사용해서 동적으로 페이지를 제작( pug, ejs 추가 사용하면 )

# MPA(정적, static)
index.html
subpage1.html
subpage2.html
subpage3.html
subpage4.html

# SPA(동적, dynamic)

컴포넌트를 조립 => index.html
컴포넌트1
컴포넌트2
컴포넌트3
컴포넌트4

# 컴포넌트 만드는 규칙

1. 파일명 첫글자는 대문자 : 태그 소문자이고 리액트의 컴포넌트는 대문자이기 때문에 구분하기 위해
2. 확장자는 .js 또는 .jsx
3. return은 반드시 한개만 리턴
4. 사용할 때는 단일 태그처럼 사용한다 ex : <컴포넌트 />
5. javascript 코드는 {} 안에 쓰기
6. html의 class와 리액트 컴포넌트를 구분하기 위해 className으로 사용함

# React 데이터

- props : 상위 컴포넌트에서 하위 컴포넌트로 전달하는 값
- state : 상태 관리자, 현재 컴포넌트에서 상태를 관리할 때 
    - state 바뀌면 화면 갱신(UI 리로드), useEffect hook(함수)
- context : 전체 컴포넌트에서 공유하고 싶은 데이터를 최상위 컴포넌트에서 지정

# extention : react snippets(단축코드)

- rfc
- rfce
- rafc
- rafce

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

