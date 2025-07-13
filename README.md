# 🎬 字幕順稿小工具 (SRT Tool)

一個智能的中文字幕修正工具，專門用於修正AI語音轉字幕時的常見錯誤。

## 🌟 功能特色

- **智能錯誤修正**：自動識別和修正常見的中文同音字錯誤
- **專有名詞保護**：優先識別劇本中的人名、地名等專有名詞
- **片段化處理**：處理被切分的短字幕片段
- **即時預覽**：修正前後對比預覽
- **文件下載**：支援下載修正後的字幕檔和修正報告

## 🚀 在線使用

**直接使用工具：** https://pokemongamer410.github.io/srttool/subtitle-editor.html

## 📖 使用方法

1. **上傳劇本文件**：選擇 `.txt` 格式的劇本文件
2. **上傳字幕文件**：選擇 `.srt` 格式的字幕文件
3. **開始處理**：點擊「開始處理字幕」按鈕
4. **預覽結果**：查看修正前後的對比
5. **下載文件**：下載修正後的字幕檔

## 🔧 技術特點

- **多層匹配算法**：字符級修正 + 子字符串匹配 + 句子級匹配
- **同音字識別**：內建中文同音字對照表
- **滑動窗口搜索**：精確匹配劇本片段
- **純前端實現**：無需服務器，支援離線使用

## 📋 支援格式

- **劇本格式**：`.txt` 文本文件
- **字幕格式**：`.srt` 字幕文件

## 🎯 常見修正案例

- `蘇秦` → `蘇晴`
- `抒情` → `蘇晴`
- `高危` → `高偉`
- `死記` → `死寂`
- `angel` → `天使`
- 更多語音識別錯誤...

## 🔍 如何查看網址

### 方法一：GitHub Pages 設定頁面
1. 進入 [GitHub Repository](https://github.com/pokemongamer410/srttool)
2. 點擊 `Settings` 標籤
3. 在左側選單點擊 `Pages`
4. 在頁面上方會顯示你的網站 URL

### 方法二：GitHub Repository 主頁
1. 進入 [GitHub Repository](https://github.com/pokemongamer410/srttool)
2. 在右側 "About" 區域會顯示網站連結（如果有設定的話）

### 方法三：記住格式
```
https://你的用戶名.github.io/repo名稱/
https://pokemongamer410.github.io/srttool/
```

## 📝 開發說明

本工具使用純 HTML、CSS、JavaScript 開發，無需額外依賴，可直接在瀏覽器中運行。

## 📄 授權

本專案使用 MIT 授權條款。

---

🤖 Generated with [Claude Code](https://claude.ai/code)