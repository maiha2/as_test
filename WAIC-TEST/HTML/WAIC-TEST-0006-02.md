

# テスト ID
WAIC-TEST-0006-02

# テストのタイトル
a 要素に指定した画像 (代替テキストあり)

# テストの目的
画像 (代替テキストあり) を a 要素に指定した場合、代替テキストが表示・読み上げされるかの確認

# テストの対象となる達成基準 (複数)
1.1.1, 2.4.4, 2.4.9

# 関連する達成方法 (複数)
H30

# テストコード (テストファイルへのリンク)
[WAIC-CODE-0006-02](https://waic.github.io/as_test/WAIC-CODE/WAIC-CODE-0006-02.html)

# テストコードのソース (抜粋)
```html
<div>
<a href="http://waic.jp/">
<img src="img/logo.png" alt="ウェブアクセシビリティ基盤委員会" height="77" width="334">
</a>
</div>

```
# テスト手順 (視覚閲覧環境)
表示 : ブラウザの設定を変更して画像非表示にし、表示内容を確認

# 期待される結果 (視覚閲覧環境)
リンク画像の代替テキスト “ウェブアクセシビリティ基盤委員会” が表示される

# テスト実施時の注意点 (視覚閲覧環境)
なし

# テスト手順 (音声閲覧環境)
リンクを読み上げ、内容を確認

# 期待される結果 (音声閲覧環境)
リンク画像の代替テキスト “ウェブアクセシビリティ基盤委員会” が読み上げられる

# テスト実施時の注意点 (音声閲覧環境)
なし

# 関連する要素や属性
a 要素 , img 要素 , alt 属性

