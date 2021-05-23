# 常用shell命令记录

## 查找

- 查找某个目录下文件中的字符串”xxx”
```sh
find . | xargs grep -rE "xxx"

grep "xxx" `find . -name "*"`
```

