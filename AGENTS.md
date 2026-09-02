# f14-weapons — Agent Entry Point

## Unified Production Feedback OS v2

このrepoで軍事資料・画像・兵器情報を追加、修正、再利用する前に `UNIFIED_PRODUCTION_SYSTEM.json` を読み、Global Governance Kernel `murata3594-cyber/military-v3` の `docs/UNIFIED_PRODUCTION_FEEDBACK_OS.md` と `data/owner_feedback_events/` を `military_reference_assets` profileで適用する。

オーナー修正を会話内だけに残さず中央event logへ追記する。同一failure signature・同一method fingerprintで2回OWNER_REJECTEDになった方式は3回目を実行しない。

このrepo固有の資料・権利・型式同定ルールは維持し、成果物の完成・releaseは中央 `scripts/unified_repository_release.py` がcurrent context・active invariant・local gate結果・最終artifact SHA-256を照合したPASS receiptを必須とする。Global Kernelをこのrepoへ複製・分岐させない。

実在軍事装備は生成AIで置き換えず、実在写真、公式映像、公式図版、権利確認済みarchive等を優先する。
