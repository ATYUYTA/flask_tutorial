# Chatbot_Dev
--------------------------------------------

先  
>git clone https://github.com/ATYUYTA/chatbot_tutorial  

>cd chatbot_tutorial  

開啟環境流程(只供開發使用，只開啟jupyter跟mysql的container)  
>docker-compose up -d  

透過瀏覽器訪問jupyter  
http://本機ip:8888  

程式碼都放在code內，可以用Jupyter編輯  

以下是repo的資料夾結構  

code/  
>#開發組的程式碼  
>code.ipynb  
>#方便devops的開啟用成py檔  

mysql_init/  
>#devops組製作的初始化資料庫  
>init.sql  

mysql_data/  
>#裡面裝資料庫內的data  
>...  

README.md  #說明檔  
