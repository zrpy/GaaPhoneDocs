# GaaPhoneDocs
Gaaphoneは完全無料な電話認証サイトです。<br>
管理者は責任を取りませんし、このサイトでは他APIを使用しています
## Request Type
すべてのリクエストにはGETが使用されます
## RequestExample

### https://gaaphone.onrender.com/api/order_phone
#### /random
ランダムに国、電話番号を取得します
#### /<country>
指定した国の電話番号を取得します

### https://gaaphone.onrender.com/api/get_message/<full_number>
指定された電話番号の来ているメッセージをすべて取得します
