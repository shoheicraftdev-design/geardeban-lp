# GearDeban — 製品LP

iPhone アプリ「GearDeban（ギアデバン）」（内部名 CampGearLog）の製品紹介ページ。GitHub Pages で公開する想定。

- 公開URL: https://shoheicraftdev-design.github.io/geardeban-lp/ **公開済**（2026-08-24）
- App Store: **公開中**。`https://apps.apple.com/jp/app/geardeban-%E3%82%AE%E3%82%A2%E3%83%87%E3%83%90%E3%83%B3/id6800662584`
- サポート / プライバシーポリシー / 利用規約: https://shoheicraftdev-design.github.io/geardeban-support/

## 位置づけ

Sodato LP（`sodato-lp`）・えも日LP（`emo-diary-lp`）と同じく、**匿名ライン（note・Xで製品名を出さない）を維持したまま
アプリ名とストアURLを出せるチャネル**。ASC のマーケティングURLに設定する。
サポート・法務ページは別リポジトリ `geardeban-support` が持つ（ここには置かない）。

## 内容の版

**v1.2（2026-09-10 App Store 公開・現行版）に合わせて更新（2026-09-28・決裁 `d-yso5qm`）。** v1.2 で芯を
「所有ではなく生存」から**「持っているギアを把握できること」と「そのギアをどう使ったかが残ること」の2本**へ
言い直した（決裁 `d-mu06vo`）のに合わせ、title・meta・ヒーロー・芯の節を v1.2 のサブタイトル／プロモーション
テキスト／説明文の書き出しへ差し替え、節の並びを説明文の順（ギアの側から読める → ギア台帳 → 「使った」だけでなく
「持って行ったが使わなかった」も残せる）へ揃え、ギア台帳の節を追加した。
文言の正本: **この LP 自身**。ASC の説明文と揃えなくてよい（2026-10-05 CEO 決裁・全製品）。機能の事実関係はアプリ側を参照し、下の「文言のルール」の禁止事項は引き続き守る。機能の参照先:
`camp-gear-log/docs/appstore/v1.2-store-listing.md`・`docs/appstore/ver-1.2-submission.md`・`docs/01_product_vision.md`。
スクリーンショットは v1.2 で撮り直していない（ストアも v1.1 の組）ため v1.1 のまま。

経緯: v1.0 で作成 → 2026-08-24 に v1.1 へ差し替え → 2026-09-28 に v1.2 へ更新。

## 素材

`images/` のスクリーンショットは、アプリ側リポジトリ `camp-gear-log` の
`docs/appstore/screenshots/v1.1/iphone-6.5-1284x2778/`（v1.1 掲載用）を長辺640pxへ縮小したもの。
`shot-add.png`（ギアを追加）のみ v1.1 で再撮影されていないため、v1.0 の
`docs/appstore/screenshots/iphone-6.7-1284x2778/05_add-gear.png` をそのまま使用（この画面は v1.1 で変更なし）。
差し替える場合は元の 1284×2778 から作り直すこと。`appicon.png` は
`CampGearLog/Resources/Assets.xcassets/AppIcon.appiconset/app-icon-1024.png` の縮小（256px）。

2026-10-05: リデザイン(d-lb8tnx の後)に合わせ、写真入りの3枚(history/add/camp)を iPhone 14 Plus シミュレータ(1284×2778)で撮り直し、長辺640pxへ縮小。
写真は CEO 提供の素材(`hero.jpg`=焚き火、ギア・キャンプの写真3枚)。⚠️ シミュレータは写真の縮小版が生成されず一覧で「写真が見つかりません」になるため、
撮影ビルドだけ PhotoLibraryResolving に一時パッチ(cloud識別子を使わない・サムネイルも highQualityFormat)を当てた(コミットしていない。実機の挙動とは差がない)。

| ファイル | 元 |
| :--- | :--- |
| `shot-add.png` | **2026-10-05 LP用に撮影**（v1.2・ギアを追加・代表写真にランタン） |
| `shot-usage.png` | v1.1 `01_gear-usage.png`（持って行ったギアを記録・上部固定ボタン） |
| `shot-history.png` | **2026-10-05 LP用に撮影**（v1.2・ギア詳細・使用履歴・代表写真にファミリーテント） |
| `shot-category.png` | v1.1 `03_gear-list-category.png`（ギア台帳のカテゴリ単位表示） |
| `shot-camp.png` | **2026-10-05 LP用に撮影**（v1.2・キャンプの詳細・写真1枚） |
| `shot-master-edit.png` | v1.1 `05_master-edit.png`（マスタ編集・カテゴリ追加/並び替え） |

## 文言のルール（アプリ側 `docs/appstore/v1-store-listing.md` の禁止事項を継承）

書いてはいけない:

- **「完璧に管理」「もう忘れない」** … 誇大。忘れ物防止アプリではない
- **「ギアを減らせます」「無駄が分かります」** … 断定。記録が示すのは事実だけで、判断はユーザーがする
- 他アプリとの比較・優劣（固有名詞での名指し）

訴求の軸は v1.2 から「持っているギアの把握」と「どう使ったかの記録」の2本（決裁 `d-mu06vo`）。
「使わなかった」は記録の結果であって看板にしない（念のため／出番なしの記録機能そのものは残っている）。
