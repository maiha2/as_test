

# テスト ID
WAIC-TEST-0011-03

# テストのタイトル
h1 要素〜 h6 要素への直接移動

# テストの目的
h1 要素〜 h6 要素へ直接移動して読み上げられるかの確認

# テストの対象となる達成基準 (複数)
2.4.1, 2.4.10

# 関連する達成方法 (複数)
H69

# テストコード (テストファイルへのリンク)
[WAIC-CODE-0011-01](https://waic.github.io/as_test/WAIC-CODE/WAIC-CODE-0011-01.html)

# テストコードのソース (抜粋)
```html
<div>
<h1>果物について</h1>
<p>このページでは、果物について解説する。</p>
<h2>定義</h2>
<p>果物とは...</p>
<h3>野菜との違い</h3>
<p>果物と野菜の一番の違いは...</p>
<h4>実は果物ではないもの</h4>
<p>一般的には果物と思われがちだが、スイカは野菜である。</p>
<h5>スイカが野菜である理由</h5>
<p>そもそもスイカは...</p>
<h6>スイカの発見</h6>
<p>世界で初めてスイカが発見されたのは...</p>
<h2>人間と果物のかかわり</h2>
<p>古くから人間は...</p>
</div>

```
# テスト手順 (視覚閲覧環境)
テスト不要

# 期待される結果 (視覚閲覧環境)
なし

# テスト実施時の注意点 (視覚閲覧環境)
なし

# テスト手順 (音声閲覧環境)
見出し間を移動し、挙動を確認

# 期待される結果 (音声閲覧環境)
直前または直後の見出し要素に移動するための何らかの手段が提供されている

# テスト実施時の注意点 (音声閲覧環境)
例えば、見出しジャンプや見出しリストのような機能が実装されていれば OK と判断

# 関連する要素や属性
h1-h6 要素

