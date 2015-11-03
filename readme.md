# PM_RetroMono

## これは何？

UE4用の、画面にゲームボーイ風？なモノトーンモザイク調の処理を施すポストマテリアルです。

## 対応バージョン

Unreal Engine 4.9.2 以降 (他の環境でも動くと思いますが未確認です)

## 使い方

1. 展開した.uassetファイルをプロジェクトのフォルダ内にコピーしてください。
1. Post Process Volume をレベル内に配置します。
1. 詳細ウィンドウの「ポスト処理ボリューム」＞「Blendables」に**PM_**RetroMonoを設定
1. Unboundにチェックを入れるとレベル全体に効果がかかります。


**MP_**RetroMonoからパラメータを調整可能です。
- Mosaic Resolution  : 解像度（大きいほど細かい）
- Steps : 色の階調数
- Base Color : 基本色

**※PM_...がポストマテリアルでMP_...がマテリアルパラメータです！**


## 注意・免責

- 内容・動作結果・今後の改善につきまして完全に無保証です。

## ライセンス

CC0 (Public Domain)  
http://creativecommons.org/publicdomain/zero/1.0/deed.ja

## 作者と連絡先

- ちょむ
- http://chomstudio.sblo.jp/
- http://chomstudio.com
- https://twitter.com/chom

## バージョン履歴

- 2015.10.31 : ver. 1.0 - BluprintUE.comにて公開
- 2015.11.03 : ver. 1.1 - ノードの見直し、マテリアルパラメータの導入、基本色指定可能に
