## 오늘 한 것
- PyInstaller 설치 및 빌드
- resource_path() 함수 추가
- --add-data 옵션으로 에셋 포함
- .exe 실행 확인

- ## 빌드 명령어
pyinstaller --onefile game.py
pyinstaller --onefile --windowed game.py
pyinstaller --onefile --windowed --add-data "assets;assets" --name=MyGame game.py

## resource_path() 를 써야 하는 이유
파이썬으로 실행할 때랑 exe로 빌드했을 때 파일 경로가 완전히 달라지기 때문에

## AI 활용 내역
빌드 명령어를 사용하는 도중 오류메세지가 생길때 어떤 부분에서 문제가 발생하여 문제가 생겼는지 확인하고 왜 그 문제가 발생했는지 이유를 설명해달라고 함

