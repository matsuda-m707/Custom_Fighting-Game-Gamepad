# 部品表

## 1. 購入するもの

| 部品名 | 型/サイズ | 数量 | 購入先の例 |
| :--- | :--- | :---: | :--- |
| Raspberry Pi Pico | - | 1 | [https://akizukidenshi.com/catalog/g/g118085/] |
| なべ小ねじ | M3 × 8mm | 8 | [https://www.amazon.co.jp/dp/B09SCV6HL5]  |
| なべ小ねじ | M3 × 16mm | 4 | 同上 |
| 六角ナット | M3 | 12 | 同上 |
| キースイッチ | Cherry MX互換 | 17 | [https://shop.yushakobo.jp/products/4278] |
| UBSコネクタ | microBタイプ　オス | 1 | [https://www.amazon.co.jp/dp/B094CC8Z1M] |
| UBSコネクタ | Bタイプ メス | 1 | [https://akizukidenshi.com/catalog/g/g100161/] |
| 導線 | - | 1 | [https://www.amazon.co.jp/dp/B0DV57SHVP] |
| 丸型磁石 | φ5 × 2mm | 2 | [https://www.amazon.co.jp/dp/B0B7BBGM81] |


>  キースイッチについて  
>  軸受けが十字のみの物に対応しています。4個はスティック操作に使うため作動点が1mm前後の物を推奨します。

---


## 2. 発注するもの

このプロジェクト内のデータを使って部品を製造サービスに発注します。  
ここではJLCPCBを想定して推奨する設定がある場合は記載します。

### プリント基板(GerberData)
| ファイル名 | 説明 | 数量 | 備考 |
| :--- | :---: | :---: | :--- |
| Main | メイン基板 |  1 | -  |
| ButtonLR | LRボタン用 |  1 | -  |
| USBConnector | USBコネクタ |  1 | -  |


### 3Dプリント(STL)
| ファイル名 | 説明 | 数量 | 備考 |
| :--- | :---: | :---: | :--- |
| Front | 本体前面 |  1 | -  |
| Back | 本体背面 |  1 | -  |
| Button | 前面ボタン |  7 | -  |
| ButtonLR | LRボタン |  4 | -  |
| ButtonS | Start・Selectボタン |  2 | -  |
| StickBase | スティックパーツ |  1 | 8001Resin推奨  |
| StickAxis | スティックパーツ |  1 |  8001Resin推奨  |
| StickHorizontai | スティックパーツ |  1 | 8001Resin推奨   |
| StickVertical | スティックパーツ |  1 | 8001Resin推奨   |
| StickHead | スティックパーツ |  1 | 8001Resin推奨   |

>  3Dプリントは素材によって同じデータでも寸法にばらつきが出る場合があります。  
>  スティックパーツは他と比べて寸法が重要なので動作を確認した8001Resinという素材を推奨しています。