# GitHub Flowとは
GitHub社が自社で用いてるワークフロー  
①masterからブランチを切って開発をする  
②開発が完了したらプルリクを発行する  
③コードレビューをして承認されたらマージしてリリースしていく

# ポイント
 - masterブランチは常にデプロイできる状態に保つ
 - 新開発はmasterブランチから新しいブランチを切ってスタート
 - 作成した新しいブランチ上で作業しコミット
 - 定期的にPushする
 - masterにマージするためにプルリクエストを行う
 - 必ずレビューを行う
 - masterブランチにマージしたらすぐにデプロイする  
 ←テストとデプロイは自動化

## メリット
  - 開発フローをシンプルにできる
  - リリース中の内容がmasterを見ればわかる
  - 以前の状態にすぐに戻せる