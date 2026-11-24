# 資料約定

這些內容是本地合成演練資料，不代表真實人物、機構、作品或交易。原始值按來源記錄；空值和待核狀態表示尚未確認，不等同否定、零或已完成。

藝術市場公開交易來源、觀察覆蓋、報告比較和發布審核資料。

- `venues.csv`：欄位 `venue_id, name, region, reporting_policy, active_from, active_to`。
- `transactions.csv`：欄位 `record_id, venue_id, work_id, event_on, event_state, price_band, region, source_ref`。
- `coverage.csv`：欄位 `venue_id, period, reporting_scope, known_gaps, review_state`。
- `reports.csv`：欄位 `report_id, period, region_scope, min_group_size, release_state, snapshot_id`。

同一標識只在其對應資料域內使用；版本、時間和狀態欄位保留各自來源含義。
