## Message Board 
一個有登入機制的留言板

* [Demo](http://chihyu.tw/message-board/index.php)

* 管理員帳號密碼：admin_user/admin_user (可進入到管理員後台)

![Imgur](https://imgur.com/LkJRCu8.gif)

### 留言板功能
* 註冊、登入功能
* 編輯暱稱功能
* 使用者可以新增、編輯、刪除自己的留言
* 管理者可以新增、編輯、刪除所有留言
* 管理者可以設定權限(使用者、管理者、停權者)
* 停權者無法新增留言但可以編輯、刪除自己的留言
* 換頁功能

![Imgur image](https://imgur.com/Mvca70z.jpg)
![Imgur image](https://imgur.com/4Q0bbch.jpg)
![Imgur image](https://imgur.com/bLDLxxk.jpg)

### 使用技術
* 以 PHP 實作具備會員系統的留言板
* 使用 prepare statement 存取 MySQL 資料庫來防範 SQL injection
* 把留言板部屬到 AWS EC2 遠端主機
