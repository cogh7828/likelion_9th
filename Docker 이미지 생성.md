## 14.5 Docker 이미지 생성

---

### Gitpot setting

- Url - hotpot.io/[remote repository url]

- Requirements 설치

  > `pip install -r requirements.txt`

- White noise 설치

  > `pip install whitenoise`

  MIDDLEWARE에서 SecurityMiddleware 바로 아래 내용 추가

  ```
  MIDDLEWARE = [
    'django.middleware.security.SecureityMiddleware',
    
    ##추가
    'whitenoise.middleware.WhiteNoseiMiddleware', 
  ]
  ```

- Gunicorn 설치

  > `pip install gunicorn`

- Dockerfile 생성

run.sh

```
#!/bin/bash
python manage.py migrate
python mange.py collecstatic
gunicorn [ProjName].wsgi -b 0.0.0.0:8000
```

- `pip freeze > requirements.txt`
- `sudo docker -up`
- `cmd` + `shift` + `'`
- `docker build -t [id]/[AppName]`
- `docker run -it -p 8000:8000 [id]/[AppName]`
- `docker login`
- `docker push [id]/[AppName]`