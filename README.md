# 자정의 기압계

태풍이 지나간 외딴 섬, 가랑도 국가기상관측소에서 소장이 숨진 채 발견됩니다. 해경 헬기가 뜨는 정오까지 관측소를 수색하고 용의자 여섯 명을 심문해서, 범인과 알리바이 트릭을 밝혀내는 three.js 머더 미스터리 보드게임입니다.

**▶ 바로 플레이: https://nalssi89.github.io/midnight-barograph/**

## 게임 방법

- 1~4인 핫시트(한 기기를 돌려 가며) 또는 솔로 플레이
- 06:30부터 11:30까지 11라운드, 라운드마다 행동 포인트로 **이동 · 수색 · 심문**
- 기압계 기록지, AWS 바람 자료, 출입 카드 기록 같은 단서를 모아 수첩에서 정리
- 마지막에 추리 보고서 5문항(범인 · 시각 · 방법 · 트릭 · 동기)을 제출하고, **범인과 트릭**을 모두 맞히면 해결

## 로컬에서 실행

빌드 과정 없이 파일 하나로 돌아갑니다. `index.html`을 브라우저로 열면 됩니다. three.js(r128)와 글꼴은 CDN에서 불러오므로 인터넷 연결이 필요합니다.

```bash
python -m http.server 8000   # http://localhost:8000
```

## 배포 (GitHub Pages)

저장소 **Settings → Pages → Build and deployment**에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 지정하면 위 주소로 공개됩니다.

## 구성

| 파일 | 내용 |
| --- | --- |
| `index.html` | 게임 전체 (HTML · CSS · JS 단일 파일, three.js r128) |
| `.nojekyll` | Pages가 Jekyll 처리 없이 파일을 그대로 내보내도록 함 |

> 정답은 코드 안에 들어 있습니다. 플레이 전에 소스를 열어보지 마세요.
