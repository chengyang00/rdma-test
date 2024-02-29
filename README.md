# RDMA test

A simple RDMA server client test. The code contains a lot of comments. Here is the workflow that happens in the example: 


#### How to run      
```text
cd ./rdma-test
cmake .
make
``` 
 
#### server
```text
./bin/rdma_server
```

#### client
```text
./bin/rdma_client -a [server ip]
```

#### parameter
```text
-n operation iterations
-s message size
-t tos (message priority)
```