# 運用ルール
- 機能追加またはバグ対応を行う際は、Issues を作成する。
- Issues を作成する際は、Labels を必ずつけて作成する。
  - 作成する Issues が何の対応をしているか判別できるようにするため。
  - 言葉・紙ベースでのやり取りは、バグが起きたときに原因を探すのが大変なため、できれば Issues を使いたい。
  - 作業内容を言葉・紙ベースで、やり取りするとバグが起きたときに原因を探すのが大変です。
    (聞いていない、見ていないとなってすったもんだするのは疲れます）
## Issues の記入ルール
- 右のメニューバーの Assignees, Labels を設定する。
  - 課題の実施が漏れるのを防ぐため。担当者は決めておく。
  - Labels を設定するのは、課題ごとにどの対応をするのかわかりやすくするため。
    ブランチを機能追加・バグ対応ごとに分ける必要もないから不要かな。

## ブランチの作成ルール
- Issues の作成後に、右のメニューバーの Development から新規ブランチを作成する。
  - 一応、ブランチを自分で作成し、Issues に作成したブランチを手動で紐づけできるが自動でそこまでやってくれるなら手動でやる必要はないか
- Issues の Closed は自動で行われるため、自ら行う必要はありません。
  - Issues に紐づけたブランチが Merged されたら、自動で Issues が Closed されます。 
- ブランチ名は、作業内容を書くか、Issues で管理している番号を明記するかのどちらかにしたいと思います。
  - 個人的には、Issues の番号と何の対応をしたかがわかる形でブランチ名を作成する。
## マージリクエストを処理する係は誰がするのか？
- ちゃんとソースをレビューできる人にお願いする形になるかと思いますが、どうしましょうか？


