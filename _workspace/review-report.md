판정. REDO

사유.
1. 형식 위반 — 프로젝트 규칙(CLAUDE.md)은 `type(scope): subject` 형식을 명시하나, 제목 `docs: add README`에는 scope가 없다.
2. 제목 길이(72자 이하)·명령형 시제는 기준 충족.
3. 본문 내용은 `git diff --cached`(README.md 신규 추가, 내용 `# my-first-harness`)와 사실 불일치 없음 — "초기 README 추가로 프로젝트 스캐폴드 확립"이라는 서술은 diff 범위를 벗어나지 않음.

수정 지시.
- 제목에 scope를 추가할 것. 예: `docs(readme): add README`
- 본문은 현재 내용 그대로 유지 가능 (사실 일치, 3줄 이내 충족).
