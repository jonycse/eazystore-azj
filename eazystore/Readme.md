

## DB setup
+ Install docker
+ Download and install [sqlectron][1] check __sqlectron-mySQL.png__





### Doker MySQL command
```javascript
sudo docker run -p 3306:3306 \
--name eazystoredb \
-e MYSQL_ROOT_PASSWORD=root \
-e MYSQL_DATABASE=eazystore \
-v /Users/ajony/Developer/me/me-fullstack/eazystore-azj/data:/var/lib/mysql \
-d mysql
```


[1]: [https://sqlectron.github.io/]