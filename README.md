# 브라질 K-뷰티 소비자 인사이트 | Executive Briefing

한국어와 브라질 포르투갈어로 볼 수 있는 정적 보고서 사이트입니다. 첫 화면의 `Português` / `한국어` 버튼으로 전환합니다. 차트, 상세 분석, Okno 참고자료, Serasa 5개 표본 × 40개 문항 탐색기와 연결된 출처·집계 데이터를 함께 제공합니다. Page4에는 문화원·경제단체·기업이 함께하는 협업 행사 파일럿과 역할·성과 지표 제안을 담았습니다.

## GitHub에 업로드하고 Pages로 공개하기

1. 이 ZIP을 풀고, 안에 있는 **모든 파일과 폴더**를 GitHub 저장소의 최상위(root)에 올립니다. `index.html`, `assets/`, `data/`, `sources/`, `.nojekyll`이 같은 위치에 있어야 합니다.
2. GitHub 저장소의 **Settings → Pages**에서 배포 원본을 `Deploy from a branch`로 선택하고, 기본 브랜치(예: `main`)의 `/(root)`를 지정해 저장합니다.
3. Pages가 제공하는 사이트 주소를 열어 언어 전환, 차트, 상세 창, 원문 링크를 확인합니다.

GitHub Pages는 인터넷에 공개되는 사이트입니다. 원자료를 포함한 보고서를 공개할 권한을 확인한 뒤 Pages를 켜세요. [GitHub 공식 안내](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

이미 `cultural-market-site`처럼 홈페이지가 있는 저장소에 추가할 때는 기존 홈페이지를 덮어쓰지 않도록 `brasil-kbeauty/` 같은 새 폴더 안에 이 ZIP의 파일을 넣으세요. 주소는 저장소의 Pages 주소 뒤에 `/brasil-kbeauty/`를 붙이면 됩니다. 새 저장소에서 이 보고서를 첫 화면으로 쓰려면 파일을 저장소 최상위(root)에 올립니다.

## 파일 구성

- `index.html`: 대시보드와 상세 보고서
- `data/`: 언어 전환, Serasa 집계 탐색용 데이터와 원본 집계 파일
- `sources/`: 출처 문서와 팝업 피드백
- `assets/fonts/`: 사이트에 포함된 글꼴과 라이선스

사이트는 상대 경로와 로컬 자료만 사용하므로 별도 빌드 도구나 외부 폰트 연결이 필요하지 않습니다. 원문 링크가 작동하려면 위 폴더 구조를 유지하세요.

## Português

Relatório estático bilíngue em coreano e português brasileiro. Use o botão `Português` / `한국어` no topo para alternar o idioma. Inclui painel, análises detalhadas, material de referência Okno, explorador dos dados agregados da Serasa, arquivos de apoio e uma proposta de evento colaborativo na Page 4.

Para publicar no GitHub Pages, envie todos os arquivos e pastas deste pacote para a raiz do repositório e selecione `Settings → Pages → Deploy from a branch → /(root)`. Se o repositório já tiver um site, coloque os arquivos em uma pasta nova, como `brasil-kbeauty/`, para preservar a página inicial atual. O site do Pages fica público na internet; confirme a autorização para publicar os documentos de apoio.
