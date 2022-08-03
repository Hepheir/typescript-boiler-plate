# Typescript boiler plate

Typescript로 간단한 Javascript 코드를 만들기 위한 프로젝트 세팅입니다.

## 사용 방법

### 초기 설정

```shell
npm install
```

### 테스트

```shell
npm run test
```

테스트 프레임워크는 jest를 사용합니다.

테스트를 위해 가상 DOM을 생성할 필요가 있을 수도 있습니다. 이때는 `jsdom`을 이용합니다.

### 빌드

```shell
npm run build
```

/dist/bundle.js 파일에 빌드된 자바스크립트 파일이 생성됩니다.

---

# 그 외

## 요구사항 

- Node.js

## 의존성

- jest
- babel-jest
- webpack
- webpack-cli
- ts-loader
- typescript
- lodash
- (optional) jsdom
