# 🚀 [Nuami-AI]

> AI 문화 액션 카드 제공 서비스(차후 수정 필)

<br>

## 👋 About Us
  
[팀원 소개, 서비스 정보 등]

- 🌐 Website: [https://google.com](https://google.com)
- 📧 Email: xx@xx.xx
- 📝 Blog: [https://google.com](https://google.com)

<br>

## 📁 Repositories

> 💡 Repository란? 하나의 프로젝트 폴더. Service or Feature 단위로 구분하여 생성

<br>

## ✍️ Conventions

### Branch 구분

작업 목적에 맞게 Branch를 나눠서 작업할 것.  
버전 관리 및 기능 업데이트 시 충돌 위험 최소화를 위함.

```
main          ← 실제 서비스에 배포되는 최종본. 직접 수정 금지 ⛔
develop       ← 개발 중인 내용을 모아두는 곳
feat/[이름]   ← 새 기능을 만들 때
fix/[이름]    ← 버그를 고칠 때
```

### Commit Message

작업 내용을 저장(Commit)할 때는 아래 형식을 따를 것.  
나중에 누가 봐도 무슨 작업인지 바로 알 수 있어야 함.

```
feat: 로그인 기능 추가
fix: 버튼이 안 눌리는 문제 수정
docs: 회원가입 안내 문구 수정
style: 버튼 색상 변경
```

| Prefix | 언제 쓰나? |
|---|---|
| `feat` | 새로운 기능을 만들었을 때 |
| `fix` | 오류나 버그를 고쳤을 때 |
| `docs` | 문서나 설명글을 수정했을 때 |
| `style` | 디자인, 색상 등 겉모습만 바꿨을 때 |
| `chore` | 설정 파일 등 기타 잡무 |

### Pull Request (PR)

- 작업이 끝나도 바로 Merge 금지. 팀원 **최소 1명의 Approve** 후 Merge할 것.
- PR 올릴 때 **무엇을 바꿨는지**, **어떻게 테스트했는지** 간단히 적을 것.
- UI가 바뀐 경우 **Screenshot 필수 첨부**할 것.

<br>

## 🔐 보안

- ❌ 비밀번호, API Key 등 **민감한 정보는 절대 코드에 직접 적지 말 것.**
- ✅ 민감한 정보는 `.env` 파일로 별도 관리할 것.
- 🚨 실수로 올라간 경우, 즉시 팀 전체에 알리고 함께 대응할 것.

<br>

## 📋 작업 관리

- 모든 작업은 **GitHub Issues** 에 먼저 등록 후 시작할 것.
- 진행 상황은 **GitHub Projects** 보드 or Slack 등 업무관리도구에서 관리할 것.
- Issue 없이 작업 시작하지 말 것. (긴급 대응(Hot fix)의 경우, 사후보고)

<br>

## 👥 Team

| 이름 | 역할 | GitHub |
|---|---|---|
| Jay | CEO / Lead | [@username](https://github.com/username) |
| Siri | COO | [@username](https://github.com/username) |
| Dion | CTO | [@username](https://github.com/username) |

<br>

---

<p align="center">Made with ❤️ by [Organization Name] Team</p>
