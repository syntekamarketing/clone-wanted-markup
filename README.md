# 퍼블리셔 과제: Wanted Design System 기반 컴포넌트 구현

## 기본 사항
[Wanted Design System](https://www.figma.com/community/file/1355516515676178246)은 퍼블릭으로 공개된 디자인 시스템입니다. 제시된 Wanted Design System 가이드라인을 준수하여, 컴포넌트를 구현합니다.


### 구현 범위
- **반응형 레이아웃**: 데스크톱 및 모바일 대응
  - Desktop XL (1600px)
  - Desktop LG (1440px)
  - Mobile (375px)
- [구현범위 피그마 바로가기](https://www.figma.com/design/ovcddDAkXLjChIj5Wg9BbH/Wanted-Design-System--Community-?node-id=15851-41248&m=dev)

### 구현 요구사항
- 웹 표준과 접근성 지침(WCAG 2.1 AA)을 준수한 시맨틱 마크업을 작성합니다.
- SEO(검색 엔진 최적화)를 고려해 구조를 설계합니다.
- UI 컴포넌트는 개발자 협업 문서화를 위해 Storybook을 활용합니다.
- 반응형 디자인을 구현하여 다양한 화면 크기에 대응합니다.
- 섹션 헤더의 trailing 버튼 클릭 시, 해당 섹션의 가로 스크롤 리스트가 컨테이너 폭 기준으로 1회 이동하는 인터랙션을 구현합니다.
- 섹션 헤더 외에도 적용하고 싶은 인터렉션이 있다면 자유롭게 구현합니다.
- 일정 내 모든 요구사항을 완료하지 못한 경우, README에 미구현 항목, 사유에 대해 정리해 주세요. 해당 내용은 평가 시 참고합니다.


### 제출 방법
- 완성된 결과물은 개인 GitHub 저장소에 업로드한 뒤, 저장소 URL을 메일로 회신합니다.

## 기술 스택
- Framework: [Next.js 14](https://nextjs.org/)
- Language: [TypeScript](https://www.typescriptlang.org/)
- Styling: [Sass](https://sass-lang.com/) / [CSS Modules](https://github.com/css-modules/css-modules)
- UI Components: [Storybook](https://storybook.js.org/)
- Linting: [ESLint](https://eslint.org/)
- Formatting: [Prettier](https://prettier.io/)
- Package Manager: [Yarn](https://yarnpkg.com/)

## 시작하기

### 전제 조건

- [Node.js](https://nodejs.org/en/) (v20.x 이상 권장)
- [Yarn](https://yarnpkg.com/getting-started/install)

### 설치

1.  저장소를 `Code → Download ZIP`으로 프로젝트를 내려받거나, `Use this template` 기능을 통해 본인 저장소를 생성합니다.
    ```bash
    https://github.com/syntekamarketing/clone-wanted-markup.git
    ```
2.  프로젝트 디렉토리로 이동합니다.
    ```bash
    cd clone-wanted-markup
    ```
3.  의존성을 설치합니다.
    ```bash
    yarn install
    ```

### 사용 가능한 스크립트

-   `yarn storybook`: Storybook을 실행합니다. (http://localhost:6006)
-   `yarn storybook:build`: Storybook을 정적 파일로 빌드합니다.
-   `yarn dev`: 로컬에서 프로젝트를 실행합니다.
