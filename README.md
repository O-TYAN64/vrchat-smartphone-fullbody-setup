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

