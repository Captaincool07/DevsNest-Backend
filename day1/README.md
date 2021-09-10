Day1 and Day2 THA

Set Up Redis and PostgreSQL
 
## 1. Redis

 - Install
```sh
sudo apt update #For update WSL

sudo apt install redis-server  #Install redis
```
- Start Redis
```sh
sudo service redis-server start  #start Redis
redis-cli  #Enter redis Cli
```


## 2. PostgreSQL
* Install
```sh 
sudo apt update #For update WSL(Ubuntu)

sudo apt install postgresql postgresql-contrib  #install
```
 - Start postgreSQL
```sh
sudo systemctl start postgresql  
sudo -iu postgres
psql                             #Enter into terminal 
```                           
