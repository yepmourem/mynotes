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

注：
[^1]: shebang = sharp(#)+bang(!)
