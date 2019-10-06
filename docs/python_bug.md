# Python bug 问题汇总

记录一些 Python 使用过程出现的 Bug 解决策略。

## PyInstaller

### 1 UnicodeDecodeError

打包时出现 UnicodeDecodeError: 'utf-8' codec can't decode byte 0xce in position 的解决策略在您的命令行中先输入 `chcp 65001` 然后再输入如下打包命令即可：

```sh
pyinstaller -Fw xxx.py
```

注意：上面使用 `chcp 65001` 虽然解决了 pyinstaller 打包的问题，但是，如果你的代码中存在中文的 I/O 则会出现中文部分乱码的问题。

查阅资料后发现这种情况是：GBK 与 utf-8 之间的编码转换出现的问题。出现异常是因为设置了 `decode()` 方法的参数 `errors` 默认为 `strict` 形式造成的。我们将其修改为 `ignore` 即可解决中文部分乱码的问题。
