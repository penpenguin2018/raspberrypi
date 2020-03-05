### raspberrypi

##라즈비안에서 한글을 사용하기 위한 3가지 방법

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


##Solar - 로지텍 디바이스 매니저(유니파잉 리시버)
로지텍은 우분투를 지원하지 않는다. 그래서 유니파잉 수신기를 사용할 수 없다.
<pre><code>sudo apt install solaar</code></pre>
solaar를 이용하면 로지텍 디바이스를 우분투에서도 사용할 수 있다.

##wifi config
<pre><code>iw pwy</code></pre>
사용가능한 채널 전부 보여줌

## QT
