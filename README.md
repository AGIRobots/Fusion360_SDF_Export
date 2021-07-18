# Fusion360で作成したモデルからUnity Robotics Hubで使うためにカスタマイズしたURDFファイルを作成

# Fusion360 SDF Export
Fusion360からSDFファイルorURDFファイル+STLファイルを生成するスクリプトです

## 使用方法
![設定&注意](https://github.com/KobayashiRui/Fusion360_SDF_Export/blob/images/img0.png)

+ SDFを出力する場合はSDF_Export, URDFを出力する場合はURDF_Exportを使用
+ ドキュメントの設定から基本単位をmに変更
+ 各リンクはコンポーネントにまとめる→ボディがない状態に
    - リンクとしてのコンポーネント内に複数のコンポーネントやボディがあっても問題なし

**※現在は回転ジョイントのみ対応しています**

## バグや追加機能について
バグや追加機能の要望,説明についてはissueに投げるか[Twitterアカウント](https://twitter.com/3pLiendefamille)に気軽にご連絡ください

## 機能追加予定
- [ ] 各ジョイントへの対応
- [ ] SDF_ExportとURDF_Exportの統合
- [x] URDF出力機能の追加
- [ ] URDFのgazebo用設定の追加