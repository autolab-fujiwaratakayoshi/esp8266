# esp8266
esp8266を使って指定のＳＳＩＤを持つ信号の受信と電波強度を確認する

発信側はサンプルコードのWiFi access pointです

開発環境
arduino ide

ハードウェア
Hiletgo
ESP8266 NodeMCU LUA CP2102 ESP-12E

以下、製品説明より抜粋

インストール手順：

1、IDEをダウンロード

2、IDEをインストール

3、arduino IDEを設置：

Go to File->Preferences。URLをコピーして、ESPボードマネージャの拡張機能を入手：

arduino.esp8266.com/stable/package_esp8266com_index.json

4、Go to Tools > Board > Board Manager> Type "esp8266"。ESP8266をダウンロードしてインストールする

5、チップを設置：

Tools -> Board -> NodeMCU 1.0 (ESP-12E Module)

Tools -> Flash Size -> 4M (3M SPIFFS)

Tools -> CPU Frequency -> 80 Mhz

Tools -> Upload Speed -> 921600

Tools-->Port--> (whatever it is)

6、Githubで32ビットフラッシャーexeをダウンロードして実行する（godubでnodemcu / nodemcu-flasher / tree / master /を検索する）
github.com/nodemcu/nodemcu-flasher/tree/master/Win32/Release

または、64ビットフラッシャーexeをダウンロードして実行してください：
github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release

7. Arduino IDEで、旧式のBlinkプログラムを探します。 ロード、コンパイル、アップロード。

8. FILE> EXAMPLES> ESP8266> BLINKに進み、点滅を開始します。

ウェブサイトへのデータダウンロードアクセス：

http://www.nodemcu.com/index_en.html

ファームウェアリンク：

https://github.com/nodemcu/nodemcu-firmware
