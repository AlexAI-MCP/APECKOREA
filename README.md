# 🇰🇷 2025 Korea AI & Security Summit

2025 대한민국 AI·안보·국제협력 APEC 경주 정상회의와 새로운 도약에 대한 정보를 제공하는 웹사이트입니다.

## 📋 주요 내용

- **한미 경제협력**: 관세 인하 합의 및 대규모 투자 프로젝트
- **핵추진 잠수함**: 동북아 군사질서의 새로운 전환점
- **AI 동맹**: 글로벌 AI 허브로의 도약
- **APEC 정상회의**: 세계가 주목한 순간
- **종합 요약**: 대한민국의 새로운 위상

## 🚀 기능

- ✨ 반응형 디자인 (모바일, 태블릿, 데스크톱)
- 🌙 다크 모드 지원
- 📱 모바일 메뉴
- 🎯 부드러운 스크롤 네비게이션
- 🔗 섹션별 앵커 링크
- 🎨 현대적이고 깔끔한 UI/UX
- 💫 스크롤 애니메이션 효과
- 📤 공유 기능

## 🛠️ 기술 스택

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Backend**: Node.js, Express.js
- **Deployment**: Railway
- **Features**: Responsive Design, Dark Mode, Smooth Scrolling

## 📦 설치 및 실행

### 로컬 개발 환경

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm start
```

서버가 시작되면 `http://localhost:3000`에서 확인할 수 있습니다.

## 🚂 Railway 배포

### 자동 배포

1. Railway 계정에 로그인
2. "New Project" 클릭
3. "Deploy from GitHub repo" 선택
4. 이 저장소 선택
5. Railway가 자동으로 감지하고 배포

### 환경 변수

필요한 환경 변수는 없습니다. Railway는 자동으로 `PORT`를 설정합니다.

### 배포 확인

- Health check endpoint: `/health`
- Railway가 제공하는 URL로 접속 가능

## 📁 프로젝트 구조

```
APECKOREA/
├── public/
│   └── index.html          # 메인 HTML 페이지
├── server.js               # Express 서버
├── package.json            # 프로젝트 의존성
├── railway.json            # Railway 배포 설정
├── .gitignore             # Git 무시 파일
└── README.md              # 프로젝트 문서
```

## 🎨 디자인 특징

- **컬러 스키마**:
  - Primary: #0073e6 (블루)
  - Light Background: #f5f7f8
  - Dark Background: #0f1923

- **타이포그래피**: Inter 폰트 패밀리
- **아이콘**: Material Symbols Outlined
- **레이아웃**: Container-based responsive grid

## 🌐 네비게이션

웹사이트는 다음 섹션으로 구성되어 있습니다:

1. **Hero Section** (#hero) - 메인 배너
2. **한미 경제협력** (#tariffs) - 관세협상 및 투자
3. **핵추진 잠수함** (#security) - 안보 협력
4. **AI 동맹** (#ai) - AI 기술 협력
5. **APEC 정상회의** (#apec) - 국제 협력
6. **종합 요약** (#summary) - 핵심 내용 정리

## 📱 브라우저 지원

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)
- 모바일 브라우저 (iOS Safari, Chrome Mobile)

## 🔧 커스터마이징

### 색상 변경
`public/index.html`의 Tailwind 설정에서 색상을 변경할 수 있습니다:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                "primary": "#0073e6", // 원하는 색상으로 변경
                // ...
            }
        }
    }
}
```

### 내용 수정
각 섹션의 내용은 `public/index.html`에서 직접 수정할 수 있습니다.

## 📄 라이선스

MIT License

## 👤 작성자

Korea AI & Security Summit Team

## 🙏 기여

이슈나 풀 리퀘스트를 환영합니다!

---

Made with ❤️ for Korea's Future
