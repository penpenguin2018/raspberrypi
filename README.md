# raspberrypi

라즈비안에서 한글을 사용하기 위한 3가지 방법

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



# QT
