# Azure Funtions Sample App

## Installation
```sh
# グローバルインストール
npm install -g azure-functions-core-tools@4 --unsafe-perm true

# バージョン確認
func --version
```

## Deploy
```sh
npm install
npm run build
func azure functionapp publish func-api-xxxxxxx --typescript --force
```