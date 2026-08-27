# 🤖 YouTubeヒット法則コンテンツ量産 AIエージェント構成ガイド

本フォルダ（`docs/ai_agents/`）は、YouTubeにおける**「欲望解消の法則（高CTR × 高維持時間）」**を満たすヒット動画の「タイトル」「サムネイルコピー」「動画構成・コミュニティ設計」をAIエージェント（Antigravity, Gemini, ChatGPT等）が高精度・再現性高く自動生成・量産するためのプロンプト指示ファイル群です。

---

## 📁 エージェント指示ファイル一覧

1. **[01_youtube_hit_core_philosophy.md](file:///Users/ymto/Documents/git/youtube-research-toolkit/docs/ai_agents/01_youtube_hit_core_philosophy.md)**:
   - AIエージェントに読み込ませる「YouTubeヒットとバズのコア原則・人間心理・アルゴリズム構造」。
2. **[02_title_generator_agent.md](file:///Users/ymto/Documents/git/youtube-research-toolkit/docs/ai_agents/02_title_generator_agent.md)**:
   - インプレッション極大化 ＋ 欲望解消フック ＋ 登録転換名言を網羅した「高品質タイトル自動生成プロンプト」。
3. **[03_thumbnail_concept_agent.md](file:///Users/ymto/Documents/git/youtube-research-toolkit/docs/ai_agents/03_thumbnail_concept_agent.md)**:
   - スクロールを止める直球の欲望解体コピー ＋ タイトル同期 ＋ 視覚構成を出力する「サムネイル作成プロンプト」。
4. **[04_video_structure_agent.md](file:///Users/ymto/Documents/git/youtube-research-toolkit/docs/ai_agents/04_video_structure_agent.md)**:
   - 平均視聴時間30分を狙う長尺/タイマー構成 ＋ コメント欄を活性化させる「エンゲージメント設計プロンプト」。

---

## 🚀 使い方（AIへの指示手順）

新規動画や新しいチャンネルの企画を行う際、AIチャット（またはカスタムGPTs / System Prompt）に以下の順で指示を出します：

1. `01_youtube_hit_core_philosophy.md` の内容を AI のシステムプロンプト（または前提知識）として与える。
2. 作成したいコンテンツの目的（タイトル / サムネイル / 構成）に応じて、`02`, `03`, `04` のプロンプトテンプレートをコピーし、入力変数（テーマ・音・ターゲット）を埋めて実行する。
