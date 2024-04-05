Define the sequence $\{b_n\}$ as follows:
$$
\begin{align*}
&b_0 = 1\\
&b_n = 2 \times b_{n-1} + 1 \text{ for } n = 1,2,3,... 
\end{align*}
$$
We then compute the first 5 terms: 
$$
\begin{align*}
b_0 &= 1\\
b_1 = 2 \times b_0 + 1 &= 3 \\ 
b_2 = 2 \times b_{1} + 1 &= 7\\ 
b_3 = 2 \times b_{2} + 1 &= 15 \\ 
b_4 = 2 \times b_{3} + 1 &= 31\\  
\end{align*}
$$
We want to find a closed formula for the sequence of answers, in this case it is:
$$
b_n = 2^{n+1} -1
$$
**Proof by Induction**
Now we will prove that $b_n = 2^{n+1} -1$ is the correct formula for the above recurrence relation for $n \geq 0$.

**Base Case:** $n=0 = b_0 = 1$
$$
\begin{align*}
&\text{Appilying the base case to our proposed formula:}\\\\
&b_0 = 2^{0+1}-1\\
&=2-1\\
&=1
\end{align*}
$$
This yields true and we can continue withe the proof. 

**Inductive Step:** Assume $b_k = 2^{k+1} -1$ for some $k \geq 0$ (**IH**)

We want to show: $$b_{k+1} = 2^{(k+1)+1} -1$$

**Starting with the LHS**
$$
\begin{align*}
&\text{From the definition of the reccurence relation} \\\\
&b_{k+1} = 2 b_{(k+1)-1} +1\\\\
&= 2 b_k +1\\\\
&\text{Appilying our definition for } b_k \text{ to the formula}\\\\
&= 2 (2^{k+1} -1) +1 \\\\
&\text{Distributing the 2 across}\\\\
&= 2 (2^{k+1} -1) +1
&= 2 (2^{k+1} -1) +1
\end{align*}
$$