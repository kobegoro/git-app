方針→アピールポイントが分かりやすくて見る気になるREADME（笑）

## :orange_book:フリマアプリ
メルカリを参考に作成したWEBアプリケーションです。<br>
誰でも簡単に売り買いが楽しめるアプリの機能を実装しました。<br>
ユーザー登録、商品出品、商品購入などの機能が再現されていますが、実際の取引はできません。<br>
＋アプリ画像？（仮）考え中<br>
<br>

## :orange_book:実装した機能
- ユーザー登録・編集機能<br>
- SNS認証による登録、ログイン機能(ローカル環境のみ)<br>
- 商品出品・編集・削除機能<br>
- 商品購入機能（pay.jp）<br>
- カテゴリ機能<br>
- コメント機能<br>
- いいね機能<br>
- 商品検索機能（あいまい検索・詳細検索）<br>
- capistranoによるAWS EC2への自動デプロイ<br>
- ActiveStorageを使用しAWS S3への画像アップロード<br>
<br>

## :orange_book:本番環境
- URL:    http://54.248.69.170/<br>
- ID:     gundam<br>
- PASS:   0079<br>
<br>

## :orange_book:使用技術(開発環境)
ruby<br>
ruby on rails<br>
MySQL<br>
unicorn<br>
Nginx<br>
capistrano<br>
haml<br>
sass<br>
jquery<br>
github<br>
AWS(EC2・S3)<br>

devise<br>
rspec<br>
carrierwave<br>
ancestry<br>
payjp<br>
kaminari<br>
<br>

## :orange_book:開発体制＆使用ツール<br>
アジャイル開発。2週間ごとにスプリントを設定しました。
- Slack（進捗報告やメンバー間の連絡）<br>
- Trello（タスク管理）<br>
- ZOOM（週2回のMTG）<br>
- スプレッドシート （開発スケジュール、各メンバーの作業時間を把握）<br>
<br>

## :orange_book:Member&担当
吉村<br>
<a href="https://github.com/Satomaru178"><img src="https://avatars2.githubusercontent.com/u/63147677?s=400&u=892b244eb8922295babc96f11011f06b9c4eccb7&v=4" width="50px"></a><br>

大澤<br>
<a href="https://github.com/osawa4017"><img src="https://avatars0.githubusercontent.com/u/64793100?s=400&v=4" width="50px"></a><br>

高橋<br>
<a href="https://github.com/Yuta1634"><img src="https://avatars0.githubusercontent.com/u/63214741?s=400&v=4" width="50px"></a><br>

山田<br>
<a href="https://github.com/Fyamada1229"><img src="https://avatars3.githubusercontent.com/u/54790413?s=400&u=ff241ff28650e2f56fb3c27ec21ddd959ae323c2&v=4" width="50px"></a><br>

寺本<br>
<a href="https://github.com/kobegoro0930"><img src="https://avatars3.githubusercontent.com/u/62911575?s=460&v=4" width="50px"></a><br>
担当：<br>
[フロントエンド]<br>
- ユーザー登録＆ログイン画面<br>
- カテゴリページ（一覧ページ、カテゴリ別ページ）<br>
- TOPページ商品表示<br>
- お気に入りの追加（TOPページ、商品詳細ページ、マイページ）<br>
[バックエンド]<br>
- カテゴリ機能（Ancestry）<br>
- お気に入り機能(javascript)<br>
[工夫したポイント]<br>
ユーザビリティーを意識し、細部にこだわって実装を行いました。<br>
- ユーザー登録ページのプログレスバーの設置<br>
- マイページのいいね一覧ページで条件分岐によるビューの表示変更<br>
- カテゴリ一覧ページでアンカーリンクを設置する<br>
<br>

### 担当箇所（工夫したポイント）:
参考：https://github.com/higakikeita/freemarket_sample_60ce<br>
<br>

## :orange_book:課題や今後実装したい機能
アンケート取るかも<br>
<br>

## :orange_book:ERD
<br>

## :orange_book:DB設計

