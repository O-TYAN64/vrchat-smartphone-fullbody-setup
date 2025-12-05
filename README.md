# 日本語
## slimeVRのインストール
[slime  VR](<https://github.com/SlimeVR/SlimeVR-Installer/releases/latest/download/slimevr_web_installer.exe>)
SteamVRを起動、steamVRの設定画面に行き、スタートアップ→アドホンの管理にslimeVRが入ってればOK
## スマートフォンのアプリのインストール
[owoTrack](<https://play.google.com/store/apps/details?id=org.ovrgyrotrackersync&hl=en>):Android

[owoTrack](<https://apps.apple.com/jp/app/owotrack/id1563711037>):IOS
## slimeVRのセッティング
下の画像のように自動でトラッカーを決めるのを外して、自分が動かす部位にチェック

おすすめは、kneeにチェックを外す(理由：精度の問題)

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/e0927e21-e105-43c9-8b63-1c3a80cde367.png)
## slimeVRのセッティング2
VRChatでフルトラができるように、下記の画像にあるVRChat OSCトラッカーを有効

トラッカーのチェックに関しては、自分が動かしたい部位にチェック

おすすめは、膝にチェックを外す(理由：精度の問題)

![image２２２.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/178b1731-dbe8-4e34-840a-53cafac8e519.png)
## owoTrackOverlayインストール
[リンク](<https://mega.nz/file/rQ5inKyZ#jdKOLWbBzjMd02jONfn5n7L-hSHPFBiMN3y9sRbKozc>)からダウンロードしたファイルを解凍し、Cドライブ直下に置く。（2バイト文字がなければどこでもよい）
[batファイル](<https://note.com/api/v2/attachments/download/433ab4aa1d34c87a183fc8ac64bf281f>)をダウンロードして、管理者権限で実行する。
## PCのIPアドレス
スマートフォンをトラッカーにするのには、PCとUDP通信するのでPCのローカルiPアドレスを調べる　

1.windowsキーを押してcmdと入力

2.コマンドプロンプト上でipconfigと打ち込みEnter

3.IPv4 アドレス.  .   .  .192.168~と出てるとこがPCのiPアドレス

IPは覚えとく

※人によってそのIP変わるので、スマホフルトラするときは毎回調べてね
## SlimeVRとスマートフォンの接続
androidまたはiPhoneでowo trackを開く

下のConnectをタッチ、そしたら先ほど確認したPCのiPアドレスを上の192.168~入力

入力ができたらConnectをタッチしslimeVRと接続

これでスマホ側はPCと接続できる

※トラッカーの位置の設定は各自で行ってください

## VRChatでの設定
VRChatの設定のトラッキングとIKの欄のOSC経由で頭部と手首のとトラッキングデータの送信を許可 をオンにする

![16d668a59cf565c99144f53d2e5eb545.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/068d7945-570a-45d5-9f01-25b97f96ccb0.png)

# ENGLISH
## Installing slimeVR
[slime VR](<https://github.com/SlimeVR/SlimeVR-Installer/releases/latest/download/slimevr_web_installer.exe>)
Launch SteamVR, go to the SteamVR settings screen, and under Startup > Add-ons, check that slimeVR is listed.
## Installing the smartphone app
[owoTrack](<https://play.google.com/store/apps/details?id=org.ovrgyrotrackersync&hl=en>): Android

[owoTrack](<https://apps.apple.com/jp/app/owotrack/id1563711037>): iOS
## SlimeVR Settings
As shown in the image below, uncheck Automatic Tracking and select the body parts you will be moving.

We recommend unchecking the knee (due to accuracy issues).

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/e0927e21-e105-43c9-8b63-1c3a80cde367.png)
## SlimeVR Settings 2
To enable full tracking in VRChat, uncheck the VRChat tracker shown in the image below. Enable OSC Tracker

Check the tracker box for the part of the body you want to move.

We recommend unchecking the knee (due to accuracy issues).

![image２２２.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/178b1731-dbe8-4e34-840a-53cafac8e519.png)
## Install owoTrackOverlay
Unzip the file downloaded from [link](<https://mega.nz/file/rQ5inKyZ#jdKOLWbBzjMd02jONfn5n7L-hSHPFBiMN3y9sRbKozc>) and place it directly under your C: drive. (Any location is fine as long as there are no double-byte characters.)
Download the [bat file](<https://note.com/api/v2/attachments/download/433ab4aa1d34c87a183fc8ac64bf281f>) and run it with administrator privileges.
## PC IP Address
To use your smartphone as a tracker, you'll need to find your PC's local IP address via UDP communication.

1. Press the Windows key and enter cmd.

2. In the command prompt, type ipconfig and press Enter.

3. The IPv4 address (192.168~) is your PC's IP address.

Memorize your IP address.

*This IP address varies depending on the person, so be sure to check it every time you use full smartphone tracking.
## Connecting SlimeVR and Your Smartphone
Open owo track on your Android or iPhone.

Touch Connect at the bottom, then enter the PC's IP address (192.168~) you found earlier.

Once you've done so, touch Connect to connect to SlimeVR.

Your smartphone will now be connected to your PC.

*You will need to set the tracker position yourself.

## VRChat Settings
In the Tracking & IK section of VRChat Settings, enable sending head and wrist tracking data via OSC. Turn on

![16d668a59cf565c99144f53d2e5eb545.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3788219/068d7945-570a-45d5-9f01-25b97f96ccb0.png)

