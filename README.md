# novel_proofreader

VSCode と textlint とかで小説の校正するやつ

## 使い方

1. 以下のソフトウェアをあらかじめインストールておきします。
   - [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
     - [textlint の拡張機能](https://marketplace.visualstudio.com/items?itemName=taichi.vscode-textlint)
   - [Node.js の LTS 版](https://nodejs.org/ja/)
2. このリポジトリを[ダウンロード](https://github.com/chisamikan/novel_proofreader/archive/refs/heads/main.zip)して解凍するか、Git が使える人はこのリポジトリをクローンした後、VSCode の『フォルダーを開く』から開いてください。
3. VSCode のターミナルを開き、`npm i`します。
4. file.md に小説を書きます。
5. VSCode の問題タブに校正すべき箇所が表示されます。

## 自動修正

`npm run fix`である程度自動修正してくれます。

## 整形について

作者が最終的に InDesign で編集する都合上、Prettier のマークダウン整形がウザったいので.prettierignore で整形しない設定にしています。  
マークダウンと添い遂げたい人は.prettierignore を削除してください。

## License

MIT © 千紗みかん
