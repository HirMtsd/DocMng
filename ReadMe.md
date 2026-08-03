# DocMng
ドキュメントの記述方法や管理方法のまとめ
(JavaやPythonの開発プロジェクトのドキュメント管理を適切にしたい)
- ドキュメント変換ツール
- ドキュメント記述のベストプラクティス


## ツール
### 変換
- Pandoc
文書ファイルの相互変換
https://pandoc.org/
https://pandoc.org/MANUAL.html
https://pandoc-doc-ja.readthedocs.io/ja/latest/users-guide.html

- DocUtil
TextのHTML,LaTeX,man page,OpenDocument,XML化
https://docutils.sourceforge.io/

- PyMuPDF
PDFのデータ抽出、分析、変換用Pythonライブラリ
https://pymupdf.readthedocs.io/en/latest/

- zerox
PDF,DOCXのMarkdown化
https://github.com/getomni-ai/zerox

### 図表
- グラフツール
 - graphviz
https://graphviz.org/

 - matplotlib
https://matplotlib.org/

 - mermaid
https://github.com/mermaid-js/mermaid
https://github.com/mermaid-js/mermaid-cli

 - draw.io
https://github.com/jgraph/drawio-desktop

 - PlantUML
https://plantuml.com/ja/


| ツール名 |	主な用途・分類 |	記述形式 |	主な強み |	弱点・注意点 |
|:--    |:--    |:--    |:--    |:--    |
|Graphviz	 | ネットワーク構造・有向グラフ	| DOT言語	    | 自動配置に優れ、大規模なノード構造に強い | 見栄えの細かい調整や最新デザイン化が難しい|
|Matplotlib| データ分析・数値プロット	    | Pythonコード	| 統計グラフや複合データの自由な描画が可能 | 自動レイアウトのダイアグラム作成には不向き|
|PlantUML	 | ソフトウェア設計（UML）	    | PlantUML構文 | UML全般を高機能にカバーし拡張性が高い | Java実行環境や外部サーバー連携が必要な場合がある|
|Mermaid	 | Markdownドキュメント内作図	  | 軽量テキスト構文 | GitHub/Notion等で直接レンダリング可能 | 複雑な図や細かな配置制御には限界がある|
|draw.io	 | 汎用ダイアグラム・システム構成図 | CSV / XML / Mermaid（GUI補完） | GUI主体の自由配置とテキスト生成の両立 | 純粋なコード管理・自動描画メインの運用には不向き|



## QRコード
【簡単】QRコードの作成と読み取り in Python
https://qiita.com/PoodleMaster/items/0afbce4be7e442e75be6

Python qrcode
https://pypi.org/project/qrcode/

## 他の二次元コード
Python treepoem
https://pypi.org/project/treepoem/

BWIPP
https://github.com/bwipp/postscriptbarcode

## ベストプラクティス(サンプル)
### ReadMe
Awesome README
https://github.com/matiassingers/awesome-readme

Make a README
https://www.makeareadme.com/

Shields.io (バッジ)
https://shields.io/

shields.ioを使って技術系アイコンを量産した 2020-05-16
https://qiita.com/s-yoshiki/items/436bbe1f7160b610b05c

https://img.shields.io/badge/-CISSP-white?log=isc2
https://img.shields.io/badge/-CISSP-468145?log=isc2&labelColor=white
https://img.shields.io/badge/Python-3.10-3776AB?log=python&labelColor=white
https://img.shields.io/badge/-Keybase-33A0FF?log=keybase&labelColor=white
https://img.shields.io/badge/Creative_Commons-CC--BY--4.0-ED592F?log=creativecommons&labelColor=white

プライベートリポジトリでもBudgeを貼りたい 2023-12-01
https://qiita.com/ma91n/items/6c572c5887a50223c2b1
Shields.io経由でだいたいなんでも自由にバッジ表示する 2017-12-14
https://qiita.com/ymtszw/items/77d1d6bbe0687848470b

### CHANGELOG

Keep a Changelog (変更履歴)
https://keepachangelog.com/

Semantic Versioning
https://semver.org/spec/



絵文字チートシート
https://github.com/ikatyang/emoji-cheat-seet/blob/master/README.md


### LICENCE
ライセンス
https://gigazine.net/news/20180607-choose-a-license/
https://www.gnu.org/licenses/license-list.html.en

CC BY-NC-ND
https://creativecommons.org/licenses/by-nc-nd/4.0/deed.ja

PolyForm Noncommercial License
https://polyformproject.org/licenses/noncommercial/1.0.0

OSSライセンス解説
https://jpn.nec.com/oss/osslc/doc/20210828_ODC.pdf
https://tech.bitbank.cc/20210823/

### コミットメッセージ
Conventional Commits
https://www.conventionalcommits.org/ja/
https://note.com/st_dev0/n/n8eccdc549129


### Docstring Conventions
[Docstring Conventions](https://peps.python.org/pep-0257/)
https://github.com/whosaysni/pep-ja/blob/master/pep-0257.rst

## 参考
数式の無いドキュメントに LaTeX を使うことは意義があるのか - 日常のカフスボタン https://share.google/2pp8bbc9RxxyJwJua




## 各種文書
### 行政文書
行政文書をマークダウン化しよう！
https://metidx-gov.note.jp/n/n2bd18b23dba3

条項・条文をcode blockで括る際に自動改行されないことへの対応策
https://github.com/meti-oi-startups/METI-JPO-Model-Contract/issues/33

## ロゴ
https://worldvectorlogo.com/
