# free-korean-fonts
무료 혹은 오픈소스 한국어 글꼴 중에서 **복제 및 배포**가 가능한 것들을 모아둔다.

Free and redistributable Korean Fonts.

## Linux 에 설치하기
### 개인 계정에 설치하기
```
mkdir -p ~/.fonts # 만약 자신의 HOME에 .fonts 디렉토리가 없으면 생성한다.

cd ~/.fonts

git clone https://github.com/kwon37xi/free-korean-fonts.git

# Font 다시 인덱싱
fc-cache -v
```
### 전역 설치하기
`root` 권한으로 변경하고 작업한다.
```
cd /usr/share/fonts

git clone https://github.com/kwon37xi/free-korean-fonts.git

# Font 다시 인덱싱
fc-cache -v
```
