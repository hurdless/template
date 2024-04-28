# template

`template`은 `Typescipt` 기반 라이브러리를 만들기 위해 최소한의 프로젝트 기본 구조를 세팅할 수 있도록 도와줍니다.

{npm | yarn | pnpm} publish cli를 입력하면 [tsup](https://www.npmjs.com/package/tsup)  라이브러리를 활용하여 ESM, CommonJS 환경 모두 구현된 라이브러리를 사용할 수 있게 됩니다.
라이브러리의 진입점 `./lib/index.ts` 파일에 구현한 라이브러리 함수를 `export` 하면 됩니다.

