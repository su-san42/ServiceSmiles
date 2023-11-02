#  サービス名：Check-your-mind


## サービス概要

飲食店での接客を行う中で、外国人従業員とお客様との意思の疎通
国籍問わず経験不足による接客対応の心理的不安を軽減できるアプリ

##　想定されるユーザー層
飲食店のお客様との対応に苦手意識を抱えてる人
飲食店で働く外国人従業員

## サービスコンセプト
旅館・飲食店において店長や従業員経験をした中で、人材不足による外国人雇用・時間や指導者不足による不充分な教育現場が多く感じ、現場に出て勤務した際　従業員が少しでも心理的不安を軽減できるようにしたいと思いこのアプリを考えました。

## 実装を予定している機能
* 会員登録（ニックネーム・パスワード）今回ユーザーの結果保存を用いて振り返りするためににログイン機能を想定しました。

*ログイン前に行える機能
* 語彙力言いかえ検索（敬語や言葉がけなど、意味と言いかえての例文で出力）例：この人はすごい力を持った人です。⇨この人は人知を超える力を持った人です。
　 語彙力を鍛えるメリットや方法を記述した上で検索バーを設け記載　
*言語翻訳　deeplAPIを用いて　ポップアウト表示でいつでも手軽に検索できるようにする

*ログイン後の機能
*適性検査（１０個前後想定）現場で想定される対応をセレクト形式で（４択）で表示　結果と傾向（どういった点に重きを置き、改善の気づき、お客様の心境や従業員心理）をテキスト表示

＊接客ロールプレイングゲーム（Pythonにて構築予定：時間制限や条件を設け適性検査で行った類似の内容を選択肢から選択したら次の場面に出るよう設計　お客様が来店〜退店までの飲食店でいかに適切にできるか検証）
結果と傾向をテキスト表示 参考の接客動画（YouTube)をリンク表示

*お客様対応集　飲食店におけるクレームやトラブルにおいて一般的な意見としての経験や対応を記載

※お気に入り登録（語彙力言い換え検索・翻訳したものなど確認できるようにする）

## 差別化売りのポイント
＊従業員教育は個々の会社のマニュアルなどによる比重が大きいが、マインドの育成や語彙力などマニュアルでは対応できない部分に　も行き届いている
　具体的な機能として、言いかえ検索・接客ロールプレイング・適性検査など

## 継続的なサービス運用
＊体験共有（この行動して喜ばれたなど、ユーザーが投稿できて　成功体験を共有いいねボタン・お気に入り登録できるようにする）

### MVP
レコメンド機能の実装（接客ロールプレイングゲーム・適性検査結果をもとに　動画の表示やコメント）
マルチ検索・オートコンプリート（言語翻訳・語彙力言いかえ検索に適応）

### その後の機能
＊多言語化を実装予定
