# 大谷研究室macOS向けTeXテンプレート

東京都市大学大谷研究室のmacOS向け卒論・修論テンプレートです．

[大谷研究室ホームページ](http://www.comm.tcu.ac.jp/otani-lab/)


# 使い方

詳しいことは[詳しい人](https://texwiki.texjp.org/)に聞きましょう。

1. リポジトリをクローンします

```
git clone git@github.com:toshikiohnogi/otanilab-paper-mac.git
```

2. ディレクトリに入ります

```
cd /path/to/repository/otanilab-paper-mac/paper
```

3. LaTeXコマンドを打ち込みましょう

```
platex paper
platex paper
dvipdf mx
```

4. 美しいPDFが出力されます

```
open paper.pdf
```
