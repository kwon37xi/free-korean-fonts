# free-korean-fonts
무료 혹은 오픈소스 한국어 글꼴 중에서 복제 및 배포가 가능한 것들을 모아둔다.

이를 모아 두는 이유는 일부 글꼴들이 링크를 임의로 변경하거나 삭제하여 Linux 패키지화 등이 어려울 수 있기 때문이다.

## Linux 에 설치하기
```
cd ~/.fonts # 만약 자신의 HOME에 .fonts 디렉토리가 없으면 생성한다.
git clone https://github.com/kwon37xi/free-korean-fonts.git

# Font 다시 인덱싱
fc-cache -v
```
