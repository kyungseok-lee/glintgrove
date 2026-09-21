# 문서 안내

현재 실행·배포 방법은 [프로젝트 README](../README.md), 소스와 에셋의 위치는
[폴더 안내](../FOLDERS.md), 편집·내보내기는 [아트 작업실](../art/README.md)을 따릅니다.
GitHub Pages의 현재 주소는 [공개 게임](https://kyungseok-lee.github.io/glintgrove/)이며,
`main` 루트 게시에서 `_config.yml`의 제외 목록을 적용합니다.

## 현재 제작과 유지보수

| 대상 | 기준 문서 |
| --- | --- |
| 아트 조회·로컬 보관함 | [아트 스튜디오](art/art-studio.md) |
| 화면 방향 | [아트 방향](art/art-direction.md) |
| 숲 v6·석문 v2 | [고대 숲 제작](../art/recipes/ancient-forest-v6.md) |
| 게임명 이미지 v2 | [제작과 갱신](../art/recipes/jeweled-title-v2.md) |
| 96초 음악 v2 | [악보·합성과 검증](../art/recipes/ancient-forest-v2-music.md) |
| 300개 퍼즐 생성기 | [레벨 제작·재현](art/remade-levels.md) |
| 즉시 표시하는 광선 | [빛 발사 v3](design/beam-emission-v3.md) |
| 메인 버튼 | [황동 프레임 v3](design/title-buttons-v3.md) |
| 제작 경위와 현재 파일 해시 | [재제작 이력](legal/remake-audit.md), [파일 명부](legal/replacement-register.json) |
| 제작 스크립트 라이선스 | [범위별 고지](../tools/art/LICENSES.md), [사용물 고지](../THIRD_PARTY_NOTICES.md) |

## 날짜별 기록 읽기

`docs/art/*verification.md`, `browser-qa.md`, `progression-fix.md`와
`docs/design/`의 설계·독립 검토는 작성일 당시의 구현과 검사 결과를 보존합니다.
과거 테스트 수·캐시 버전·화면 크기·명령·경로를 현재 검사 결과로 해석하지 않습니다.
최신 실행은 README의 검사 명령과 실제 소스를 기준으로 확인합니다.

`reference-research.md`, `commercial-reference-recheck.md`, `model-access.md`는
당시 외부 자료와 도구 접근 조사입니다. 이후 새 이미지 생성 또는 제작 변경을
소급해 입증하지 않습니다. `remade-ui.md`는 초기 재제작 기록으로, 이후 게임명·색
표식·광선 변경은 위 현재 문서에서 확인합니다.

v2/v3 Blender 배경과 GPT 숲 v4, v1 타이틀·72초 음악의 레시피는 부모 원본과
재현 절차를 보존합니다. 현재 카탈로그·로더에 연결되는 버전은 위 표를 따릅니다.
원래 생성 프롬프트, 입력·출력 해시, 법률 조사 및 캡처·시험 로그는 당시 증거로
유지하며 현재 상태에 맞춰 다시 쓰지 않습니다.

[초기 개발 사이클](../CYCLES.md), `docs/legal/history/`,
[전체 작업 보관 폴더](../art/history/2026-09-14-complete-work/README.md)의
스냅샷·이전 배포물은 역사 자료입니다. 과거 파일 경로는 보관 `inventory.json`의
원래 경로와 현재 보관 경로를 대조합니다. GitHub 이름 변경 전 관찰 URL은
해당 증거 JSON의 `usernameMigration` 안내와 함께 읽습니다.
