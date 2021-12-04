簡単に長形3号封筒へ宛先を印刷するためのテンプレート

<img src="https://user-images.githubusercontent.com/45380191/144691571-fe3c3f81-1655-4fbe-98b9-072c06eac991.png" width=700px>

## 説明
- os: mac / app: notes
- envelope-no3long.pagesは管理対象外ファイルに指定しており、誤って情報を書き込んだファイルをpushしないためテンプレートファイルをコピーして使用する
```sh
cp template-envelope-no3long.pages envelope-no3long.pages
```


## 使用手順

0. template-envelope-no3long.pagesを「envelope-no3long.pages」という名前でコピーする
1. アプリnotesでファイルenvelope-no3long.pagesを開く
1. nodesから{dest_...}, {stc_...}の6つの値を任意の文字列に置き換える
1. 「様/御中」の文字から使用する方だけ残し、もう一方を削除する
1. 内容を確認し印刷する


### 印刷時の注意
- 印刷時の設定から[レイアウト] >[ページの方向を反転]にチェックを入れる
### プリンターの用紙
<img src="https://user-images.githubusercontent.com/45380191/144691414-78b89677-5329-4b11-a989-cf7a4e5170a4.png" width=400>


## 備忘録
### 敬称
| 敬称 | 説明 |
| :-- | :--- |
| 様  | 個人 |
| 御中 | 団体名, 組織名, ※係の後は御中|
| 行/宛 | 返信用封筒, 個人:宛, 団体:行 |
