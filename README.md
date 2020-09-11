# 📜우리에게 project  [죽음의조]
  
## 💪Project Informations
+ 해당 프로젝트는 SCH LikeLion 8th - 피닉스톤 팀 **죽음의조** 에서 진행한 프로젝트입니다.  
+ BackEnd - 박형민, 최민석
+ FrontEnd - 박병호, 강민서, 임수빈, 하유민
+ ![슬라이드1](https://user-images.githubusercontent.com/60251579/92381667-3bb5db00-f146-11ea-9701-eafff9eeb8ca.PNG)
+ ![슬라이드2](https://user-images.githubusercontent.com/60251579/92381670-3c4e7180-f146-11ea-919f-066fd9f5f74f.PNG)
+ ![슬라이드3](https://user-images.githubusercontent.com/60251579/92381672-3ce70800-f146-11ea-9593-44d431c0c3bf.PNG)
+ ![슬라이드4](https://user-images.githubusercontent.com/60251579/92381673-3ce70800-f146-11ea-91f4-0aa6bda6cd4b.PNG)
+ ![슬라이드5](https://user-images.githubusercontent.com/60251579/92381674-3d7f9e80-f146-11ea-9933-5264abaa4679.PNG)
+ ![슬라이드6](https://user-images.githubusercontent.com/60251579/92381676-3d7f9e80-f146-11ea-8220-9054bf4a277f.PNG)
+ ![슬라이드7](https://user-images.githubusercontent.com/60251579/92381677-3e183500-f146-11ea-88f8-06e20a1ed772.PNG)
+ ![슬라이드8](https://user-images.githubusercontent.com/60251579/92381659-3a84ae00-f146-11ea-94e0-bf251c83d1af.PNG)


## ⚙ used package
+ asgiref==3.2.10
+ Pillow==7.2.0
+ pytz==2020.1
+ sqlparse==0.3.1

## ⚙ Installation   
+ 🛠 Django release: 3.1.1
+ 🛠 Python 3.8.4    
+ 🎨 HTML5, CSS3 , JS, JQuery, BOOTSTRAP 

## 🏁 프로젝트 시작 과정 
1. 가상환경 생성 및 실행
```python
python -m venv <가상환경 폴더이름> # 사용 할 수 있는 가상 환경 생성
. <가상환경 폴더>/scripts/activate # 가상 환경 실행 - Mac의 경우 scripts 대신 bin 폴더
```
2. Django Project 시작
```python
django-admin startproject projectname . 
# 이 방식은 협업에 좋은 구조화 방식을 만듬. 불필요한 폴더 생성X 
```


## 📚 APP 
+ 💾 core : Abstract Model로 각 모델이 생성 된 시기, 업데이트 시기를 저장하는 기능
+ 💾 accounts : User, Login, Logout 구현, 회원가입, 로그인 Page 구현
+ 💾 comment : lists(일기장)의 코멘트 기능
+ 💾 essays : lists(일기장)을 합쳐서 essay로 바꾸는 기능
+ 💾 groups : 하나의 가족(그룹)을 정의한 기능, 가족 생성 및 참가 기능
+ 💾 lists : 가족(groups)에 입장하여 일기장을 저장 할 그룹, 일기장 생성 및 삭제 기능
+ 💾 orders : 생성 한 essays(에쎄이)를 주문 하는 기능, 결제 기능, 표지 선택 및 그리기 기능


