# Imagination Workspace (IW)

Mac向けのネイティブSwiftUIワークスペースです。画面の部品を選び、MCP対応の会話ホストから編集できます。作業は自動保存され、保存した案の比較・復元、Undo/Redoを利用できます。

## 必要環境

Apple Silicon、macOS 26.0以降、XcodeまたはCommand Line Tools、uvが必要です。表示コード生成の検証環境はSwift 6.3 / macOS 26.4 SDKです。

## 導入

1. [GitHub Releases](https://github.com/hikaru777/imagination-workspace-releases/releases)からZIPをダウンロードして展開します。
2. app・scripts・mcp-adapter・fixturesを含むフォルダ全体を `~/Applications/IW` に配置します。
3. `ImaginationWorkspace.app` を起動し、アプリ内の「その他」→「外部会話(MCP)」で設定値をコピーして会話ホストへ登録します。

この配布版はDeveloper ID署名・Apple公証済みです。

[最新版ZIPをダウンロード](https://github.com/hikaru777/imagination-workspace-releases/releases/download/v1.0.0/IW-Workspace-V1-Final-macOS-arm64-SIGNED-NOTARIZED.zip)

SHA-256: `557ca401938339454ac09098c17c69ac9c578d6bcfd5c7212099f36709adb97f`
