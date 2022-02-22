# Where is the HDFS Data?

- HDFS is separate from your local machine or local file system - it is stored in distributed servers
- HDFS is not suited for small frequently changing filesystem
- Data must be moved to (put) and from (get) HDFS
- All Hadoop processes at scale happens in HDFS


<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/hdfsarchitecture.gif" alt="Hadoop Architecture"/>
</p>
<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/hdfs001.png" alt="Hadoop Architecture"/>
</p>

# Commands


## Base command
```
hdfs dfs
```

## List files and folder in HDFS
```
hdfs dfs -ls /
hdfs dfs -ls
```

