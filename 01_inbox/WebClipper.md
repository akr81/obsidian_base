---
Aliases: []
Tags:
  - TIPS
  - WebClipper
---

## WebClipperを使ってみよう

Obsidianには、ブラウザ拡張機能としてWebClipperが用意されています。
気に入ったWeb記事などをmarkdown形式でvaultに取り込んで、タグ付けして管理したり、自分のメモとリンクさせることができます。

- [Chromeの拡張機能](https://chromewebstore.google.com/detail/obsidian-web-clipper/cnjifjpddelmedmihgijeibhnjfabmlf?pli=1)

## テンプレートの例

Webclipperでは、取り込み時にテンプレートによる加工をすることができます。
著者が使っている例をいくつか紹介します。
(設定ファイルを10_materialsに入れてありますので、インポートすれば利用可能です)

### Amazon読書ノート

Amazonの書籍ページを、読書ノートのガワとして取り込みます。
著者はこのように使っています。

1. 買った本はまず取り込む
2. (optional)ページ内や出版社のページから目次をコピペする
3. (optional)書評や概要を探してコピペする
4. タグを更新する

2, 3は必須ではありませんが、目次には書籍のタイトル以上の情報があるため、積ん読にしてしまってもvault内を検索した際に再度出会う可能性が高くなります。

### Kindleハイライト

Kindleでは読書中にハイライトすることができ、[専用のサイト](https://read.amazon.co.jp/kp/notebook)から確認することができます。
このページの内容を取り込みます。
(このテンプレートは、[Jazzと読書の日々 - Obsidian:WebClipperをkindle対応にする](https://wineroses.hatenablog.com/entry/2024/12/06/170041)で公開されているものをベースにしています)

その本を読んでいる時には気づかなかったり知らなかった知識を、あとからリンクしたりさらにまとめたりすることができるようになります。

取り込んだハイライトの英数字が全角で見づらい(検索しづらい)場合には、`04_templates`にある全角半角変換テンプレートを適用すると半角にできます。
