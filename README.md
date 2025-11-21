# Coffee Supply 랜딩페이지

## 배포 방법
1. GitHub에 새 레포지토리 생성
2. 위 파일들을 업로드 (images 폴더 포함)
3. Netlify에 로그인 후 "New site from Git" 선택
4. GitHub 연동 후 레포지토리 선택
5. 빌드 명령: `npm run build` (정적 사이트이므로 생략 가능)
6. 퍼블리시 디렉토리: `/root`

## 커스터마이징
- 이미지: `images/` 폴더에 새로운 이미지 추가
- 텍스트: `index.html` 내 내용 수정
- 색상/폰트: `style.css` 수정
- 폼 연동: `formspree.io` 계정으로 폼 ID 변경