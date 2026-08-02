---
layout: post
title: "[Medium] 33. Search in Rotated Sorted Array"
date: 2025-09-23 20:26:18 -0700
categories: [Leetcode]
excerpt: "Note: Leetcode questions moved to github page: https://robinali34.github.io/blog_leetcode/ Template in C++ Binary search on answer Solution in C++ Solution in Python"
wp_id: 54
---

<p>Note: Leetcode questions moved to github page: <a href="https://robinali34.github.io/blog_leetcode/" title="https://robinali34.github.io/blog_leetcode/">https://robinali34.github.io/blog_leetcode/</a></p>



<h2>Template in C++</h2>



<h3>Binary search on answer</h3>



<pre><code>int bs_on_answer(int left, int right) {<br>    while (left &lt;= right) {<br>        int pivot = left + (right - left) / 2;<br>        if (condition(pivot)) {<br>            right = pivot + 1;<br>        } else {<br>            left = pivot + 1;<br>        }<br>    }<br>    return -1;<br>}</code></pre>



<h2>Solution in C++</h2>



<pre><code>class Solution:<br>    def search(self, nums: List&#91;int], target: int) -&gt; int:<br>        left, right = 0, len(nums) - 1<br>        while left &lt;= right:<br>            mid = left + (right - left) // 2<br>            if nums&#91;mid] == target:<br>                return mid<br>            # Subarry on mid's left is sorted<br>            elif nums&#91;mid] &gt;= nums&#91;left]:<br>                if target &gt;= nums&#91;left] and target &lt; nums&#91;mid]:<br>                    right = mid - 1<br>                else:<br>                    left = mid + 1<br>            # Subarray on mid's right is sorted<br>            else:<br>                if target &lt;= nums&#91;right] and target &gt; nums&#91;mid]:<br>                    left = mid + 1<br>                else:<br>                    right = mid - 1<br>        return -1</code></pre>



<h2>Solution in Python</h2>



<pre><code>class Solution:<br>    def search(self, nums: List&#91;int], target: int) -&gt; int:<br>        left, right = 0, len(nums) - 1<br>        while left &lt;= right:<br>            mid = left + (right - left) // 2<br>            if nums&#91;mid] == target:<br>                return mid<br>            # Subarry on mid's left is sorted<br>            elif nums&#91;mid] &gt;= nums&#91;left]:<br>                if target &gt;= nums&#91;left] and target &lt; nums&#91;mid]:<br>                    right = mid - 1<br>                else:<br>                    left = mid + 1<br>            # Subarray on mid's right is sorted<br>            else:<br>                if target &lt;= nums&#91;right] and target &gt; nums&#91;mid]:<br>                    left = mid + 1<br>                else:<br>                    right = mid - 1<br>        return -1</code></pre>
