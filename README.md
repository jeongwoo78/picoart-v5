# 🎨 PicoArt v5

AI 아트 스타일 변환 웹 애플리케이션 - 최종 완성 버전

## ✨ 특징

- 🎨 6가지 예술 스타일 (Van Gogh, Picasso, Monet, Munch, Klimt, 수채화)
- ⚡ 빠른 변환 (10-20초)
- 📱 반응형 디자인
- 🔒 안전한 API 토큰 관리 (저장하지 않음)

## 🚀 배포 방법

### 1. GitHub Desktop 사용

1. **새 저장소 만들기**
   - File → Create New Repository
   - Name: `picoart-v5`
   - Local Path: 이 폴더 선택

2. **Publish**
   - "Publish repository" 클릭
   - Public으로 설정

### 2. Vercel 배포

1. https://vercel.com/new 접속
2. `picoart-v5` 저장소 Import
3. Deploy 클릭!

## 📁 파일 구조

```
picoart-v5/
├── index.html       # 메인 페이지
├── api/
│   ├── convert.js   # 변환 API
│   └── status.js    # 상태 확인 API
├── vercel.json      # Vercel 설정
└── README.md        # 이 파일
```

## 🧪 테스트

1. Replicate API 토큰 발급: https://replicate.com/account/api-tokens
2. 사진 업로드
3. 스타일 선택
4. 변환 시작!

## 💰 비용

- Vercel: 무료
- Replicate: 변환 1회당 약 $0.0059

---

**PicoArt v5 - Made with ❤️**
