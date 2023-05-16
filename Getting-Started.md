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
* dev : Next.js 개발 모드 시작 명령어
* build : 프로덕션 사용을 위한 애플리케이션 빌드 명령어
* start : Next.js 프로덕션 서버 시작 명령어
* lint : Next.js의 기본 제공 ESLint 구성 설정 명령어 <br/><br/>
## Manual Installation - Create the app folder
앱 폴더를 만들고 layout.tsx 및 page.tsx 파일을 추가한다. 사용자가 응용프로그램 루트를 방문할 때 해당 정보가 렌더링된다. <br/>
## Manual Installation - Create the public folder
선택적으로 이미지, 글꼴 등의 정적 자산을 저장할 공용 폴더를 만들 수 있다. 이는 공용 디렉토리 내의 파일을 기본 URL(/)에서 시작하는 코드로 참조가능하게 한다. <br/><br/>
## Run the Development Server
1. **npm run dev**를 실행하여 개발 서버를 시작한다.
2. 프로그램을 보려면 http://localhost:3000을 방문하면 된다.
