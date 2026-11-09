# 森光斗

滋賀大学大学院でデータサイエンスを学んでいます。地理空間データや自然言語処理に関心があり、分析結果を人が使えるアプリや仕組みにすることに取り組んでいます。

学内機械学習コンペで2年連続1位、SIGNATEで銀・銅メダルを獲得。PythonのOSSにもコントリビュートしています。

## 関心のある領域

分散した情報やデータを整理・結合し、検索・予測・推薦を通じて意思決定を支えることに関心があります。特に、地理空間データの活用、自然言語処理、継続して使えるデータ基盤やWebサービスの開発に取り組みたいと考えています。

## 代表作品

### [滋賀大学 研究室探索アプリ](https://github.com/mote24405-coder/shiga-lab-recommend)

修士論文117件を整理し、59研究室の研究テーマ・手法・使用データから、興味に合う研究室を探せるWebアプリです。絞り込み、全文検索、推薦機能を実装しました。

**技術:** Python、FastAPI、PostgreSQL、SQLAlchemy、HTMX、Tailwind CSS

## OSSへの貢献

- **[PR-Agent #3565](https://github.com/The-PR-Agent/pr-agent/pull/3565) — マージ済み（2026年9月）**  
  類似Issue検索で処理件数の上限が正しく適用されない不具合を修正。Pinecone・LanceDB・Qdrantの処理を直し、回帰テストを追加しました。

- **[dlt #4504](https://github.com/dlt-hub/dlt/pull/4504) — レビュー中（2026年10月提出）**  
  Apache Airflow 3でログレベルが正しく扱われない問題に対し、ログ伝播の設定・処理とテストを実装しました。

## コンペティション

- **久留米工業大学 学内機械学習コンペティション — 2年連続1位**  
  2024年度の画像分類課題で1位。2025年度のBERTを用いた著者分類課題でも1位を獲得しました。画像分類では学習方法の工夫やアンサンブルの導入、著者分類では敵対的学習を用いて文章の内容への依存を抑えるモデルの構築に取り組みました。

- **[第2回 国土交通省 地理空間情報データチャレンジ](https://user.competition.signate.jp/ja/competition/detail/?competition=2b0105bc0c674f258e39cb2c7711e36f) — 48位・銀メダル**  
  不動産売買価格の予測に取り組み、駅までの距離、周辺施設数、地域の人口構成など、外部の地理空間データを特徴量に活用しました。

- **[SIGNATE × TECH OCEAN Student Cup 2025](https://user.competition.signate.jp/ja/competition/detail/?competition=385dcbba17b645f3ac10f827dfba03f6) — 245名中69位・銅メダル**  
  生成AIを活用した自然言語処理の課題に取り組みました。

## 技術スタック・手法

- **プログラミング言語:** Python、SQL
- **機械学習・深層学習:** PyTorch、scikit-learn、Hugging Face Transformers
- **コーディングエージェント:** Claude Code、OpenAI Codex、GitHub Copilot
- **データ分析・データ基盤:** dbt、Snowflake、Google BigQuery
- **バックエンド・データベース:** FastAPI、PostgreSQL、SQLAlchemy
- **フロントエンド:** HTMX、Tailwind CSS
- **開発・品質管理:** Git、GitHub、回帰テスト
- **機械学習・分析手法:** 画像分類、データ拡張、アンサンブル学習、敵対的学習、BERT、自然言語処理、地理空間データを用いた特徴量設計
