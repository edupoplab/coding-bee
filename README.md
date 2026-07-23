# 🐝 coding-bee — 길찾기 코딩놀이 (Bee Path)

유아(만 3~5세)를 위한 **컴퓨팅 사고력** 디지털 놀이입니다.
꿀벌이 목표까지 가는 길을 **미리 예상하고**, 방향 화살표로 명령을 순서대로 쌓은 뒤 **출발**을 눌러 결과를 확인합니다.
순서(알고리즘) · 예측 · 오류 수정(디버깅) · 방향/위치 · 규칙을 놀이로 익혀요.

> Coding-play that grows computational thinking in young children (ages 3–5): predict the path, stack direction commands in order, press start, and check the result.

## 🎮 바로 놀기 (Live Demo)

GitHub Pages를 켜면 아래 주소에서 열립니다. (`USERNAME`을 본인 아이디로 바꾸세요)

```
https://USERNAME.github.io/coding-bee/
```

## ✨ 주요 기능

- **세 가지 모드**: 바로 놀기(난이도 직접 선택) · 도전 모드(단계 지도로 점점 어려워짐) · 내가 만들기(자기 판 제작)
- **아이별 프로필**: 아바타 + 이름으로 각자 별·진행을 따로 저장, "여러 명 만들기"로 한 번에 등록
- **보상**: 별을 모으면 새 친구(캐릭터) 잠금 해제, 스티커판
- **음성 안내**: "위로!", "출발!", "잘했어요!" (소리·음성 끄기 가능)
- **교사 안전장치**: 삭제·초기화·프로필 편집은 '어른 확인'(간단한 덧셈) 뒤에서만
- 인터넷 없이 단일 HTML로 작동, 태블릿·PC 터치/클릭 지원

## 📄 교사용 안내서

- 인트로 화면의 **"교사용 안내서 (선생님용)"** 버튼 → 유아 오작동 방지 질문(**개정 누리과정은 몇 년? → 2019**)에 답하면 열립니다.
- 파일: [`teacher-guide.pdf`](./teacher-guide.pdf)
- 내용: 2019 개정 누리과정 연계, 「따뜻한 AI 교육」 5대 요소 매핑, 수업 운영·발문·관찰평가·자가 점검표

## 🚀 배포 방법 (GitHub Pages)

1. 이 저장소에 **`index.html`** 과 **`teacher-guide.pdf`** 를 같은 폴더(루트)에 올립니다.
2. **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**
3. 1~2분 뒤 `https://USERNAME.github.io/coding-bee/` 에서 놀이가 열립니다.

> 두 파일은 반드시 같은 폴더에 있어야 안내서 링크가 작동합니다. 로컬에서 `index.html`을 더블클릭해도 동일하게 작동해요.
> 안내서 파일 이름을 바꾸려면 `index.html` 안의 `const GUIDE_URL='./teacher-guide.pdf'` 한 줄을 수정하세요.

## 📁 구성 파일

| 파일 | 설명 |
|---|---|
| `index.html` | 놀이 본체 (단일 HTML) |
| `teacher-guide.pdf` | 교사용 지도 안내서 |
| `README.md` | 이 문서 |

## ©️ 저작권

ⓒ 2026 **edulab_pop · 놀이팝**. All rights reserved.
이 놀이와 안내서의 저작권은 제작자에게 있으며, 무단 복제·배포를 금합니다.
