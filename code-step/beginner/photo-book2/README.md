### 題材

https://code-step.com/photo2-menu/

#### setup

以下を叩くと画像ダウンロード・展開される。

```console
make setup
```

#### 学びメモ

* display:flexを指定している要素自体を中央揃えするにはmargin: 0 auto;を使う。justify-content: center;で揃えることはできない
* display:flexを指定している要素はボックスモデルであり、要素自体にflexboxが適用されている訳ではない
* imgにmax-width: 100%をつけることでboxのサイズに合わさるためレスポンシブ対応にする
* box-sizing: border-boxを指定することでwidthの範囲をmarginやpaddingも含めたものにできる
