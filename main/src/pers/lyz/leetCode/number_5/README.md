<h1>题目：</h1>
<p>
编写一个函数来查找字符串数组中的最长公共前缀。<br>
如果不存在公共前缀，返回空字符串 ""。<br>
示例1:<br>
输入: ["flower","flow","flight"]<br>
输出: "fl"<br>
示例2:<br>
输入: ["dog","racecar","car"]<br>
输出: ""<br>
解释: 输入不存在公共前缀。<br>
说明:<br>
所有输入只包含小写字母a-z。<br>
</p>
<h1>解题思路</h1>
<p>纵向遍历：依次遍历每个字符串，更新最长公共前缀。<br>从前往后遍历所有字符串的每一列，比较相同列上的字符是否相同，如果相同则继续对下一列进行比较，<br>
如果不相同则当前列不再属于公共前缀，当前列之前的部分为最长公共前缀。
</p>