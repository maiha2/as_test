

# テスト ID
WAIC-TEST-0003-03

# テストのタイトル
フォーカス移動順序を指定した複数のリンク (マークアップ順)

# テストの目的
複数のリンクにフォーカス順序を指定した場合、指定した順序でフォーカスが移動するかの確認

# テストの対象となる達成基準 (複数)
2.4.3

# 関連する達成方法 (複数)
H4

# テストコード (テストファイルへのリンク)
[WAIC-CODE-0003-03](https://waic.github.io/as_test/WAIC-CODE/WAIC-CODE-0003-03.html)

# テストコードのソース (抜粋)
```html
<div>
<a href="#" tabindex="4">リンク 1</a> <a href="#" tabindex="3">リンク 2</a> <a href="#" tabindex="2">リンク 3</a> <a href="#" tabindex="1">リンク 4</a> <a href="#" tabindex="0">リンク 5</a> <a href="#" tabindex="-1">リンク 6</a> <a href="#" tabindex="0">リンク 7</a>
</div>

```
# テスト手順 (視覚閲覧環境)
キーボード操作 : Tab キーを押下し、フォーカスの移動順序を確認

# 期待される結果 (視覚閲覧環境)
次の 1. 〜 2. をすべて満たしている
1. 次の順序でフォーカスが移動する : (カッコ内は、指定されている tabindex 属性値)
リンク 4 (1) 
リンク 3 (2) 
リンク 2 (3)
リンク 1 (4)
リンク 5 (0)
リンク 7 (0)
2. リンク 6 (tabindex="-1") にはフォーカスが移動しない

# テスト実施時の注意点 (視覚閲覧環境)
なし

# テスト手順 (音声閲覧環境)
キーボード操作 : Tab キーを押下し、フォーカスの移動順序を確認

# 期待される結果 (音声閲覧環境)
次の 1. 〜 2. をすべて満たしている
1. 次の順序でフォーカスが移動する : (カッコ内は、指定されている tabindex 属性値)
リンク 4 (1) 
リンク 3 (2) 
リンク 2 (3)
リンク 1 (4)
リンク 5 (0)
リンク 7 (0)
2. リンク 6 (tabindex="-1") にはフォーカスが移動しない

# テスト実施時の注意点 (音声閲覧環境)
なし

# 関連する要素や属性
a 要素 , tabindex 属性

