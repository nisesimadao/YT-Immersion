# YT Immersion (Beta)

YT Immersion は、YouTube のミュージックビデオを歌詞中心のプレイヤー表示へ切り替える Chrome 拡張機能です。半透明の UI、歌詞表示、専用プレイヤーを組み合わせ、通常の YouTube とは異なる再生画面を提供します。

YT Immersion is a Chrome extension that turns YouTube music videos into a lyrics-focused player. It combines a translucent interface, lyric display, and alternate playback views without replacing YouTube itself.

## 主な機能 / Features

### 歌詞表示 / Lyrics

- **歌詞中心の表示 / Lyrics-focused view**
  - 楽曲の進行に合わせた歌詞表示とオートスクロールに対応します。
  - Displays lyrics with automatic scrolling during playback.
- **2 言語表示 / Dual-language display**
  - 原文と訳詞の同時表示と切り替えに対応します。
  - Supports displaying and switching between original and translated lyrics.

### 画像作成 / Capture tools

- **ベストショット撮影 / Best-shot capture**
  - バースト撮影したフレームから、ブレの少ない画像を選択します。
  - Captures multiple frames and selects a clearer result.
- **チェキ風画像作成 / Instax-style card creator**
  - 撮影したフレームに任意の歌詞を添え、カード画像として保存できます。
  - Adds selected lyrics to a captured frame and saves it as a card-style image.

### プレイヤー表示 / Player modes

- **iPod 風 PiP / iPod-style PiP**
  - iPod を模した操作 UI を持つ PiP プレイヤーです。
  - A picture-in-picture player with controls inspired by classic iPod layouts.
- **レコードモード / Record mode**
  - アナログレコードをモチーフにした再生画面です。
  - An alternate playback view styled after a vinyl record player.

## インストール / Installation

1. [Releases](../../releases) から最新の配布物をダウンロードし、展開します。  
   Download the latest release and extract it.
2. Chrome で `chrome://extensions/` を開きます。  
   Open `chrome://extensions/` in Chrome.
3. 「デベロッパーモード」をオンにします。  
   Enable **Developer mode**.
4. 「パッケージ化されていない拡張機能を読み込む」を選び、展開したフォルダを指定します。  
   Choose **Load unpacked** and select the extracted folder.

## 使い方 / Usage

1. YouTube でミュージックビデオを開きます。  
   Open a music video on YouTube.
2. サイドパネルの「文字起こしを表示」から歌詞データを読み込みます。  
   Use **Show transcript** in the side panel to load lyric data.
3. プレイヤー下の「MV モード」ボタンから YT Immersion を起動します。  
   Start YT Immersion with the **MV Mode** button below the player.
4. 「閉じる」ボタンまたは `Esc` キーで終了します。  
   Exit with the close button or the `Esc` key.

## 対応について / Compatibility

YT Immersion は YouTube の Web UI に依存しています。YouTube 側の DOM やプレイヤー仕様が変更された場合、一部機能が動作しなくなる可能性があります。

YT Immersion depends on YouTube's web interface. Changes to YouTube's DOM or player behavior may temporarily break some features.

## 免責事項 / Disclaimer

- **プライバシー / Privacy** — 本拡張機能には、利用者の個人情報を独自に収集・送信することを目的とした機能はありません。 / The extension is not designed to independently collect or transmit users' personal information.
- **非公式 / Unofficial** — 本プロジェクトは個人制作物であり、Google LLC および YouTube とは関係ありません。 / This project is not affiliated with Google LLC or YouTube.
- **保証 / Warranty** — 本ツールは無保証で提供されます。 / The software is provided without warranty.

## ライセンス / License

MIT License  
Copyright (c) 2025 Naikaku
