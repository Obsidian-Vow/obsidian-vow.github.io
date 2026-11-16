졸업작품 상영관 사이트
=====================

파일 구성
- index.html   사이트 본체 (고칠 필요 없음)
- content.js   사이트에 나오는 모든 글과 파일 경로 (admin.html 에서 만들어짐)
- admin.html   편집 페이지: 내용을 고치고 content.js 를 내려받는 곳
- assets/      로고, 영상, 3D 모델(.glb)을 넣는 폴더

처음 올리기 (GitHub Pages, 무료)
1. github.com 가입 후 오른쪽 위 + → New repository
   이름 예: screening  /  Public 선택  →  Create repository
2. 저장소 화면의 "uploading an existing file" 링크를 눌러
   이 폴더 안의 파일과 assets 폴더를 통째로 끌어다 놓고 Commit changes
3. Settings → Pages → Branch 를 main / (root) 로 고르고 Save
4. 1~2분 뒤 https://아이디.github.io/screening/ 으로 접속

내용 고치기
1. https://아이디.github.io/screening/admin.html 접속
2. 고친 뒤 [content.js 내려받기]
3. 저장소에서 Add file → Upload files 로 content.js 를 올리고 Commit
4. 새 로고/영상/모델은 assets 폴더 안에 같은 방법으로 올리기

주의
- GitHub 웹 업로드는 파일당 25MB까지. 영상은 유튜브(일부 공개)에 올리고
  admin.html 의 영상 칸에 유튜브 주소를 넣는 방법을 추천합니다.
- 3D 모델은 텍스처를 포함한 .glb 로 내보내 주세요.
- index.html 을 컴퓨터에서 더블클릭해서 열면 3D 캐릭터가 안 보일 수 있습니다.
  올린 사이트 주소로 확인해 주세요.
