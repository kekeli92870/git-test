# 快速入門 - Git 版本管理與 GitHub 雲端專案管理服務
---
## Git 本機端專案管理基本操作
**初始化 Git Repository**  
`git init`  
**觀察 Repository 檔案追蹤狀況**  
`git status`  
**將檔案加入追蹤(Index)清單**  
`git add 檔案`  
`git add .`  
**建立一組版本更新**  
`git commit -m "版本更新訊息"`  
**查看分支(Branch)**  
`git branch`  
**列出版本庫的提交歷史記錄(以反向的時間順序)**  
`git log`  

## 上傳本機專案記錄到 GitHub 雲端專案
**查詢遠端的 Repository**  
`git remote -v`  
**加入遠端的 Repository**  
`git remote add 遠端空間的名稱 網址`  
`git remote add origin https://github.com/kekeli92870/git-test.git`  
**上傳到 GitHub 雲端專案空間**  
`git push 遠端空間的名稱 遠端空間的分支`  
`git push origin master`  
