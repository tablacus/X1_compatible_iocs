# X1版S-OS"SWORD"用の互換IOCS v1.0.0.0

## 概要

SHARP X1版S-OS"SWORD"で使用可能なオープンソースの互換IOCSです。  

[THE SENTINEL - RetroPC.NET](http://www.retropc.net/ohishi/s-os/)で入手できるX1/C/D/Cs/Ck/F/G/Twin版のS-OS"SWORD"ではHuBASICが必要になりますが、それのIOCSの部分を代替することができます。

S-OS互換の[L-os Angeles](https://github.com/tablacus/LosAngeles)で作成していたIOCSの部分をS-OS"SWORD"に合わせて調整ました。

## ディスクイメージの作成方法

1. X1版S-OS"SWORD"用の互換IOCSをダウンロードして適当なフォルダに展開してください。

2. [THE SENTINEL - RetroPC.NET](http://www.retropc.net/ohishi/s-os/)で入手できるX1/C/D/Cs/Ck/F/G/Twin版のS-OS"SWORD"の`binaries`の中にある`sword.bin`を 1. と同じフォルダに置いてください。

3. Windowsのコマンドラインから`msxcat.bat`を実行してください。

`x1sword.2d`がディスクイメージになります。X1用のエミュレータにセットして実行することができます。

## ライセンス

MIT Licenseのフリーソフトウェアです。
