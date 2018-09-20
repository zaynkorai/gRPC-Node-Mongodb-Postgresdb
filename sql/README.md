## [gRPC with SQl (PostgresDB)](https://github.com/gRPC-Node-Mongodb-Postgresdb/tree/master/sql)

### Clone
```
git clone https://github.com/zaynkorai/gRPC-Node-Mongodb-Postgresdb/

cd /gRPC-Node-Mongodb-Postgresdb/sql

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
node test/grpcclienttest.js insert "Ultimate Todo Part 4" "writing code  part 4 of ultimate todo App"
node test/grpcclienttest.js update 1 "Ultimate Todo Part 5" "writing code and developing part 4 of ultimate todo App"
node test/grpcclienttest.js get 1
node test/grpcclienttest.js delete 1

```

#### Progress
- [x] gRPC
- [x] PostgresDB
- [x] List All
- [x] Insert
- [x] Get
- [x] Update
- [x] Delete

