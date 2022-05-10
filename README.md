# サービス概要
**Youtubeで新しいボカロ曲に出会う事に苦労している人達の為の**

**便利な絞り込み機能を備えた** 

**ボカロ曲特化のサーチサービスです** 

# メインのターゲットユーザー
- ボーカロイドの楽曲を好んで聴く人
- youtubeでのネットサーフィン(知らないボカロ曲探し旅)に満足していない人
- youtubeでもniconico動画と似た検索機能を使ってボカロ曲を検索したい人
# ユーザーが抱える課題
- 現状のyoutubeアプリでボカロ曲だけを検索することが困難(niconico動画のようなタグ機能がほとんど機能していない、検索機能の使い勝手が良くなく、歌ってみたなど関係のない動画が混入する)

- youtubeの「あなたへのおすすめ」機能は自身がチャンネル登録している人の新曲、最近再生数を伸ばしているhotな曲に偏っており、完全に知らないボカロ曲が表示されることが少ない
# 解決方法

youtubeに投稿されたボーカロイド楽曲だけを抽出し、その中でソート、ボーカル別(初音ミクor鏡音リン…)や再生回数など便利なフィルター機能を使えるようにする。

→ 従来のyoutubeよりも、ボーカロイド楽曲を探すのに特化した快適なサービスにする!!

# 実装予定の機能
## MVP

- ボーカロイド楽曲専用のサーチ機能
  - 検索結果にはボーカロイドオリジナル楽曲しか表示されない
  - ソート機能(再生回数、投稿日時順…)
  - フィルター機能(再生回数、ボーカル別)
- ランダム曲選出機能
  - 全ての楽曲、もしくはフィルターを付けてランダムで1曲オススメしてくれる(聴く?orもう一回選出する!画面も実装)
- 今日のピックアップ機能
  - 1日おきに全ての楽曲から3曲ほどランダムでピックアップされトップ画面に表示される
- お問合せ機能
  - 検索結果に不適切な動画が含まれていた場合URLを添えて報告できる
  - その他問題があった場合に管理ユーザーに報告することができる
- 管理ユーザー
  - 管理画面から検索結果を確認することができる
  - 検索結果から動画を削除することができる
  - 検索結果に動画を追加することができる


## 本リリース前(MVP後)
- ログイン機能
  - ユーザー登録やログイン機能
- タグ機能
  - ユーザー登録済みのユーザーのみタグを作成可能
  - ユーザー登録済みのユーザーのみタグによる検索が可能になる(登録なしでも動画についてるタグの閲覧は可能)
- 管理画面
  - 管理画面からタグの作成状況を閲覧、削除、追加可能。
  - 管理画面からユーザーがどの動画にどのタグをつけたか閲覧可能(念の為、タグの乱立や関係ないタグをつけまくるユーザーがいた場合、アカウントを特定したいため。処置は検討中)


### 『補足』
元々ログイン機能＆タグ機能は本リリース後の追加機能として考えていましたが、ユーザーに公表する前に実装することにしました！


なぜならユーザーにとって、後からユーザー登録の欄が増えるのは少し違和感があるのではと思いました。それにタグ機能はユーザーがいないと成り立たないものなので、後出しするより勢いのあるリリース直後の時点で実装されていた方が興味を持ってもらえると判断したためです！

# なぜこのサービスを作りたいのか？

私は昔からボーカロイド楽曲が好きで、既にある程度知名度のある楽曲は知っており、niconico動画でマイナーなボカロ曲を検索しては自分の知らない良曲や新曲を見つけたりするのが好きでした!!

ただ現状のyoutubeには上記のような問題があり、正直検索機能は使い勝手が悪く感じます。結果マイナーな楽曲や自分の知らない投稿者の曲を聴く機会が減っちゃって、それを改善するツールがあれば以前のような楽しみ方がyoutubeでも出来ると思いこのサービスを作りたいと思いました!!!

最近プロセカも盛り上がっているので、普段niconico動画を使用しない層にもたくさんのボーカロイド楽曲を知ってもらいたいです!

# 画面遷移図
https://www.figma.com/file/ko6a1353Y9GotB8a8uUYLy/Untitled?node-id=0%3A1

#  ER図
https://drive.google.com/file/d/1fJFZBqG2-kH_nd3G7hl-zNFCgalW6WJn/view?usp=sharing
# スケジュール

README〜ER図作成：5/2 〆切

メイン機能実装：5/3 - 6/3

β版をRUNTEQ内リリース（MVP）：6/3〆切

本番リリース：6/17

