# Namazuo Bot - FF14 Discord Bot
Namazuo Bot（ナマズオbot）は日本語対応のFF14拡張Discord Botです  
Discord上でアイテムやギャザクラ、天気予報、イベントなど様々な情報を確認することができます  

## 導入方法
- [Discordに招待](https://discordapp.com/api/oauth2/authorize?client_id=423156211534397461&permissions=1611000912&scope=bot)を押してNamazuo Botを招待  
- テキストに`!readme`と入力してDiscord Botの概要が表示されれば完了

## コマンド一覧

使用できるコマンドは `,help`、  
コマンドの詳細は`,help コマンド名` または ,`help カテゴリ名` で確認できます。  
使用できるプレフィックスは `,` `!` `！` です。  
このいずれかの文字を先頭に入れて、コマンドを実行するとDiscord Botが応答します。

```
■Action：アクション
  action    … アクション情報を表示
■Achieve：アチーブメント
  achieve   … アチーブメント情報を表示
■Adventure：探検手帳
  adventure … 探検手帳情報を表示
■Buff：バフ
  buff      … バフ・デバフ情報を表示
■ContentFinder：コンテンツファインダー
  cf        … コンテンツ情報を表示
■Craft：クラフター
  craft     … クラフター情報を表示
    └ craft trans … 英語圏のクラフターマクロを日本語マクロへ変換
■Event：イベント
  event     … 公式イベント情報を表示
  userevent … ユーザーイベント情報を表示
■Fate：FATE
  fate     … FATE情報を表示
■Fashion：ファッションチェック
  fashion  … ファッションチェック１００点の情報を表示
■FFLogs：FFLogs
  fflogs   … FFLogsの情報を表示
    ├ fflogs best   … 各層の個人のベストDPSを表示
    ├ fflogs job    … ジョブ別DPSランキングを表示
    └ fflogs speed  … Speedrunランキングを表示
■Finder：パーティー募集
  finder   … Discord内でパーティー募集をする際に使用
■FishingCondition：釣り情報
  fishing  … 釣り情報を編集
■Gather：ギャザラー
  gather   … ギャザラー情報を編集
■Item：アイテム
  item     … アイテム情報を表示。リアクションで表示項目を変更
             📝:アイテム詳細、🔨：クラフター情報、🌿：ギャザラー情報、🛒：交換情報、👿：モブドロップ
■Leve：リーヴ
  leve     … リーヴ情報を表示
■Minion：ミニオン
  minion   … ミニオン情報を表示
■Mob：モブ
  mob      … モブ情報を表示
■Mount：マウント
  mount    … マウント情報を表示
■Note：Note
  note     … メモ機能
■NotoriousMonster：リスキーモブ
  nm       … リスキーモブ情報を表示
   └ nm tour … モブハンツアー巡回経路を作成
■Other：その他
  aether   … 風脈情報を表示
  eureka   … エウレカ情報を表示
  maint    … メンテナンス情報を表示
  et       … 現在のエオルゼア時間を表示
  party    … コピーしたチャットテキストを `/p` マクロに変換
  treasure … 宝の地図主催用
  pos      … 指定座標位置にピンを表示した地図画像を作成
  readme   … このDiscord BOTについて表示
  reset    … Weekly、Dailyなど各リセット時間を表示
  weather  … ゲーム内の天気予報を表示
  webhook  … 公式のお知らせ等をDiscordチャンネルに表示するようにする
■Orchestrion：オーケストリオン
  orchestrion … オーケストリオン情報を表示
■Pet：ペットアクション
  pet     … ペットアクション情報を表示
■Profile：プロフィール
  profile … キャラクターのプロフィール情報を表示
  params  … キャラクターのパラメータ情報を表示
  gearset … キャラクターのギアセット情報を表示
  class   … キャラクターのジョブ／クラスのレベルを表示
  mounts  … キャラクターが所持するミニオン・マウントの数を表示
■Quest：クエスト
  quest   … クエスト情報を表示
■Recipe：レシピ
  recipe  … レシピの中間素材、末端素材の合計値を表示
    └recipe search  … キーワードアイテムを使ったレシピを検索
■TextCommand：テキストコマンド
  textcommand … テキストコマンド情報を表示
■Trade：交換できるアイテム
  trade … アイテムを使って交換できるアイテムと必要個数の一覧を表示
■Voyager：ボイジャー（飛空艇・潜水艦）
  voyager     … ボイジャー情報を編集
```

## 注意点
- JPサーバー向けです。他のサーバーだと天気、エオルゼア時間等が正確でない場合があります。
- Namazuo Botがオフラインのときはメンテ中、またはアップデート中です。その間は利用できません。

## 謝辞
- [xivapi](https://xivapi.com/)
- [FFLogs](https://www.fflogs.com/)
- [SaintCoinach](https://github.com/Rogueadyn/SaintCoinach)
