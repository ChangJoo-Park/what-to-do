# what-to-do

앞으로 해야할 일 또는 생각하는 걸 보관하기 위함

## 블로그

- [ ] trophy-jekyll 테마 수정
- [ ] https://changjoo-park.github.io 로 배포
- [ ] 기존 자료는 여기로 옮김

## Hexo

- [ ] 테마 boilerplate만들기
- [ ] Hexo git 배포 - [문서](https://hexo.io/docs/deployment.html)
- [ ] Hexo 테마를 개발하는 경우, 테마가 수정되면 어떻게 hexo가 알아채게 할 수 있는지?
- [ ] Hexo post의 날짜는 어떻게 규격(format)을 정할까? [문서](https://hexo.io/docs/helpers.html#date)

## Slate

### 왜?

- [ ] REST API 문서를 만들어야 한다.
- [ ] Markdown 으로 작성하고 싶다.
- [ ] 배포 및 갱신이 쉬워야 함.
  - [ ] Middleman 을 사용한 경험이 있어 익숙하다고 판단
    - [ ] https://www.gitbook.com/book/changjoo-park/middleman4/details
  - [ ] Vagrant를 이미 Slate에서 기본 설정으로 가지고 있음
  - [ ] 그밖에 Docker로 하는 내용이 있음
  - [ ] 둘 다 잘 모르면 바로 Middleman 빌드 후 올려도 됨

  
### 어떻게 할지?

- [x] Slate를 Middleman으로 직접 사용한다
- [x] Slate를 Vagrant를 이용해서 로컬에서 사용한다
  - [ ] Ryzen CPU환경에서는 VirtualBox의 VM을 실행하다가 블루스크린
- [ ] Slate를 Docker 컨테이너로 사용한다
  - [ ] [tutumcloud/slate](https://github.com/tutumcloud/slate) 를 이용해서 컨테이너를 올려봄
  - [ ] https://github.com/ChangJoo-Park/docker-slate 를 직접 만듦
    - tutumcloud의 slate는 git submodule을 사용해서 참조하는 것인데 몰랐음 
    - [공식문서 git 서브모듈](https://git-scm.com/book/ko/Git-%EB%8F%84%EA%B5%AC-%EC%84%9C%EB%B8%8C%EB%AA%A8%EB%93%88)

## 자바스크립트 애니메이션

- [ ] 라이브러리 문서 읽기
  - [ ] Animate.css
  - [ ] Mo.js
  - [ ] Anime.js
- [ ] 해볼 것
  - [ ] [카카오 헤어샵](http://www.kakao.com/kakaohairshop)

## Crystal

- [ ] 기본 문법 보기 :  https://crystal-lang.org/docs/
- [ ] [Kemal](http://kemalcr.com/) 읽기
- [ ] [Amber Framework](https://amberframework.org/) 읽기
  - [ ] [Granite-ORM](https://github.com/amberframework/granite-orm)
- [ ] [Lucky Framework](https://luckyframework.org/) 읽기
- [ ] [Awesome Crystal](http://awesomelists.top/#/repos/veelenga/awesome-crystal) 에서 라이브러리 확인
- [ ] [Crystal Shards](https://crystalshards.xyz/) 확인
- [ ] Image Resize Server + [MagickWand Crystal](https://github.com/blocknotes/magickwand-crystal)

## CSS

- [ ] postcss + webpack 설정


## Firebase

- [x] Cloud Functions + Hosting을 이용해서 웹페이지 만들기 [예제](https://github.com/ChangJoo-Park/firebase-functions-express)


## NativeScript

- [ ] Grocery NativeScript Vue [Template](https://github.com/nativescript-vue/nativescript-vue-webpack-template), [Sample](https://github.com/tralves/groceries-ns-vue), [Sample, NS + Vue](https://github.com/tralves/groceries-ns-vue)


## Google Spreadsheet

- [x] Vue.js 와 Google Spreadsheet를 이용해 웹 앱 만들기 [참고](https://coderwall.com/p/duapqq/use-a-google-spreadsheet-as-your-json-backend)
- [x] [Get Sheet Done](https://github.com/giladaya/get-sheet-done)
- [ ] Lean Canvas 
