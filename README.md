
# 大悲行者

靈鷲山 · 觀音法門 · 大悲咒持誦記錄系統

[![React](https://img.shields.io/badge/React-18-blue)](https://reactjs.org/)

## 功能

✅ 每日持誦記錄  
✅ 累計總數即時顯示  
✅ 發願目標進度條  
✅ 大悲十心（滿 1000 遍起逐步解鎖）  
✅ 里程碑成就系統（1000 ~ 100000 遍）  
✅ 連續持誦天數  
✅ 月份明細查詢  
✅ Google 試算表同步  

## 畫面預覽

登入 → 儀表板 → 記錄持誦 → 解鎖十心 → 圓滿大悲行者

## 設定

1. 建立 Google 試算表與 Apps Script（提供 `getSummary`、`submitEntry`、`updateEntry`、`getMonthly`、`checkEntry` 等 API）
2. 修改 `index.html` 中的 `SCRIPT_URL`
3. 部署至靜態主機或直接開啟

## 技術細節

- 純前端 SPA，無須建置工具
- JSONP 跨域請求
- 使用 sessionStorage 記住登入狀態

## 授權

非商業用途 · 修行使用

---

願此功德，迴向法界眾生
