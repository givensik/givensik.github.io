# 📚 개인 자료실 사용 가이드

## 🎯 개요
이 자료실은 개인 파일들을 체계적으로 관리하고 공유할 수 있는 웹 기반 플랫폼입니다.

## 📁 파일 카테고리

### 📖 페이지로 보기
- **HTML 파일** (`.html`, `.htm`): 웹페이지로 직접 열림
- **Markdown 파일** (`.md`): 마크다운 문서로 표시
- **텍스트 파일** (`.txt`): 일반 텍스트로 표시

### 📥 다운로드
- **문서 파일**: PDF, Word, PowerPoint, Excel
- **이미지 파일**: PNG, JPEG, GIF, SVG
- **비디오 파일**: MP4, AVI, MOV
- **코드 파일**: JavaScript, CSS, Python 등
- **압축 파일**: ZIP, RAR, 7Z

## 🚀 사용 방법

### 1. 파일 추가
1. `public/files/` 하위 폴더에 파일 복사
2. `public/data/files.json`에 파일 정보 추가

### 2. 파일 정보 형식
```json
{
  "id": 12,
  "name": "파일명.확장자",
  "path": "/files/폴더/파일명.확장자",
  "category": "documents",
  "size": "1.2MB",
  "uploadDate": "2024-02-03",
  "description": "파일 설명"
}
```

### 3. 배포
```bash
npm run build
npm run deploy
```

## 💡 팁
- HTML 파일은 새 탭에서 열립니다
- Markdown 파일은 마크다운 형식으로 렌더링됩니다
- 다른 파일들은 자동으로 다운로드됩니다

## 🔧 기술 스택
- **Frontend**: React + Vite
- **Hosting**: GitHub Pages
- **Styling**: CSS3 with modern features

---
*이 문서는 개인 자료실의 사용법을 설명합니다.*
