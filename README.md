# hdfs-command
hdfs command


switch user
```
su -- hadoop
```

list all file
```
hadoop dfs -ls /
```

mkdir new directory
```
hadoop dfs -mkdir /test
```

mkdir new directory and child directory
```
hadoop dfs -mkdir -p /test/zzz
```

create empty file
```
hadoop dfs  -touchz  /abc.txt
```

copyFromLocal: Copy file from local to hdfs 
```
hadoop dfs  -copyFromLocal def.txt /user
```

copyToLocal: Copy file from hdfs to local
```
hadoop dfs  -copyToLocal  /user/def.txt def2.txt
```

see more
```
https://www.geeksforgeeks.org/hdfs-commands/
```
