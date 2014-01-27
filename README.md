# GYU-Mouse
## sfc2013-design-strategy
This document is made by [gitfab](http://gitfab.org)
---
#ぎゅッマウス
マウスにふれると、手をぎゅッしてくれるマウス

【コンセプト】
2013年6月に4年と2ヶ月つきあってた彼女が家からでていってしまったぼくが、クリスマス寂しく仕事してすごさなくていいような、手をぎゅっとしてくれるマウス。

【仕様】
マウスに触れるとイルミネーションモード
マウスを右クリックすると、手をギュッと。
専用のマウスパッドをつくって、好きなキャラを着せ替え可能。


---
#用意するもの
•Arduino Uno
•USB A-Bケーブル
•6V1A DCアダプター
•サーボモータ
•2.1mmDCジャック
•感圧センサ
•1wフルカラーLED
•可変抵抗(10kΩ)
•ブレッドボードorユニバーサル基板
•ジャンプワイヤ(線材)
•手袋
•綿
•ドライバー
•グルーガン
•グルースティック
•はんだ
•はんだごて
•ガラス板
•両面テープ
•傘の骨のさきっぽ
•マウス
•好きなキャラのクリアファイルとか写真とか
•はさみ
•寂しい心
•遊び心
---
# 完成予想図

スケッチ
![写真 2014-01-07 15 01 45.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/写真-2014-01-07-15-01-45.jpg)

![写真 2014-01-07 15 01 45.jpg](https://raw.github.com/tactoryy/GYU-Mouse/master/gitfab/resources/写真-2014-01-07-15-01-45.jpg)
---
#作り方(手編)

手袋のなかに、綿をいれて、弾力をつける。
手袋の手首の部分を内側におりこんで、両面テープで固定し落ちないようにする。
サーボモータに付属の歯車とサーボモータの間に手袋をうめて、ドライバーでねじを固定。


![手袋サーボモータ.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/手袋サーボモータ.jpg)

![prt_te.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/prt_te.jpg)
---
#作り方(マウス編)

マウスに、感圧センサをとりつける。

![写真 2014-01-07 15 01 16.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/写真-2014-01-07-15-01-16.jpg)
---
#作り方(ハード編)

DCジャック、フルカラーLED、感圧センサをはんだづけして、ブレッドボードにさせるようにする。
Arduinoとタッチセンサ、フルカラーLED、サーボモータを配線する。

•プロトタイプ
![prt.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/prt.jpg)

•完成
![配線.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/配線.jpg)
---
#作り方(マウスパッド編)

ガラス板の四隅に、傘の骨のさきのキャップをとりつける。
サーボを、実際に動かしながら、手にぎゅっとなるちょうどいいところを探し、固定する。
ガラス板の下に、お気に入りのキャラのクリアファイルとか写真とかをはりつける。
ガラス板の下、左側に、フルカラーLEDの配線部分をはりつけ、LED自体はぶらんとするように固定。

![四隅.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/四隅.jpg)

![LEDとりつけ.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/LEDとりつけ.jpg)

![サーボの固定.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/サーボの固定.jpg)
---
#作り方(ソフトウェア編)

1.感圧センサのしきい値をシリアルモニターで確認し、クリック用と触れている用にふたつしきい値を設定する。

2.触れてる時は、ランダムカラーでゆっくりと光がかわる。
クリックのときは、サーボが120度うごく
触っていないときは、サーボが0度にもどり、LEDも消える。

---
#完成

完成！！！
![完成図.jpg](https://raw.github.com/tactoryy/NIGI-Mouse/master/gitfab/resources/完成図.jpg)


---
#感想•今後広げられること

【感想】

暗いとこで触っていると、光がきれいで、エロい気分になる。
右クリック使う頻度で、ギュッとされるくらいがちょうどいい。
もうちょいぎゅっとしてほしいけど、素材がやわらかいから、ぎゅっされてきもちいい。
なにげに、マウスパッドがおしゃれでしかもかわいくて、気に入ってるw
着せ替え可能な点も◎

【改善点】

•なかに針金をいれて、それを曲げれば、もう少しぎゅっとしてもらえる気がする。。

•手袋が100均だからださい。変えたい。。

•サーボの音がうるさい。

•ブレッドボードじゃなくて、マウスにいれるように、実装すればよかった。

•タッチセンサの上にシールでもはって可愛くすれば良かった。

•光の拡散のために、四隅の柱をもっと高くすれば、ぽぉっと光る。

•マウス自体を、もっと小さくて、可愛いのにしたい。
---
