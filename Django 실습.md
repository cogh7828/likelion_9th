### Django 실습

---

- 에러나는 이유

  > 오타 저장 안함
  >
  > 이외엔 구글링

- App : Django 프로젝트 이루는 작은 단위

- App 만들기

  > 1. (terminal에서) firstproject
  > 2. (terminal에서) python manage.py startapp firstapp
  > 3. firstproject 폴더에서 settings.py 열기
  > 4. INSTALLED_APPS =  [ 'firstapp.apps.FirstappConfig', ]  작성

- 웹사이트 구동순서

  > 1. 사용자가 서버에 요청
  > 2. 서버의 VIEW는 Model에게 요청한 필요한 데이터를 받음
  > 3. view는 받은 데이터를 적절하게 처리해서 template으로 넘김.
  > 4. template은 받은 정보를 사용자에게 보여줌

- 실습