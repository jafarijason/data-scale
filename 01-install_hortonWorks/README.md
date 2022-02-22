# Install Hortonworks Hadoop and Spark HDP Sandbox

## For installing horton works there are several ways and one is virtual box

### Minimum requirement for installation for Hadoop and Spark HDP is cpu i7 with 16G RAM and 100G Hard Drive

---
### For installing virtualbox you can go to [download page](https://www.virtualbox.org/wiki/Downloads) in virtualbox website
---

### For hortonworks downloading you can use [this link](https://www.cloudera.com/downloads/hortonworks-sandbox.html)

After installation you can use [http://127.0.0.1:1080/](http://127.0.0.1:1080/)

### for ssh connect user name is root and password is hadoop web port is 4200 and ssh port is 2222

test  this command to see all directories in our distributed file system
```
hdfs dfs -ls /
```

## For checking Namenode information you can use [http://127.0.0.1:50070](http://127.0.0.1:50070)



## For checking YARN jobs manager you can use [http://127.0.0.1:8088](http://127.0.0.1:8088)



