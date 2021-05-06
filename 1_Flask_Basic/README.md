# 1. Flask Basic

* 가상환경 생성
```bash
conda create --name FLASK_BASIC python=3.7
```
* 가상환경 활성화
```bash
source activate FLASK_BASIC
```
* 패키지 설치
```bash
pip3 install -r requirements.txt
```
* httpie 설치
```bash
brew install httpie
```
* app.py 실행
```bash
FLASK_APP=app.py FLASK_DEBUG=1 flask run
```
* HTTP 요청을 보냄
```bash
http -v GET http://127.0.0.1:5000/hello
``` 
