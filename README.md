# docker-react-yarn-typescript
## 概要
- `typescript`を使用して`yarn`で`react`を起動する`dockerfile`と手順を記したリポジトリ。
- 詳細な使用方法は、以下のQiitaか個人ブログを参照。
	1. [【環境構築】DockerでReactをyarnを使用して作成&起動する方法（typescript編）](https://qiita.com/takuma-1234/items/4dfb947ba02d2bdc3ae8)
	2. [【環境構築】DockerでReactをyarnを使用して作成&起動する方法（typescript編）](https://takuma-tech.com/2023/07/13/592/)
    
### Docker起動コマンド
```bash:
$docker-compose up -d --build
```
### react起動までの基本手順コマンド
- `vscode`でコンテナ内部に入る。
- `vscode`でターミナルを起動し作業ディレクトリに移動する。
```bash:
$cd ../react_yarn_typescript_workdir/
```
- `react`アプリの雛形を作成
```bash:
$yarn create react-app react_yarn_typescript
```
- 作成されたディレクトリへ移動
```bash:
$cd react_yarn_typescript/
```
- `react`を起動する。
```bash:
$yarn start
```
#### 参考資料
