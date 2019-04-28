# PDF__Kit
由於網路上很多PDF沒有目錄，自己暫時還沒找到一個小工具來"自動"生成目錄的，就做了這個 PDF_Kit

# 功能
1. 合併PDF
2. PDF生成目錄

# 使用說明
1. 如果是生成書籤，則至少說明目錄所在頁數和內容第一頁所在頁數，輸出原PDF的副本文件（* _copy.pdf）
2. 如果合併PDF，則按順序說明被合成的PDF所在路徑，輸出merge.pdf

![help](https://user-images.githubusercontent.com/48882710/56858991-d630d680-69b6-11e9-90fb-385f7a98962f.jpg)

# 運行注意事項：
1. 需要PyPDF2（1.23）庫，sudo pip3 安裝PyPDF2
2. 需要docopt（0.6.2）庫，sudo pip3 安裝docopt
3. 進入PDF目錄後，運行pk.py文件即可看到基本的命令，pk -h進一步查看命令

# 變更內容
# 環境
Windows10，Python3

# 功能
1. 移除掉原本的合併功能
2. 將LAST_PAGE_NUMBER的功能改成FIRST_PAGE_NUMBER
