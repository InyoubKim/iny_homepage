# in.Y 홈페이지

아이앤와이(주) 공식 홈페이지 소스입니다. 순수 HTML/CSS/JS 한 파일(`index.html`)로 구성되어 있어 별도의 빌드 과정 없이 바로 배포할 수 있습니다.

## 배포 방법 (Netlify)
1. 이 저장소를 GitHub에 올립니다.
2. [Netlify](https://app.netlify.com) 에 GitHub 계정으로 로그인합니다.
3. "Add new site" → "Import an existing project" → 이 저장소 선택
4. Build command는 비워두고, Publish directory는 `.`(루트)로 설정 후 배포합니다.
5. Site settings → Domain management 에서 보유한 도메인을 연결합니다.

## 업데이트 방법
`index.html` 파일 내용을 수정하고 GitHub에 다시 업로드(커밋)하면, Netlify가 자동으로 변경 사항을 감지해 몇 초 안에 새로 배포합니다.
