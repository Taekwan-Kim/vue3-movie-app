# Vue3 Movie app

Vue3와 OMDb API를 사용하는 영화 검색 애플리케이션입니다.<br>
[vue3-webpack-template#vue-router](https://github.com/ParkYoungWoong/vue3-webpack-template)에서 프로젝트를 시작합니다.

[Nuxt](https://nuxtjs.org/docs/2.x/get-started/installation) 프로젝트로 이관할 용도의 [Vue2 Movie App](https://github.com/ParkYoungWoong/vue2-movie-app) 프로젝트도 확인하세요!

[DEMO](https://stupefied-hodgkin-d9d350.netlify.app/)

## 🌿 Branches

진행 순서에 맞는 브랜치를 확인하세요.

- [Master](https://github.com/ParkYoungWoong/vue3-movie-app)
- [Default](https://github.com/ParkYoungWoong/vue3-movie-app/tree/default)
- [Netlify CLI](https://github.com/ParkYoungWoong/vue3-movie-app/tree/netlify-cli)

## 📖 Docs

- [Vue3](https://v3.ko.vuejs.org/guide/introduction.html)
- [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [Vuex](https://next.vuex.vuejs.org/)
- [Vue Router](https://next.router.vuejs.org/installation.html)
- [Netlify](https://docs.netlify.com/)

## 🎯 Goals

- 영화검색 사이트를 클론코딩. 검색어를 입력하여 원격에 있는 OMDb API와 통신하여 영화정보를 검색 > 화면에 출력
- 페이지 갱신은 SPA 단위로 구성
- 현재 프레임워크에 대한 경험과 지식이 없기 때문에, 처음에 접근하기 쉬운 Vue로 선정
- 클론코딩할때는 OMDb를 사용하지만, 활용 가능하다면 실제 현업에서 사용하고 있는 AWS 계정의 API와 통신하여 업무에 활용 할만한 작은 기능이 있을지 고민
- Vuex(Store)로 중앙 집중식 데이터를 처리하고 네임스페이스를 관리
- SPA(Single Page Application)를 위한 Vue Router를 구성해 Hash 기반의 페이지 단위로 개발
- OMDb API를 활용해 실제 영화 정보를 검색하고 출력
- Vue 플러그인을 생성하고 적용
- API Key가 노출되지 않도록 Netlify Functions(서버리스 함수)와 환경 변수(`.env`)를 사용해 백엔드를 구성하고, 로컬에서 테스트
- GitHub 저장소에 Push(업로드)하고 Netlify Hosting으로 CD(지속적인 배포)를 적용

## 💡 Specs

- Vue3
- Vuex
- Vue-Router
- Webpack
- OMDb API
- Netlify
  - Hosting with GitHub(Continuous Deployment)
  - Functions(Serverless)
- Axios
- Lodash

## 📦 Packages

> 설치할 각 패키지(모듈)의 설치 버전이 예제와 다른 경우 사용법이 달라질 수 있습니다.<br>
> 모든 패키지를 완성 예제의 [package.json](https://github.com/ParkYoungWoong/vue3-movie-app/blob/master/package.json) 파일에 명시된 버전과 동일하게 설치하는 것을 권장합니다.<br>
> [유뷰트에서 '강의 예제와 모듈(패키지) 버전 일치시키기' 영상 강의 보기](https://www.youtube.com/watch?v=5L9Ugz9eYxI)

- [bootstrap](https://github.com/twbs/bootstrap): 다양하고 강력한 기능을 제공하는 UI 프레임워크입니다.
- [vuex](https://github.com/vuejs/vuex): Vue.js를 위한 중앙 집중식 상태 관리 라이브러리입니다.
- [vue-router](https://github.com/vuejs/vue-router-next): Vue.js SPA를 위한 공식 라우터입니다.
- [axios](https://github.com/axios/axios):  HTTP 클라이언트 라이브러리로, OMDb API를 통해 영화 정보를 요청하기 위해 사용합니다.
- [lodash](https://github.com/lodash/lodash): 다양한 유틸리티 기능을 제공하는 자바스크립트 라이브러리입니다.
- [netlify-cli](https://www.npmjs.com/package/netlify-cli): Netlify 명령을 사용해 로컬에서 프로젝트와 서버리스 함수가 통신하기 위해 사용합니다.
- [dotenv-webpack](https://www.npmjs.com/package/dotenv-webpack): Webpack에서 dotenv로 환경 변수를 설정합니다. 

### 패키지 설치 주의사항

Vue 3버전에 대응하는 플러그인들과 최신의 부트스트랩 5버전 패키지를 설치하세요!

- `npm i bootstrap@next`
- `npm i vuex@next`
- `npm i vue-router@4`
- `npm i @vue/test-utils@next`
- `npm i vue-jest@next`
