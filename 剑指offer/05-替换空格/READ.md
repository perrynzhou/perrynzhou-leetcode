### 剑指 Offer 05. 替换空格
请实现一个函数，把字符串 s 中的每个空格替换成"%20"。

 

示例 1：

输入：s = "We are happy."
输出："We%20are%20happy."
 

限制：

0 <= s 的长度 <= 10000

### 解题思路
- 开辟一个slice,把非空格字符和替换的字符append到数组
- 遍历数组，每当遇到空格进行替换

