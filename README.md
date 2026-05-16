# EF-Palette 共有選手データ

EF-Palette アプリ用の選手データを配布するリポジトリ。

## 📥 取り込み方

1. EF-Palette アプリを開く
2. 設定 → 「他ユーザーから取り込み」（v1.1.0以降）
3. 下記URLを貼り付けて取得
4. 取り込みたい選手をチェックボックスで選択 → 取り込み

## 📦 シード一覧

| バージョン | 選手数 | URL | 備考 |
|---|---:|---|---|
| sample | 3 | [sample.json](snapshots/sample.json) | 動作確認用ダミー |

## 🔗 直接URL（アプリ取り込み用）

```
https://raw.githubusercontent.com/<account>/ef-palette-shared-data/main/snapshots/sample.json
```

## ⚠️ 注意

- このシードに含まれるデータは **基本情報・初期能力値のみ** です
- チケット拡張で設定したポジ・スキルは含まれません
- 取り込み時、既存データを上書きするか・スキップするか選べます

## 🛡️ 免責

本リポジトリは EF-Palette アプリのための非公式データ集です。
EF-Palette 自体が eFootball (KONAMI) のファンメイドツールであり、
公式データではありません。

選手データは利用者が独自に登録・確認したものを共有しています。
正確性は保証されません。
