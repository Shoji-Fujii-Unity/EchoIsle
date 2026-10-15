# Echo Isle: Tideglass Lock / 残響島：潮鎖の解錠

A single-file, browser-based, point-and-click escape game.
単一のHTMLファイルだけで動く、ブラウザ上のポイント＆クリック型脱出ゲーム。

This README is written in English and Japanese in one file.
このREADMEは1つのファイルの中に、英語と日本語の両方を含みます。

---

## English

### Game title

**Echo Isle: Tideglass Lock**

### File information

The game is saved as:

index.html

It is a single HTML file. No CSS file, no JavaScript file, no image file, no audio file, and no game engine are required.

### Overview

You wake up on a shore with your small boat wrecked behind you.  
A lighthouse glows faintly on the far cliff.  
A transparent tideglass barrier seals the sea road around the island.

Explore the shore, jungle, cave, lagoon, ruins, and lighthouse.  
Find keys, lenses, ropes, lights, and hidden mechanisms.  
Activate the lighthouse and break the tideglass lock.

### How to open the game

1. Place the game file in a folder.
2. Make sure the game file is named:
   index.html
3. Open the file with a modern desktop browser:
   Google Chrome
   Microsoft Edge
   Firefox
   Safari
4. On a smartphone or tablet, use a modern browser.
5. Rotate the device to landscape mode.
6. The game displays in a 16:9 frame for both desktop and mobile.

If your browser restricts file access or local storage, open the game through a local web server instead of opening the file directly. You can use any local web server.

### Controls

Use one of the following input methods:

- Mouse click
- Touch tap
- Stylus tap

In the scene:

- Tap or click objects to investigate them.
- Tap highlighted hotspots to interact.
- Use arrows on the screen edges to move between locations.

In the top bar:

- Language button: switch between Japanese and English.
- Sound button: turn sound on or off.
- Save button: save the current game data.
- Load button: load the last saved game data.
- Title button: return to the title screen.
- Fullscreen button: request fullscreen mode if the browser allows it.

In the bottom area:

- Inventory buttons show the items you have.
- Tap an item to read its name.
- Use items by clicking the correct object in the scene.

### Sound

The game has sound effects.  
They are generated with Web Audio, so no external audio files are used.

If sound does not start immediately:

1. Click or tap the game scene once.
2. Press the sound button and set it to ON.
3. Make sure the system volume is not muted.

### Save data

The game saves data inside your browser.

Two local storage keys are used:

- game save key: tideglass_isle_save
- settings key: tideglass_isle_settings

The game also saves automatically after many actions.  
Manual saving is available from the top bar.

Saved data stays in the same browser and the same site or file origin.  
If you use another browser, another device, another profile, or incognito/private mode, the save may not be visible.

To clear the save:

- Clear site data or cookies for this game.
- Or remove browser local storage for this page.
- Or start a new game from the title screen.

### Compatibility

The game is intended to work in modern browsers:

- Chrome
- Edge
- Firefox
- Safari
- Chromium-based mobile browsers
- Safari on iPhone and iPad

It is optimized for landscape display.  
Portrait mode can still work, but the game will be letterboxed and harder to play.

### Basic gameplay hint

A possible route:

1. On the shore, find a sharp shell shard.
2. Use the shell shard on the netted crate to get an iron key.
3. Open the sea chest to get a lantern.
4. A message bottle may give a clue for the ruins.
5. Go to the jungle.
6. Use the shell shard on the vines to get a rope.
7. Use the shell shard on the pack to get goggles.
8. Enter the cave with the lantern.
9. In the cave, use the rope on the lever to lower the water.
10. Take the blue lens and find the hidden wave key after the lever is operated.
11. Go to the lagoon.
12. Pick up the reed tube.
13. Use goggles and the reed tube to inspect the submerged crate.
14. Use the rope to pull the crate out and get the pearl key.
15. Use the wave key on the ruins door.
16. In the ruins, read the tablet if you have the bottle.
17. Solve the three stone pillars.
18. The safe rune pattern is:
   left open
   middle open
   right closed
19. Put the blue lens on the altar to reveal the red prism.
20. Combine the blue lens and red prism into the tideglass lens.
21. Go to the lighthouse.
22. Insert the tide key.
23. Insert the pearl key.
24. Mount the tideglass lens.
25. Activate the beacon.

### Privacy

The game runs entirely in your browser.  
It does not require an account.  
It does not send your progress to a game server.  
All data stays in your local browser storage.

### Troubleshooting

The game does not open:

- Rename the file to:
  index.html
- Make sure the file is an HTML file and not a text file with an extra hidden extension.
- Open it with a desktop browser first.

The game does not save:

- Do not use incognito or private mode.
- Use the same browser and the same file path or website origin.
- Enable site storage.
- Try opening the game through a local web server.
- If the browser asks whether to allow storage, allow it.

The sound does not work:

- Press the sound button.
- Click or tap the screen once to allow browser audio.
- Check system mute, volume, and media volume.
- Some browsers block sound until the user interacts with the page.

The screen is too small on mobile:

- Rotate the device to landscape.
- Use fullscreen if the browser allows it.
- Use a modern browser with good viewport support.

The language is wrong:

- Use the language button in the top bar.
- The game also tries to use your browser language on first load.

The game cannot be resized or fullscreened:

- Use the fullscreen button.
- If it fails, use the browser menu.
- Some browsers require fullscreen to be triggered by a user tap or click.

### Notes about implementation

The scenes are drawn with SVG.  
The interface is built with HTML and CSS.  
The game logic is built with JavaScript.  
Sound effects are synthesized with Web Audio.  
Save data is stored with localStorage.

There are no required external assets.

---

## 日本語

### ゲームタイトル

**残響島：潮鎖の解錠**

### ファイル情報

ゲームファイル名は次の通りです。

index.html

このゲームは単一のHTMLファイルだけで動作します。  
CSSファイル、JavaScriptファイル、画像ファイル、音声ファイル、ゲームエンジンなどは必要ありません。

### 概要

あなたは浜辺で目を覚ましました。  
小さなボートは壊れ、遠い崖の上の灯台だけが仄かに光っています。  
その周囲には透明な「潮ガラスの結界」があり、島への海路が封じられています。

浜辺、密林、洞窟、潟湖、遺跡、灯台を調査してください。  
鍵、レンズ、ロープ、明かり、隠された機構を見つけてください。  
灯台を起動し、結界を破って脱出してください。

### 開き方

1. ゲームファイルをフォルダに置きます。
2. ファイル名が次のようになっていることを確認してください。
   index.html
3. モダンなデスクトップブラウザで開きます。
   Google Chrome
   Microsoft Edge
   Firefox
   Safari
4. スマートフォンやタブレットでは、対応ブラウザを使ってください。
5. 端末を横向きにしてください。
6. ゲームはデスクトップでもスマホでも横長16:9の枠で表示されます。

ブラウザがファイル読み込みやローカルストレージを制限する場合は、ファイルを直接開くのではなく、ローカルサーバー経由で開いてください。  
どのローカルサーバーを使っても構いません。

### 操作方法

次の操作に対応しています。

- マウスクリック
- タッチタップ
- スタイラスタップ

ゲーム画面では:

- オブジェクトをタップまたはクリックして調査します。
- ハイライトされた場所をタップして操作します。
- 画面端の矢印を押すと場所を移動します。

上部バーでは:

- 言語ボタン: 日本語と英語を切り替えます。
- サウンドボタン: 効果音のON/OFFを切り替えます。
- 保存ボタン: 現在のゲームデータを保存します。
- 読込ボタン: 最後に保存したデータを読み込みます。
- タイトルボタン: タイトル画面に戻ります。
- 全画面ボタン: ブラウザが許可している場合、全画面表示を要求します。

下部エリアでは:

- 所持アイテムが表示されます。
- アイテムをタップすると名前を確認できます。
- アイテムの利用は、正しいオブジェクトをタップすることで行われます。

### サウンド

このゲームには効果音があります。  
効果音はWeb Audioで生成されています。  
外部音声ファイルは不要です。

音が出ない場合:

1. ゲーム画面を一度タップまたはクリックしてください。
2. サウンドボタンを押してONにしてください。
3. システム音量がミュートでないか確認してください。

### セーブデータ

ゲームデータはブラウザ内に保存されます。

使用されるローカルストレージキーは次の通りです。

- ゲームデータキー: tideglass_isle_save
- 設定キー: tideglass_isle_settings

多くの操作後に自動保存も行われます。  
手動保存も上部バーから可能です。

セーブデータは、同じブラウザで同じファイルまたは同じサイト情報からアクセスした場合に復元されます。  
別のブラウザ、別の端末、別のプロファイル、シークレットモードでは、セーブデータが表示されないことがあります。

セーブデータを消したい場合は:

- このページのサイトデータやCookiesを消してください。
- またはブラウザのローカルストレージを削除してください。
- またはタイトル画面から新規スタートを選んでください。

### 動作環境

モダンなブラウザでの動作を想定しています。

- Chrome
- Edge
- Firefox
- Safari
- Chromium系モバイルブラウザ
- iPhone/iPadのSafari

ゲームは横長画面で遊ぶことを前提に設計されています。  
縦画面でも動作しますが、上下に黒帯が入り、操作しにくくなります。

### 基本攻略ヒント

一通りの進み方:

1. 浜辺で鋭い貝殻を拾う。
2. 貝殻で網を切って鉄の鍵を入手する。
3. 海の宝箱を開けてランタンを入手する。
4. 瓶の地図は遺跡の重要なヒントになる。
5. 密林へ移動する。
6. 貝殻で蔓を切ってロープを入手する。
7. 貝殻で袋を切り開いて水中メガネを入手する。
8. ランタンのある状態で洞窟に入る。
9. 洞窟でロープを使って石のレバーを操作し、水位を下げる。
10. 青いレンズを取る。
11. レバー操作後、隠し区画から波型の鍵を入手する。
12. 潟湖へ移動する。
13. 呼吸管を拾う。
14. 水中メガネと呼吸管を使って沈んだ木箱を調査する。
15. ロープを使って木箱を引き寄せ、真珠の鍵を入手する。
16. 波型の鍵で遺跡の扉を開ける。
17. 遺跡で瓶の地図を持っていれば石板を読む。
18. 三つの石柱を解く。
19. 正しい石柱の組み合わせは次の通り:
   左 開
   中央 開
   右 閉
20. 青いレンズを祭壇に置いて赤いプリズムを出現させる。
21. 青いレンズと赤いプリズムを組み合わせて潮ガラスのレンズにする。
22. 灯台へ移動する。
23. 潮の鍵を灯台制御装置に差し込む。
24. 真珠の鍵を差し込む。
25. 潮ガラスのレンズを焦点リングに取り付ける。
26. 制御レバーを引いて結界を破る。

### プライバシー

ゲームはすべてブラウザ内で動作します。  
アカウント登録は不要です。  
プレイデータをゲームサーバーへ送ることはありません。  
データはすべてブラウザのローカル保存に保持されます。

### トラブルシューティング

ゲームが開かない:

- ファイル名を次のようにしてください。
  index.html
- 余分な拡張子が付いてテキストファイルになっていないか確認してください。
- まずデスクトップブラウザで開いてください。

ゲームが保存されない:

- シークレットモードやプライベートモードを避けてください。
- 同じブラウザ、同じファイルパス、同じサイト情報から開いてください。
- サイトのストレージを許可してください。
- ローカルサーバー経由で開いてください。
- ブラウザがストレージ利用を尋ねた場合は許可してください。

サウンドが鳴らない:

- サウンドボタンをONにしてください。
- 画面を一度タップまたはクリックしてください。
- システム音量、メディア音量、ミュートを確認してください。
- 一部のブラウザは、ユーザー操作があるまで音声を許可しません。

スマホで画面が小さい:

- 端末を横向きにしてください。
- 可能なら全画面ボタンを使ってください。
- モダンブラウザで表示してください。

言語が切り替わらない:

- 上部バーの言語ボタンを使ってください。
- 初回はブラウザ言語に合わせて自動選択される場合があります。

全画面表示できない:

- 上部バーの全画面ボタンを押してください。
- 失敗した場合はブラウザメニューを使ってください。
- 全画面はユーザー操作が必要になる場合があります。

### 実装メモ

シーン画像はSVGで描画されています。  
操作画面はHTMLとCSSで構成されています。  
ゲームロジックはJavaScriptで実装されています。  
効果音はWeb Audioで合成されています。  
セーブデータはlocalStorageで保存されています。

外部ファイルは一切不要です。