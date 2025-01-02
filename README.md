# M5StampFly Simulink

オリジナルM5StampFlyスケルトンコードをベースに、MathWorks Simulinkで動作する用に変更を加え得たベースコード

## 方針
基本的には、ベースAPIを全て利用し、400Hzでループされるコード部分のみ、SimlulinkからのCode生成に頼る
最終的にマージしたコードはPlatformIOでビルドを行う

### M5 Stamp Fly関連

- オリジナルファームウェア https://github.com/m5stack/M5StampFly
- こうへい版ファームウエア https://github.com/M5Fly-kanazawa/M5StampFly
