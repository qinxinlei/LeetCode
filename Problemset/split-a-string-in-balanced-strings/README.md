
| [English](README_EN.md) | 简体中文 |

# [1221. 分割平衡字符串](https://leetcode-cn.com/problems/split-a-string-in-balanced-strings/)

## 题目描述

<p>在一个「平衡字符串」中，'L' 和 'R' 字符的数量是相同的。</p>

<p>给出一个平衡字符串 <code>s</code>，请你将它分割成尽可能多的平衡字符串。</p>

<p>返回可以通过分割得到的平衡字符串的最大数量<strong>。</strong></p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "RLRRLLRLRL"
<strong>输出：</strong>4
<strong>解释：</strong>s 可以分割为 "RL", "RRLL", "RL", "RL", 每个子字符串中都包含相同数量的 'L' 和 'R'。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "RLLLLRRRLR"
<strong>输出：</strong>3
<strong>解释：</strong>s 可以分割为 "RL", "LLLRRR", "LR", 每个子字符串中都包含相同数量的 'L' 和 'R'。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>s = "LLLLRRRR"
<strong>输出：</strong>1
<strong>解释：</strong>s 只能保持原样 "LLLLRRRR".
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 1000</code></li>
	<li><code>s[i] = 'L' 或 'R'</code></li>
	<li>分割得到的每个字符串都必须是平衡字符串。</li>
</ul>


## 相关话题

- [贪心算法](https://leetcode-cn.com/tag/greedy)
- [字符串](https://leetcode-cn.com/tag/string)

## 相似题目


