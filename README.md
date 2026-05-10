# NEEDU COMPANY Cafe24 Renewal

NEEDU COMPANY 카페24 기반 홈페이지 리뉴얼 작업 저장소입니다.

## 작업 개요

- 기존 카페24 쇼핑몰 스킨을 회사 홍보형 홈페이지 구조로 정리
- 상단 메뉴를 `회사소개 / 포트폴리오 / 업체 제휴문의 / 셀럽 제휴문의`로 변경
- `JOIN / LOGIN / ORDER / CART / 검색 / 마이쇼핑` 등 쇼핑몰 요소 숨김
- 블랙, 웜 베이지, 브라운 중심의 브랜드 톤 적용
- 영문은 세리프, 한글은 고딕 계열 폰트 방향으로 정리
- 메인, 회사소개, 포트폴리오, 업체 문의, 셀럽 문의를 별도 페이지 구조로 구성

## 이번에 직접 수정한 기존 파일

- `index.html`
- `layout/basic/main.html`
- `layout/basic/layout.html`
- `layout/basic/navigation.html`
- `layout/basic/sidebar.html`
- `layout/basic/footer.html`
- `layout/basic/css/common.css`

## 이번에 새로 만든 파일

- `.gitignore`
- `README.md`
- `layout/basic/company.html`
- `layout/basic/portfolio.html`
- `layout/basic/partner.html`
- `layout/basic/creator.html`

## GitHub에는 올라갔지만 이번에 직접 수정하지 않은 기존 파일

- `layout/basic/brand.html`
- `layout/basic/schedule.html`
- `preference/product/product_category.ini`
- `robots.txt`
- `robots.txt.20260429_0828`

## 로컬에는 있지만 GitHub에 올리지 않은 항목

- `.temp/` 내부 임시 HTML 파일
- `.git/` 내부 저장소 데이터
- `web/upload/` 빈 폴더

## 로컬 확인

정적 서버 실행 후 아래 URL에서 확인합니다.

```bash
python -m http.server 5173 --bind 127.0.0.1
```

- `http://127.0.0.1:5173/index.html`
- `http://127.0.0.1:5173/layout/basic/company.html`
- `http://127.0.0.1:5173/layout/basic/portfolio.html`
- `http://127.0.0.1:5173/layout/basic/partner.html`
- `http://127.0.0.1:5173/layout/basic/creator.html`
