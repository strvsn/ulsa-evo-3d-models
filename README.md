# ULSA EVO — 外形参照用3Dモデル / 3D Reference Model

[日本語のみ / Japanese only](README.ja.md) · [製品サイト / Product](https://ulsa-evo.strvsn.net/) · [配布パッケージ / Download package](https://github.com/strvsn/ulsa-evo-3d-models/releases/latest)

![ULSA EVO — STEP外形参照モデル / STEP exterior reference](assets/ogp-3d-models.jpg)

STRVSN / StratoVision LLC.の超音波風速計 **ULSA EVO** の簡易外形モデルです。設置スペース、独立した周辺機器の設計、画像・動画制作などに利用できます。

A simplified exterior reference of the **ULSA EVO ultrasonic wind sensor**, published by STRVSN / StratoVision LLC. for space planning, independent accessory design and visualization.

**外形参照用のデータです。** 製造図面やオープンソースハードウェア設計ではありません。重要な寸法・接続部は実機と最新の正規製品資料で確認してください。

**Reference use only.** This is not a manufacturing drawing or an open-source hardware design. Critical dimensions and interfaces must be checked against actual hardware and current product documentation.

## ダウンロード / Download

- [STEPモデル / STEP model](models/ULSA_EVO_Exterior_Reference.step)
- [ライセンス・注意事項を含む配布パッケージ / Package with license and notices](https://github.com/strvsn/ulsa-evo-3d-models/releases/latest)
- [モデルの説明 / Model notes](docs/MODEL_NOTES.md) · [ファイル情報 / File information](model-manifest.json)

STEPファイルのページで **Download raw file** を選ぶと保存できます。再配布時にはライセンス・注意事項を添付してください。

Use **Download raw file** on the STEP file page. Include the license and notices when redistributing the model.

## モデル情報 / Model information

| 項目 / Property | 内容 / Value |
| --- | --- |
| 形式・単位 / Format and units | STEP AP242 / mm (millimeters) |
| ボディ / Bodies | 有効なソリッド1個 / One valid solid |
| 上方向 / Up axis | +Y |
| 外接寸法 / File bounding box, X × Y × Z | 約 / Approximately 50.000 × 66.312 × 50.550 mm |

外接寸法は突起を含むこのデータの計測値です。製品仕様値や公差の保証値ではありません。

The bounding box includes modeled protrusions and describes this file only. It is not a guaranteed product dimension or tolerance.

## 用途と留意事項 / Intended use and limitations

外形の収まり、設置スペース、独立した周辺機器の設計、画像・動画制作、許諾された非機能モックアップに利用できます。寸法、公差、ねじ、材質、質量、重心、強度、気流やセンサー性能を保証する資料ではありません。周辺機器を製造する前に、重要な接続部・取付条件を実機で確認してください。

Use this model for exterior clearance, mounting-space planning, independent accessory design, visualization and licensed non-functional mockups. It does not provide authoritative dimensions, tolerances, thread details, material properties, mass, center of gravity, structural strength, airflow behavior or sensor performance. Check critical interfaces on actual hardware before manufacturing accessories.

<img src="assets/model-preview.png" width="540" alt="外形モデルのプレビュー / Exterior geometry preview">

画像は配布外形モデルを描画したものです。描画材質はイメージであり、製品の材質・色の指定ではありません。

The graphics depict the supplied reference geometry. Rendering materials are illustrative and do not specify product materials or colors.

## ライセンス / License

[STRVSN Reference Model License](LICENSE)は、**商用の周辺機器設計・画像制作を許可**し、出典表示や再配布条件を定めています。収まり確認・展示用の非機能モックアップも許可します。**センサー本体・部品の複製製造、および物理的な複製品の販売は許諾しません。**

The [STRVSN Reference Model License](LICENSE) permits **commercial accessory design and visualization**, with attribution and redistribution conditions. Non-functional fit-check and display mockups are also permitted. **Reproduction manufacturing of the sensor or its components, and sales of physical replicas, are not licensed.**

参照用途の独自ライセンスであり、オープンソースハードウェアのライセンスではありません。独自に作成した周辺機器設計や画像・動画に同じライセンスの適用を強制しません。ただし、再配布するモデルデータには本条件が適用されます。商標・産業財産権は留保します。[英語原文](LICENSE)と[日本語訳](docs/LICENSE.ja.md)を参照してください。

This is a custom reference-use license, not an open-source hardware license. Independently authored accessory designs and visualizations do not have to adopt these terms; redistributed model data remains subject to them. Trademarks and industrial property rights are reserved. See [LICENSE](LICENSE) and its [Japanese translation](docs/LICENSE.ja.md).

Copyright © 2026 StratoVision LLC.

## 関連リポジトリ / Related repositories

- [ULSA EVO app](https://github.com/strvsn/ulsa-evo-app)
- [ULSA EVO ESP32 firmware](https://github.com/strvsn/ulsa-evo-esp32-firmware)

関連リポジトリのソフトウェアライセンスは、本CADデータには適用されません。

Their software licenses do not apply to the CAD data in this repository.
