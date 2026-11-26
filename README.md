# AutoDora V3.4.3 64 位元版（火珠修正）

原版 AutoDora V3.4.3 的 64 位元重包版本。

## 內容
- 補齊 arm64-v8a／x86_64 原生程式庫，可在只支援 64 位元 App 的 Android 裝置安裝執行。
- 修正「使用者符石設定」視窗中火珠點不到的問題（原版 adapter 每次更換 LayoutParams，導致 GridView 第一顆珠從未正確掛上視窗，點擊不會觸發）。

## 安裝
- 從 Releases 下載 `AutoDora-V3.4.3-64bit-firefix6.apk`。
- Android 14 以上以 adb 安裝需加參數：`adb install -r --bypass-low-target-sdk-block AutoDora-V3.4.3-64bit-firefix6.apk`
- 自動轉珠需要 root。

## 聲明
原程式著作權歸原作者所有。
