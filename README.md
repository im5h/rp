# rp

通过给定的正则表达式和字符串，对标准输入的内容进行替换或删除。

说明：rp regexp string

　或：rp regexp

示例一：

　echo Hello,123 | rp [0-9] A

　输出：Hello,AAA

示例二：

　echo Hello,123 | rp [0-9]

　输出：Hello,
