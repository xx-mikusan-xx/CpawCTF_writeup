# 問題:Can you open this file ?
## 概要
ファイルの種類を調べて実行する．



## 解き方
fileコマンドを使用し，ファイルの種類を確かめる．コマンドの実行方法は以下の通り．

``` 
file open_me
```

実行結果を見ると次のような情報が得られる．

- ファイル形式: Composite Document File V2 (Word ドキュメント)
- エンディアン形式: Little Endian
- 作成者: 不明 (?v??)
- テンプレート: Normal.dotm
- 最後に保存したユーザー: 不明 (?v??)
- リビジョン番号: 1
- 作成アプリケーション: Microsoft Office Word
- 編集時間: 28分
- 作成日時: 2015年10月12日 04:27
- 最後に保存された日時: 2015年10月12日 04:55
- ページ数: 1
- 単語数: 3
- 文字数: 23
- セキュリティ: なし

実行結果からwordファイルであることがわかるので`.doc`の拡張子をつけてファイルを開くとフラグを得ることができる．

