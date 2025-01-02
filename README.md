# M5StampFly Simulink

オリジナルM5StampFlyスケルトンコードをベースに、MathWorks Simulinkで動作する用に変更を加えたコード

## 方針
基本的には、ベースAPIを全て利用し、400Hzでループされるコード部分のみ、SimlulinkからのCode生成を利用する（Embedded Coderを利用する）
最終的にマージしたコードはPlatformIOでビルドを行う
XCP on WIFI経由にて、内部データをSimulink側にて確認／モニタできるようにする

### M5 Stamp Fly関連

- オリジナルファームウェア https://github.com/m5stack/M5StampFly
- こうへい版ファームウエア https://github.com/M5Fly-kanazawa/M5StampFly
