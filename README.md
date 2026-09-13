# gootoo-maps-data

Gootoo Maps（旅の割引を探す）iOS アプリ向けの公開配信データ。本体リポジトリ `pplog4/travel-support-app` は private のため、
GitHub Pages が匿名で読めるようにデータだけ分離している。

| ファイル | 用途 | アプリ側の設定 |
|---|---|---|
| `official-feed.json` | 公式補完データ（`npm run build:feed` の出力をそのまま置く） | `EXPO_PUBLIC_OFFICIAL_FEED_URL` |

更新手順は本体の `docs/OFFICIAL-FEED.md`。ファイル全体を一度に置き換える（部分編集しない）。認証情報は含めない。
