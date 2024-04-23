# Local-Chat-Messenger

## 概要
クライアントサーバ間で情報のやりとりができるアプリケーション

## デモ
![output](https://github.com/Aki158/Local-Chat-Messenger/assets/119317071/bb9ae2a2-584a-45fa-953b-0a6f928184c0)

## 説明
このアプリケーションは、クライアントサーバ間で情報のやりとりができるシンプルなアプリケーションです。

このアプリケーションでは、メッセージの送信と受信というシンプルな情報のやりとりを体験することができます。

ユーザーがメッセージを送信すると、サーバは、そのメッセージを受け取り、何らかのメッセージを返してくれます。

サーバから返されるメッセージは、フェイクデータなので送信したメッセージの正確な返答ではありません。

例. 送信:Hello! / 受信:Apple

基本的な機能として、メッセージの送信と受信/ステータスの表示ができます。


## インストール

1. リポジトリをクローンする
```
git clone https://github.com/teraz1112/Local-Chat-Messenger.git
```

2. クローンしたリポジトリへ移動する
```
cd Local-Chat-Messenger
```

## 開発環境の構築
### Faker

Fakerは、様々な種類の偽データを生成することができるPythonのパッケージです。

1. Fakerがインストールされているか確認する。
```
pip3 show Faker
```

2. Fakerをインストールする
```
pip3 install Faker
```

3. Fakerがインストールされたことを確認する。
```
pip3 show Faker
```
## 使用方法
1. 1つ目のターミナル(**サーバ用ターミナル**とする)を起動する
2. サーバ用ターミナルに下記コマンドを入力する
```
python3 server.py
```
3. 2つ目のターミナル(**クライアント用ターミナル**とする)を起動する
4. クライアント用ターミナルに下記コマンドを入力する
```
python3 client.py
```
5. クライアント用ターミナルにメッセージを入力し送信する
6. クライアントが送信したメッセージが、サーバ用ターミナルに表示される
7. サーバ用ターミナルが何らかのメッセージを送信し、クライアント用ターミナルにメッセージが表示される

## 使用技術
<table>
<tr>
  <th>カテゴリ</th>
  <th>技術スタック</th>
</tr>
<tr>
  <td>開発言語</td>
  <td>Python</td>
</tr>
<tr>
  <td rowspan=3>インフラ</td>
  <td>Ubuntu</td>
</tr>
<tr>
  <td>Docker</td>
</tr>
<tr>
  <td>VirtualBox</td>
</tr>
<tr>
  <td rowspan=3>その他</td>
  <td>Git</td>
</tr>
<tr>
  <td>Github</td>
</tr>
<tr>
  <td>FFmpeg</td>
</tr>
</table>
