# Connect Line

**[English](README.en.md)**

2点間を結ぶ直線メッシュ

## Install

### OpenUPM

See [OpenUPM page](https://openupm.com/packages/net.narazaka.unity.connect-line/)

### VCC用インストーラーunitypackageによる方法（おすすめ）

https://github.com/Narazaka/ConnectLine/releases/latest から `net.narazaka.unity.connect-line-installer.zip` をダウンロードして解凍し、対象のプロジェクトにインポートする。

### VCCによる方法

1. https://vpm.narazaka.net/ から「Add to VCC」ボタンを押してリポジトリをVCCにインストールします。
2. VCCでSettings→Packages→Installed Repositoriesの一覧中で「Narazaka VPM Listing」にチェックが付いていることを確認します。
3. アバタープロジェクトの「Manage Project」から「Connect Line」をインストールします。

## Usage

1. UnityConstraintまたはVRCConstraintのお好みの方を選び、LineStart prefabを配置します。
2. LineStartとLineEndを好きな位置に追従させます。（Position ConstraintやMA Bone Proxyで）

## License

[Zlib License](LICENSE.txt)
