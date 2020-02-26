# Mordred記述子テーブルの自動生成プログラム

#### 概要
三次元化した化合物のsdfファイルから, Mordred記述子を算出しcsvファイルを出力するプログラム<br>
<br>
<br>

#### 機能
記述子にはMordredの記述子を使用.<br>
2D, 3D記述子の両者を算出<br>
※ FingerPrint等の算出にも対応したバージョンにアップグレード予定<br>
※ RDKitにはロードに失敗する化合物が存在する. そのような化合物の記述子計算はスキップされ行から外される.

#### 使用方法
コマンドラインからDescriptor.pyを実行するのみ.<br>
Descriptor.pyは引数を3つ有する.
* 第一引数: sdfファイルのパス
* 第二引数: データテーブル(csvファイル)のパス
