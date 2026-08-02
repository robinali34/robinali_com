---
layout: post
title: "Look back: AI tools v.s. coding"
date: 2025-09-25 00:03:16 -0700
categories: [Notes]
excerpt: "For a long time I am not sure about what role AI tools shall be when I am coding. Key questions are: Recently I got some dedicated free time doing personal practice and projects regarding coding. And had been actively us"
wp_id: 60
---

<p>For a long time I am not sure about what role AI tools shall be when I am coding. Key questions are:</p>



<ol>
<li>When I shall use AI tool and what tool shall be used</li>



<li>How much I can trust the response AI tools regarding knows issues like hallucination and miscommunication</li>



<li>Also, what situations I need to be extra careful review the AI generated results/suggestions; while what scenarios I can blindly take whatever AI generated response as it it. </li>
</ol>



<p>Recently I got some dedicated free time doing personal practice and projects regarding coding. And had been actively using ChatGPT and Cursor for weeks. Now with more practices done, I have a better hint regarding those confusions.</p>



<p>Keyword in how to use AI is: you know what you are doing. That, before you start use the tool you have deep understanding in what to be expected or what right answer is. Otherwise you will get sidetracked and miss-use them. For now, AI is a tool not a replacement of your brain.</p>



<ol>
<li>When &amp; what
<ul>
<li>As for well supported platforms like leetcode practice, AI tool like ChatGPT and Cursor can be very helpful. ChatGPT can be used to get question catagories, template of solutions, review my solutions, and quick QA. Cursor can be used to generate source code project, update README etc. And save me a lot of time while conducting those data copy, formatting, generated test cases, and project setup stuff for me.
<ul>
<li>BUT! Be <strong>careful about </strong>some<strong> details</strong>. For example, the leetcode solutions from AI is not optimal and may has small issues like memory leak with C++ code.  And test cases they generated are more trending to make the test pass but actually test the code/feature. If you have a high standard and reliability request, do review those generated code before submission.</li>
</ul>
</li>



<li>As for context generation like resume update, use AI as reference for outline, rewording but it will generate hallucinated context and remove your keywords automatically, do a before &amp; after comparison before submission.</li>



<li>As for mini project, that you know exactly what to be expected, AI IDE like Cursor is helpful, while you need to be extra patient with it. Treated it like a child trying really hard to make you happy during the interlocution.
<ul>
<li>For example, I did a mini project to generate a pdf resume that matching my current resume. I want it using latex or markdown format. But to get it down I need to reword my request dozens of times while it is repeatedly make the 1st page only have the title line during my requests. In the end it took me few hours to have a okay version.</li>



<li>Another example is mini project in learning new approach that you do not expecting a reliable long term execution. For example I was curious about Python SQLAlchemy with PostgreSQL. Cursor can generated a project about it in few hours and help add examples of most common manipulations help me better understanding how they works.</li>
</ul>
</li>
</ul>
</li>



<li>How much I can trust it.
<ul>
<li>The TA of my algorithm course Joves from Google said something give me the hint: when you do algorithms questions, read the questions and try solving it before you go to AI tools. <strong>Think before asking for help. </strong></li>



<li>In the Resume case above, I know exactly what I want. I can ask for AI IDE to generate it for me. BUT, in case I am not sure, e.g.: I did not read through the Algorithm question and ask AI to understand it for me, the outcome can be sideways greatly.
<ul>
<li>For example, there is a DP question that a variation of knapsack question, the ChatGPT directly take is as the Leetcode question and answered it. Which is not the real question about.</li>



<li> Take AI like a auto-fill correction when you typing, you need to know you want word like &#8220;Hallucination&#8221;, not the auto-corrected &#8220;calumniation&#8221;. </li>
</ul>
</li>



<li>In sort, do not trust AI to understand things for me. Use it as a Wikipedia, a teacher, not your-self.</li>



<li>Do review (based on your understanding) before you submit the AI generated results.</li>
</ul>
</li>



<li>What situation and how much I can trust AI generated result?
<ul>
<li>Know what reliability you want, and review AI generated code to matching the reliability you want. 
<ul>
<li>If you want a pdf generation or a blog site, as long as generated results match your expectations, fine. No Unit test needed.</li>



<li>If you want a auto-drive app, unit test, corner cases, real-environment validation etc. all needed.</li>



<li><strong>Do not trust AI with your life.</strong></li>
</ul>
</li>
</ul>
</li>
</ol>



<p></p>
