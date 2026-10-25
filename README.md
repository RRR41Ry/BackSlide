# BackSlide

A lightweight Dalamud plugin for **Final Fantasy XIV (FFXIV)** that lets you simulate short W (forward) and S (backward) key presses using in-game macros.

Designed for controller players who want precise forward and backward movement without accidental diagonal inputs.

## Features

- Simulate W and S key presses using in-game macros.
- Customize key press duration from **0.05 to 0.99 seconds**.
- Automatically release the key after the specified duration.
- Supports forward, backward, and stop commands.
- Compatible with controller cross hotbars.
- No additional configuration window required.

## Installation

1. Launch FFXIV using XIVLauncher with Dalamud enabled.
2. Open the chat window and enter `/xlsettings`.
3. Navigate to the **Experimental** tab.
4. Find **Custom Plugin Repositories**.
5. Add the following repository URL:

   `https://raw.githubusercontent.com/RRR41Ry/BackSlide/main/repo.json`

6. Click the **+** button and make sure the repository is enabled.
7. Click **Save**.
8. Enter `/xlplugins` in the chat window.
9. Search for **BackSlide** under **All Plugins**.
10. Click **Install**.

## Commands

### Move Backward (S Key)

Press S for 0.1 seconds:

```text
/backslide 0.1
```

### Move Forward (W Key)

Press W for 0.1 seconds:

```text
/forwardslide 0.1
```

### Stop Movement Input

Release any movement key currently held by BackSlide:

```text
/slidestop
```

### Custom Duration

You can specify any duration between **0.05 and 0.99 seconds**.

Examples:

```text
/backslide 0.05
/backslide 0.2
/backslide 0.5
/forwardslide 0.3
```

If no duration is specified, the default is **0.5 seconds**.

## Controller Setup

1. Open **User Macros** in FFXIV.
2. Create a new macro.
3. Enter a BackSlide command, such as:

   ```text
   /backslide 0.1
   ```

4. Assign the macro to your cross hotbar.
5. Press the assigned controller button to execute it.

This allows precise forward or backward movement without using the analog stick.

## Notes

- Designed for Windows.
- Actual input duration may vary slightly depending on frame rate and system performance.
- Test the plugin in a safe area before using it during gameplay.
- This is an unofficial third-party plugin and is not affiliated with or endorsed by Square Enix.
- Using third-party plugins may violate the FFXIV Terms of Service. Use at your own risk.
- Compatibility with all Dalamud versions is not guaranteed.

## Version

**v0.1.0.0**

## Credits

Developed for the FFXIV Dalamud plugin ecosystem.

Inspired by existing keyboard input handling implementations in the Dalamud community.


--------------------------------------------------------------------------------
# BackSlide

FF14（FINAL FANTASY XIV）用のDalamudプラグインです。

ゲーム内のマクロから、Wキー（前進）またはSキー（後退）を短時間だけ入力できます。

コントローラー操作時に、スティックの斜め入力を避けて前後に移動したい場合などに使用できます。

## 主な機能

- マクロからWキー・Sキーの入力を実行
- 入力時間を0.05～0.99秒の範囲で指定可能
- 指定した時間が経過すると自動的にキーを解除
- 前進・後退・入力停止の3種類のコマンドに対応
- ゲーム内のホットバーにマクロを登録して、コントローラーから操作可能

## インストール方法

1. XIVLauncherとDalamudを導入したFF14を起動します。
2. チャット欄に `/xlsettings` と入力します。
3. 上部の「試験的機能（Experimental）」を開きます。
4. 「カスタムプラグインリポジトリ」に以下のURLを追加します。

   `https://raw.githubusercontent.com/RRR41Ry/BackSlide/main/repo.json`

5. 右側の「＋」を押し、Enabledにチェックを入れます。
6. 「Save」を押します。
7. チャット欄で `/xlplugins` と入力します。
8. 「すべてのプラグイン」から `BackSlide` を検索してインストールします。

## マクロの使い方

**後退（Sキーを0.1秒入力）**

```text
/backslide 0.1
```

**前進（Wキーを0.1秒入力）**

```text
/forwardslide 0.1
```

**入力を停止**

```text
/slidestop
```

入力時間を省略した場合は0.5秒です。

例えば、`/backslide 0.3` と入力すると、Sキーを約0.3秒間入力します。

## コントローラーで使用する方法

1. FF14のメインコマンドから「マクロ管理」を開きます。
2. 新しいマクロを作成します。
3. `/backslide 0.1` などのコマンドを登録します。
4. マクロをクロスホットバーに配置します。
5. コントローラーからマクロを実行します。

## 注意事項

- Windows版FF14向けです。
- 非公式プラグインの利用はFF14の利用規約上のリスクがあります。
- キー入力の持続時間は、ゲームのフレームレートや処理状況によって多少変動する可能性があります。
- 使用する前に、通常フィールドなど安全な場所で動作を確認してください。
- 開発者用環境で動作を確認したバージョンを基にした配布です。すべての環境での動作を保証するものではありません。

## バージョン

v0.1.0.0

