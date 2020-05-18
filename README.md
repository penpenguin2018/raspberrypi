#### raspberrypi

## 라즈비안에서 한글을 사용하기 위한 3가지 방법

* ibus
* nabi
* fcitx

이중에서 fcitx를 쓰자!

<pre><code>sudo apt-get update
sudo apt-get upgrade

sudo apt-get install fcitx-hangul
sudo apt-get install fonts-unfonts-core
im-config -n fcitx
</code></pre>

im-config -n fcitx  시작될때 fcitx 실행

fcitx 설정에 들어가서 한/영 키 설정까지 해주면 끝


## Solaar - 로지텍 디바이스 매니저(유니파잉 리시버)
로지텍은 우분투를 지원하지 않는다. 그래서 유니파잉 수신기를 사용할 수 없다.
<pre><code>sudo apt install solaar</code></pre>
solaar를 이용하면 로지텍 디바이스를 우분투에서도 사용할 수 있다.
k580 키보드는 ESC+O, ESC+O, ESC+B 를 누르면 초기화 된다.

## wifi config
<pre><code>iw phy</code></pre>
사용가능한 채널 전부 보여줌
wpa_supplicant.conf2 파일에서 2를 지우고
/etc/wpa_supplicant 폴더로 복사할 것

## transmission-daemon
설정 파일을 편집할 떄에는 먼저
<pre><code>sudo /etc/init.d/transmission-daemon stop</code></pre>
항상 정지한 뒤에 start 할 것
https://geeksvoyage.com/raspberry%20pi/transmission-for-pi/
참고하기

## 가상키보드
keyboard.sh

## 화면 보호기
xscreensaver.sh


## QT
