---
title: "【CTR最大化＆情緒刺激】NanoBanana Pro 画像生成プロンプト設計フレームワーク"
date: 2026-08-30
tags:
  - youtube
  - prompt-engineering
  - nanobanana-pro
  - imagen-3
  - ctr
  - visual-design
  - quiet-luxury
status: completed
---

# 🎨 【CTR最大化＆情緒刺激】NanoBanana Pro 画像生成プロンプト設計フレームワーク
*(by `visual-prompt-director`)*

YouTubeサムネイルにおいて、ユーザーが動画をクリックするかどうかは**「0.1秒〜0.5秒の視覚的直感」**で決まります。
本ドキュメントは、単なる「綺麗なイラスト」を超え、**人間の感情・情緒・知的欲望を強烈に刺激してクリック率（CTR）を最大化するNanoBanana Pro (Gemini AI Pro / Imagen 3) 専用のプロンプト設計論**です。

---

## 🏛️ 1. CEO・エグゼクティブ高級空間 3大ビジュアルスタイル

YouTubeで何百〜何千万回と再生されるトップ層のDeep Workサムネイルで共通している、**「誰もが憧れる最高峰のエグゼクティブ空間」**の3大パターンです。

```text
┌────────────────────────────────────────────────────────────────────────┐
│                   CEO・エグゼクティブ 3大高級空間スタイル               │
├────────────────────────────────────────────────────────────────────────┤
│ ①【CEO Office / Modern Studio（雨の絶景森林 × ハイエンドデスク）】     │
│    └ 床から天井までの巨大パノラマ窓、雨に煙る雄大な針葉樹林と滝、     │
│      ダークウォールナットのフローティングデスク、アーロンチェア、      │
│      デュアルモニター（コード・データ画面）、洗練された間接LED。       │
│                                                                        │
│ ②【Penthouse Deep Work Lounge（オーシャンビュー × 夕暮れ/朝焼け）】    │
│    └ 太平洋を一望する崖の上のガラス張り邸宅、水平線に沈む夕日、        │
│      イームズラウンジチェア、天井までの本棚、ミニマルラップトップ。    │
│                                                                        │
│ ③【Calm Executive Bedroom / Workspace（大都市の夜景 × 静寂の寝室）】   │
│    └ 超高層タワーマンション最上階、大都市のボケた夜景（Bokeh）、      │
│      キングサイズベッド、奥に整然とした作業デスク、コーブ間接照明。    │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📐 2. DaVinci Resolve 文字後付け用「ネガティブスペース設計」

DaVinci Resolveで中央や上部にシャープな英字タイトル（`CEO WORK`, `DEEP WORK`, `CALM WORK` 等）を配置した際に、最も文字が際立ち視認性を極大化できるよう、プロンプト内で**「計算された明暗比と背景の抜け感」**を設計します。

```text
┌────────────────────────────────────────────────────────────┐
│ [文字配置エリア（中央または上部）]                         │
│ 雄大な雨の森林・夕暮れの空・都市の夜景の静かなグラデーション│
│ ※文字（白サンセリフ/セリフ体）がくっきり発光して映える背景 │
├────────────────────────────┬───────────────────────────────┤
│ [左側：知性と洗練]         │ [右側〜手前：高級デスク・家具]│
│ 天井までの間接照明付き本棚 │ フローティング木製デスク、    │
│ アートオブジェ、観葉植物   │ 高級チェア、湯気の立つカップ  │
└────────────────────────────┴───────────────────────────────┘
```

---

## ⚡ 3. NanoBanana Pro特化型 CEO空間プロンプト黄金テンプレート

NanoBanana Pro（Gemini AI Pro / Imagen 3）に入力する英文プロンプトは、以下の構成で構築します。

```text
[単一画像・バリエーション禁止制約 (Single image only, no color variations)]
+ [写真スタイル・画質（Architectural Digest photorealistic）]
+ [CEO空間の指定（モダンオフィス / ペントハウスラウンジ / 高級寝室）]
+ [大開口パノラマ窓 ＆ 絶景（雨の森林・滝 / 夕暮れオーシャン / 都市夜景）]
+ [高級家具・ディテール（ウォールナット机 / 高級チェア / デュアルモニター / 湯気）]
+ [文字後付け用ネガティブスペース指定（clean negative space in the center）]
+ [CEO共通ライティングブロック（単一の照明・配色固定、Ray-tracing、Chiaroscuro）]
```

### 🏆 【CEO/エグゼクティブCTR最大化共通ライティングブロック（1枚限定版）】
> `ultra-realistic architectural interior photography, Architectural Digest style, quiet luxury aesthetic, cinematic moody lighting, chiaroscuro, warm amber ambient cove lighting, soft glowing screens, floor-to-ceiling panoramic glass windows, high contrast between cozy warm interior and dramatic moody outdoor scenery, ray tracing reflections, volumetric atmosphere, ultra-detailed textures, 8k resolution, photorealistic masterwork, generate strictly only 1 single full-frame 16:9 image, no variations, no multiple color palettes, no grid, no contact sheet --ar 16:9`

---

## 💡 4. 実践プロンプト集（添付サムネイル準拠・即コピペ可能）

### 🌧️ ①『CEO WORK』スタイル：雨の森林・滝を望むエグゼクティブオフィス
```text
Ultra-realistic architectural interior photography of a luxurious CEO corner office and modern workspace, massive floor-to-ceiling panoramic glass windows with gentle rain dripping down, breathtaking moody view of a vast evergreen pine forest, misty river, and distant waterfalls outside, sleek dark walnut floating desk equipped with dual minimalist monitors displaying clean coding and financial charts, high-end ergonomic executive chair, subtle warm green and amber LED ambient light strips under shelves, modern bookshelf filled with books and globe, steaming hot espresso cup on the desk, ample clean negative space in the upper-left and center for typography, Architectural Digest style, quiet luxury aesthetic, cinematic moody lighting, chiaroscuro, ray tracing reflections, volumetric mist, 8k resolution, photorealistic masterwork --ar 16:9
```

### 🌅 ②『DEEP WORK』スタイル：夕暮れの海と水平線を一望するペントハウス書斎
```text
Ultra-realistic architectural interior photography of a serene luxury penthouse study at sunset, immense floor-to-ceiling frameless glass window overlooking a calm ocean and golden sunset on the horizon, floating dark wood desk with a sleek laptop and a minimalist vase with a single rose, warm modern ambient desk lamp casting a golden glow, classic leather lounge chair, floor-to-ceiling illuminated bookshelf with warm backlighting, ample clean negative space in the center for elegant typography overlay, Architectural Digest style, quiet luxury aesthetic, warm amber and teal color harmony, cinematic lighting, ray tracing, shallow depth of field, 8k resolution, photorealistic masterwork --ar 16:9
```

### 🌃 ③『CALM WORK』スタイル：都会の夜景を望む高級ペントハウス寝室＆ワークスペース
```text
Ultra-realistic architectural interior photography of an ultra-luxurious modern bedroom and executive workspace in a high-rise penthouse at midnight, huge floor-to-ceiling glass window showcasing a breathtaking panoramic bokeh of glowing city night lights, minimalist king-size bed with premium textured dark grey linens, warm hidden cove lighting along the headboard and ceiling, sleek wooden work desk in the background with an elegant chair and indoor potted plant, clean and dark minimalist composition with ample negative space in the center for typography, Architectural Digest style, quiet luxury aesthetic, deep shadows, soft warm ambient lighting, 8k resolution, photorealistic masterwork --ar 16:9
```

