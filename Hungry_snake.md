# 貪食蛇(Hungry snake) 🐍

## 目錄

- [簡介](#簡介)
- [功能](#功能)
- [使用方法](#使用方法)
- [開發細節](#開發細節)
- [貢獻](#貢獻)

## 簡介

貪食蛇是一個經典的街機遊戲，控制蛇吃到食物來增長身體。注意不要撞到牆壁或自己的身體。

## 功能

- 遊戲開始：在遊戲視窗中使用鍵盤「i、k、j、l」開始。
- 遊戲中離：在遊戲視窗中按下 ESC 鍵或右上角的遊戲視窗 X。
- 遊戲結束：當蛇撞到牆壁或咬到自己後遊戲結束。
- 遊戲時間：追蹤遊戲的時間，以秒計算。
- FPS(每秒幀數)：追蹤遊戲的運行速度及運動的平滑度。
- 蛇身計數器：顯示目前蛇的身體長度為多少。
- 得分統計：顯示目前的得分，當蛇吃掉果實會獲得相應分數。

## 使用方法

1. 使用鍵盤「i、k、j、l」分別控制蛇的上下左右移動。
2. 每吃掉一顆果實，蛇的身體會長大，蛇越大隻額外獎勵越高，但要注意不要咬到自己了。
3. 果實會在地圖上無限的生成，吃越多分數會越高，請盡可能地吃多一點吧!
4. 地圖上偶爾會出現金光閃閃的果實，因營養豐富且稀有，蛇會長的比較大，得分較高~
5. 若輸入法為中文或英文大寫，需切換成小寫英文即可正常操作移動。
6. 中途想離開可以按下X，或是ESC鍵。

## 開發細節

- 前端技術：HTML、CSS、JavaScript
- 後端技術：Flask 框架、Python
- 資料庫：SQL Server

## 貢獻

歡迎任何形式的貢獻！如果你想要貢獻，請遵循以下步驟：

1. **Fork 本儲存庫**：點擊 GitHub 頁面右上角的 "Fork" 按鈕。
2. **創建分支**：在你的儲存庫中創建一個新分支來開發你的變更。
```bash
git checkout -b feature-branch
```
3. **提交更改**：將你的變更提交到該分支。
```bash
git commit -m "Add some feature"
```
4. **推送到 GitHub**：將你的分支推送到 GitHub。
```bash
git push origin feature-branch
```
5. **開 Pull Request**：在 GitHub 上開一個 Pull Request，描述你的變更，等待維護者的審核與合併。