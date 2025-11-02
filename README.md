# ekuut.github.io

這個專案使用 [Hugo](https://gohugo.io/) 與 [DoIt](https://github.com/HEIGE-PCloud/DoIt) 主題，建立「數理筆記」靜態網站，並透過 GitHub Pages 自動部署。

## 快速開始

```bash
# 取得主題（初次使用需執行）
git clone https://github.com/HEIGE-PCloud/DoIt.git themes/DoIt

# 本地啟動開發伺服器
hugo server -D
```

## 多語言

網站預設語言為繁體中文，並提供英文與台語（台灣閩南語）介面與文章。可透過導覽列的語言切換器直接轉換。

## 部署

GitHub Actions 會在 `main` 分支有變更時自動執行 Hugo build，並將結果部署至 `gh-pages` 分支供 GitHub Pages 使用。
