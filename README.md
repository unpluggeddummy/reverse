# reverse — 세기말의 방랑자 보관함

[세기말의 방랑자](https://unpluggeddummy.github.io/fin-de-siecle-wanderer/) 사이트에서 쓰는 큰 파일(Live2D)을 따로 담아 두는 저장소입니다.

- `live2d/index.json` — 스킨 번호 → 모델 파일 목록 (사이트가 이걸 보고 불러옵니다)
- `live2d/<모델>/` — 웹용으로 줄인 Live2D 모델 (텍스처는 webp, 모델 뼈대는 gzip)
- Actions의 **Live2D 채우기**가 매주 새 모델을 받아 옵니다. 직접 돌리려면 Actions → Live2D 채우기 → Run workflow.
- GitHub Pages 한도(1GB) 때문에 약 900MB까지만 담고, 나머지는 원본 저장소에서 바로 불러옵니다.

게임 그림과 모델의 권리는 Bluepoch에 있습니다. 개인 비영리 팬 아카이브 용도입니다.
Live2D 모델 출처: [Reverse-1999-CN-Asset](https://github.com/myssal/Reverse-1999-CN-Asset)
