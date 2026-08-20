# 動画台本連動 イラスト＆背景ビジュアル制作ガイド

本ドキュメントは、BGM・環境音・ポモドーロ動画の台本（ポモドーロ25分＋5分休憩、時間の経過、雰囲気の変化）に完璧にマッチしたイラスト・背景ビジュアルを作成するためのガイドラインです。

---

## 1. 台本連動イラスト制作の4ステップ

```text
[Step 1: 構図設計] ──► [Step 2: キービジュアル生成] ──► [Step 3: 台本連動の差分作成] ──► [Step 4: 動画化・演出]
 文字/タイマーの       スタイル・キャラクター一貫性        集中モード vs 休憩モード         雨・炎・湯気の微アニメ
 ネガティブスペース確保    (Midjourney / FLUX)           の視覚的差分イラスト            (DaVinci / AI Video)
```

---

## 2. 具体的な作成手順

### Step 1: 「ネガティブスペース（文字・タイマー余白）」を考慮した構図設計
サムネイルの巨大文字（`雨音×ピアノ 2時間`）や画面上のタイマー（`25:00`）を配置するため、暗くシンプルな余白（ネガティブスペース）を意図的に作成します。

* **プロンプト指定のコツ**：
  `wide camera angle, spacious dark background on the left for UI text overlay, cinematic lighting`

### Step 2: 参照画像機能（Style / Character Reference）による一貫性保持
ポモドーロ動画では「同じ部屋」「同じ人物」が時間経過とともに変化していく演出が強固なフックになります。

* **Midjourney / FLUX の活用**：
  * **スタイル固定（`--sref`）**：画風・配色・質感を100%統一。
  * **キャラクター/空間固定（`--cref`）**：同じ部屋・デスク・人物を保ったまま、ポーズや照明のみを変更。

### Step 3: 台本のフェーズ（集中 vs 休憩）に応じた差分イラスト作成
ポモドーロのセクション（集中25分 / 休憩5分）に合わせて背景イラストに小さな変化をつけ、離脱を防ぎます。

| 台本フェーズ | イラストの視覚的変化 | プロンプトでの変化付け |
|---|---|---|
| **第1セット（集中）** | 窓の外はしとしと雨。デスクの電球が灯る。集中して作業する人物。 | `working intently on laptop, rainy window, focused mood` |
| **5分休憩** | コーヒーカップから温かい湯気。人物が背伸びをする/窓の外を眺める。 | `taking a coffee break, steam rising from mug, relaxing posture` |
| **第2セット（集中）** | 窓の外の雨足が少し強まる / 夜が深まり月明かりが差し込む。 | `deep night, moonlight streaming through window, heavy rain` |

### Step 4: DaVinci Resolve による「シネマグラフ・動的演出」
静止画のままの投稿（重複コンテンツリスク）を避けるため、DaVinci Resolve (Fusion) 等で微細な動きを付与します。
* **カメラワーク**：じわーっと寄る・引くパン＆ズーム。
* **パーテイクル効果**：雨、降り注ぐ光、炎の揺らめき、コーヒーの湯気。

---

## 3. 画像生成プロンプト構造テンプレート

```text
[全体のスタイル・質感] + [主要被写体・空間] + [台本の状態（集中/休憩）] + [光・天候] + [構図・余白指定]
```

### プロンプト実例（深夜の雨×ポモドーロ）
* **【集中フェーズ用】**
  > `Anime aesthetic illustration, a cozy dark study room, a female medical student working intently at a wooden desk with a laptop and textbooks, heavy rain outside the window, soft warm desk lamp light, dark space on top-left for text overlay, highly detailed, 8k resolution, cinematic composition --ar 16:9`
* **【休憩フェーズ用】**
  > `[参照画像URL] same room and girl, now leaning back taking a short break, holding a warm mug with gentle steam rising, peaceful expression, soft ambient lighting --ar 16:9`
