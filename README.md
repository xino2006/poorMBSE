# poorMBSE

MBSEをテキストファイルとExcelとVBAによって実現する貧乏人のプロジェクトです。


ルール)

機能を1つのディレクトリとする。

1つのディレクトリには、少なくともディレクトリ名と同名の.mdlファイル(主mdlファイル)を置く。(機能が多くて分割する場合は、主mdlファイルから呼び出す)

.mdlファイルに状態、機能を記述する。

1つ下の機能、状態を呼び出し、参照することができる。(2つ以上下は不可)

ディレクトリ名は頭文字は大文字。そのほかの識別子は小文字。(1文字目にアンダーラインは使用不可)

例)

/(プロジェクト名).mdl

     /Ctrl/Ctrl.mdl

     /Tempctrl/Tempctrl.mdl
    
     /Speedctrl/Speedctrl.mdl


TODO)

機能のモデルの記法(YAML) -> とりあえずサンプルを作成。　ふるまいが記述できていない。独自記法が必要？？

モデルファイルの解析VBAプログラム

解析結果の表記法
