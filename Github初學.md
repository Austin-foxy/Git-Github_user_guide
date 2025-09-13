初次見面，Github!

#終端機的基礎操作說明：
1.git --version
//顯示git當前版本
2.git config --gloabal user.name "姓名"
//設定姓名
3.git config --gloabal user.email "信箱(...@gmail.com)"
//設定信箱
4.git init
//設定隱藏.git資料夾(儲存檔案歷史與備份紀錄)
5.clear
//清空螢幕內容

#檔案相關內容：
1.git status
//檢查當前目錄中每個檔案的狀態
2.git add 檔案名稱.md
//將未追蹤(U)檔案改成已追蹤(A)
//檔案名稱可改用"*"，代表所有副檔名為md的文件
//也可直接將"檔案名稱.md"直接改為"."，代表將所有變更放到暫存區
3.git commit -m "簡短訊息"
//提交檔案並附加額外說明訊息
4.git log
//列出先前提交歷史
5.git log --oneline
//git log指令簡化版