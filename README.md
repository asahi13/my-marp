# Overview
marp cliを利用してプレゼン資料作成するリポジトリ

# install 
## 環境 
- windows10 
- nodejs v14.16.1
- yarn 1.22.5
- VSCode 1.69.2

## marp-cli install 
```bash
yarn global add @marp-team/marp-cli
```
## vscode install 
1. vscodeExternal追加 `marp-team.marp-vscode`
2. vscode設定の`Marp Themes`で`./marp-themes/mystyle.css`を設定

# usage
```bash
# html形式で出力
yarn build
# PDF形式で出力
yarn build_pdf
```
# structure 
```bash
contents      # プレゼンコンテンツ
┗img          # プレゼンコンテンツ用の画像ファイル
dest          # プレゼン資料出力先
draws         # 画像作成用のワークスペース(drawio用)
marp-themes   #marp用のスタイルシート
```

# 参考
- [本家Marp](https://marp.app/)
- [Marpを Azure Static Web Appsサンプル](https://github.com/SakaITa/MarpToAzureStaticWebAppsSample)
- [vscode-remote-try-node](https://github.com/Microsoft/vscode-remote-try-node)