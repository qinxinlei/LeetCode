
| English | [简体中文](README.md) |

# [91. Decode Ways](https://leetcode-cn.com/problems/decode-ways/)

## Description

<p>A message containing letters from <code>A-Z</code> is being encoded to numbers using the following mapping:</p>

<pre>
&#39;A&#39; -&gt; 1
&#39;B&#39; -&gt; 2
...
&#39;Z&#39; -&gt; 26
</pre>

<p>Given a <strong>non-empty</strong> string containing only digits, determine the total number of ways to decode it.</p>

<p>The answer is guaranteed to fit in a <strong>32-bit</strong> integer.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;12&quot;
<strong>Output:</strong> 2
<strong>Explanation:</strong> It could be decoded as &quot;AB&quot; (1 2) or &quot;L&quot; (12).
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;226&quot;
<strong>Output:</strong> 3
<strong>Explanation:</strong> It could be decoded as &quot;BZ&quot; (2 26), &quot;VF&quot; (22 6), or &quot;BBF&quot; (2 2 6).
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;0&quot;
<strong>Output:</strong> 0
<strong>Explanation:</strong> There is no character that is mapped to a number starting with &#39;0&#39;. We cannot ignore a zero when we face it while decoding. So, each &#39;0&#39; should be part of &quot;10&quot; --&gt; &#39;J&#39; or &quot;20&quot; --&gt; &#39;T&#39;.
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;1&quot;
<strong>Output:</strong> 1
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 100</code></li>
	<li><code>s</code> contains only digits and may contain leading zero(s).</li>
</ul>


## Related Topics

- [String](https://leetcode-cn.com/tag/string)
- [Dynamic Programming](https://leetcode-cn.com/tag/dynamic-programming)

## Similar Questions

- [Decode Ways II](../decode-ways-ii/README_EN.md)
