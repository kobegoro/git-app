## :orange_book: フリマアプリ
メルカリを参考に作成したWEBアプリケーションです。<br>
誰でも簡単に売り買いが楽しめるアプリの機能を実装しました。<br>
ユーザー登録、商品出品、商品購入などの機能が再現されていますが、実際の取引はできません。<br>
<br>
<img width="1089" alt="スクリーンショット 2020-08-27 0 09 50" src="https://user-images.githubusercontent.com/62911575/91321525-ac313380-e7f9-11ea-936a-ebce2c4f9d24.png"><br>
<br>

## :orange_book: 実装した機能
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

## :orange_book: 本番環境
- URL:    http://54.248.69.170/<br>
- ID:     gundam<br>
- PASS:   0079<br>
<br>

## :orange_book: 使用技術(開発環境)
<a href="https://www.ruby-lang.org/ja/"><img src="https://i1.wp.com/qs.nndo.jp/wp-content/uploads/2017/06/ruby.png?fit=393%2C346" height="50px"></a>
　<a href="https://railsguides.jp/"><img src="https://job.fellow-s.co.jp/limg/public/wsystem/wp-content/uploads/rails_lo.jpg" height="50px"></a>
　<a href="https://www.mysql.com/jp/"><img src="https://cdn-ak.f.st-hatena.com/images/fotolife/o/oasist/20200614/20200614000533.png" height="50px"></a>
　<a href="https://unicorn.bogomips.org/"><img src="https://livedoor.sp.blogimg.jp/sasata299/imgs/b/d/bdc11dd3.png" height="50px"></a>
　<a href="https://www.nginx.co.jp/"><img src="https://i2.wp.com/tadtadya.com/wp-content/uploads/2017/08/nginx-min-edit.png?fit=626%2C329&ssl=1" height="50px"></a>
　<a href="https://github.com/capistrano/capistrano"><img src="https://capistranorb.com/assets/images/CapistranoLogo.png" height="50px"></a>
　<a href="https://haml.info/"><img src="https://haml.info/images/haml.png" height="50px"></a>
　<a href="https://sass-lang.com/"><img src="https://cdn.worldvectorlogo.com/logos/sass-1.svg" height="50px"></a><br>
 <br>
　<a href="https://jquery.com/"><img src="https://cdn.worldvectorlogo.com/logos/jquery-1.svg" height="30px"></a>
　<a href="https://github.co.jp/"><img src="https://i.pinimg.com/originals/3c/d5/67/3cd5679f54dc60811383649f9f6ea37d.png" height="50px"></a>
　<a href="https://aws.amazon.com/jp/"><img src="https://www.skyarch.net/blog/wp-content/uploads/2014/11/Non-Service_Specific_copy_AWS_Cloud.png" height="50px"></a><br>
<br>

## :orange_book: 開発体制＆使用ツール<br>
アジャイル開発。2週間ごとにスプリントを設定しました。
- Slack（進捗報告やメンバー間の連絡）<br>
- Trello（タスク管理）<br>
- ZOOM（週2回のMTG）<br>
- スプレッドシート （開発スケジュール、各メンバーの作業時間を把握）<br>
<br>

## :orange_book: Member（Github-link）&担当
### <a href="https://github.com/Satomaru178">吉村</a><br>
<a href="https://github.com/Satomaru178"><img src="https://avatars2.githubusercontent.com/u/63147677?s=400&u=892b244eb8922295babc96f11011f06b9c4eccb7&v=4" width="50px"></a><br>

### <a href="https://github.com/osawa4017">大澤</a><br>
<a href="https://github.com/osawa4017"><img src="https://avatars0.githubusercontent.com/u/64793100?s=400&v=4" width="50px"></a><br>

### <a href="https://github.com/Yuta1634">高橋</a><br>
<a href="https://github.com/Yuta1634"><img src="https://avatars0.githubusercontent.com/u/63214741?s=400&v=4" width="50px"></a><br>

### <a href="https://github.com/Fyamada1229">山田</a><br>
<a href="https://github.com/Fyamada1229"><img src="https://avatars3.githubusercontent.com/u/54790413?s=400&u=ff241ff28650e2f56fb3c27ec21ddd959ae323c2&v=4" width="50px"></a><br>

### <a href="https://github.com/kobegoro0930">寺本</a><br>
<a href="https://github.com/kobegoro0930"><img src="https://avatars3.githubusercontent.com/u/62911575?s=460&v=4" width="50px"></a><br>
**フロントエンド**<br>
・ユーザー登録＆ログイン画面<br>
・カテゴリページ（一覧ページ、カテゴリ別ページ）<br>
・TOPページ商品表示<br>
・お気に入りの追加（TOPページ、商品詳細ページ、マイページ）<br>
・README<br>

**バックエンド**<br>
・カテゴリ機能（Ancestry）<br>
・お気に入り機能(javascript)<br>

**工夫したポイント**<br>
ユーザビリティーを意識し、細部にこだわって実装を行いました。<br>
・ユーザー登録ページのプログレスバーの設置<br>
・マイページのいいね一覧ページで条件分岐によるビューの表示変更<br>
・カテゴリ一覧ページでアンカーリンクを設置する<br>
<br>

## :orange_book: 課題や今後実装したい機能
- ポイント機能<br>
- ユーザ評価機能<br>
- レスポンシブ対応<br>
<br>
