# 第一章 小试牛刀
## 1.2 在终端输出

提示符格式形式如下：

```shell
username@hostname$
```

其中`hostname`可在`/etc/hostname`中更改。
`$`表示普通用户，`#`表示超级用户。

Linux脚本通常以shebang[^1]起始。

```shell
#!/bin/bash
```

`#!`位于解释器路径前，`/bin/bash`为解释器路径

脚本有两种执行方式
1. 脚本作为命令行参数：
  
  ```shell
  bash myScript.sh
  ```

2. 授予脚本执行权限，将其变为可执行文件

  ```shell
  chmod 755 myScript.sh
  ./myScript.sh
  ```

以第一种方式执行，shebang就没用了;利用shebang实现脚本的独立运行，内核会读取脚本的首行，识别出`/bin/bash`并执行：

```shell
/bin/bash sample.sh
```

当启动一个交互式shell时，它会执行一组命令来初始化提示文本、颜色等设置。这组命令来
自用户主目录中的脚本文件~/.bashrc（对于登录shell则是~/.bash_profile）。 Bash shell还维护了一
个历史记录文件~/.bash_history，用于保存用户运行过的命令

`#`表示注释

`%s`、`%c`和`%d`、`%f`都是格式替换符：

1.  %-5s指明了一个格式为左对齐且宽度为5的字符串替换（ -表示左对齐）。如果不指明-，
字符串就采用右对齐形式。
2. 宽度指定了保留给某个字符串的字符数量。

### 补充内容

注：
[^1]: shebang = sharp(#)+bang(!)
