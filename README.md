# myled1
ロボットシステム学  課題１　デバイスドライバ

# 内容
ロボットシステム学の授業で作成したものを改変

# 必要機材
 ・Raspberry Pi4 Computer Model B 
 ・LED ×2
 ・ブレッドボード
 ・抵抗器　220Ω　×2
 ・ジャンパー線　×3

# 動作方法
make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0

# 動作内容
$ echo > 1 /dev/myled0  LEDを点灯する
$ echo > 0 /dev/myled0  LEDを消灯する

# ライセンス
GNU General Public License v3.0
