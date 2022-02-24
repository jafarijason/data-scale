# Understand the MapReduce paradigm

```
grep " Kutuzov " war-and-peace.txt
grep " Kutuzov " war-and-peace.txt | wc -l
# 257
```

```
cat  war-and-peace.txt | ./mapper.sh
cat  war-and-peace.txt | ./mapper.sh | more
cat  war-and-peace.txt | ./mapper.sh | ./reducer.sh
# Kutuzov,315
# Petersburg,128
```