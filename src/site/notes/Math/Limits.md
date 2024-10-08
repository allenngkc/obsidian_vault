---
{"dg-publish":true,"permalink":"/math/limits/"}
---

### Precise Definition of Limits

Let $f$ be defined n some interval around $a$. Then $lim_{x\rightarrow a}f(x)=L$. If for all $\epsilon > 0$, there exists $\delta > 0$ such that $|f(x)-L|<\epsilon$ whenever $0 <|x-a|<\delta$ 

![Pasted image 20240928215525.png|450](/img/user/Photos/Pasted%20image%2020240928215525.png)

### Proving Limits

1. Write Find $\delta$ such that $0<|x-a|<\delta \implies |f(x)-L|<\epsilon$

> Essentially we are deriving $\delta$ with $|f(x)-L|<\epsilon$ <---- Rearrange this into $|x-a|<\delta$

##### Proving Infinity

1. Write let $M>0$, Show $\forall M>0,\exists \epsilon > 0$ such that $0<|x-a|<\delta \implies f(x)>M$

> This line basically means for all values of M > 0, we are deriving the $\delta$ with $M$.
### Squeeze Theorem

Suppose that $g(x)\leq f(x) \leq h(x)$ on an interval around $a$, If $lim_{x\rightarrow a}g(x)=lim_{x\rightarrow a}h(x)=L$, then $lim_{x\rightarrow a}f(x)=L$

