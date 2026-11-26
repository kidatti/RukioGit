# RukioGit

Rukio Git は Git / GitHub のデスクトップクライアントです。このリポジトリはバイナリ配布専用です。

## ダウンロード

配布ファイルは [Releases](https://github.com/kidatti/RukioGit/releases) の Assets からダウンロードしてください。

| 環境 | ファイル |
| --- | --- |
| macOS 13 以降 / Apple Silicon | `aarch64.dmg` |
| macOS 13 以降 / Intel | `x64.dmg` |
| Windows / x64 | `x64-setup.exe` |
| Linux / x64 | `amd64.deb` または `amd64.AppImage` |

Git を別途インストールしてください。Linux でサインイン情報を保存するには Secret Service（GNOME Keyring / KWallet など）が必要です。各リリースの説明で対応環境を確認してください。

macOS 版は **v0.1.4 以降、Developer ID 署名・Apple 公証済み**です。DMG を開き、`Rukio Git.app` を「アプリケーション」へコピーして起動してください。

v0.1.2 以前で「壊れている」と表示される場合は、[最新リリース](https://github.com/kidatti/RukioGit/releases/latest) の DMG をダウンロードし、アプリを置き換えてください。M4 Mac は Apple Silicon 向けの `aarch64.dmg` を選びます。

`SHA256SUMS.txt` に各ファイルの SHA-256 を掲載します。

GitHub が自動表示する「Source code」は配布案内のアーカイブであり、アプリのソースコードは含みません。

## 不具合・お問い合わせ

不具合の報告やご要望は [Issues](https://github.com/kidatti/RukioGit/issues) にお寄せください。
不具合の報告には、利用バージョン、動作環境、再現手順を記載してください。
個人情報や認証情報は記載しないでください。
