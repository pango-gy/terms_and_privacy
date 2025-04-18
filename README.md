# Pango-GY 서비스 약관 및 개인정보처리방침 관리

이 레포지토리는 **Pango-Gy에서 제공하는 각 서비스의 이용약관 및 개인정보처리방침을 관리하고, GitHub Pages를 통해 이를 쉽게 서빙하기 위한 목적**으로 운영됩니다.

---

## 🏢 **레포지토리 목적**

- **각 서비스의 약관 및 개인정보처리방침을 통합 관리**하여 최신 버전으로 유지
- **GitHub Pages를 활용하여 쉽게 공유 및 배포**
- **각 서비스별 개별 정책 문서 관리 및 접근 편의성 제공**

---

## 📂 **디렉토리 구조**

이 레포지토리는 `docs/` 디렉토리를 기준으로 운영되며, 각 서비스별 약관 및 정책 문서는 서비스 이름별 폴더 아래 정리됩니다.

```
/docs
├── _config.yml          # GitHub Pages 및 Jekyll 설정 파일
├── index.md            # 메인 페이지
├── 서비스명1/          # 각 서비스별 약관 및 정책 폴더
│   ├── index.md       # 서비스 소개 및 문서 목록
│   ├── terms.md       # 서비스 이용약관
│   ├── privacy.md     # 개인정보처리방침
│   └── 기타 정책 문서   # 추가 가능
│
├── 서비스명2/
│   ├── index.md
│   ├── terms.md
│   ├── privacy.md
│   └── 기타 정책 문서
```

---

## 🌐 **GitHub Pages에서 보기**

이 레포지토리는 GitHub Pages를 통해 정적 웹사이트로 제공되며, 아래 URL에서 확인할 수 있습니다.

> 📌 **서비스 약관 페이지:**  
> `https://pango-gy.github.io/<레포지토리명>/`

> 📌 **특정 서비스의 약관 페이지 예시:**  
> `https://pango-gy.github.io/<레포지토리명>/서비스명/terms`

> 📌 **특정 서비스의 개인정보처리방침 예시:**  
> `https://pango-gy.github.io/<레포지토리명>/서비스명/privacy`

---

## 🛠️ **레포지토리 사용 방법**

### 1️⃣ **새로운 서비스 추가**

새로운 서비스의 약관 및 개인정보처리방침을 추가하려면 다음 단계를 따르세요.

1. `docs/` 디렉토리 내 해당 서비스명 폴더를 생성합니다.
2. 서비스 폴더 내 `index.md`, `terms.md`, `privacy.md` 파일을 추가하고 내용을 작성합니다.
3. 필요한 경우, 추가적인 정책 문서를 생성할 수 있습니다.
4. 변경 사항을 커밋하고 푸시하면 자동으로 GitHub Pages에 반영됩니다.

### 2️⃣ **기존 문서 수정**

기존 문서를 수정할 경우, 해당 `.md` 파일을 편집한 후 커밋 & 푸시하면 자동 반영됩니다.

### 3️⃣ **GitHub Pages 설정 확인**

GitHub Pages가 `docs/` 디렉토리를 기준으로 동작하도록 **Settings > Pages**에서 아래와 같이 설정합니다.

- **Source:** `Deploy from a branch`
- **Branch:** `main` (또는 원하는 브랜치)
- **Folder:** `/docs`

---

## 📌 **문의 및 기여**

- 본 레포지토리에 대한 문의나 개선 제안은 **이슈(issue)를 등록**하여 공유해주세요.
- 회사 내부 구성원은 직접 수정 후 PR을 생성하여 변경을 반영할 수 있습니다.

---

**🔹 Pango-Gy 운영팀**
