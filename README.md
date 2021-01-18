# 算法笔记
算法笔记

记录算法学习中的一些问题和思路解法
以及转载一些好的内容

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
仅考虑，两指针都进入了环那一刻：  
设在环中:   
指针1位置：\\(0\\)，步长：\\(l_1\\)  
指针2位置：\\(d\\) ，步长：\\(l_2\\)  
圈长：\\(C\\(  
第n步时：  
指针1： \\(n\c_dot l_1 = aC+p_1\\)  
指针2： \\(n\c_dot l_2 +d= bC+p_2\\)  

若指针1，指针2不能相遇，即证明：不存在 \\(a,b \in N \Rightarrow p_1=p_2 \\)， 其中\\(p_1,p_2\\)为指针1和指针2在环中位置。  
两式相减：  
证明： \\(n(l_1-l_2)=(a-b)C+d  s.t. a,b \in N\\) 无解  
画图，容易看出，会存在整数解，使得两直线相交  
所以无解不成立，所以会相遇
