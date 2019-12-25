# ER図1
## 全体
- 商品とユーザが管理人とリレーションを持つ必要がない
- 決済のテーブルと購入履歴のテーブルは一つにまとめられる。

## カート
- 商品IDからアーティスト名、ジャケット画像、シングル/アルバム名は引っ張ってこれるのでカラム名として必要ない
- カート対決済がカートが1、決済が多になっているが本来は逆であるため、カートに決済IDのFKが必要である。
-

# 注意
* マークダウン形式で記入してください。
* 全体を通しての指摘事項の場合、テーブル名の部分を「全体」「共通」などとしてください。