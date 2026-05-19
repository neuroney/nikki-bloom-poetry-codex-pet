<div align="center">
  <img src="assets/previews/idle.gif" width="128" alt="Nikki Bloom Poetry idle preview">

  <h1>Nikki Bloom Poetry Codex Pet</h1>

  <p>
    Codex 데스크톱 앱에서 사용할 수 있는 Nikki / 暖暖 팬메이드 커스텀 펫입니다. <em>Shining Nikki</em>의 대표 의상 <em>Bloom Poetry</em>（诗意绽放）에서 영감을 받아 Codex 고정 8x9 스프라이트 아틀라스 형식으로 정리했습니다.
  </p>

  <p>
    <a href="README.md">简体中文</a>
    ·
    <a href="README_en.md">English</a>
    ·
    <a href="README_ja.md">日本語</a>
    ·
    <a href="README_ko.md"><strong>한국어</strong></a>
  </p>
</div>

> 이 저장소는 팬메이드 커스텀 펫 리소스이며 Papergames, Infold Games 또는 Nikki 시리즈의 공식 프로젝트가 아닙니다.

## 미리보기

![Contact sheet](assets/contact-sheet.png)

| Idle | Run Right | Run Left |
| --- | --- | --- |
| ![idle](assets/previews/idle.gif) | ![running right](assets/previews/running-right.gif) | ![running left](assets/previews/running-left.gif) |

| Wave | Jump | Failed |
| --- | --- | --- |
| ![waving](assets/previews/waving.gif) | ![jumping](assets/previews/jumping.gif) | ![failed](assets/previews/failed.gif) |

| Waiting | Working | Review |
| --- | --- | --- |
| ![waiting](assets/previews/waiting.gif) | ![running](assets/previews/running.gif) | ![review](assets/previews/review.gif) |

## 특징

- 핑크색 양갈래 머리, 흰 베레모, 부드러운 눈매를 살린 Q-style 3D 스타일 Nikki.
- *Bloom Poetry* 의 핑크 체크 드레스, 리본, 레이스, 작은 꽃 장식을 Codex 펫 크기에 맞게 정리했습니다.
- Codex 규격: `1536x1872`, 8열 x 9행, 셀당 `192x208`.
- `idle`, `running-right`, `running-left`, `waving`, `jumping`, `failed`, `waiting`, `running`, `review` 9개 상태 포함.
- RGBA, 투명 배경, 미사용 셀 투명, 투명 픽셀 RGB 잔여 없음으로 검증되었습니다.

## 설치

Releases에서 `nikki-bloom-poetry-codex-pet-v1.0.0.zip`을 다운로드한 뒤 아래 두 파일을 Codex 커스텀 펫 폴더에 복사합니다.

```text
pet.json
spritesheet.webp
```

```text
$HOME/.codex/pets/nikki-bloom-poetry/
├── pet.json
└── spritesheet.webp
```

바로 사용할 수 있는 파일:

- [dist/pet.json](dist/pet.json)
- [dist/spritesheet.webp](dist/spritesheet.webp)

Codex를 다시 시작한 뒤 커스텀 펫 목록에서 **Nikki Bloom Poetry**을 선택하세요.

## 크레딧

- 의상명과 크로스 게임 명칭 참고 자료는 [docs/sources-manifest.json](docs/sources-manifest.json)에 기록되어 있습니다.
- 이 저장소의 독자적인 패키징, 문서, 메타데이터는 [MIT License](LICENSE)로 배포됩니다.
- Nikki, *Shining Nikki* 및 관련 공식 디자인의 권리는 각 권리자에게 있습니다.
- 이 저장소는 공식 일러스트를 재배포하지 않으며, 준비된 Codex 펫 패키지와 미리보기 리소스만 포함합니다.
