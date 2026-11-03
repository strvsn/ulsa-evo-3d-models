# Model notes / モデルについて

The supplied file is a simplified exterior reference in STEP AP242 format,
with one valid solid body. Units are millimeters and +Y points upward.
The XZ plane is horizontal. In a Z-up application, use a rigid 90-degree rotation
about X. Use the same scale on all three axes to preserve proportions.

配布ファイルはSTEP AP242形式の簡易外形参照モデルです。有効なソリッド1個、単位はmm、上方向は+Yです。
Zが上方向のツールでは、X軸回りの90度回転で方向を合わせられます。
縦横比を維持するため、XYZには同じ倍率を適用してください。

## Limitations / 留意事項

This model supports exterior space planning and visualization. It is not a
manufacturing drawing or a performance simulation model. Dimensions, tolerances,
thread details, connector fit, material properties, mass, center of gravity,
structural strength, airflow and measurement performance are not guaranteed.
Confirm critical interfaces on actual hardware and current product documentation.

外形の収まり確認や画像制作のためのデータであり、製造図面や性能解析モデルではありません。
寸法・公差・ねじ・コネクタの嵌合・材質・質量・重心・強度・気流・計測性能を保証しません。
重要な接続部は実機と最新の正規製品資料で確認してください。

The file bounding box includes modeled protrusions. Rendering materials do not
specify the product's actual construction materials or colors.

外接寸法はモデル上の突起を含みます。画像の描画材質は、製品の材質・色を指定するものではありません。

## License / ライセンス

Use and redistribution are governed by [LICENSE](../LICENSE). Keep the license
and notices when sharing the model. See the [Japanese translation](LICENSE.ja.md).
