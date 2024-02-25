# PC環境セットアップ

## USBからFedora39 日本語インストール
* 日本語キーボード設定
* インストールが終わったらOS再起動

## Fedoraセットアップ開始
* サードバーティリポジトリ有効
* ユーザーとして、student/student を設定

## Fedoraのディレクトリを英語に変更
```
$ LANG=C xdg-user-dirs-gtk-update
```

## WiFi設定

## Firefoxでこのメモを開く
https://github.com/fminamot/pc-setup/

## Chromeインストール
```
sudo -i
wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm
sudo dnf localinstall google-chrome-stable_current_x86_64.rpm -y
```
* Chromeアイコンをダッシュボードにピン止め
* Firefoxアイコンのピン止めを外す
* Chromeアイコンをクリック
* Chromeを既定のブラウザーに設定

## ROLアクセス
* Chromeで rol.redhat.com にアクセス

## EPub readerインストール
* ターミナルで以下を実行
```
flatpak install foliate
```
* Foliateアイコンをダッシュボードにピン止め



