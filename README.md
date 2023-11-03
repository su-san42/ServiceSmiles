## サービス概要
接客ロールプレイングコンテストを通じて飲食店の接客や
楽しみを共有して向上できるアプリ

##　想定されるユーザー層
飲食店の勤務に心理的不安を抱える人
飲食店での接客ロールプレイング経験者
飲食店でロールプレイングコンテストに興味がある人

## サービスコンセプト
飲食店の勤務でお客様との接客に心理的不安を抱えている人に接客の楽しみや
コツを学んで接客ロールプレイコンテストや日々の業務改善に繋げてほしいと思い考えました。

## Why You?
飲食店での勤務をアルバイト〜店長まで経験して、その中での楽しみ（やりがい）やコツ（意識していること）を伝えたいと思ったこと
接客ロールプレイングコンテストに幾度となく挑戦してその苦汁飲み成長できたので　出場される人には良い結果と今後の業務改善に生かしてほしいと思ったこと

## 実装を予定している機能

* 会員登録（ニックネーム・パスワード）今回ユーザーの結果保存を用いて振り返りするためににログイン機能を想定しました。

*ユーザーはログインしてから全ての機能を使用できる

* 語彙力言いかえ検索（敬語や言葉がけなど、意味と言いかえての例文で出力）例：この人はすごい力を持った人です。⇨この人は人知を超える力を持った人です。 語彙力を鍛えるメリットや方法を記述した上で検索バーを設け記載
 #技術的にはチャットGPTを想定

* お客様対応集　飲食店におけるクレームやトラブルにおいて一般的な意見としての経験や対応を記載

＊競技タイマー　（5分タイマー・残り1分になるとベルが１回なり、終了時に２回なるようにする）

*診断検査（１０個前後想定）現場で想定される対応をセレクト形式で（４択）で表示　結果と傾向（どういった点に重きを置き、改善の気づき、 お客様の心境や従業員心理）をテキスト表示・参考の接客動画（YouTube)をリンク表示

＊接客ロールプレイングゲーム（Pythonにて構築予定：時間制限や条件を設け適性検査で行った類似の内容を選択肢から選択したら次の場面に出るよう設計　お客様が来店〜退店までの飲食店でいかに適切にできるか検証）
Pythonの実装理由は　個人でのキャッチアップが進んでいる点と、転職後もPythonを利用したい思いから生かしたいと思い選定しました。技術的なサポートが受けれないなどの点があるならrailsでの実装も視野に入れてます。
結果と審査項目表をテキスト表示して振り返る（後にレコメンド機能を設け関連する動画も埋め込めるようにする）

*お気に入り登録（語彙力言い換え検索・成功体験など確認できるようにする）

*体験共有（勤務をしてでの成功体験やロープレの練習方法を投稿、共有できる）

*レコメンド機能の実装（接客ロールプレイングゲーム・適性検査結果をもとに　動画の表示やコメント）

## 差別化売りのポイント
＊タイマーだけや動画共有サービスは他にもあるが、
練習・成功体験の共有・言い換え機能はなく、コンテストに比重は置きつつも接客について学べるのはないので考えました。

## 継続的なサービス運用
成功体験や練習の共有だけでなく、カレンダー機能を設け大会日をカウントダウンすることにより、１度きりの運用だけでなく定期的に利用が見込まれ継続的なサービス運用が見込まれる

## MVP
マルチ検索・オートコンプリート（語彙力言いかえ検索に適応）
カレンダー機能設け　練習日や大会の日程を登録カウントダウンできるようにする

## その他の機能
＊動画・音声録音　共有や分析は１人だとAPIの兼ね合いもあり、２人以上いる想定で今後検討する

## 開発環境(想定)
- Docker
- Rails ６系
- Ruby 3.2.2
- フロントエンド:React
- CSSフレームワーク: bootstrap5系
- WebAPI:
- YouTube API ,
- その他：Chat GPT
- VCS: GitHub
- CI/CD: GitHubActions
- Python3系