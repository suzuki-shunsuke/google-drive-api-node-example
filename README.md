# Google Drive連携

Node.jsでGoogle Driveにファイルアップロードするサンプルコード

## サンプルの動かし方

### 環境

* Node.js 6.7.0

### セットアップ

Google Developer Consoleでプロジェクトを作成し、プロジェクトにおいて
Google Drive APIを有効化する必要があります。
また、APIキーを生成し、ダウンロードし、プロジェクト直下に `client_secret.json` というファイル名でおいてください。

```
$ npm i
```

### 実行

```
$ node upload-file.js  # ファイルをアップロード
```
