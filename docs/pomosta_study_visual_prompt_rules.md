# 🏛️ ポモスタ専用：書斎・図書館 特化型 画像生成プロンプト＆空間演出完全規約 v3.0
（オトノバ君 RAGナレッジ / Visual-Prompt-Master ポモスタ移植・刷新版）

本ドキュメントは、YouTubeチャンネル「ポモスタ（Pomodoro Study）」において、30〜50代の知的労働者・学習者を惹きつける**「Quiet Luxury（静かな上質）× 大人の集中力UP」**を体現した最高品質の背景ビジュアル（NanoBanana Pro / Imagen 3用）を量産・再現するための完全なプロンプト設計規約です。

従来の「カフェ内装（エスプレッソマシン・レジ等）」から、**「ハイエンド書斎（Private Study）」および「学習用図書館（Modern & Academic Library）」**へと必須インフラ・構図ロジックを全面刷新し、今後開設される他チャンネル（海外向け等）と干渉しない独立モジュールとして定義します。

---

## 📖 第1章：ポモスタ・コアアイデンティティ ＆ 空間設計原則

### 1.1 ブランド・コア・コンセプト
* **コア・コンセプト**: **"Quiet Luxury"（静かな上質）**
* **空間の約束**: 「高所得者・エグゼクティブが暮らす広々とした邸宅の専用書斎」または「静寂に包まれた国内外の最高峰の学習図書館」。
* **映像・出力基準**: 1080p / 24fps（フィルムグレイン20%耐性設計）。
* **非注視UXへの配慮**: 視聴者の75%以上が別タブで作業するため、画面に戻った瞬間に「心地よい開放感と上質な静けさ」を感じる視覚刺激に限定する。

### 1.2 構図の黄金比率（自然景観 60〜70% ドミナント構図）
40本以上の動画データおよびCTR実測値に基づき、ポモスタでは以下の比率を厳守する。

* **Focus（集中シーン）**: **【自然景観 60〜70% × 室内ワークスペース 30〜40%】**
  * 床から天井までの巨大な全面ガラス窓（パノラマ窓）越しに、息を呑む自然絶景（海、森、湖、山、雨、紅葉など）が画面の60〜70%を占める。
  * 手前30〜40%に、無垢材やウォールナットのハイエンドデスク、作業アイテム（PC/本）、湯気なしカップ、猫置物を洗練された密度で配置。
  * **部屋全体の引き絵にする必要はない**（※暖炉がある場合を除く）。窓とデスクの親密な距離感を重視する。
* **Break（休憩シーン）**: **【圧倒的景観 80〜90% ドミナント構図】**
  * Focusよりもさらに外の美しさに注力し、疲れた脳を瞬時にリフレッシュする3大パターン（後述）を展開。

---

## 🎨 第2章：空間スタイル別キーワード集（書斎 ＆ 図書館 特化）

カフェ内装スタイル（v2.7）から、書斎および学習図書館に最適な要素を厳選・再定義したキーワード辞書です。プロンプト作成時、各スタイルから**最低5〜7個の具体的オブジェクト・テクスチャ**をプロンプト本文（`[FOREGROUND]`, `[MIDGROUND]`, `[BACKGROUND]`）に織り交ぜて視覚密度を高めてください。

### 2.1 書斎（Private Study）スタイル

#### ① モダン・ミニマル書斎（Executive Modern Minimal Study）
* **特徴**: 直線的な幾何学美、モノトーン＋上質な木目、洗練された秩序。
* **素材**: ダークウォールナット材, 磨かれた真鍮, ブラックアルミニウム, スモークガラス, トラバーチン石材, シームレスなモルタル床, 高級レザー.
* **家具・インフラ**: フローティングデスク, アーロンチェア/エルゴノミックチェア, 埋め込み式コーブ間接照明, 直線的なLEDタスクライト, 整理された薄型本棚.
* **小物**: スタイリッシュなMacBook（白画面）, ガラスのペーパーウェイト, ミニマルな一輪挿し, 黒革の手帳, 真鍮のペン.

#### ② 北欧ナチュラル書斎（Scandinavian Hygge Study）
* **特徴**: 白木と自然光、温かみのあるファブリック、心地よい静寂（Hygge）。
* **素材**: 明るいバーチ無垢材, ホワイトパイン, リネン, ウール, 漆喰壁, 素朴なマット陶器.
* **家具・インフラ**: Yチェアまたはハンス・ウェグナー風木製チェア, 白木の広々とした窓際デスク, 大きなガラス窓, 柔らかな生成り色のブラインド.
* **小物**: 陶器のマグカップ, 開かれた厚手のノート, 木製万年筆, 控えめな観葉植物（フィカス）, 琥珀色の木製置物.

#### ③ インダストリアル・ロフト書斎（Industrial Loft Study）
* **特徴**: 天井の高い倉庫・ロフトを改装した、知性的で無骨な隠れ家書斎。
* **素材**: 赤レンガ壁, むき出しの黒アイアン梁, 古材（足場板）, 経年変化したオイルレザー, 亜鉛メッキ金具.
* **家具・インフラ**: アイアンフレームの大型木製デスク, ヴィンテージレザークラブチェア, エジソン電球アームランプ, 工業用スチールガラス窓.
* **小物**: 重厚な卓上時計, 真鍮のルーペ, アンティーク地球儀, 無骨な真鍮トレイ, 革表紙のスケッチブック.

#### ④ ヴィンテージ・クラシック書斎（English Country & Heritage Study）
* **特徴**: 英国マナーハウスや伝統的書斎の風格。重厚な木製家具と知的な気品。
* **素材**: 濃色オーク材, マホガニー, 深緑のベルベット, ボタン留めチェスターフィールドソファ, ペルシャ絨毯.
* **家具・インフラ**: 重厚な木製エグゼクティブデスク, 天井まで届く格子本棚（革装丁本がぎっしり）, 真鍮のバンカーズランプ, 石造りマントルピース.
* **小物**: 万年筆とインク壺, 真鍮の砂時計, 天体望遠鏡, 革張りの書類トレイ, 陶器のヴィンテージカップ.

#### ⑤ 和モダン・禅書斎（Wa-Modern Zen Study）
* **特徴**: 陰影礼賛、引き算の美学、自然素材と静謐な「間（Ma）」。
* **素材**: 檜（ヒノキ）, 杉無垢材, 和紙, 土壁, 墨色の玄昌石, 格子木組み.
* **家具・インフラ**: 低めの無垢一枚板デスク, 格子戸付きのパノラマ大窓, 和紙シェードの間接照明, 坪庭を望む縁側風ステップ.
* **小物**: 陶芸作家の湯呑み/マグ, 和紙ノート, 硯と筆, 幾何学的な組子細工のオブジェ（※安易な盆栽は禁止）.

#### ⑥ サンルーム・ボタニカル書斎（Conservatory Botanical Study）
* **特徴**: ガラス張りの温室・サンルームに設えられた、光と緑に包まれるリゾート書斎。
* **素材**: 全面ガラス構造, 細身のブラックアイアンフレーム, テラコッタタイル, ラタン, リネン.
* **家具・インフラ**: ガラスに面した明るいオークデスク, ラタンチェア, ハンギングプラント, 天窓からの均一なディフューズ光.
* **小物**: ボタニカルアートのスケッチブック, ガラスの水差し, 銅製ジョウロのミニチュア, クリアハーブティーの耐熱グラス.

---

### 2.2 学習用図書館（Library / Study Hall）スタイル

#### ① 国内現代建築モダン図書館（Japanese Contemporary Architectural Library）
* **特徴**: 光あふれる吹き抜け、美しい木格子、曲面構造、現代的な知の殿堂（武蔵野プレイス、金沢海みらい、角川武蔵野ミュージアム等の洗練美）。
* **素材**: 明るいオーク材, コンクリート打ちっぱなし, 規則的な丸窓/格子スクリーン, 高透過ペアガラス, 吸音ファブリック.
* **家具・インフラ**: 窓に向かって並ぶパーソナル学習ブースデスク, ミニマルなデザイナーズスタディチェア, 埋め込み式スリットLED, 整然と並ぶ書架.
* **小物**: 静かに置かれたノートPC（白画面）, 専門書数冊, クリアボトル, ステンレス製ペンケース.

#### ② 欧米アカデミック図書館（Oxbridge & Ivy League Academic Library）
* **特徴**: オックスフォード、ケンブリッジ、トリニティカレッジを彷彿とさせる壮麗な学術空間。
* **素材**: 重厚なダークオーク, 彫刻石材, アーチ型ボールト天井, 錬鉄製の手すり, モザイク寄木張り床.
* **家具・インフラ**: 長大な無垢材スタディテーブル, エメラルドグリーンのガラスシェードを持つ真鍮バンカーズランプ, 2階層吹き抜けの書架と螺旋階段, 巨大なステンドグラス/アーチ窓.
* **小物**: 積み上げられた厚い学術書・辞書, ノートと万年筆, 真鍮のデスク番号プレート.

#### ③ ダークアカデミア・ゴシック図書館（Dark Academia Gothic Library）
* **特徴**: 知的好奇心とミステリアスな静寂が同居する、古典文学・哲学の研究空間。
* **素材**: 煤けた黒木材, 石積み壁, ステンドグラス, 深紅/深緑のファブリック, 経年変化した真鍮.
* **家具・インフラ**: 個別キャレル（木製仕切りブース）, 高い書架に架かる木製梯子（ラダー）, ほの暗い天井と卓上ランプのドラマチックな明暗（Chiaroscuro）.
* **小物**: 羊皮紙ノート, 古代ギリシャ風のミニマル石膏彫像, 天体儀, 真鍮のペーパーナイフ.

#### ④ 北欧ミニマル公立図書館（Nordic Minimal Public Library）
* **特徴**: ヘルシンキOodi中央図書館を思わせる、波打つ木製天井、光と静けさが調和する市民の学習聖域。
* **素材**: 淡いスプルース材, ホワイトスチール, 巨大な天窓, 柔らかなカーペット.
* **家具・インフラ**: 広大なパノラマ窓に面した学習カウンター, アアルト風のプライウッドチェア, 均一な北欧の自然光.
* **小物**: 白いタブレット（木製スタンド付き）, ミニマルなタンブラー, 整理されたデザイン書籍.

---

## ⚙️ 第3章：必須インフラ ＆ 構図設計ルール

### 3.1 全Focus共通：必須インフラ（Mandatory Study/Library Infra）
プロンプトの `[BACKGROUND]` および `[FOREGROUND]` に必ず以下の要素を組み込むこと。
旧カフェ機材（エスプレッソマシン、レジ等）の混入は**完全禁止**とする。

1. **全面パノラマ大窓 ＆ デスク配置（最重要）**:
   * `massive floor-to-ceiling panoramic glass window overlooking a breathtaking [scenery]` を配置。窓外の絶景が画面の60〜70%を占める。
   * デスクは窓のすぐそばに設置（`sleek premium desk positioned directly against the vast window`）。
2. **高所得者層の広々とした空間性（Quiet Luxury）**:
   * 安っぽいワンルーム感を排除し、天井が高く開放感のあるエグゼクティブ空間として描画（`spacious high-ceiling executive interior with understated luxury`）。
3. **猫モチーフ置物（The Easter Egg Motif）**:
   * **1〜3個の猫モチーフ置物**を室内に配置（後述の `[CAT_LOGIC]` に従い、1つずつ個別に材質・配置場所を記述）。
4. **壁面のアートワーク / ポスター**:
   * 壁面の70%はクリーンな余白を保ちつつ、残りの30%には空間スタイルに完璧に調和したアートを適度に配置（`tastefully framed abstract art or minimalist architectural print matching the room's aesthetic`）。
5. **クリーンな卓上アイテム**:
   * ノートPCまたはタブレット（`pure blank white screen`）、上質な本・ノート、筆記具、陶器またはガラスのカップ。
   * **湯気（Steam）の完全排除**: 温かい飲み物であっても必ず `completely without steam` とし、ネガティブに `steam, smoke, vapor` を含める。

### 3.2 暖炉特例ルール（Fireplace Pull-Back Rule）
暖炉（Fireplace / 薪ストーブ）が登場するテーマ（例：山の別荘書斎、冬の高原書斎）の場合、AIが机の真横や不自然な至近距離に暖炉を生成する事故を防止するため、以下の特例ルールを適用する。

> [!important] 暖炉指定時のカメラ引き構図
> * **カメラ位置**: 通常の寄り気味デスク構図を解除し、**「カメラ位置を後方に引き、部屋全体（暖炉、デスク、窓）の空間関係が美しく描写されるミドル〜ワイドショット」**とする。
> * **プロンプト構文**:
>   `pulled-back wide shot capturing the entire harmonious room layout, stone fireplace with a gentle crackling fire positioned naturally along the adjacent sidewall at a safe distance from the executive desk, establishing elegant depth between the hearth, the study workspace, and the panoramic window.`

### 3.3 図書館指定時の特例ルール（Library Solitude Rule）
テーマが「図書館（Library）」の場合、YouTube視聴者の「自分だけのプライベートな集中空間」という没入感を担保するため、以下のルールを適用する。

> [!important] 図書館指定時の絶対無人化 ＆ 書棚の構造美
> * **人物の完全排除**: 図書館であっても他の利用者や司書は一切描かない（`strictly unoccupied, completely empty study space, no other patrons, peaceful solitary atmosphere`）。
> * **書棚の幾何学的整合性**: 書架の歪みや溶けを防止するため、`architecturally straight bookshelves, pristine linear shelving` をポジティブに付与し、ネガティブに `warped bookshelves, distorted book spines` を追加する。
> * **学習ブースまたは大窓カウンター**: 視聴者が着席している主観視点（POV）を保つ。

---

### 3.4 全Break共通：3大シーン設計（景観美ドミナント）
休憩フェーズ（5分Break）は、Focusシーンと同じ席・アイテムのコピペを**完全厳禁**とし、以下の3パターンからテーマに合わせて厳選・展開する。いずれも**外の美しい景色の描画（80〜90%）**に全力を注ぐ。

```text
┌─────────────────────────────────────────────────────────────────────────┐
│                     全Break共通 3大シーン展開パターン                    │
├─────────────────────────────────────────────────────────────────────────┤
│ パターン①：【室内・窓際最前列からの外景観（Indoor Window-Edge View）】 │
│   └ カメラが後方に下がりすぎず、窓ガラスのフレームと広大な外の絶景が    │
│     主役となる視点。手前に本物の猫が静かに外を眺めている。              │
│                                                                         │
│ パターン②：【完全屋外・テラス席からの外景観（Outdoor Terrace Lounge）】 │
│   └ 室内から完全に外へ出た状態。テラスにリラックスできるプレミアムな    │
│     ラウンジチェアとサイドテーブルが1組あり、そこから絶景を見渡す。     │
│                                                                         │
│ パターン③：【完全屋外・自然景観＆リアル猫（Pure Nature & Real Cat）】   │
│   └ 家具やテラス席すら存在しない、100%外の純粋な自然景観。              │
│     穏やかに佇む本物の猫と、息を呑む大自然のパノラマのみを描写。        │
└─────────────────────────────────────────────────────────────────────────┘
```

#### 各パターンの具体的プロンプト構文

* **パターン①（窓際最前列・室内）**:
  `first-person perspective from the immediate edge of a grand floor-to-ceiling window, the camera positioned close to the glass to showcase the breathtaking outdoor [scenery] filling 80% of the frame, a calm fluffy real cat sitting quietly on the polished windowsill gazing outward, subtle clean window frame, no bulky indoor furniture obstructing the view.`
* **パターン②（屋外テラス席）**:
  `fully outdoor terrace view overlooking the vast and stunning [scenery], an elegant minimalist outdoor lounge chair and a small round side table set neatly on the teak wood terrace deck, a peaceful real cat lounging comfortably, crisp open air and unobstructed natural beauty.`
* **パターン③（完全屋外・純粋景観＆猫）**:
  `breathtaking open-air natural landscape, completely outdoors with no human-made furniture or terrace structures, expansive and crystal-clear panoramic view of [scenery] taking up the entire composition, a serene real cat gracefully resting on a natural rock/grassy knoll, pure restorative connection with nature.`

---

## 🔍 第4章：被写界深度（DOF）と合成感（コラージュ感）解消ルール

### 4.1 なぜ「一律DOF指定」が合成感を生むのか？
プロンプトに `shallow depth of field`（浅い被写界深度）や `heavily blurred background` を明示すると、生成AI（Imagen 3 / NanoBanana Pro）は「手前（机や小物）」と「背景（窓外の景色）」を2つの分離されたレイヤーとしてレンダリングし、**切り抜いて貼り付けたような不自然な境界線（コラージュ感・合成感）**を発生させます。

さらに、ポモスタの最大の強みである**「窓の外の美しい自然景観（60〜70%）」がボケで消失し、CTRと視聴満足度が著しく低下**します。

### 4.2 ポモスタのDOF新基準：ディープフォーカス＆自然光学
* **一律DOF指定の廃止**: プロンプト本文への安易な `shallow depth of field` の挿入を禁止する。
* **標準光学プロンプト**: 手前デスクから窓外の絶景まで破綻なくシャープに描写する以下の構文を標準適用する。
  > `natural photographic depth, crisp optical clarity from the foreground study desk to the distant outdoor horizon, deep focus capturing both rich interior textures and breathtaking panoramic landscape seamlessly, anti-reflective architectural glass, balanced interior and exterior exposure.`
* **ボケが許容される例外**: マグカップや手帳の超近接マクロ撮影（Close-up）タグが指定された場合のみ、局所的に `subtle cinematic depth` を適用する。

---

## 📘 第5章：ポモスタ専用 外部辞書モジュール v3.0

### 1. 🏺 `[AESTHETIC_PREFIX]`（冒頭スタイル構文）
プロンプトの最先頭に必ず展開し、空間の哲学・空気感・解像度を決定づける構文。

* **`Universal Lifestyle`（汎用エグゼクティブ・ライフスタイル）**:
  `(Photorealistic:1.5), (Modernist Architectural Photography:1.3), (Quiet Luxury:1.3), (Sophisticated Lifestyle Magazine Style:1.2), (hyper-detailed micro-textures:1.2), (cinematic dramatic lighting:1.2). Carefully curated space, impeccable composition. Soft interplay of light and shadow, balanced natural lighting providing even illumination.`
* **`Purist Zen`（静謐な建築空間・和モダン書斎向け）**:
  `(Photorealistic:1.5), (Quiet Luxury:1.3), (Sophisticated Lifestyle Magazine Style:1.2), (hyper-detailed micro-textures:1.2), (cinematic dramatic lighting:1.2). Architectural masterpiece photography, purist Japanese modernism interior, minimalist aesthetic rooted in the concept of Ma (negative space). Clean geometric forms. Soft diffused indirect window light casting gentle, subtle shadows. Muted neutral color palette, serene and pristine atmosphere.`
* **`Staged Designer`（洗練されたハイエンド・デザイナー書斎）**:
  `(Photorealistic:1.5), (Quiet Luxury:1.3), (Sophisticated Lifestyle Magazine Style:1.2), (hyper-detailed micro-textures:1.2), (cinematic dramatic lighting:1.2). High-end lifestyle magazine interior editorial, sophisticated staged designer aesthetic, l'harmonie au quotidien. Tasteful arrangement of modern executive furniture and organic elements. Monochromatic palette with warm earth tone accents, highly detailed, sharp focus.`
* **`Academic Solitude`（図書館・学術空間特化・新設）**:
  `(Photorealistic:1.5), (Architectural Digest Interior:1.3), (Quiet Luxury:1.3), (Academic Sanctuary Aesthetic:1.3), (hyper-detailed micro-textures:1.2), (cinematic atmospheric lighting:1.2). Magnificent architectural library interior, noble silence and intellectual clarity, soaring ceilings and majestic bookshelves. Natural daylight streaming through monumental windows, dust motes dancing in warm sunbeams, pristine scholarly atmosphere.`
* **`Curated Clutter & Cozy`（英国風・隠れ家書斎向け）**:
  `(Photorealistic:1.5), (Quiet Luxury:1.3), (Sophisticated Lifestyle Magazine Style:1.2), (High visual density:1.2), (hyper-detailed micro-textures:1.2), (cinematic dramatic lighting:1.2). Lived-in cozy atmosphere, carefully curated intellectual collection, rich tactile details. Warm and inviting environment with layered textures, an eclectic mix of classic literature, brass instruments, and aesthetic decor, avoiding sterile emptiness.`

---

### 2. 🎥 `[CAMERA_&_COMPOSITION]`（カメラ構図 ＆ POV）

#### 🚫 【絶対禁止】真上からの視点（Top-down / Overhead）の除外
* **禁止理由**: 真上からの平面的バードアイは、ポモスタの核である「窓の外の美しい自然景観（60〜70%）」が完全に消滅し、単なる机の上の物撮りになってしまうため**完全使用禁止**とする。
* **許容されるアングル**:
  * `Eye-level`（目線の高さ / 標準）
  * `Slight low-angle`（やや見上げるアングル：天井の高さと大窓のスケールを強調）
  * `High-angle`（斜め上からのハイアングル：デスク上の作業環境と窓外の景色の両方を綺麗に収める ※真上真俯瞰は不可）

#### POV Tags（視点展開ルール）
* **`POV: First-Person Workspace`（標準Focus）**: 窓に向かって着席している作業者の主観視点。手前にデスク天板、奥に広大なガラス窓と絶景。
* **`POV: Window-Edge Solitude`（Break パターン①）**: 窓ガラスのすぐそばからの視点。窓枠と外の絶景が視界の大部分を占める。
* **`POV: Open Terrace Lounge`（Break パターン②）**: 開放的な屋外テラスのラウンジチェアからの視点。
* **`POV: Pure Landscape Observer`（Break パターン③）**: 人工物のない完全な屋外の自然景観視点。

#### 代替カメラ構図タグ（Focus / Break 各2案の必須記述ルール）
マスタープロンプト出力時、各テーマの末尾に必ず**Focus用2案、Break用2案（計4案）**の代替構図タグと日本語解説を記載すること。

---

### 3. 🐈‍⬛ `[CAT_LOGIC]`（猫の振る舞い・配置定義）

#### Focus時：【置物モチーフ（Cat Motif）1〜3個の個別指定】
Focusシーンでは本物の猫ではなく、**「1〜3個の猫モチーフ置物（彫刻・フィギュア）」**を室内に分散配置する。
AIの増殖バグ・融合バグを防ぐため、**必ず1個ずつ個別に「素材（木製、真鍮、陶器等）」「ポーズ」「具体的な配置場所（本棚の上、デスクの端等）」を自然言語で明記する**。

* **記述例（2個指定の場合）**:
  `[CAT_MOTIF]: Two distinct cat figurines placed in separate areas of the room: one small minimalist white ceramic cat curled up sleeping quietly on the corner of the executive desk, and one sleek carved dark walnut cat figurine sitting upright on the middle bookshelf in the background.`

#### Break時：【本物の猫（Real Cat）の登場】
休憩フェーズでは、癒やしの象徴として**本物の猫が1匹**登場する。
* **状態・視線**: 画面に向かってカメラ目線をさせず、窓の外を眺めている（`gazing out at the distant scenery`）か、心地よさそうに目を細めて微睡んでいる（`peacefully dozing`）状態を基本とする。

---

### 4. 🎛️ `[CONTROL_PANEL]`（変数マッピング）
YAMLフロントマター内の設定値をプロンプト本文に反映させるルール。

| 変数名 | 設定値 | プロンプト本文への展開（物理描写） |
| :--- | :--- | :--- |
| **`dof_level`** | **Natural（推奨）** | `natural photographic depth, seamless sharpness across desk and outdoor landscape` |
| | **Deep** | `deep focus throughout, edge-to-edge optical clarity, hyper-detailed background` |
| | **Subtle Close-up** | `gentle cinematic depth, crisp focus on foreground item with softly organic backdrop` |
| **`color_temperature`**| **Warm** | `warm amber interior cove lighting, golden hour glow, cozy tranquil palette` |
| | **Neutral** | `balanced neutral daylight, pristine clear illumination, pure realistic tones` |
| | **Cool** | `crisp cool morning daylight, calm misty tones, refreshing serene atmosphere` |
| **`botanical_density`**| **10%〜30%** | `tastefully curated single potted bonsai or minimalist vase with a green twig on shelf` |
| | **40%〜60%** | `lush indoor potted ficus and elegant trailing plants gracefully framing the window` |

---

### 5. ⚠️ `[OVERRIDE_RULES]`（絶対条件分岐・IF文）

プロンプト出力前にAIが必ずチェック・適用すべき絶対ルール：

1. **IF (Room includes Fireplace):**
   * カメラ構図を強制的に `pulled-back wide shot` に変更し、暖炉とデスクが適切な距離を保った部屋全体のレイアウトを描写する。
2. **IF (Theme = Library):**
   * デスクを「学習ブース（Study carrel）」または「重厚な木製長机」に変更。
   * 背景を「壮麗な本棚・書架」とし、`strictly unoccupied, no people, silent scholarly sanctuary` を強制。
3. **IF (Type = Focus):**
   * 猫は本物を禁止し、必ず「1〜3個の置物モチーフ（個別に材質・場所を分離）」にする。
   * 飲み物は `completely without steam`。
4. **IF (Type = Break):**
   * Focusのデスク・構図の流用を絶対禁止。3大パターン（窓際 / テラス席 / 完全屋外景観）のいずれかに完全に切り替える。
   * 猫は本物のリアル猫（1匹）にする。
5. **IF (Angle = Top-down / Bird's-eye Overhead):**
   * **即時却下・置換**: 真上視点は強制的に `eye-level straight shot` または `elegant high-angle shot showcasing both the desk surface and the expansive panoramic window` に書き換える。
6. **IF (Style = Wa Modern):**
   * ネガティブに `bonsai` を追加（AIが安易に机上にミニ盆栽を生やして和室模型化するのを防止）。

---

### 6. 📐 `[UNIVERSAL_CONSTRAINTS]`（普遍的ディテール制約）

* **デジタル画面**: ノートPCやタブレットは必ず `pure blank white screen`。ネガティブに `computer ui, desktop icons, graphs on screen, screensaver` を明記し、ダミーUIや青空壁紙の混入を根絶する。
* **湯気・煙の根絶**: `no steam, no smoke, no vapor` をネガティブプロンプトおよび本文末尾に徹底。
* **無人空間の徹底**: 人物・手・人影は一切排除（`no people, no humans, no silhouettes`）。
* **商標・ロゴ排除**: リンゴマーク、ブランドロゴ、不自然な文字は完全排除（`unbranded, no logos, no text`）。
* **末尾固定構文**: 必ず `--ar 16:9 --v 3.1-pro --style raw` を末尾に付与。

---

## 📋 第6章：完全出力テンプレート（Obsidian / プロンプト管理対応）

マスタープロンプト生成時は、以下のフォーマットを厳密に出力してください。

````markdown
### No. [No]: [Title] ([日本語タイトル])

#### ℹ️ 基本データ
- **Concept:** [1行コンセプト：誰が、どんな空間で、どう集中するか]
- **Space-ID:** `[Season]_[Style]_[Location]_[No]`
- **Thumbnail Copies (English Only / 3-4 words):**
  - 案1 (Functional Benefit): `[Copy]` ([日本語訳])
  - 案2 (Emotional Scene): `[Copy]` ([日本語訳])
  - 案3 (Hybrid): `[Copy]` ([日本語訳])

#### 🤖 プロンプト

[!success]- Focus
```yaml
---
type: asset
asset_type: image
asset_id: 2026_img_[No]_f-01_[Kebab-Case-Title].png
channel_id: ポモスタ
visual_style: [Style Mix]
space_type: [Private Study / Academic Library]
scene_id: [Space-ID]
season: [Season]
time_of_day: [Time]
camera_composition: [Camera & Composition]
dof_level: Natural
color_temperature: [Warm/Neutral/Cool]
cat_logic: [Motif, Count, Materials, Poses, Placements]
keywords: [keyword1, keyword2, keyword3]
---
```
```text
[AESTHETIC_PREFIX]. A highly detailed 1080p cinematic **[CAMERA_&_COMPOSITION (POV & Angle)]** of a luxurious [Private Study / Library Space], [SEASON_&_TIME]. [STYLE_MIX].
[FOREGROUND]: Sleek premium desk positioned directly against the window, equipped with a clean laptop with a pure blank white screen, a ceramic mug of coffee completely without steam, and neatly placed stationery. Natural photographic depth with balanced sharpness.
[MIDGROUND]: Spacious executive study interior with high ceilings and tasteful negative space. Strictly unoccupied and peaceful. [BOTANICAL_DENSITY].
[BACKGROUND]: Massive floor-to-ceiling panoramic glass window taking up 60-70% of the entire frame, showcasing a crystal-clear, breathtaking view of [Natural Scenery]. [WALL_ART: Tastefully framed minimalist art print]. [Apply Fireplace Rule if applicable].
[CAT_MOTIF]: [Explicit individual descriptions for 1-3 figurines with materials, poses, and distinct locations].
--ar 16:9 --v 3.1-pro --style raw --no people, humans, text, watermarks, brand logos, apple logo, steam, smoke, vapor, top-down view, messy desk, computer ui, desktop icons, graphs on screen [Apply OVERRIDE_RULES]
```

**💡 代替カメラ構図タグ（Focus用・真上除外）**
- **案1（広角スケール重視）**: 
  `Wide-angle eye-level shot establishing the full breath of the panoramic window and the floating executive desk.`
  *(解説: 部屋の横幅とパノラマ大窓のスケール感を強調し、開放感を極大化するアングル)*
- **案2（ハイアングル斜め俯瞰）**: 
  `High-angle three-quarter perspective looking down softly at the organized desk workspace while retaining 60% view of the outdoor scenery.`
  *(解説: 机の上の作業アイテムの整理美と、窓外の美しい景色をバランスよく両立させる斜め俯瞰)*

[!success]- Break
```yaml
---
type: asset
asset_type: image
asset_id: 2026_img_[No]_b-01_[Kebab-Case-Title].png
channel_id: ポモスタ
visual_style: [Style Mix]
space_type: [Break Pattern: Window / Terrace / Pure Nature]
scene_id: [Space-ID]
season: [Season]
time_of_day: [Time]
camera_composition: [Camera & Composition]
dof_level: Natural
color_temperature: [Warm/Neutral/Cool]
cat_logic: [Real, 1, Breed/Color, Tail, Pose]
keywords: [keyword1, keyword2, keyword3]
---
```
```text
[AESTHETIC_PREFIX]. A highly detailed 1080p cinematic **[CAMERA_&_COMPOSITION (Break Pattern 1, 2, or 3)]**, [SEASON_&_TIME].
[SCENE_DESCRIPTION]: [Constructed strictly based on Break Pattern 1 (Indoor Window-Edge), Pattern 2 (Outdoor Terrace Lounge), or Pattern 3 (Pure Nature Landscape), with outdoor scenery occupying 80-90% of the frame].
[REAL_CAT]: A serene, fluffy [Breed & Color] cat with a [Tail] tail, [Sitting peacefully gazing out at nature / Lounging comfortably], seamlessly integrated into the setting.
--ar 16:9 --v 3.1-pro --style raw --no people, humans, text, watermarks, brand logos, indoor clutter, steam, smoke, vapor, top-down view
```

**💡 代替カメラ構図タグ（Break用・真上除外）**
- **案1（猫越しPOV景観）**: 
  `First-person POV over the shoulder of a calm real cat sitting on the ledge, looking out into the expansive landscape.`
  *(解説: 手前の猫の背中越しに雄大な景色を見渡す、癒やしと没入感の極致構図)*
- **案2（ローアングル・オープンパノラマ）**: 
  `Slight low-angle outdoor shot emphasizing the vast sky and majestic horizon with the relaxed cat resting naturally in the frame.`
  *(解説: 空と景色の広がりをダイナミックに捉え、深呼吸したくなる解放感を演出する構図)*
````
