# poorMBSE

MBSEをテキストファイルとExcel/VBAなどのツールよって実現するプロジェクト。
(日本の企業だと高いツールは導入しづらいし、ソフトのインストールも難しいのでMS-Office/フリーのツールを使う。)

●全体方針

モデルをテキストにより記述する。
文法にはSysML2.0の文字記述方法を利用する。

各システムによって最適な表現が異なるので、独自拡張性を持たせて、独自の変換をする。
(例えば、各アクチュエータやセンサについて外部から見えるふるまいだけをSysMLで記述して、内部的に必要な状態を拡張部に記載する。)

-----------------------------------------

当面は、SysML2.0モデル記述をPlantUMLの記法に変換してPlantUMLを使ってビジュアル化する。

UMLで表現できない記述は、文字で表現する。利用できるSysML2.0の文法に制限を加える。

TODO)

◎SysML2.0 -> PlantUML変換ツールを作る。　

■(SysML2.0 - UML)差分表現文法を考える。

◎モデルチェックツールを作る。　(文法チェック、整合性チェック、)

◎様々な切り口に変換して、PlantUMLで表現するツールを作る。

■構造化のルールを決める。

-----------------------------------------

SysMLでは記述方法のみを定義している。構造化(階層化)されていないので追加のルールを作成する。

参考)
https://marketplace.visualstudio.com/items?itemName=sensmetry.sysml-2ls
