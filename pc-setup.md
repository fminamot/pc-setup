# PC環境セットアップ

## USBからFedora39 日本語インストール
* 日本語キーボード設定
* インストールが終わったらOS再起動

## Fedoraセットアップ開始
* サードバーティリポジトリ有効
* ユーザーとして、student/student を設定

## Fedoraのディレクトリを英語に変更（オプション）
```
LANG=C xdg-user-dirs-gtk-update
```
* Don't ask me again にチェック
* [Update Names]を押す

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

## Foliateインストール
* ターミナルで以下を実行
```
flatpak install foliate
```
* Foliateアイコンをダッシュボードにピン止め

## EPubが読めることを確認
* Foliateでepubファイルを開く

## Foliateの調整
* 設定 > Font&Layout Setting > Layout > Page > Maximum Page Number を1に設定
* 設定 > Scrolled mode にチェック



