創建一個資料夾

mkdir node    // node 為資料夾名稱

git init 初始化

創建一個 .gitignore 因為有些檔案是不準備進去版本控制的

git add . -> 

git commit -m "新增環境" -> 

git branch dev 避免檔案蓋過master(main) ->

git remote add origin https://github.com/0oWeiYuo0/gitHubFlowRule.git 開啟 gitHub 專案後會有 push 的指令，複製即可 ->

git push origin dev 若有創建分支，記得上傳 // dev 為名稱

git checkout "dev" 切換至分支 // dev 為分支名稱

git checkout -b "分支名稱" 創建新分支並切換到新分支

合併後若出現衝突用 git checkout -b "change_site" 先創建一個分支，把內容修改完成後再切回 main 合併剛剛修改內容的檔案"change_site"，防止內容勿刪

=========================================

另個開發人員

git clone "#################"  複製檔案

