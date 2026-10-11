# SignerCheck(電子署名の検証)

PDF の電子署名について、署名者の氏名・署名日時・証明書の種類・改ざんの有無を一覧表示するアプリです。
Adobe Acrobat は不要で、Mac と Windows で動きます。検証は手元のパソコンの中だけで行い、PDF を外部に送信しません。

## ダウンロード

[最新版のダウンロードページ](https://github.com/no9osaka/SignerCheck-Releases/releases/latest)から、お使いのパソコンに合うファイルを選んでください。

| パソコン | インストーラー | アンインストーラー |
| --- | --- | --- |
| Mac(macOS 14 以降) | `SignerCheck-0.1.pkg` | `SignerCheck-Uninstaller-0.1.pkg` |
| Windows 10 / 11(64ビット) | `SignerCheckApp-Setup-0.1.exe` | `SignerCheckApp-Uninstaller-0.1.exe` |

## インストール

### Mac

`SignerCheck-0.1.pkg` をダブルクリックし、画面の案内に従ってください。「アプリケーション」フォルダに SignerCheck が入ります。

このインストーラーには Apple の公証(開発元の確認)が付いていないため、最初に開くときに警告が表示されます。

- macOS 15 以降: 警告を「完了」で閉じ、「システム設定」→「プライバシーとセキュリティ」の下の方にある「このまま開く」をクリックします。
- macOS 14: pkg を control キーを押しながらクリック(右クリック)し、「開く」を選びます。

### Windows

`SignerCheckApp-Setup-0.1.exe` をダブルクリックし、画面の案内に従ってください。スタートメニューに SignerCheck が登録されます。

このインストーラーにはコード署名が付いていないため、「Windows によって PC が保護されました」と表示されます。「詳細情報」→「実行」で進めます。

## 使い方

1. SignerCheck を起動する。
2. 検証したい PDF をウィンドウにドロップする(複数まとめて可)。
3. 検証結果が表示される。テキストでの保存と印刷ができます。

## アンインストール

- Mac: `SignerCheck-Uninstaller-0.1.pkg` をダブルクリックします。
- Windows: 「設定」→「アプリ」から SignerCheck を削除するか、`SignerCheckApp-Uninstaller-0.1.exe` をダブルクリックします。

## ご注意

検証結果は参考情報です。内容の正確さを保証するものではなく、利用によって生じた損害について作者は責任を負いません。
