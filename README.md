# Morse_code_LED
ロボットシステム学の課題のためのプログラムです。

引用元は https://github.com/ryuichiueda/robosys_device_drivers であり、myled10.cを改変しています。

改変個所は、LEDの点滅回数、点灯時間、入力された文字に対する条件式です。

このプログラムは、接続されたLEDが入力された数字に対応するモールス信号を表現します。

*echo 2 5 0 1 > /dev/myled0*　や　*echo 4 2 > /dev/myled0*　のように数字をデバイスファイルを書き込むことで連続したモールス信号として出力します。
