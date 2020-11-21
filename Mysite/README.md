## 外部にて調べたことや復習内容等・各種メモ

現在書籍勉強中.......

---

- header

  - 同page内ジャンプは、

    ジャンプ元で**href="#hoge"**

    ジャンプ先で**name="hoge"**と指定する。

  - Bookers2のように、ヘッダー左にタイトル・ヘッダー右に各コンテンツを表示するnavbar記載は、

    (Boostrapの記載では

    左側は<a class="navbar-brand">を用いる。

    右側は<ul class="navbar-nav">を用いる。)

    

    html上での記載は、高さを指定し、float: left;オプション(左揃えの場合)、navも同様に右揃えオプションで記載する。

  - nav内構造 body-header-nav-ul-li-a タグ

  - line-heightオプションはheightと同数にする

  - 両端のpaddingが指定されている場合、1箇所あたりのpadding*4を全体のwidthとすると等間隔で見やすいyy