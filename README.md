# django-example

## Setup

macOS 기준입니다.

```sh
$ pip3 install virtualenv
$ virtualenv venv
(venv) pip3 install -r requirements.txt
```

## Run the server

```sh
$ python3 manage.py runserver
```

## Other supported Django and Python commands

```sh
$ pip3 install 패키지명  # 패키지 설치
$ pip3 freeze > requirements.txt  # 가상환경에 저장된 패키지 목록을 파일에 저장
$ pip3 install -r requirements.txt  # 패키지 목록을 읽어들여 가상 환경에 패키지 설치
$ django-admin startproject mysite  # Django 프로젝트 시작
$ python3 manage.py startapp 앱이름  # Django 앱 생성
$ python3 manage.py createsuperuser  # 어드민 계정 생성
$ python3 manage.py shell  # Django shell 실행
$ python3 manage.py makemigrations # DB 마이그레이션 파일 생성
$ python3 manage.py migrate  # DB 테이블 생성
```
