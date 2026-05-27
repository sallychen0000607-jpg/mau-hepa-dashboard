# MAU HEPA 更換警報系統

這是可直接部署到 Vercel 的 React/Vite 專案。

## 本機測試

```bash
npm install
npm run dev
```

## 部署到 Vercel

1. 將整個資料夾上傳到 GitHub repository
2. 到 Vercel 選擇 Import Project
3. 選擇此 GitHub repo
4. 按 Deploy

## 支援資料格式

Excel/CSV 欄位需包含：

- TimeStamp
- Out_TT
- Out_MT
- MAUC01_KW, MAUC01_FREQ, MAUC01_HEPAPT, MAUC01_ColdPT, MAUC01_FilterPT
- 依此類推 MAUC02 ~ MAUC08
