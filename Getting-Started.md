## Automatic Installation(권장)

```
npx create-next-app@latest
```

## Manual Installation

```
npm install next@latest react@latest react-dom@latest
```
```json: package.json
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  }
}
```
* ** dev ** : Next.js 개발 모드 시작 명령어
* <span style="background-color:#fff5b1"> build </span>: 프로덕션 사용을 위한 애플리케이션 빌드 명령어
* <span style="background-color:#fff5b1"> start </span>: Next.js 프로덕션 서버 시작 명령어
* <span style="background-color:#fff5b1"> lint </span>: Next.js의 기본 제공 ESLint 구성 설정 명령어
