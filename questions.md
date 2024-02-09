# Questions

## Q: 使用 `virtualenv` 建立虛擬環境 #116
1.先確認有無安裝python (我是安裝python3) 指令輸入:  python3
2.輸入指令pip install <我的資料夾名稱>
3.我輸入mkdir microblog的資料件 cd microblog 移動到此資料夾
4.確定在此資料夾內 輸入python3 -m venv venv 前venv是建立一個虛擬環境  後venv是資料夾名稱
5.然後我輸入啟動指令 source vene/bin/activate
6.建立之後安裝 pip install flask 然後系統提到需要更新pip 按照升級指令做版本升級
7.終端輸入python3 啟動後 啟動成功會顯示>>> 後輸入 import flask 沒顯示其他東西成功
8.mkdir app 在裡面建立 名為init.py, routes.py(主頁路由) 後在app資料架外 建立 microblog.py(模組)
9.啟動flask前 設置環境變數導入 export FLASK_APP=microblog.py 輸入後 在輸入 flask run 
正常就會顯示 http:127.0.0.1:500/ 不正常就會顯示其他錯誤訊息

## Q: python-dotenv 如何使用？ #119
1.在終端虛擬環境輸入 flask run --port 5001
2.然後安裝 pip install python-dotenv
3.在microblog資料夾內 mkdir touch .flaskenv文件 在把FLASK_APP=microblog.py輸入
4.輸入flask run 即可查看有沒有成功 正常啟動代表成功
## Q: 如何使用 Flask-SQLAlchemy 連接上 MySQL？ #123
<!--SQLlite的連接方式 -->
1.Flask-SQLAlchemy 輸入 pip install Flask-SQLAlchemy （在vue環境安裝)
2.設定資料庫,建立資料庫模型,建立資料庫表.加入資料到資料庫, 更新資料庫中的資料 大致上這些就可以了
<!--MySQL連接方式 -->
1.導入了 SQLAlchemy 和 Flask 模組
2.創建了一個 SQLAlchemy 物件，用於與資料庫進行交互
3.創建了一個 Flask 應用程式物件
4.設定了應用程式的配置項，包括關閉追蹤修改和設定資料庫的連接 URI
5.初始化 SQLAlchemy 應用程式，將剛剛建立的 Flask 應用程式與 SQLAlchemy 連接起來
## Q: Flask-Migrate 如何使用？ #124

## Q: 如何使用 SQLAlchemy 下 Raw SQL？ #125

## Q: 如何用土炮的方式建立 Table？ #126

## Q: 什麼是密碼雜湊？如何使用 Python 實現？ #129