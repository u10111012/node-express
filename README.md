# node-express

# 前端
```
cd client
npm install
npm start
```

# 後端
```
cd server 
npm install
npm run devStart
```

#資料庫
```
ps -ef | grep mysql #確認是否運行
初次設定需重新設定密碼並清洗權限
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '你的新密碼'; # 重設密碼
flush privileges; #清洗權限
exit #退出
```

#打開與關閉mysql
```
mysql.server start
mysql.server restart
mysql.server stop
```
```
mysql -u root -p #進入資料庫
show databases; #查看資料庫
create database employee; #建立資料庫
use employ; #使用資料庫
show tables; #查看table
create table employees(id int NOT NULL AUTO_INCREMENT,name text(100), age int ,country text(100), position text(100), wage varchar(45),primary key(id)); # 創建table
desc employees; #查看table型態
select * from employees; #查看全部資料
```
如果有看到以下代表連線成功
Db is connected - The solution is:  2




