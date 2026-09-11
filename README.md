# Kids 3D Playgrand

iPad / browser向けの子ども用3D工作アプリです。

- App: https://plzsayyes3.github.io/kids-3d-playgrand/
- Manual: https://plzsayyes3.github.io/kids-3d-playgrand/manual.html

## Features

- 起動時に立方体を1個表示
- 箱・球・円柱・円錐を追加
- 移動・回転・拡大縮小
- コピー・削除
- 「つける」と「きりぬく」のシンプルなモード切替
- 赤い切り抜き形を重ねて、Boolean subtraction の結果だけを残す
- 切り抜き後も既存パーツは個別編集可能
- 地面までつながっているか判定
- 条件を満たしたときだけSTL出力
- iPad Safari向けタッチ操作・Safe Area・画面回転対応
- カメラ操作とタップ選択が競合しにくいタッチ判定

## Cutout

1. `− きりぬく` を選ぶ
2. 箱・球・円柱・円錐から赤い切り抜き形を置く
3. 本体へ少し重ねる
4. `✂ きりぬく！` を押す

重なった本体パーツごとに subtraction を実行し、切り抜き形は消えて結果形状だけが残ります。
STLは画面上に残っている完成形から出力します。

## Manual

`manual.html` に、子ども向けの操作説明と保護者向けのSTL出力・トラブルシューティングをまとめています。

## Run

`index.html` を静的ホスティングしてください。
GitHub Pagesでは main branch / root を公開元に設定します。
