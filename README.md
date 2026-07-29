# 간파 (PivotDuel) — 플레이 빌드

**▶ 플레이: https://kjh6036.github.io/NAN2026-play/**

NHN NAN 2026 게임×AI 해커톤 예선 사전 과제 제출물입니다.
이 저장소는 **웹 빌드 산출물만** 담고 있습니다. 전체 소스 코드와 커밋 이력은
심사용 비공개 저장소에 있으며 심사 계정을 초대해 두었습니다.

브라우저에서 링크를 열면 바로 플레이됩니다. 설치가 필요 없습니다.

## 게임

1인칭 대결. 적 드론은 몸이 아니라 **가슴의 작은 코어**를 맞혀야 죽습니다.
탄약은 유한하고, 라운드를 깰 때마다 보급 카드 3장 중 하나를 고릅니다.

**적은 당신의 무기 선택 패턴을 한 판 안에서 학습합니다.**
n-gram이 다음 무기를 예측하고, 온라인 Q러닝이 그 상황에서 무엇을 할지 고릅니다.
사전 학습 모델도, 서버 추론도 없습니다.

## 조작

| | |
|---|---|
| 이동 | WASD |
| 지향사격 | 좌클릭 — 빠른 연사 · 낮은 피해 |
| 조준사격 | 우클릭으로 전환 — 느림 · 약점 명중 시 즉사 |
| 수류탄 | G — 반경 안은 무조건 즉사. **판 전체에서 2발** |
| 재장전 | R |

화면을 한 번 클릭하면 시작합니다.

## 실행 환경

WebGL. Chrome·Edge·Firefox 최신 버전에서 동작합니다.
최초 로딩에 약 64 MB를 내려받습니다.

---

## 크레딧 · 에셋 출처

### Sketchfab — CC BY 4.0 (저작자 표시 필수)

이 빌드에는 아래 저작자들의 3D 모델이 포함되어 있습니다.

| 에셋 | 저작자 |
|---|---|
| Sci-Fi Flying Drone Robot | **PolyNeast** |
| Sci-fi Assault Riffle | **Fearell** |
| Sci-fi Corridor | **Eliu_Villanueva** |
| Sci-Fi Corridor - Revisited 2019 | **Robert Berrier** |
| Sci-fi Spaceship Corridor | **J4747** |
| SCI FI HANGAR | **Kerem Kavalci (Keremz)** |
| Monitoring Station · Lumen hologram Table · GeoSynth Table | **PolyPhantom** |
| Low Poly Space Fighter | **Mesh-Base** |
| Industrial robotic arm | **Mibisa** |
| Sci-Fi Laboratory Op Table | **Michael V (bossdeff)** |

라이선스: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

### NASA — 크레딧 표기 (저작권 주장 없음)

- **Deep Star Maps 2020** — *NASA/Goddard Space Flight Center Scientific Visualization Studio*
  · <https://svs.gsfc.nasa.gov/4851/>
- **Cassini 목성 전구 맵 (PIA02864)** — *NASA/JPL/University of Arizona*
  · <https://science.nasa.gov/resource/full-jupiter-map/>

### ambientCG — CC0

MetalPlates017A · Metal027 · DiamondPlate009 — <https://ambientcg.com/>

### 폰트

Noto Sans KR — [SIL Open Font License 1.1](https://openfontlicense.org/)

### 엔진

Unity 6000.3.7f1 · Universal Render Pipeline
**외부 ML 라이브러리는 사용하지 않았습니다. 게임 속 AI는 전량 직접 구현했습니다.**
