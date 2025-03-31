# TypeScript Vanilla Template

このテンプレートはTypeScriptを使用したVanillaJSプロジェクトのための厳格なコード品質管理環境を提供します。Vite、ESLint、Prettierを組み合わせて、高品質で一貫性のあるコードベースを維持するための基盤を整えています。

## 特徴

- 📦 **Vite** - 高速な開発環境と最適化されたビルドを提供
- 🔍 **TypeScript** - 静的型付けによるコード品質向上
- 🧹 **ESLint v9** - 最新の設定形式を使用した厳格なコード品質ルールによるリンティング
- ✨ **Prettier** - 一貫したコードフォーマット
- 🛠 **VSCode統合** - エディタ内での自動フォーマットとリント

## セットアップ

```bash
# 依存関係のインストール
npm install

# 開発サーバーの起動
npm run dev

# 本番用ビルド
npm run build
```

## コード品質ツール

このテンプレートには以下のコード品質ツールが組み込まれています：

### リンティング

```bash
# コードのリント
npm run lint

# リントエラーの自動修正
npm run lint:fix
```

### フォーマット

```bash
# コードの自動フォーマット
npm run format
```

### 型チェック

```bash
# TypeScriptの型チェック
npm run check-types
```

## ESLintの設定

このテンプレートでは、ESLint v9の新しい設定形式(`eslint.config.js`)を使用し、以下のような厳格なルールを採用しています：

- TypeScriptの厳格な型チェック
- 明示的な関数の戻り値型の宣言
- anyの使用禁止
- 未使用変数のエラー検出
- 厳格なブール式の評価
- その他多数の品質向上ルール

## Prettierの設定

コードスタイルの一貫性を保つために、以下のPrettier設定を採用しています：

- 行末のセミコロン
- シングルクォート
- 最大行長100文字
- インデントは2スペース
- その他標準的なフォーマットルール

## 推奨される開発環境

- VSCode
- ESLint拡張機能
- Prettier拡張機能 