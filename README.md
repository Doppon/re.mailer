## 設定

### 送信する側(Gmail)
`app/mailers/notice_mailer.rb` で設定

### 受信する側の設定(任意)
`config/enviroments/development.rb` で設置

## 実行コマンド
```
rails c
NoticeMailer.sendmail_confirm.deliver
```
