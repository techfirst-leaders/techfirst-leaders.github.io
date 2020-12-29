# 環境構築方法

1. Ruby 2.5.8をインストール
2. Bundlerをインストール
3. `bundle install` を実行
4. `bundle exec jekyll serve` で動作することを確認

# 新規ポストを追加する

詳しくは公式ドキュメントを参照のこと.

- [Posts（ポスト） | Jekyll • シンプルで、ブログのような、静的サイト](view-source:http://jekyllrb-ja.github.io/docs/posts/)

1. docs/_posts にMarkdownファイルを追加する
    - ファイル名は `yyyy-mm-dd-POST_TITLE.md` とする
2. [front matter](http://jekyllrb-ja.github.io/docs/front-matter/) に従い、または他のMarkdownの先頭行をコピーし、編集する
3. 記事を書く
