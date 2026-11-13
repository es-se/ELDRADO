# ELDRADO layered battle prototype

## 起動
`index.html` をブラウザで開いてください。既存フィールド試作を残し、戦闘画面を5レイヤー構造に変更しています。

## 5レイヤー
1. `assets/battle_background.svg` — 背景のみ（キャラクター/UIなし）
2. `assets/fel.svg` — フェル独立スプライト
3. `assets/alice.svg` / `assets/alice_link.svg` — アリス通常・リンク状態。リンク値に応じて切替
4. `assets/mob.svg` — 敵MOB独立スプライト
5. `assets/battle_interface.svg` + HTML/CSS — 下段インターフェースの枠素材。HP・コマンド・戦闘ログはHTMLで動的管理

## 今回の変更
- 味方を左、MOBを右へ配置。
- 戦闘背景からキャラクターとUIを分離。
- フェル、アリス、MOBは独立した画像要素。
- HPバーを味方/敵の下段パネルに配置。敵HPを頭上に表示しない。
- AUTO表示と戦闘ログを独立要素に変更。

※キャラクター素材は現段階ではレイヤー配置と切替確認用の仮素材です。確定済みのキャラクター立ち絵に差し替える前提です。
