# ObjectViewController
Unity2018でマウスによる視点の変更と、視点方向へのオブジェクト移動を行います。
右クリックでフリー視点移動、垂直キーで前進、後退、水平キーで水平方向への視点移動マウスホイールで拡大縮小を行えるようにします。


# 動作環境・言語
Unity2018
C#

## インストール
 ObjectViewController.unitypackage をUnityエディタのプロジェクトにドラッグアンドドロップしてください。

## アンインストール
 Unityエディタのプロジェクトにあるアセット(CodeLab/ObjectViewController)を削除してください。

## 使い方
scropt/CameraController.csをメインカメラにアタッチする
scropt/MoveController.csをに動かしたいオブジェクト(プレイヤーオブジェクト）にアタッチする。
ヒエラルキからメインカメラを選択しスクリプトのTargetObjにプレイヤーオブジェクトをアタッチする。
必要なら、プレイヤーオブジェクトの子に空のオブジェクトを作成し、TargetViewObjにアタッチすれば、視点がそちらの方向に向くようになります。指定しない場合は、TargetObjの原点座標が視点になります。


## License

Copyright (c) 2018 CodeLab
Released under the MIT license

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

