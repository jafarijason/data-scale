# [Source](https://www.cloudera.com/tutorials/learning-the-ropes-of-the-hdp-sandbox.html)

## Terminal Access

```
ssh root@sandbox-hdp.hortonworks.com -p 2222
```

## Shell Web Client Method:
The shell web client is also known as Shell-in-a-Box. It's an easy way to issue shell commands without needing to install additional software
example: [sandbox-hdp.hortonworks.com:4200](sandbox-hdp.hortonworks.com:4200)

## Send Data Between Sandbox and Local Machine
<ul>
    <li>
        Transfer file from local machine to sandbox:
        <ul>
            <li>
                scp -P 2222 "local_directory_file" root@sandbox-hdp.hortonworks.com:"sandbox_directory_file"
            </li>
        </ul>
    </li>
    <li>
        Transfer file from sandbox to local machine:
        <ul>
            <li>
                scp -P 2222 root@sandbox-hdp.hortonworks.com:"sandbox_directory_file" "local_directory_file"
            </li>
        </ul>
    </li>
</ul>

## Welcome Page
The Sandbox Welcome Page is also known as the Splash Page. It runs on port number :1080. To open it, use your host address and append the port number. For example: [http://sandbox-hdp.hortonworks.com:1080/](http://sandbox-hdp.hortonworks.com:1080/)



# [User](https://www.cloudera.com/tutorials/learning-the-ropes-of-the-hdp-sandbox.html#appendix-a-reference-sheet)
1. admin - System Administrator

2. maria_dev - Responsible for preparing and getting insight from data. She loves to explore different HDP components like Hive, Pig, HBase.

3. raj_ops - Responsible for infrastructure build, research and development activities like design, install, configure and administration. He serves as a technical expert in the area of system administration for complex operating systems.

4. holger_gov - Primarily for the management of data elements, both the content and metadata. He has a specialist role that incorporates processes, policies, guidelines and responsibilities for administering organizations' entire data in compliance with policy and/or regulatory obligations.

5. amy_ds - A data scientist who uses Hive, Spark and Zeppelin to do exploratory data analysis, data cleanup and transformation as preparation for analysis.

# [Concept: Hadoop & HDP](https://www.cloudera.com/tutorials/getting-started-with-hdp-sandbox/1.html)