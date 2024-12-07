# 狀態
- git status

# 站在攝影棚
- git add .
- git add *.副檔名
- git add 完整檔名
- git add --all
# 快照
- git commit -m "訊息"

# log
- git log 

# 簡短 log
- git log --oneline

# 比對差異
- git diff 序號
- git diff 序號 檔名

# HEAD 指向 某個 紀錄
- git checkout 序號
- git checkout master

# 還原
- git checkout 序號 檔名
<!-- 最後要 commit 才算完成 -->

# 還原並捨棄
- git reset --hard 序號

# 刪除檔案
<!-- 最後也要 add、commit -->

# 忽略檔案清單
<!-- 新增 .gitignore -->
<!-- 最後也要 add、commit -->


# 第一次上傳到 github
 - git remote add origin https://github.com/k000033/test.gi 
 <!-- remote 遠端
 add 新增
 origin 遠端儲存庫名稱 -->

 - git branch -M main 
 <!-- branch 分支管理
 -M 重新命名
 main 新的分支名稱  -->

- git push -u origin main
<!-- push 推送
-u 建立關聯
origin 遠端儲存庫名稱
main 本地名稱 -->

## 第二次上傳 github
- git add 
- git commit -m "訊息"
- git push


# 將檔案拉下來 
- git clone 網址

# 建立並切換分之
- git checkout -b develop

# 查看分支
- git branch

# 同步檔案
- git pull

# 名詞
## master
- 主線任務
## HEAD
- 目前進度
