# 스토리 모드용 신규 배경 19종 (마누스 산출물)

2026-11-21, 공용 채팅방에 마누스가 올린 ZIP
`https://files.manuscdn.com/user_upload_by_module/session_file/310519663912573806/wwHUxYHENOoonrdz.zip`
을 내려받아 검수·반영한 파일들입니다. **아직 어느 코드에서도 참조하지 않습니다**(맵 id가 MAPHAS/MAP_DEFS에 없음).

## 파일

- 본 이미지: `assets/maps/{id}.jpg` — 720×1280 JPEG(RGB), 15~27KB
- 썸네일: `assets/maps/t/{id}.jpg` — 240×427 JPEG, 기존 썸네일 규격(240×427)에 맞춰 LANCZOS 리사이즈로 생성
- id 19종: `alley` `pond` `burrow` `hatchery` `wheatfield` `octocave` `fruitfarm` `savanna`
  `halloween` `slimemarsh` `boxing` `mansionclean` `ruins` `oldinn` `hospital`
  `sharkbay` `trench` `vcastle` `demonking`

## 참고

- 원본은 "세로형 픽셀풍"이라고 표기돼 있으나 실제로는 도형 위주의 플레이스홀더 수준입니다.
  기존 정식 맵(`fuji.jpg` 등 16비트 픽셀아트)과 같은 화면에 쓰려면 아트 재생성이 필요합니다.
- 경로가 루트 `assets/` 인 이유: `muse-v5-9/index.html`이 `<base href="../">`라 상대 경로 `assets/maps/…`가
  저장소 루트로 해석됩니다. `muse-v5-9/assets/` 아래에 두면 로드되지 않습니다.
- 효과음 5종(`dlg_tick`, `boss_warn`, `boss_hit`, `boss_ko`, `unlock`)은 `audio/sfx/`에 함께 반영했습니다.
