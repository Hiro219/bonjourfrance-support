# Bonjour, France サポートサイト

App Store の「サポートURL」「プライバシーポリシーURL」に出すための静的ページ。
GitHub Pages で公開する（リポジトリ: Hiro219/bonjourfrance-support）。

| ページ | URL |
|---|---|
| トップ | https://hiro219.github.io/bonjourfrance-support/ |
| サポート | https://hiro219.github.io/bonjourfrance-support/support.html |
| プライバシーポリシー | https://hiro219.github.io/bonjourfrance-support/privacy.html |

## 直すとき

HTML を書き換えて push すれば、1〜2分で反映される。

アプリの仕様を変えたら、次の箇所も合わせて直すこと。

- `privacy.html` の「3. 端末内に保存される情報」… `GameState` / `AudioManager` で保存する項目が増減したとき
- `support.html` のよくあるご質問 … 操作、ひとやすみ、音の鳴り方（マナーモード・他アプリとの混ざり方）、時間帯の進み方
- どちらも冒頭の「最終更新日」

配色はアプリ本体（`Core/Palette.swift` の `#FBF4E6` / `#2B3A4A` / `#C0483E` / `#2F5D88`）に合わせてある。
