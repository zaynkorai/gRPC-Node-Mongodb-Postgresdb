## [gRPC with NoSQl-(MongoDB)](https://github.com/zaynkorai/gRPC-Node-Mongodb-Postgresdb/tree/master/nosql)

### Clone
```
git clone https://github.com/zaynkorai/gRPC-Node-Mongodb-Postgresdb/
cd /gRPC-Node-Mongodb-Postgresdb

npm install
```

### Run Server
```
node src/server.js


```
### Run Client
```
node app.js

```
### Run Test
```
node test/grpcclienttest.js list
node test/grpcclienttest.js insert 11 "Ultimate Todo Part 4" "writing code  part 4 of ultimate todo App"
node test/grpcclienttest.js update 11 "Ultimate Todo Part 5" "writing code and developing part 4 of ultimate todo App"
node test/grpcclienttest.js get 11
node test/grpcclienttest.js delete 11

```

#### Progress
- [x] gRPC
- [x] Mongodb
- [x] List All
- [x] Insert
- [x] Get
- [x] Update
- [x] Delete