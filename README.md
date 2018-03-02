# TUT生のためのLaTeX様式テンプレート集

TUT生のためにLaTeXで各資料をかけるようにしようぜってリポジトリです．
今はまだ作っている書類の数が少ないので，手伝っていただける方を募集してます．

## 使い方

`pinfo.yaml`を自分用に書き換えてください．
そして，各申請書のディレクトリで次の例のようにタイプセットします．
以下の例では，申請書の`.tex`ファイルを`form.tex`としています．

~~~~
$ platex form.tex
$ pythontex form.tex
$ platex form.tex
$ dvipdfmx form.dvi
~~~~


## 必要なもの

* [pdffill.sty](https://github.com/kmaed/pdffill)

### 以下はpipで入れて

* pygments
* mojimoji
* pyyaml

## 注意

大学から怒られたらこのリポジトリは消します．
