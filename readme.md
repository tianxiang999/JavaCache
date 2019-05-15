
1. ssh onto heming-rdma18
2. cd ~/Migration/cheng/JavaCache/
3. ./gradlew shadowJar
4. ./script/perf.py

Note: the folder Migration is on NFS.

The `numbers` in perf.py specifies the machines. machine14 works as the server, and all the other machines work as the clients. 
