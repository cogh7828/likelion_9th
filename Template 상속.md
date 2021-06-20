### Template 상속

---

- 부트스트랩

  >1. http://bootstrapk.com/  → CSS코드, JS코드 head에 넣기
  >
  >2. 모든 페이지마다 navbar필요
  >
  >   - 모든 페이지에 navbar 코드 복붙 번거로움
  >
  >   - Django에선 Template 상속 지원
  >
  >     > html에서 겹치는 부분을 base.html에 만들고 이것 상속

- Template 상속하기

  > 1. base.html 생성 (실습)
  >
  >    > - 프로젝트 설정 폴더(url.py, settings.py 있는 폴더)에 templates 폴더 안에 생성
  >    > - navbar 코드 포함하여 위까지(html태그)까지 복사 후 base.html에 붙여넣기
  >    > - 페이지마다 달라지는 부분은 block content로 묶음
  >
  > 2. 각 페이지 html에서도 해당 부분 block content로 묶음(실습)
  >
  > 3. settings.py설정(실습)
  >
  >    > - Templates 부분의 DIRS에 base.html 경로 입력
  >
  > 4. urls.py 정리(실습)
  >
  >    > 1. Blog app 폴더 내 urls.py 생성 후 기존 코드 복붙
  >    > 2. 기존 urls.py 수정