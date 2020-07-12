# 新手必须掌握的Linux命令

## shell

shell是一个充当人和内核之间的翻译官的命令行工具，主流的Linux系统默认使用Bash解释器作为默认终端。优势主要有：

1. 通过方向键来调取使用过的Linux命令
2. 可使用Tab补全
3. 具有强大的批处理脚本
4. 具有实用的环境变量功能

## 查看帮助命令

Linux的明令格式通常是这样的：

```bash
command [command-args] [command-object]
```

**命令对象**一般是指要处理的文件、目录、用户等资源

**命令参数**可以用长格式（完整的选项名称）， 也可以用短格式（单个字母的缩写）， 两者分别用--与-作为前缀

使用`man`命令可查看帮助

## 常用系统工作命令

1. echo
2. date
3. reboot
4. poweroff
5. wget/curl
6. ps
7. top
8. pidof
9. kill
10. kilall

### 详解

#### echo

`echo`命令打印对应的信息，比如：

```bash
echo "Hello, world" # 输出"Hello, world"
echo "$(ls /)" #输出根目录的文件
```

