<h1>题目：</h1>
<p>
判断一个整数是否是回文数。回文数是指正序（从左向右）和倒序（从右向左）读都是一样的整数。
示例 1:<br>
输入: 121<br>
输出: true<br>
示例2:<br>
输入: -121<br>
输出: false<br>
解释: 从左向右读, 为 -121。 从右向左读, 为 121- 。因此它不是一个回文数。<br>
示例 3:<br>
输入: 10<br>
输出: false<br>
解释: 从右向左读, 为 01 。因此它不是一个回文数。<br>
进阶:<br>
你能不将整数转为字符串来解决这个问题吗？<br>
</p>
<h1>解题思路</h1>
<p>
首先判断是否为负数，负数返回false<br>
然后转换为字符串，再反转，最后比较；
使用其他方法待更新（栈？）</p>