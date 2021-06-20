### From

---

- From

  > - 입력 공간
  >
  > - Django에서 form.py로 관리하게끔 지원
  >
  > -  form태그로 하면되는데??
  >
  >   > - 지난 시간, blog객체에 image 필드 추가하고서, views.py 등등 수정함
  >   > - form.py로 관리하면 db가 변해도 하나하나 수정 안해도 됨

- 실습 영상!!!!!!!

  > 1. blog 테이블에 맞는 forms.py를 블로그 앱에 생성
  >
  > 2. views.py 코드 추가
  >
  >    > - 위의 form 을 임포트
  >    >
  >    >   > from .forms import BlogForm
  >    >
  >    > - 입력받는 공간을 new.html에 보내줌
  >
  > 3. new.html 수정
  >
  >    > - 기존의 입력 태그 삭제 후, fom변수 사용
  >
  > 4. views.py 수정
  >
  >    > - create 함수에서 기존에 값 받아오던 방식 수정
  >    > - form을 이용해 유효성 검사 후 받아오는 것으로 수정할 것

