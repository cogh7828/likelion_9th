### Media

---

- 실습

  > 1. settings.py에 media 설정
  >
  > 2. urls.py 설정
  >
  >    > - 사용자가 요청한 사진은 url 통해 보여줌
  >
  > 3. models.py 설정
  >
  >    > - 사용자가 글 올리면 업로드할 사진 저장해야 함
  >    > - pip install pillow
  >    > - Blog에 image field 추가
  >
  > 4. 기존 데이터 삭제
  >
  >    > - 필드가 변경되었으니
  >    >
  >    >   > 1. 파일 탐색기 > 프로젝트 폴더 > blog > migrations
  >    >   > 2. 0001_initial 삭제
  >    >   > 3. pycache폴더 들어가서 0001_initial_python~~ 삭제
  >    >   > 4. 프로젝트 폴더로 가서 db_sqllite3 삭제
  >
  > 5. 다시 데이터 저장할 준비
  >
  >    > 1. python manage.py makemigrations
  >    >
  >    > 2. python manage.py migrate
  >    >
  >    > 3. 슈퍼유저 다시 생성
  >    >
  >    >    > 1. python manage.py createsuperuser
  >
  > 6. 사진 업로드 기능 추가
  >
  >    > 1. new.html 코드 추가
  >    >
  >    > 2. views.py에서 create 수정
  >    >
  >    >    > - 사진 저장하도록 추가
  >    >
  >    > 3. detail.html 수정
  >    >
  >    >    > - 저장된 사진을 보여주기 위함
  >    >    > - 사진없이 새 글 업로드 하면 에러나지 않도록 수정