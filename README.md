# 株式会社Yoriyoi — ブランド & Web

**人生と社会の選択肢を増やす会社。**
一緒につくる人がいると、世界はもっと面白くなる。

株式会社Yoriyoi のブランド資料と Web 制作物のリポジトリです。
コーポレートサイト、名刺ハブサイト、物理名刺、それらの設計プロセス（HCD）をまとめて管理しています。

---

## 📁 構成

```
.
├── brand/                      ブランドの一次資料
│   ├── message.md              ★会社の Mission / Vision / 事業 / VEN（最優先の一次資料）
│   └── design-system.md        ブランドデザインシステム v0.2（思想・トーン・実装トークン）
│
├── hcd/
│   └── hcd-process.md          HCD進行ドキュメント（利用状況→要求→設計→評価）
│
├── wireframes/                 ワイヤーフレーム v0.2（構造・情報設計の確定用）
│   ├── index.html              目次
│   ├── corporate.html          ① コーポレートサイト
│   ├── card-hub.html           ② 名刺 → 名刺ハブサイト
│   └── wf.css                  共通スタイル
│
├── hub-site/
│   └── index.html              名刺ハブサイト 実装（HTML/CSS 一枚完結）
│
└── assets/
│   ├── logo/                   ロゴ各種（svg / png）
│   └── patterns/               地紋素材（七宝ほか）
```

---

## 🧭 どこから読む？

| 知りたいこと | 見るファイル |
|---|---|
| 会社が何をする会社か | [`brand/message.md`](brand/message.md) |
| 色・書体・余白などの実装ルール | [`brand/design-system.md`](brand/design-system.md) Part II（§24〜26） |
| なぜこの設計にしたのか | [`hcd/hcd-process.md`](hcd/hcd-process.md) |
| 画面の構造・情報の並び | [`wireframes/index.html`](wireframes/index.html) |
| 決定の経緯・背景 | [`logs/`](logs/) |

> ⚠️ **2026-07-25 に事業の方向転換がありました。**
> `brand/design-system.md` の Part I には転換前の記述（AIマッチング前提）が一部残っています。
> 内容が食い違う場合は **`brand/message.md` を優先**してください。詳細は design-system.md 冒頭の有効範囲表を参照。

---

## 🖥 ローカルでの確認方法

ビルド不要です。HTML をブラウザで開くだけで表示されます。

```bash
open hub-site/index.html
```

```bash
open wireframes/index.html
```

ロゴや地紋を正しく表示するため、**リポジトリのフォルダ構成を保ったまま**開いてください
（`hub-site/index.html` は `../assets/` を相対参照しています）。

---

## 🤝 編集への参加

- 気軽に Fork → 修正 → Pull Request で提案してください。
- デザインの方針は [`brand/design-system.md`](brand/design-system.md) に準拠します。
- 新しい画面や機能を作るときは、design-system.md §21「Design System Decision Checklist」で確認を。

---

## 🏢 ブランド

- **社名**：株式会社Yoriyoi（よりよい）
- **由来**：「より良い」＋糸を撚り合わせる「縒る」＋人が集まる「寄り合い」
- **中核事業**：AI社会実装支援（AI・DX導入から人材育成・自走化まで伴走）
- **将来構想**：Virtual Expert Network（VEN）— 専門家がプロジェクト単位でつながるネットワーク
- **ドメイン**：`yoriyoi-inc.co.jp`
