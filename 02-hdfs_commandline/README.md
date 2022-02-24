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
## Where is your home directory in HDFS
```
hdfs dfs -ls /
hdfs dfs -ls /user

```

## For upload file into HDFS
```
hdfs dfs -put or -copyFromLocal <file from local computer>
hdfs dfs -ls
```

## For download file into HDFS
```
hdfs dfs -get or -copyToLocal <file from local computer>
hdfs dfs -ls
```

## For copy file in HDFS
```
hdfs dfs -cp <source file> <destination file>
hdfs dfs -ls
```
## For remove file in HDFS
```
hdfs dfs -rm <file>
hdfs dfs -rm  -r <directory>
hdfs dfs -rm -skipTrash <file>
hdfs dfs -ls
```


## For create directory in HDFS
```
hdfs dfs -mkdir <directory>
hdfs dfs -ls
```

## You can mount HDFS as local drive and it will be in
```
...
```
