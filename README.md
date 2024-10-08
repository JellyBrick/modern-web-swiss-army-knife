# modern-web-swiss-army-knife

## 요약

라이브러리 하나로 모던 웹 99% 만들기

### 주의사항

 - npm 및 yarn legacy 환경에서만 동작합니다.
  - 패키지 호이스팅을 가정하고 만들어진 라이브러리입니다. (의도적인 ghost-deps)
  - pnpm에서는 정상 동작하지 않습니다. (별도의 설정이 필요합니다)

## 라이브러리 설명

- `@chakra-ui/react`: Chakra UI
- `@chromatic-com/storybook`: Storybook Util
- `@dotenvx/dotenvx`: `.env` reader
- `@egjs`: egjs 라이브러리 모음 (by naver)
  - `@egjs/axes`
  - `@egjs/conveyer`
  - `@egjs/grid`
  - `@egjs/imready`
  - `@egjs/persist`
  - `@egjs/react-flicking`
  - `@egjs/react-infinitegrid`
- `@emotion`: CSS-in-JS 라이브러리
  - `@emotion/babel-plugin`
  - `@emotion/babel-preset-css-prop`
  - `@emotion/css`
  - `@emotion/react`
  - `@emotion/styled`
- `@floating-ui`: 팝업 UI 위치 계산해주는 라이브러리
  - `@floating-ui/core`
  - `@floating-ui/dom`
  - `@floating-ui/react`
- `@fluentui`: ms Fluent UI 프레임워크
  - `@fluentui/react`
  - `@fluentui/react-components`
- `@headlessui/react`: UI 프레임워크
- `@hocuspocus`: Tiptap 에디터의 Collaborative Editing을 위한 라이브러리
  - `@hocuspocus/extension-database`
  - `@hocuspocus/extension-logger`
  - `@hocuspocus/provider`
  - `@hocuspocus/server`
  - `@hocuspocus/transformer`
- `@hono`: Hono 웹서버
  - `@hono/node-server`
  - `@hono/node-ws`
  - `@hono/swagger-ui`
  - `@hono/trpc-server`
  - `@hono/typia-validator`
  - `@hono/zod-openapi`
  - `@hono/zod-validator`
- `@hookform/resolvers`: `shadcn-ui`에서 사용
- `@linaria`: CSS-in-JS 라이브러리
  - `@linaria/core`
  - `@linaria/react`
- `@mantine`: UI 프레임워크
  - `@mantine/carousel`
  - `@mantine/charts`
  - `@mantine/code-highlight`
  - `@mantine/core`
  - `@mantine/dates`
  - `@mantine/dropzone`
  - `@mantine/form`
  - `@mantine/hooks`
  - `@mantine/modals`
  - `@mantine/notifications`
  - `@mantine/nprogress`
  - `@mantine/spotlight`
  - `@mantine/tiptap`
- `@mui`: Material UI 프레임워크
  - `@mui/base`
  - `@mui/icons-material`
  - `@mui/material`
  - `@mui/system`
  - `@mui/x-charts`
  - `@mui/x-data-grid`
  - `@mui/x-date-pickers`
  - `@mui/x-tree-view`
- `@radix-ui`: UI 프레임워크 (shadcn-ui용)
  - `@radix-ui/react-accordion`
  - `@radix-ui/react-alert-dialog`
  - `@radix-ui/react-aspect-ratio`
  - `@radix-ui/react-avatar`
  - `@radix-ui/react-checkbox`
  - `@radix-ui/react-collapsible`
  - `@radix-ui/react-context-menu`
  - `@radix-ui/react-dialog`
  - `@radix-ui/react-dropdown-menu`
  - `@radix-ui/react-hover-card`
  - `@radix-ui/react-label`
  - `@radix-ui/react-menubar`
  - `@radix-ui/react-navigation-menu`
  - `@radix-ui/react-popover`
  - `@radix-ui/react-progress`
  - `@radix-ui/react-radio-group`
  - `@radix-ui/react-scroll-area`
  - `@radix-ui/react-select`
  - `@radix-ui/react-separator`
  - `@radix-ui/react-slider`
  - `@radix-ui/react-slot`
  - `@radix-ui/react-switch`
  - `@radix-ui/react-tabs`
  - `@radix-ui/react-toast`
  - `@radix-ui/react-toggle`
  - `@radix-ui/react-toggle-group`
  - `@radix-ui/react-tooltip`
- `@react-spring/web`: React Spring 애니메이션 라이브러리
- `@solid-primitives`: solid-js용 유틸리티 라이브러리
  - `@solid-primitives/active-element`
  - `@solid-primitives/audio`
  - `@solid-primitives/clipboard`
  - `@solid-primitives/connectivity`
  - `@solid-primitives/context`
  - `@solid-primitives/controlled-props`
  - `@solid-primitives/date`
  - `@solid-primitives/destructure`
  - `@solid-primitives/devices`
  - `@solid-primitives/event-bus`
  - `@solid-primitives/event-listener`
  - `@solid-primitives/event-props`
  - `@solid-primitives/fetch`
  - `@solid-primitives/fullscreen`
  - `@solid-primitives/graphql`
  - `@solid-primitives/immutable`
  - `@solid-primitives/intersection-observer`
  - `@solid-primitives/jsx-tokenizer`
  - `@solid-primitives/keyed`
  - `@solid-primitives/map`
  - `@solid-primitives/media`
  - `@solid-primitives/memo`
  - `@solid-primitives/mouse`
  - `@solid-primitives/mutable`
  - `@solid-primitives/mutation-observer`
  - `@solid-primitives/page-visibility`
  - `@solid-primitives/permission`
  - `@solid-primitives/promise`
  - `@solid-primitives/props`
  - `@solid-primitives/raf`
  - `@solid-primitives/range`
  - `@solid-primitives/refs`
  - `@solid-primitives/resize-observer`
  - `@solid-primitives/resource`
  - `@solid-primitives/rootless`
  - `@solid-primitives/scheduled`
  - `@solid-primitives/script-loader`
  - `@solid-primitives/set`
  - `@solid-primitives/share`
  - `@solid-primitives/signal-builders`
  - `@solid-primitives/state-machine`
  - `@solid-primitives/static-store`
  - `@solid-primitives/storage`
  - `@solid-primitives/stream`
  - `@solid-primitives/timer`
  - `@solid-primitives/transition-group`
  - `@solid-primitives/tween`
  - `@solid-primitives/websocket`
- `@solidjs/router`: SolidJS 라우터
- `@stitches/react`: CSS-in-JS 라이브러리
- `@storybook`: UI 테스팅 & 프리뷰 프레임워크
  - `@storybook/addon-docs`
  - `@storybook/addon-essentials`
  - `@storybook/addon-interactions`
  - `@storybook/addon-links`
  - `@storybook/addon-onboarding`
  - `@storybook/blocks`
  - `@storybook/react`
  - `@storybook/react-vite`
  - `@storybook/test`
- `@suid`: solid-js 용 material UI 라이브러리
  - `@suid/icons-material`
  - `@suid/material`
  - `@suid/vite-plugin`
- `@suspensive/react`: React Suspense 라이브러리
- `@suyongs/solid-utility`: solid-js용 유틸리티 라이브러리
- `@svgr/plugin-svgo`: svg를 react 컴포넌트로 변환해주는 라이브러리
- `@swc`: Rust로 만든 TypeScript 컴파일러
  - `@swc/cli`
  - `@swc/core`
- `@tailwindcss/typography`: Tailwind용 Typography 플러그인
- `@tanstack`: TanStack 라이브러리 모음
  - `@tanstack/react-query`: react-query
  - `@tanstack/react-virtual`: virtualization
  - `@tanstack/solid-query`: solid용 query
  - `@tanstack/solid-virtual`: solid용 virtualization
- `@tiptap`: wysiwyg 에디터
  - `@tiptap/extension-collaboration`
  - `@tiptap/extension-collaboration-cursor`
  - `@tiptap/pm`
  - `@tiptap/react`
  - `@tiptap/starter-kit`
- `@total-typescript/ts-reset`: TypeScript 설정 리셋 라이브러리
- `@types`: 타입 지원용
  - `@types/axios`
  - `@types/color`
  - `@types/d3`
  - `@types/d3-array`
  - `@types/hammerjs`
  - `@types/luxon`
  - `@types/node`
  - `@types/node-forge`
  - `@types/react`
  - `@types/react-dom`
  - `@types/stylis`
  - `@types/three`
  - `@types/turndown`
  - `@types/uuid`
- `@typescript-eslint/eslint-plugin`: ts용 eslint 플러그인 1
- `@typescript-eslint/parser`: ts용 eslint 플러그인 2
- `@use-gesture/react`: 제스쳐 라이브러리 (react용)
- `@use-gesture/vanilla`: 제스쳐 라이브러리 (vanilla용)
- `@vanilla-extract`: CSS-in-JS 라이브러리
  - `@vanilla-extract/css`
  - `@vanilla-extract/css-utils`
  - `@vanilla-extract/dynamic`
  - `@vanilla-extract/recipes`
  - `@vanilla-extract/rollup-plugin`
  - `@vanilla-extract/sprinkles`
  - `@vanilla-extract/vite-plugin`
- `@vitejs/plugin-react-swc`: react vite 플러그인 (swc용)
- `@wyw-in-js`: `@linaria`용 유틸리티
  - `@wyw-in-js/babel-preset`
  - `@wyw-in-js/vite`
- `allotment`: pane 라이브러리 (react용)
- `antd`: UI 프레임워크
- `atropos`: 3D Parallax 라이브러리
- `autoprefixer`: tailwind용
- `axios`: HTTP 클라이언트
- `babel`: JS Transpiler
  - `babel-preset-react`
  - `babel-preset-solid`
- `builtin-modules`: node.js 내장 모듈 리스트 가져오는 라이브러리 (번들러용 유틸리티)
- `class-variance-authority`: CSS-in-JS 라이브러리 (tailwind용)
- `clsx`: CSS 클래스 조합 라이브러리
- `cmdk`: shadcn-ui용 라이브러리
- `color`: 색상 관련 라이브러리
- `concurrently`: 스크립트 병렬 실행 라이브러리
- `d3`: 데이터 시각화 라이브러리
  - `d3-array`
- `date-fns`: 날짜 관련 라이브러리 (moment 대체 1)
- `dayjs`: 날짜 관련 라이브러리 (moment 대체 2)
- `deepmerge-ts`: 객체 병합 라이브러리
- `embla-carousel-react`: shadcn-ui용 라이브러리
- `emotion-solid`: `@emotion`을 solid-js에서 사용하기 위한 라이브러리
- `es-hangul`: 한글 유틸리티 라이브러리
- `es-toolkit`: lodash같은 JS 유틸리티 라이브러리
- `esbuild`
- `eslint`: 코드 품질 검사 
  - `eslint-import-resolver-typescript`
  - `eslint-plugin-import`
  - `eslint-plugin-prettier`
  - `eslint-plugin-react-hooks`
  - `eslint-plugin-react-refresh`
  - `eslint-plugin-solid`
- `fast-average-color`: 이미지 색상 추출 라이브러리
- `framer-motion`: react용 애니메이션 라이브러리
- `hammerjs`: 제스처 라이브러리
- `hono`: hono 웹서버 (@hono와 동일)
  - `hono-rate-limiter`
- `immutable`: 불변 객체 라이브러리
- `input-otp`: `shadow-ui`용 라이브러리
- `jotai`: 상태 관리 라이브러리 (react용)
- `jotai-cache`: jotai 플러그인
- `jsonwebtoken`: jwt 라이브러리
- `lightningcss`: css 파서
- `lossless-json`: recursive한 JSON도 제대로 파싱해주는 라이브러리
- `lucide-react`: shadcn-ui용
- `luxon`: 날짜 라이브러리 (moment 대체 3)
- `magic-regexp`: regexp 빌더
- `matter-js`: 2D 물리 라이브러리
- `moment`: 날짜 라이브러리 (deprecated, 비추)
- `msw`: API Mocking 라이브러리
- `nanoid`: unique한 ID 생성하는 라이브러리
- `next-themes`: shadcn-ui용
- `node-forge`: 브라우저단 암호화 라이브러리
- `overlay-kit`: 오버레이(toast, modal 등)들 제어용 라이브러리
- `patch-package`: npm 패키지 수정 라이브러리
- `peerjs`: webrtc 라이브러리
- `postcss`: css 후처리기
  - `postcss-loader`
  - `postcss-preset-mantine`
  - `postcss-simple-vars`
- `prettier`: 코드 포맷터
- `prisma`: ORM 라이브러리
- `prop-types`: prop 타입 체크 라이브러리
- `prosemirror`: Tiptap의 base 에디터
  - `prosemirror-dev-toolkit`
  - `prosemirror-history`
  - `prosemirror-inputrules`
  - `prosemirror-markdown`
  - `prosemirror-model`
  - `prosemirror-transform`
  - `prosemirror-view`
- `react`: 리액트
- `react-day-picker`: `shadcn-ui`용
- `react-dom`: 리액트 DOM
- `react-flip-toolkit`: MAGIC 애니메이션 라이브러리
- `react-hook-form`: form 라이브러리 (shadow-ui용)
- `react-resizable-panels`: panel 라이브러리
- `react-router`: 리액트 라우터
- `react-theme-provider`: 테마 프로바이더 라이브러리
- `react-three-fiber`: Three.js 래퍼 라이브러리
- `react-transition-group`: 리액트 애니메이션 라이브러리
- `react-virtualized`: virtualization 라이브러리 1
- `react-virtuoso`: 리액트 최고존엄 virtualization 라이브러리
- `react-window`: virtualization 라이브러리 2
- `recoil`: 상태 관리 라이브러리 (react용)
- `reflect-metadata`: ts legacy decorator에 metadata를 추가하는 라이브러리 (`typeorm`용)
- `remark-gfm`: markdown 파서 (github향 첨가)
- `rollup`: 롤업
- `rooks`: 리액트용 훅 라이브러리
- `semver`: 버저닝 라이브러리
- `serve`: 파일 서빙용 서버 유틸리티
- `solid-floating-ui`: `@floating-ui`의 solid-js용 라이브러리
- `solid-js`: react 대체 라이브러리 (react보다 빠르고 간편함)
- `solid-tiptap`: `@tiptap`의 solid-js용 라이브러리
- `solid-transition-group`: solid-js 애니메이션 라이브러리
- `sonner`: shadow-ui용 라이브러리
- `storybook`: 위 설명 참고
  - `storybook`
  - `storybook-solidjs`
  - `storybook-solidjs-vite`
- `styled-components`: CSS-in-JS 라이브러리
- `stylis`: lightweight css 파서
- `tailwind-merge`: tailwind class 병합 유틸리티
- `tailwindcss`: tailwind
- `tailwindcss-animate`: tailwind 애니메이션 플러그인
- `terser`: JS 압축기
- `three`: 3D 라이브러리
- `ts-pattern`: ts 패턴 매칭 라이브러리
- `ts-regex-builder`: ts regexp 빌더
- `tstl`: stl ts버전
- `tsx`: node-ts 대용품 (ts 바로 실행가능)
- `turndown`: 마크다운 파서
- `type-fest`: 타입 유틸리티 라이브러리
- `typeorm`: ORM 라이브러리
- `typescript`: 타입스크립트
- `typia`: samchon 깃허브 참고
- `use-gesture`: 제스처 라이브러리
- `uuid`: uuid v4 생성 라이브러리
- `vaul`: `shadow-ui`용 라이브러리
- `vite`: 최고 존엄 번들러
  > (발음법: "veet"와 비슷한 _**/vit/**_ 입니다.)
- `vite-plugin-react`: react용 vite 플러그인
- `vite-plugin-solid`: solid-js용 vite 플러그인
- `vite-plugin-static-copy`: vite용 파일 복사 플러그인
- `vite-plugin-svgr`: svgr vite 플러그인
- `vitest`: 테스팅 라이브러리
- `wouter`: 경량화된 react router
- `y-prosemirror`: prosemirror 라이브러리
- `zod`: type validation 라이브러리
- `zustand`: 상태 관리 라이브러리 (react용)
