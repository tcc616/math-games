# math-games — AGENTS.md

## 專案入口

專案名稱：math-games
專案用途：建立一個數學遊戲總專案，專門收納各式各樣跟數學有關的遊戲。各個遊戲為附屬此專案的分支、子資料夾或後續模組。
主要工作目錄：G:\我的雲端硬碟\math-games
GitHub repo：https://github.com/tcc616/math-games
預設 branch：main

## Obsidian 對應筆記

Obsidian vault：C:\Users\張達偉\Documents\Obsidian 使用指南
專案駕駛艙：math-games/專案工作流程.md
收工時優先更新：同上

> 注意：專案駕駛艙是 Obsidian vault 裡的一篇筆記，不是工作資料夾裡的 Markdown 檔。

## 工作桌 + 三個家

- 工作桌：G:\我的雲端硬碟\math-games
- GitHub：https://github.com/tcc616/math-games
- Obsidian：C:\Users\張達偉\Documents\Obsidian 使用指南 + math-games/專案工作流程.md
- Firebase：未使用；等第一個需要資料庫的遊戲再設定

## 同步規則

開工時：
- 使用 `startup-sync` 流程
- 讀本檔
- 讀 Obsidian 駕駛艙
- 檢查 Git 狀態
- 不自動 pull / commit / push

收工時：
- 使用 `shutdown-sync` 流程
- 更新 Obsidian 駕駛艙
- 如規則、路徑、專案邊界改變才更新本檔
- 需要時 commit + push GitHub

新專案初始化時：
- 使用 `project-init-sync` 流程

## 專案結構原則

- 每個數學遊戲放在獨立資料夾，例如 `games/<game-name>/`。
- 共用素材、共用元件或共用工具放在 `shared/`。
- 每個遊戲應有自己的簡短說明，包含玩法、學習目標與入口檔。
- 若使用學生資料，只能使用座號與班級代號，不存真名。

## 主要檔案

入口檔：games/九九乘法遊戲/index.html
設定檔：尚未建立
部署位置：GitHub Pages，尚未啟用

## 不要做

- 不要把每日進度寫進 AGENTS.md
- 不要自動納入無關 git 變更
- 不要把 API key、token、密碼寫進 repo
- 不要儲存學生姓名；正式資料只用座號與班級代號
