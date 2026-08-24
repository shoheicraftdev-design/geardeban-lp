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

**v1.1（2026-08-24 App Store 公開・現行版）に合わせて作成。** カテゴリの一級市民化・同行スタイル/サイト種別の
ユーザー定義化・写真上限100枚（キャンプ1件あたり）を反映済み。当初 v1.0 で作成したものを、v1.1 公開を受けて
2026-08-24 に差し替えた。参照: `camp-gear-log/docs/appstore/v1.1-store-listing.md`

## 素材

`images/` のスクリーンショットは、アプリ側リポジトリ `camp-gear-log` の
`docs/appstore/screenshots/v1.1/iphone-6.5-1284x2778/`（v1.1 掲載用）を長辺640pxへ縮小したもの。
`shot-add.png`（ギアを追加）のみ v1.1 で再撮影されていないため、v1.0 の
`docs/appstore/screenshots/iphone-6.7-1284x2778/05_add-gear.png` をそのまま使用（この画面は v1.1 で変更なし）。
差し替える場合は元の 1284×2778 から作り直すこと。`appicon.png` は
`CampGearLog/Resources/Assets.xcassets/AppIcon.appiconset/app-icon-1024.png` の縮小（256px）。

| ファイル | 元 |
| :--- | :--- |
| `shot-add.png` | v1.0 `05_add-gear.png`（ギアを追加） |
| `shot-usage.png` | v1.1 `01_gear-usage.png`（持って行ったギアを記録・上部固定ボタン） |
| `shot-history.png` | v1.1 `02_gear-history.png`（ギア詳細・使用履歴） |
| `shot-category.png` | v1.1 `03_gear-list-category.png`（ギア台帳のカテゴリ単位表示） |
| `shot-camp.png` | v1.1 `04_camp-detail.png`（キャンプの詳細・サイト種別ユーザー定義） |
| `shot-master-edit.png` | v1.1 `05_master-edit.png`（マスタ編集・カテゴリ追加/並び替え） |

## 文言のルール（アプリ側 `docs/appstore/v1-store-listing.md` の禁止事項を継承）

書いてはいけない:

- **「完璧に管理」「もう忘れない」** … 誇大。忘れ物防止アプリではない
- **「ギアを減らせます」「無駄が分かります」** … 断定。記録が示すのは事実だけで、判断はユーザーがする
- 他アプリとの比較・優劣（固有名詞での名指し）

訴求の軸は「所有」ではなく「生存」——買ったギアが自分のキャンプで生き残ったか。主役は「使わなかった」。
