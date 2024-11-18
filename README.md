# AX1800_rtl8852au_ubuntu
tp-link USB Wi-Fiアダプタ（AX1800）用ドライバのインストール

Ubuntu20.04 にて動作確認済

## Installation
```
git clone https://github.com/Tokyo-University-of-Science-Arai-lab/AX1800_rtl8852au_ubuntu.git

cd rtl8852au

make

sudo make install

sudo reboot
```

linux のカーネルが新しくなったら上記手順をもう一度行う必要があるかもしれません

参照：https://github.com/lwfinger/rtl8852au

