# Fraxinus 00tw

[ENGLISH](README.en.md) | [日本語](README.md)

Fraxinus 00twはFraxinusコミュニティのプロジェクトの一つで、福馬洋平氏 (https://x.com/fukumay1) による Fraxinus 00w をベースにした派生プロジェクトです。

Fraxinus 00tw の設計者は SummerOrange 氏 (https://x.com/PlasticMikan) です。

このリポジトリでは、Fraxinus 00tw の設計データを公開しています。押し出し機構、ベッド、操作パネル、プリントヘッドなどには一部選択肢があります。

![](https://fraxinus.jp/images/community/Fraxinus00tw.png)

## Highlights / 仕様概要

- Fraxinus 00w をベースにした小型 CoreXY 3D プリンタです。
- 造形範囲の目安は X/Y 70 mm、Z 約 60 mm です。  
  実際の可動範囲は採用する構成や調整によって変わる場合があります。
- 3Dプリント部品、パネル加工用 DXF、組立マニュアル、BOM をこのリポジトリから辿れるようにしています。
- ベッド、エクストルーダー周辺、フット、操作パネル、プリントヘッドに選択式の構成があります。

## はじめに

- 3Dプリンタをまだ持っていない方へ  
  このプロジェクトは、ある程度の3Dプリンタの知識や運用ノウハウを前提としています。Fraxinus 00tw の部品を印刷し、組み立て、調整し、保守していくことも考えると、3Dプリンタをまだ持っていない場合は、まず1台導入してから進めることをおすすめします。
- 初めて3Dプリンタを自作する方へ  
  初めての自作3Dプリンタとして Fraxinus 00tw に挑戦することは可能ですが、製作にはメカ、エレキ、ソフトウェアにまたがる幅広い知識やノウハウが必要になります。現在は AI を活用して問題解決を進めることもできますが、最終的な判断や安全確認は自分で行ってください。不明点があれば、Discord で相談しながら少しずつ進めていくのがおすすめです。

## ビルドを始めるには

- BOM は [BOM.md](BOM.md) を参照してください。
- 3Dプリント用の部品は `3MFs/` にあります。
  - 一括ダウンロード： [3MFs (download-directory.github.io)](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FFraxinus-3D%2FFraxinus-00tw%2Ftree%2Fmain%2F3MFs)
  - ファイル名やディレクトリ名の見方は [3MFs/README.md](3MFs/README.md) を参照してください。
- パネル加工用のデータは `DXFs/` にあります。
  - 一括ダウンロード： [DXFs (download-directory.github.io)](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FFraxinus-3D%2FFraxinus-00tw%2Ftree%2Fmain%2FDXFs)
  - パネルデータの概要とクレジットは [DXFs/README.md](DXFs/README.md) を参照してください。
- スライサー向けの一式データは `PrintSets/` にあります。
  - 一括ダウンロード： [PrintSets (download-directory.github.io)](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FFraxinus-3D%2FFraxinus-00tw%2Ftree%2Fmain%2FPrintSets)
- 組立マニュアルは `Manuals/` にあります。
  - 内容の概要と利用条件は [Manuals/README.md](Manuals/README.md) を参照してください。
- 変更履歴は [CHANGELOG.md](CHANGELOG.md) を参照してください。
- 組み立てや選定について不明点がある場合は、Fraxinus Discord で相談してください。

## リポジトリ内のデータ

- `3MFs/Bed` にはベッド関連の部品があります。
- `3MFs/Frames` にはフレームやパネル関連の部品があります。
- `3MFs/PrintHead` にはプリントヘッド関連の部品があります。
- `3MFs/Extruder_RearPanel` にはエクストルーダー周辺とリアパネル関連の部品があります。
- `3MFs/PanelControl` には操作パネル関連の部品があります。
- `3MFs/Electronics_FilamentRouting` には配線やフィラメントルーティング関連の部品があります。
- `3MFs/XCarriage_ZCarriage_XYGantry` にはキャリッジやガントリー関連の部品があります。
- `PrintSets/Printed Parts for Bambu Studio.3mf` と `PrintSets/Printed Parts for OrcaSlicer - Colorized.3mf` には、印刷用セットがまとまっています。

## 構成の見方

- Fraxinus 00tw は単一の本体構成です。
- ただし、用途や好みに応じて一部の部品に選択肢があります。
- 主な選択肢は以下のとおりです。
  - ベッド: `normal bed` / `heated bed`
  - エクストルーダー周辺: `HGX-Lite` / `sherpa mini`
  - フット: `corn` / `pillar`
  - 操作パネル: `DPDT SW` / `PWM volume`
  - プリントヘッド: `normal` / `IR sensor`
- どの組み合わせを採用するか迷う場合は、Discord で相談してください。

## License

このリポジトリには複数のライセンスが適用されています。  
このプロジェクトは、許可のない組み立てキット化や販売を認めていません。  
特に、CC BY-NC-SA 4.0 で公開されているドキュメント、画像、BOM、説明資料を商用キットの作成、販売、宣伝、サポートに利用することはできません。

### 設計データとスクリプト

設計データ、スクリプト、その他の設計関連データは、[GPLv3](LICENSE.md#GPLv3) ライセンスで公開しています。

### ドキュメントと画像

ドキュメント、画像、BOM、その他のドキュメント関連データは、[CC BY-NC-SA 4.0](LICENSE.md#CC-BY-NC-SA) ライセンスで公開しています。

## コントリビューション

Issue や Pull Request を作成する前に、まずは Discord で相談してください。  
詳しくは [CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。

## 免責

本プロジェクトが公開するデータの使用は使用者の自己責任とし、使用によって生じた問題について、著作者やプロジェクト運営者はいかなる保証・責任も負いません。  
詳細は [LICENSE.md](LICENSE.md) を参照ください。
