$$\begin{eqnarray}
条件: \quad
&①& \quad n= \ | \ V(G) \ | \ <12 \\
&②& \quad G是\textcolor{pink}{\underline{\textbf{简单}}}\textcolor{orange}{\underline{\textbf{平面图}}}
\end{eqnarray}$$
### 证明
$$\exists \ v_{0} \in V(G) \quad S.t. \quad d(v_{0})   \leqslant 4$$
### Proof

#### 反证法


$$\textcolor{orange}{\underline{\textbf{反证法}}}$$
假设

$$\forall \ v \in V(G)  \quad \rightarrow \quad  d(v)  > 4 \quad \leftrightarrow \quad d(v)  \geqslant 5$$
只需证明

$$n  \geqslant 12$$
或
$$G是 \textcolor{orange}{\underline{\textbf{非平面图}}}$$

#### 条件假设

假设

$$m=|E(G)|$$
$$r=|R(G)|$$


##### G是连通的

$if$
$$\tag{核心手法}G是\textcolor{orange}{\underline{\textbf{连通的}}}$$
###### $e    \leqslant 2$

$$\forall \ v \in V(G)  \quad \rightarrow \quad d(v)  \leqslant 2  \leqslant 4$$
$$\quad \Downarrow \quad $$
$$\qquad QED\ !$$
###### $e  \geqslant 3$

此时

$$\tag{核心手法}\deg \ (R_{i})  \geqslant m  \geqslant 3$$
$Euler$得

$$n-m+r=2$$

$Shake_{1}$得

$$\sum\limits_{i}^{r}\deg \ (R_{i}) = 2m$$
$Shake_{2}$得

$$\sum\limits_{i}^{}d(v_{i}) = 2m$$

$Shake_{1}$得

$$\tag{1}\sum\limits_{i}^{r}\deg \ (R_{i}) = 2m   \geqslant 3r$$
$Shake_{2}$得

$$\tag{2}\sum\limits_{i}^{}d(v_{i}) =2m  \geqslant 5n$$
联立(1)(2)$Euler$得

$$\tag{1.1}2n  \geqslant r+4$$
$$\quad \Updownarrow \quad$$
$$\tag{*}r  \leqslant 2n-4$$
并且
$$\tag{2.1}3n  \leqslant 2r-4$$
$$\quad \Updownarrow \quad$$
$$\tag{*}\frac{3}{2}n+2  \leqslant r$$

联立$(*)$得

$$ \frac{3}{2}n+2   \leqslant r  \leqslant 2n-4$$
$$\quad \Downarrow \quad $$
$$\frac{3}{2}n+2  \leqslant 2n-4$$
$$\quad \Downarrow \quad $$
$$6  \leqslant \frac{1}{2}n$$
$$\quad \Downarrow \quad $$
$$n  \geqslant 12 $$
$But$ , 由$条件①$得

$$n <12 \quad 矛盾!$$
$$\quad \Downarrow \quad $$
$$\qquad QED\ !$$

##### G是不连通的

$if$
$$G是\textcolor{orange}{\underline{\textbf{不连通的}}}$$
$$\quad \Downarrow \quad $$
$$对\quad G的\textcolor{orange}{\underline{\textbf{连通分支}}}G_{i} \quad 进行讨论 \quad  (1\leqslant  i\leqslant k)$$
$因为$

$$对 \quad \forall \ G_{i}  \quad 都是\textcolor{orange}{\underline{\textbf{连通的}}} \quad (1 \leqslant i  \leqslant k)$$
$$\quad \Downarrow \quad $$
$$\forall \ 1  \leqslant i  \leqslant k  \quad \rightarrow \quad  \exists \  v_{0i} \in V(G) \quad S.t. \quad d(v_{0i})  \leqslant 4$$
$$\quad \Downarrow \quad $$
$$\exists \ v_{0}=\{\ v_{0i} \ , \ \cdots \ , \ v_{0i} \ , \ \cdots \ , \ v_{0k}\ \} \quad S.t. \quad d(v_{0}) \in V(G)  \leqslant 4$$
$$\quad \Downarrow \quad $$
$$\qquad QED\ !$$
