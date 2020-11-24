## 外部にて調べたことや復習内容等・各種メモ

---

- Markdown記法

  - タグを囲うときは、`` ->　バッククォートで囲む。

  

- header

  - 同page内ジャンプは、

    ジャンプ元で**href="#hoge"**

    ジャンプ先で**name="hoge"**と指定する。

  - Bookers2のように、ヘッダー左にタイトル・ヘッダー右に各コンテンツを表示するnavbar記載は、

    (Boostrapの記載では

    左側は`<a class="navbar-brand">`を用いる。

    右側は`<ul class="navbar-nav">`を用いる。)

    html上での記載は、高さを指定し、float: left;オプション(左揃えの場合)、navも同様に右揃えオプションで記載する。

  - nav内構造 body-header-nav-ul-li-a タグとなるように覚える。

  - line-heightオプションはheightと同数にすることで、中央始まりに出来る。

  - 両端のpaddingが指定されている場合、1箇所あたりのpadding*4を全体のwidthとすると等間隔で見やすい。

- main-visual(mv)

  - CSS background-sizeプロパティ containとcoverの違い

    containは縦横倍率固定で空白あり、coverは縦横倍率固定で空白なし

  - 各コンテンツラインが存在するときは、`<section id="hogehoge">`として区切るのが良いかもしれない。→ idのプロパティに注意… 例　#hogehoge

- portfolio(pf)

  - タイトルの下の線の入れ方…擬似クラスを用い、指定された条件での装飾を行う記述。

    〜つかいかた〜

    htmlには特に記述は追加しない。cssにおけるオプション指定で、**::before** もしくは **::after** をオプション名の後に追加して、装飾の設定を行う。

  - **::nth-child** 擬似クラス (-n+m) 最初〜m番目の数まで指定

- profile

  - 背景が上手く表示されない要因の解決策として、floatオプション設定時の回り込みをclearfixオプションを用いて回避することが必要であった。

- レスポンシブ対応

  