<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/ecc53a42-d79b-42e2-8852-5126b810a4c8.svg">
</p>

한국어 | [English](./README.md) | [日本語](./README.ja.md) | [Spanish](./README.es.md)

## 简介

[vue-element-admin](https://panjiachen.github.io/vue-element-admin)은 [vue](https://github.com/vuejs/vue) 및 [element-ui](https://github.com/ElemeFE/element)를 기반으로 하는 백엔드 프런트엔드 솔루션입니다. 최신 프런트 엔드 기술 스택을 사용하고 i18n 국제화 솔루션, 동적 라우팅 및 권한 확인이 내장되어 있으며 일반적인 비즈니스 모델을 개선하고 풍부한 기능 구성 요소를 제공합니다. 엔터프라이즈 수준의 중간 및 백 엔드를 빠르게 구축하는 데 도움이 됩니다. 최종 제품 프로토타입. 나는 귀하의 요구 사항이 무엇이든 이 프로젝트가 귀하에게 도움이 될 수 있다고 믿습니다.

- [온라인 미리보기](https://panjiachen.github.io/vue-element-admin)

- [이용문서](https://panjiachen.github.io/vue-element-admin-site/zh/)

- [Gitter 토론방](https://gitter.im/vue-element-admin/discuss)

- [위키](https://github.com/PanJiaChen/vue-element-admin/wiki)

- [Gitee](https://panjiachen.gitee.io/vue-element-admin/) 온라인 미리보기 (국내 사용자는 이 주소로 접근 가능)

- 기본 템플릿 사용을 권장합니다: [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template)
- 데스크톱: [electron-vue-admin](https://github.com/PanJiaChen/electron-vue-admin)
- Typescript 버전: [vue-typescript-admin-template](https://github.com/Armour/vue-typescript-admin-template) (신용: [@Armour](https://github.com/Armour) )
- [awesome-project](https://github.com/PanJiaChen/vue-element-admin/issues/2312)

**`v4.1.0+` 버전 이후 기본 마스터 브랜치는 국제화를 지원하지 않습니다. 필요한 경우 [i18n](https://github.com/PanJiaChen/vue-element-admin/tree/i18n)을 사용하세요. 브랜치 마스터와 동기적으로 업데이트됩니다**

**이 프로젝트는 낮은 버전의 브라우저(예: ie)를 지원하지 않습니다. 필요한 경우 폴리필을 직접 추가하세요. [자세히](https://github.com/PanJiaChen/vue-element-admin/wiki#babel-polyfill) **

**현재 버전은 `v4.0+`이며 `vue-cli`를 기반으로 구축되었습니다. 문제를 발견하면 [이슈](https://github.com/PanJiaChen/vue-element-admin)를 제기해 주세요. 이전 버전을 사용하려면 브랜치를 [tag/3.11.0](https://github.com/PanJiaChen/vue-element-admin/tree/tag/3.11.0)으로 전환하면 됩니다. `vue-cli`에 의존하지 않음**

## 사전예약 준비

[node](http://nodejs.org/) 및 [git](https://git-scm.com/)을 로컬에 설치해야 합니다. 이 프로젝트의 기술 스택은 [ES2015+](http://es6.ruanyifeng.com/), [vue](https://cn.vuejs.org/index.html), [vuex](https: //vuex.vuejs.org/zh-cn/), [vue-router](https://router.vuejs.org/zh-cn/), [vue-cli](https://github.com/ vuejs/vue-cli), [axios](https://github.com/axios/axios) 및 [element-ui](https://github.com/ElemeFE/element), 모든 요청 데이터는 [Mock. js] (https://github.com/nuysoft/Mock) 시뮬레이션을 위한 내용이므로 이러한 지식을 미리 이해하고 학습해 두시면 본 프로젝트를 활용하는데 큰 도움이 될 것입니다.

또한 처음부터 완전한 백엔드 프로젝트를 구축하는 방법에 대한 일련의 튜토리얼 기사도 함께 제공됩니다. 이 프로젝트를 연습하기 전에 이 기사를 읽어 보는 것이 좋습니다.

- [직접, Vue를 사용하여 백엔드를 엿먹이는 방법을 보여드리겠습니다. 시리즈 1(기본)](https://juejin.im/post/59097cd7a22b9d0065fb61d2)
- [손대접, Vue를 활용한 백엔드 시리즈 2 플레이 방법을 알려드리겠습니다(로그인 권한)](https://juejin.im/post/591aa14f570c35006961acac)
- [직접, Vue를 사용하여 백엔드 시리즈 3을 엿먹이는 방법을 보여드리겠습니다(연습)](https://juejin.im/post/593121aa0ce4630057f70d35)
- [손에 손잡고 vue를 사용하여 백엔드 시리즈 4를 만드는 방법을 보여드리겠습니다(vueAdmin, 미니멀리스트 백엔드 기본 템플릿)](https://juejin.im/post/595b4d776fb9a06bbe7dba56)
- [백스테이지 시리즈 5(v4.0 새 버전) 플레이 시 Vue 사용법을 직접 보여드리겠습니다](https://juejin.im/post/5c92ff94f265da6128275a85)
- [당신의 손으로 vue 컴포넌트를 캡슐화하는 것을 도와드리겠습니다](https://segmentfault.com/a/1190000009090836)
- [손을 맞대고, 아이콘을 우아하게 사용해보세요](https://juejin.im/post/59bb864b5188257e7a427c09)
- [직접, webpack4를 합리적으로 사용하는 방법을 알려드립니다(1부)](https://juejin.im/post/5b56909a518825195f499806)
- [직접, webpack4를 합리적으로 사용하는 방법을 알려드립니다(2부)](https://juejin.im/post/5b5d6d6f6fb9a04fea58aabc)

**궁금한 점이 있으시면 위의 사용문서와 글을 먼저 읽어보시고, 만족스럽지 않으시다면 발행 및 홍보를 환영합니다**

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/PanJiaChen/vue-element-admin/tree/CodeSandbox)

<p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

## 기능

````
- 로그인/로그아웃

- ASD
  - 페이지 권한
  - 명령 권한
  - 권리 프로필
  - 2단계 로그인

- 다중 환경 퍼블리싱
  -dev
  - 앉다
  - 무대
  -찌르다

- 글로벌 기능
  - 국제 및 다국어
  - 다양하고 역동적인 피부 변화
  - 동적 사이드바(다단계 라우팅 중첩 지원)
  - 동적 탐색경로
  - 빠른 탐색(탭 페이지)
  - SVG 스프라이트 아이콘
  - 로컬/백엔드 모의 데이터
  - 전체 화면 전체 화면
  - 적응형 축소 사이드바

- 편집자
  - 리치 텍스트
  - 마크다운
  - JSON 및 기타 형식

- 엑셀
  -엑셀로 내보내기
  -엑셀 가져오기
  - 프론트엔드 시각화 엑셀
  - zip 내보내기

- 시트
  - 동적 테이블
  - 테이블 드래그 앤 드롭
  - 인라인 편집

- 오류 페이지
  - 401
  - 404

- 구성 요소
  - 아바타 업로드
  - 맨 위로
  - 드래그 앤 드롭 대화상자
  - 드래그 선택
  - 드래그 앤 드롭 보드
  - 목록 드래그 앤 드롭
  -SplitPane
  - 드롭존
  - 끈적끈적
  -CountTo

- 종합적인 예시
- 오류 기록
- 대시보드
- 가이드 페이지
- ECharts 차트
- 클립보드(잘라내기 및 복사)
-Markdown2html
````

## 개발

```bash
# 프로젝트 복제
git clone https://github.com/PanJiaChen/vue-element-admin.git

# 프로젝트 디렉토리를 입력하세요
CD vue-element-admin

# 종속성 설치
npm install

# 다양한 이상한 버그가 있을 수 있으므로 cnpm을 사용하여 종속성을 직접 설치하지 않는 것이 좋습니다. 다음을 수행하여 느린 npm 다운로드 속도 문제를 해결할 수 있습니다.
npm install --registry=https://registry.npm.taobao.org

# 서비스 시작
npm run dev
```

브라우저 접속 http://localhost:9527

## 게시

``bash
# 테스트 환경 구축
npm run build:stage

# 프로덕션 환경 구축
npm run build:prod
```

## 다른

``bash
# 출판 환경 효과 미리보기
npm run preview

# 출판 환경 효과 미리보기 + 정적 자원 분석
npm run preview -- --report

# 코드 형식 확인
npm run lint

# 코드 형식 확인 및 자동 복구
npm run lint -- --fix
```

자세한 내용은 [사용문서](https://panjiachen.github.io/vue-element-admin-site/zh/)를 참조하세요.

## 변경 로그

각 릴리스에 대한 자세한 변경 사항은 [출시 노트](https://github.com/PanJiaChen/vue-element-admin/releases)에 문서화되어 있습니다.

## 온라인 데모

[온라인 데모](https://panjiachen.github.io/vue-element-admin)

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](https://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge | last 2 versions | last 2 versions | last 2 versions |

## License

[MIT](https://github.com/PanJiaChen/vue-element-admin/blob/master/LICENSE)

Copyright (c) 2017-present PanJiaChen
