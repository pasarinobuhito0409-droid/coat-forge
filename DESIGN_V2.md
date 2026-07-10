# COAT FORGE v2 デルタ仕様（マスター: C:\Users\今林拓也\forge-standard\FORGE_V2.md）

対象: `C:\Users\今林拓也\coat-forge\`。現状v1.1＝**器の正そのもの**（全旧装備あり）。
**追加＝新機能5（サビ・自信ベット・DAILY・教える・ガチャ）＋XPヘッダー＋RQのv2ペイロード化のみ。**
既存演出/本文/分子の目/現場の目/PASSPORTは変更禁止（PASSPORT先頭にLv表示だけ追加）。

## D1 ガチャ超レア演出（塗装オリジナル）

育つ塗装パネルに金のスプレーミストが吹かれ、鏡面フレアが走って金鏡面に（2秒）。称号「鏡面の匠」。

## D2 サビマップ対応

塗装街道のレッスンノードに適用。ドリルtag（iro/maku/mask/yaki/fuki/cost）→レッスン対応: iro→l4, maku→l5, mask→l6, yaki→l2, fuki→l3, cost→l6（変更してよいが報告書に記載）。

## D3 その他

- 新キー: `coat-forge-fresh-v1`。既存キー変更禁止。
- 自アプリはFORGE DAILYの「持ち主」側にもなる: rqUpsertのv2ペイロード化を最優先で実装（他5機のDAILYが読む）。
