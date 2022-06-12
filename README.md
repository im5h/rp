# repl

通过给定的正则表达式和字符串，对标准输入的内容进行替换或删除。

说明：repl regexp string

　或：repl regexp

示例一：

　echo Hello,123 | repl [0-9] A

　输出：Hello,AAA

示例二：

　echo Hello,123 | repl [0-9] A

　输出：Hello,
