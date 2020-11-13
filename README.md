# hamonikr-kakaotalk

하모니카 카카오톡을 설치하는 패키지

# Developer

HamoniKR <pkg@hamonikr.org>

# Installation

## 사용자 home이 있는 경우

```
$ sudo apt install hamonikr-kakaotalk
```

## 사용자 home이 없는 경우

```
$ sudo apt install hamonikr-kakaotalk
/etc/skel/.config/autostart/kakaotalkset.desktop
```


# Issues

- 해당 패키지는 hamonikr-wine 사용자 상태에서 빌드하였습니다. 레지스트리 추가와 프로그램을 설치했을 때 사용자 이름을 통일해 주어야 합니다.
- /home/$USER/.wine/dirve_c/Program Files/Kakao/KakaoTalk/default/Image/2.0/ad_banner.png 파일이 변경되면 카톡이 실행 안됨(빌드시 변경됨)
- /home/$USER/.wine/dirve_c/Program Files/Kakao 폴더를 압축 하여 푸는 방식으로 대체

https://hamonikr.org/
