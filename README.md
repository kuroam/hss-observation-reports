# HSS Observation Reports

このリポジトリは、HSSモデルを用いた実際の観測レポート集です。

English working version: [README.en.md](README.en.md)

HSSモデル本体は、別リポジトリで管理します。

- HSS core model: https://github.com/kuroam/hss-observation-notes

ここに置くレポートは、HSSの証明ではありません。

また、観測対象に対する確定解釈でもありません。

HSS語彙を仮の観測軸として置いたときに、見えにくい接続構造がどのように見えるかを整理するための、暫定的な観測レポートです。

レポートは、ソース、解釈、観測軸の更新に応じて修正される可能性があります。

本リポジトリでは、日本語版の観測レポートを正本として管理します。

英語版は、HSS語彙と観測意図を保つための作業訳として、順次追加・更新します。

PDFなどの派生形式は、必要に応じて追加します。

## Reports

| No. | Title                | File                                                                                 | 論点                                                 |
| --- | -------------------- | ------------------------------------------------------------------------------------ | -------------------------------------------------- |
| 001 | ドラッカーのマネジメントとKPIへの圧縮 | [reports/ja/001_drucker_management_kpi.md](reports/ja/001_drucker_management_kpi.md) | ドラッカーはKPIを言っていたのか、それともKPIから戻る問いを言っていたのかを、HSSで分解する。 |
| 002 | 一発ギャグ、バズ、芸体系への接続 | [reports/ja/002_ippatsu_gag_buzz_gei_system.md](reports/ja/002_ippatsu_gag_buzz_gei_system.md) | 一発ギャグはなぜ消費されるのか。強い記号が芸体系へ接続される場合と、バズで終わる場合の差をHSSで分解する。 |
| 003 | イノベーションはなぜ伝票の束で止まるのか | [reports/ja/003_innovation_invoice_bundle.md](reports/ja/003_innovation_invoice_bundle.md) | 新しい接続候補が、既存の承認・予算・評価形式へ圧縮される構造をHSSで分解する。 |
| 004 | 「刺さる」と「かする」の接続構造 | [reports/ja/004_sasaru_kasuru_connection.md](reports/ja/004_sasaru_kasuru_connection.md) | 「刺さる」は新しさではなく既存の積層historyへの接続である。「かする」痕跡が、文化やイノベーションの接続候補として残る構造をHSSで観測する。 |
| 005 | 自己責任化は個人版KPIである | [reports/ja/005_han_self_responsibility_kpi.md](reports/ja/005_han_self_responsibility_kpi.md) | Hanの議論に見られる自己管理・自己最適化・自己責任化を、管理・最適化・責任が個人側へルーティングされたように見える接続状態としてHSSで観測する。 |
| 006 | AI slopはベルトコンベア問題である | [reports/ja/006_ai_slop_conveyor_belt.md](reports/ja/006_ai_slop_conveyor_belt.md) | いわゆるAI slopを、AI生成そのものではなく、候補供給構造・再生数ビジネス・反応指標に生成AIの大量生成能力が接続された観測状態としてHSSで分解する。 |

## Source Notes

| No. | File                                                                   |
| --- | ---------------------------------------------------------------------- |
| 001 | [sources/ja/001_drucker_sources.md](sources/ja/001_drucker_sources.md) |
| 002 | [sources/ja/002_ippatsu_gag_sources.md](sources/ja/002_ippatsu_gag_sources.md) |
| 003 | [sources/ja/003_innovation_sources.md](sources/ja/003_innovation_sources.md) |
| 004 | [sources/ja/004_sasaru_sources.md](sources/ja/004_sasaru_sources.md) |
| 005 | [sources/ja/005_han_sources.md](sources/ja/005_han_sources.md) |
| 006 | [sources/ja/006_ai_slop_sources.md](sources/ja/006_ai_slop_sources.md) |

## レポート間の接続

初期レポート群では、各レポートを単独の事例としてだけでなく、HSS上の接続構造として相互に参照します。

- 001 → 005: 組織側のKPI圧縮と、個人側への管理・最適化・責任ルーティング
- 002 → 004 → 006: 一発symbol、刺さる/かする、低接続symbolと再生数ビジネス
- 003 → 004: 未固定の接続候補、かすって残る痕跡、伝票のまま残る処理形式

これらの接続は、各レポートの結論を固定するものではなく、HSSを仮の観測軸として用いたときに見える接続関係のメモです。

## 権利・ライセンスについて

Copyright (c) 2026 kuro amak.

特に明記がない限り、すべての権利を留保します。

このリポジトリは閲覧・参照のために公開しています。

明示的な許可なく、内容の複製、再配布、改変、翻訳、派生物の作成を許可するものではありません。

## Notes

このリポジトリは、HSS本体の定義を追加・変更するための場所ではありません。

HSS本体の概念、用語、観測テンプレートは、core model repository 側で管理します。

このリポジトリでは、HSSを仮の観測軸として用いた個別レポートを管理します。
