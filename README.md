# React サンプルコンポーネント

[デジタル庁デザインシステム](https://design.digital.go.jp/) のコンポーネントの一部をReact / Tailwind CSSベースで実装したサンプル集です。

[Storybook](https://digital-go-jp.github.io/design-system-example-components/)で最新版を公開しています。

## 未実装コンポーネント

このリポジトリでは全てのコンポーネントは実装していません。  
（定期的にサンプルは追加予定です。）  
未実装のコンポーネントについてはスクラッチで書かずに、ヘッドレスUIライブラリの利用を推奨します。

スクラッチで書く必要がある場合は、[ARIA Authoring Practices Guide (APG)](https://www.w3.org/WAI/ARIA/apg/)の[Patterns](https://www.w3.org/WAI/ARIA/apg/patterns/)を参考にして実装を進める事を推奨します。

## サンプルコード

### 動作確認

以下のコマンドでStorybookを実行してください。

```sh
npm install
npm run storybook
```

### スタイリング

- [Tailwind CSS](https://www.npmjs.com/package/tailwindcss)
- [@digital-go-jp/tailwind-theme-plugin](https://www.npmjs.com/package/@digital-go-jp/tailwind-theme-plugin)

[@digital-go-jp/tailwind-theme-plugin](https://www.npmjs.com/package/@digital-go-jp/tailwind-theme-plugin) は、デジタル庁デザインシステムのデザイントークンをベースにしたTailwind CSSのプラグインです。

プラグインで定義されるトークン一覧は、[トークン一覧](https://github.com/digital-go-jp/design-system-example-components/tree/main/src/tokens) をご確認ください。

プロジェクト固有のトークン等については `tailwind.config.js` の extend で拡張してください。

### 注意事項

- サンプルコードは Google Chrome / Microsoft Edge / Safari / Firefox の最新版で動作を確認しています。
- サンプルコードはプロジェクトの特性に合わせて自由に拡張してください。

## Issues, Pull Requests

ご興味を持って頂きありがとうございます。  
リリース直後のため、現在体制がまだ整っておりません。  
そのため、何かお気づきの点やご要望がございましたら、まずはIssueの作成をお願いします。PRはそのIssueでの議論が終わった後に作成してください。  
また、現時点ではコンポーネントそのものに関するIssueのみを受け付けておりますので、予めご了承ください。

## 求人情報

デジタル庁デザインシステムのチームメンバーを募集しています。行政のデジタル環境を支える基盤づくりに、あなたのスキルや経験を活かしてみませんか？　求人ページからご応募ください。

- [プロダクトデザイナ ー（デザインシステム） - デジタル庁](https://herp.careers/v1/digitalsaiyo/IjQ4ovK9BFPl)
