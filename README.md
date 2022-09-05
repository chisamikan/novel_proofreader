# novel_proofreader

VSCode と textlint とかで小説の校正するやつ

## 使い方

1. 以下のソフトウェアをあらかじめインストールておきします。
   - [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
     - [textlint の拡張機能](https://marketplace.visualstudio.com/items?itemName=taichi.vscode-textlint)
   - [Node.js の LTS 版](https://nodejs.org/ja/)
2. VSCode のターミナルを開き、`npm i`します。
3. file.md に小説を書きます。
4. VSCode の問題タブに校正すべき箇所が表示されます。

## 整形について

作者が最終的に InDesign で編集する都合上、Prettier のマークダウン整形がウザったいので.prettierignore で整形しない設定にしています。  
マークダウンと添い遂げたい人は.prettierignore を削除してください。

## License

MIT © Chisamikan
