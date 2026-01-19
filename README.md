# 段位tja分解ツール

**[👉 ツールをブラウザで起動する (ここをクリック)](https://fjfjdkdk706-lgtm.github.io/TJA-Decomposition-tool/)**

段位道場のTJAファイルを、シミュレータで再生可能な単曲形式（フォルダ分け＋音声同梱）に変換・分割するWebツールです。

## 特徴
- フォルダの一括ドラッグ＆ドロップに対応
- TJAファイルの `SUBTITLE` や `WAVE` 記述の揺れを補正
- `#DELAY` を `OFFSET` に変換し、再生ズレを防止
- 不要な命令（EXAM, LEVELHOLD等）の自動削除
- ブラウザ上で完結し、サーバーにファイルは送信されません

## 使い方
1. [上記のリンク](https://fjfjdkdk706-lgtm.github.io/TJA-Decomposition-tool/)からツールを開きます。
2. TJAファイルと音声ファイルが入ったフォルダを、枠内にドラッグ＆ドロップします。
3. 変換処理が行われ、自動的にZIPファイルとしてダウンロードされます。

## ライセンスと使用ライブラリ
本ツールは [MIT License](LICENSE) の下で公開されています。

本ツールは、ZIPファイルの生成に以下のライブラリを使用しています。
- **JSZip** (MIT License)
  - Copyright (c) 2009-2016 Stuart Parmenter
  - https://github.com/Stuk/jszip

## 免責事項 (Disclaimer)
- 本ツールは現状有姿（As-Is）で提供されます。本ツールの使用によって生じたデータの損失、破損、その他のトラブルについて、開発者は一切の責任を負いません。
- 本ツールを使用して変換・生成されたファイルの著作権および利用については、利用者の自己責任において管理してください。
