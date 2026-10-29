# 엔지니어랩 할인코드 — GitHub Pages 업로드 안내

홈페이지 주소: https://engineerlab-secret-discount.github.io/

## 1. GitHub 준비

1. GitHub에서 **Organization** 이름을 `engineerlab-secret-discount`로 생성합니다. 이미 존재한다면 해당 Organization을 선택합니다.
2. 이 Organization 아래에 **Repository** 이름을 `engineerlab-secret-discount.github.io`로 생성합니다.
3. 저장소 공개 설정은 **Public**으로 지정합니다. 기본 브랜치는 **main**으로 준비합니다.

## 2. 홈페이지 파일 업로드

1. 전달받은 ZIP 파일을 내 컴퓨터에서 **압축 해제**합니다.
2. 압축 해제한 폴더 안의 `index.html`, `assets`, `favicon.png`, `robots.txt`, `sitemap.xml`, `.nojekyll`, `README.md`를 모두 선택합니다.
3. GitHub의 `engineerlab-secret-discount.github.io` 저장소에서 **Add file → Upload files**를 선택합니다.
4. 파일과 폴더를 저장소의 **최상위(root)**에 올립니다. 바깥 폴더 자체를 한 단계 더 올리지 마세요. `index.html`이 저장소 첫 화면에 보여야 합니다.
5. 아래쪽 **Commit changes**를 선택합니다.

> `.nojekyll`은 숨김 파일이므로 파일 탐색기에 보이지 않을 수 있습니다. 없어도 이 사이트의 HTML·CSS 표시에는 큰 영향이 없지만, 보이면 함께 올리세요. GitHub 웹 업로드에서 빈 파일 처리가 불편하면 `.nojekyll`은 생략해도 됩니다.

## 3. GitHub Pages 공개

1. 저장소 메뉴의 **Settings → Pages**로 이동합니다.
2. **Build and deployment → Source**를 **Deploy from a branch**로 선택합니다.
3. **Branch: main**, **Folder: /(root)**를 선택하고 **Save**합니다.
4. 배포가 반영된 후 **https://engineerlab-secret-discount.github.io/**에 접속해 홈페이지를 확인합니다. 배포 전 404는 정상입니다.

## 4. 최종 확인

- 헤더의 **6만원 쿠폰 받기** 버튼을 누르면 새 탭에서 다음 페이지가 열려야 합니다: https://www.engineerlab.co.kr/ee/promotion/2025/partner/index.php?partnerID=e7288
- 첫 본문 바로 아래의 긴 랜딩 이미지 어느 부분을 눌러도 **같은 프로모션 URL**이 새 탭에서 열려야 합니다.
- 본문의 **엔지니어랩 할인코드 e7288 사용 안내** 링크는 https://engineerlab-guide.netlify.app/secret-code/ 로 이동해야 합니다.
- 상단 로고와 사이트명은 홈페이지 루트 `/`로 이동하며, `index.html` 주소를 강제로 표시하지 않습니다.
- PC 및 모바일 화면에서 헤더가 스크롤 중에도 상단에 표시되는지 확인합니다.

## 5. 검색 등록 및 수정

- 배포된 URL로 네이버 서치어드바이저와 구글 서치 콘솔에 등록한 뒤 `sitemap.xml`을 제출할 수 있습니다.
- 검색 등록과 색인은 별개의 과정이며, 검색 1위·AI 브리핑 노출을 보장할 수 없습니다.
- 수정할 때는 `index.html` 또는 `assets/css/style.css`를 고친 뒤 저장소의 같은 경로에 다시 업로드하고 Commit하면 됩니다.

## 6. 파일 구성

```text
index.html
assets/
  css/style.css
  images/landing.webp      # 사용자 제공 원본: 936 × 8416 px, 변환·축소 없음
  images/logo.png          # 생성한 사이트 로고
  images/thumbnail.webp    # 생성한 정사각형 썸네일
favicon.png                # 생성한 파비콘
robots.txt
sitemap.xml
.nojekyll
README.md
```

사이트 이름: **엔지니어랩 할인코드**

설정 주소는 Organization 루트 웹사이트이며 별도 유료 서비스나 서버가 필요하지 않습니다.
