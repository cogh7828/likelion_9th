### Static

- Django에서 다루는 파일

  > - 동적파일
  >
  >   > - 서버의 데이터들이 가공된 다음 보여지는 파일
  >
  > - 정적파일
  >
  >   > - 미리 서버에 저장된 파일
  >   >
  >   > - 서버에 저장된 그대로 서비스 해주는 파일
  >   >
  >   > - 종류
  >   >
  >   >   > Static : 개발자가 서버 개발 시 미리 넣은 정적 파일(lmg, js, css)
  >   >   >
  >   >   > Media : 사용자가 업로드할 수 있는 파일

- 실습

  > 1. blog app에 static 폴더 생성
  >
  > 2. static 폴더에 멋사 로고 사진 삽입
  >
  > 3. settings.py 가서 Static 파일 설정
  >
  >    > - 정적 파일들 관리 위함
  >    > - Static 부분 코드 추가
  >
  > 4. static에 저장된 사진을 모든 html에 띄우기
  >
  >    > 1. bast.html에 가서 static 로드
  >    > 2. 나머지 navbar 링크 설정