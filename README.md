# open-source-mouse
## sfc2013-design-strategy
This document is made by [gitfab](http://gitfab.org)
---
#価値のないものの価値は、必然性から生まれてくる

今の時代でマウスに価値なんてない。
マウスの役割は、トラックパッドや、ペンタブに移行した。
マウスに価値をつけ、新しいものにするには、必然性が必要だ。
ここでいう必然性は、例えば、
おれは、子どもたちの教育をデジタルななにかできたらって思ってるから、
その構想のなかで、アイディアをつめていくと、必然的にそのアウトプットにマウスがぴったりだ、だからマウスをつかったという、そういう必然性。
それを無視して考えたら、できあがるものは、なんの意味もないものになっちゃうから、もうちょっとアイディアが浮かんでくるまで考えたい。

#にぎにぎマウス
マウスにふれると、手をにぎってくれるマウス

#用意するもの
•Arduino Uno
•6V1A DCアダプター
•サーボモータ
•感圧センサ
•LED
•可変抵抗(10kΩ)
•抵抗(330Ω)
•ブレッドボードorユニバーサル基板
•ジャンプワイヤ(線材)
•手袋
•綿
•靴下用ホッカイロ
•ドライバー
•布用のボンド
•キラキラの星の飾り
•グルーガン
•グルースティック
•棒2~4本
•ドリル

#完成予想スケッチ
あとで、写真はります。

#作り方(手編)
手袋のなかに、綿とホッカイロをいれて、弾力をつける。
手袋の手首の部分を内側におりこんで、落ちないようにする。

#作り方(マウス編)
マウスに綿を、お好みで、布用ボンドで固定していく。
さらにお好みで、上からキラキラするのをまぶして装飾。

#作り方(ハード編)
Arduinoとタッチセンサ、LED、サーボモータを配線する
タッチセンサを、マウスのどこか、触れるとこに貼付ける
LEDはテスト用の、おまけだから適当なとこでいい
(あとで回路図添付します)

#作り方(サーボモータとマウスつなぐ編)
サーボモータに、ホットボンドで棒を2本固定する
マウスにその棒がはまる穴をあけ、棒をいれ、ホットボンドで固定する

#作り方(ソフトウェア編)
arduinoで、感圧センサが感知したら、
サーボを90度うごかし、感知していないときは、0度にもどるような仕様。

#完成
写真あとで、のせます

#感想•今後広げられること
あったかくて、感触もきもちい
手の指の間接も曲げれたらいいなあ。
ArduinoをMEGAにして、さらにLED24個分くらいマウスに穴あけて、
マウスにしこんで、触ってるときに、ピカピカ光ってたらもっとかわいい

---
