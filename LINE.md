LINE連携が変わるタイミング：LINE案内を送って顧客が連携をしたとき
担当設定は担当営業員ができたタイミング

DBについて
サロゲートキー方式：一意となるID列で統一する
ナチュラルキー方式：複数のカラムをつなげてそのまま主キーにする

現場はナチュラルキー方式


グループ設定
担当設定がされていないとグループ一覧には追加されない




疑問点
一人の顧客に複数のLINEアカウントを連携することは可能なのか？
(一つのLOGIN_IDに対してDB上では)


172.19.221.32

LIN

検証用LINE DB
対面営業監視端末#1
LINEの1系
本支店員サイト
[ログイン](https://line.ir-service.net/Login/Admin/ABC/0)
営業員
[ログイン](https://line.ir-service.net/Login/SalesRep/ABC/0)
検証用アカウント
**営業員**
営業員名：テスト用営業員01
ログインID：salesRep01
メールアドレス：salesRep01@example.com
パスワード：salesRep01


**顧客**
営業員名：テスト用顧客(TCS開発用1)
顧客ID：tcs_kaihatsu01
メールアドレス：tcs_kaihatsu01@icloud.com
パスワード：tcs_kaihatsu01
紐づいているIphone:TCS開発用1

顧客名：テスト用顧客(TCS開発用3)
顧客ID：tcs_kaihatsu03
メールアドレス：tcs_kaihatsu03@icloud.com
パスワード：tcs_kaihatsu03
紐づいているIphone:TCS開発用3





