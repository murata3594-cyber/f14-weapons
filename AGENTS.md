# f14-weapons — Agent Entry Point

## Unified Production Feedback OS v2

このrepoで軍事資料・画像・兵器情報を追加、修正、再利用する前に `UNIFIED_PRODUCTION_SYSTEM.json` を読み、Global Governance Kernel `murata3594-cyber/military-v3` の `docs/UNIFIED_PRODUCTION_FEEDBACK_OS.md` と `data/owner_feedback_events/` を `military_reference_assets` profileで適用する。

オーナー修正を会話内だけに残さず中央event logへ追記する。同一failure signature・同一method fingerprintで2回OWNER_REJECTEDになった方式は3回目を実行しない。

このrepo固有の資料・権利・型式同定ルールは維持し、成果物の完成・releaseは中央 `scripts/unified_repository_release.py` がcurrent context・active invariant・local gate結果・最終artifact SHA-256を照合したPASS receiptを必須とする。Global Kernelをこのrepoへ複製・分岐させない。

実在軍事装備は生成AIで置き換えず、実在写真、公式映像、公式図版、権利確認済みarchive等を優先する。

<!-- ONE_STROKE_WORKFLOW:BEGIN -->
## 一度の依頼で品質確認・保存まで完遂する工程
新規・継続の実作業開始時に `docs/knowledge/ONE_STROKE_WORKFLOW.md` を読み、対象案件のCURRENT・過去の修正・採用済み成果へ接続してください。
不要な再指示待ちをせず、実装・検査・原因修正・再検査・保存まで進めます。
既存担当との重複、結果不明の再送、未変更成果の全再生成を避け、実物の品質確認を省略しません。
この追補は既存の案件仕様・専門審査・担当・費用承認・公開条件を変更しません。
<!-- ONE_STROKE_WORKFLOW:END -->
