# LEUNG 릉 공식 홈페이지

정적 웹사이트입니다. 빌드 과정이 없어 그대로 배포하면 됩니다.

- `index.html` : 메인 / 상품 목록(#shop) / 상품 상세(#product-p1 ~ p8)
- 이미지 파일(jpg, svg) : 배경 사진, 상품 앞·뒤 사진, 로고(SVG)

## 사이즈 추천 데이터 추가
`index.html` 안의 `SIZE_DATA` 배열에 한 줄씩 추가합니다.
예) `{h:175,w:68,size:'M'}`

## 배포
- Vercel: 저장소를 Import → Framework Preset은 "Other", Build Command 비움, Output Directory는 `./`
- GitHub Pages: Settings → Pages → Branch `main` / `/ (root)`
