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


# Understand how MapReduce works

<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/Understand_how_MapReduce_works.png" alt=""/>
</p>
<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/Understand_how_MapReduce_works1.png" alt=""/>
</p>
<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/Understand_how_MapReduce_works2.png" alt=""/>
</p>
<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/Understand_how_MapReduce_works3.png" alt=""/>
</p>
<p align="center">
    <img src="https://github.com/jafarijason/data-scale/raw/main/assets/images/Understand_how_MapReduce_works4.png" alt=""/>
</p>
