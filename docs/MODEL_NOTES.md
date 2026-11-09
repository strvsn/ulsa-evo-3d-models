# Model notes / モデルについて

## 日本語

ULSA EVOの簡易外形参照モデルを、STEP・STL・3MF・USDZで配布しています。STL・3MF・USDZは、同梱のSTEPから変換した近似メッシュです。寸法比率は共通です。

| 形式 | 単位 | 上方向 | 内容 |
| --- | --- | --- | --- |
| STEP AP242 | mm | +Y | 有効なソリッド1個。元の座標系を保持 |
| STL（バイナリ） | mmとして読み込み | +Z | 閉じたメッシュ1個。単位情報はファイルに含まれません |
| 3MF | mm（ファイル内で指定） | +Z | 閉じたメッシュ1個、ビルド項目1個。プリンター・スライサーの設定は含みません |
| USDZ | m（実寸スケール） | +Y | メッシュ1個と表示用の中立色マテリアル。Apple系ビューアー・AR向け |

STL・3MFはSTEPをX軸回りに+90度回転し、最下点をZ=0に配置しています。USDZはY上向きのまま、最下点をY=0に配置し、mmからmへ一様に単位変換しています。表示する際はXYZに同じ倍率を適用してください。

### 留意事項

外形の収まり確認や画像制作のためのデータであり、製造図面や性能解析モデルではありません。寸法・公差・ねじ・コネクタの嵌合・材質・質量・重心・強度・気流・計測性能を保証しません。重要な接続部は実機と最新の正規製品資料で確認してください。

外接寸法はモデル上の突起を含みます。メッシュ形式には曲面の近似誤差があります。CADで外形を参照する場合はSTEPを使用してください。画像・USDZの描画材質は、製品の材質・色を指定するものではありません。

### ライセンス

利用・再配布には[LICENSE](../LICENSE)が適用されます。共有時にはライセンス・注意事項を添付してください。[日本語訳](LICENSE.ja.md)も参照してください。

## English

The simplified ULSA EVO exterior reference is provided in STEP, STL, 3MF and USDZ formats. STL, 3MF and USDZ are approximate meshes converted from the included STEP. All formats preserve the same proportions.

| Format | Units | Up axis | Contents |
| --- | --- | --- | --- |
| STEP AP242 | mm | +Y | One valid solid; original coordinates retained |
| Binary STL | Import as mm | +Z | One closed mesh; the format does not store units |
| 3MF | mm, explicitly defined | +Z | One closed mesh and one build item; no printer or slicer settings |
| USDZ | m, at physical scale | +Y | One mesh and a neutral display material; for Apple viewers and AR |

STL and 3MF use a rigid +90-degree rotation about X, with the lowest point placed at Z=0. USDZ remains Y-up, with its lowest point at Y=0 and a uniform conversion from millimeters to meters. Use the same scale on all three axes when displaying the model.

### Limitations

This model supports exterior space planning and visualization. It is not a manufacturing drawing or a performance simulation model. Dimensions, tolerances, thread details, connector fit, material properties, mass, center of gravity, structural strength, airflow and measurement performance are not guaranteed. Confirm critical interfaces on actual hardware and current product documentation.

The file bounding box includes modeled protrusions. Mesh formats approximate curved surfaces. Use STEP for CAD reference. Rendering materials in images and USDZ do not specify the product's actual materials or colors.

### License

Use and redistribution are governed by [LICENSE](../LICENSE). Keep the license and notices when sharing the model. See the [Japanese translation](LICENSE.ja.md).
