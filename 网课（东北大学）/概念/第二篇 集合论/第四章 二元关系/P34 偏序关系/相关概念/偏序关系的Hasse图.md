> [!info] **自反性**
> $$每个顶点\textcolor{pink}{\underline{\textbf{都有环}}}\quad \Rightarrow \quad 故\textcolor{red}{\underline{\textbf{省去}}}$$

> [!tip] **反对称性**
> $$两个\textcolor{pink}{\underline{\textbf{不同顶点}}}至多只有\textcolor{orange}{\underline{\textbf{一条边}}}$$
> $$约定: \quad \textcolor{orange}{\underline{\textbf{第一元素}}}在\textcolor{red}{\underline{\textbf{左}}}\ \ \textcolor{orange}{\underline{\textbf{第二元素}}}在\textcolor{red}{\underline{\textbf{右}}}$$
> $$约定: \quad \textcolor{orange}{\underline{\textbf{第一元素}}}在\textcolor{red}{\underline{\textbf{下}}}\ \ \textcolor{orange}{\underline{\textbf{第二元素}}}在\textcolor{red}{\underline{\textbf{上}}}$$
> $$并且\quad \textcolor{orange}{\underline{\textbf{省略箭头}}}$$
> ![[Pasted image 20240520171538.png]]

>[!success] **传递性**
>$$\textcolor{red}{\underline{\textbf{只画}}}<a,b>,<b,c>对应的边$$
>$$\textcolor{orange}{\underline{\textbf{省略}}}边<a,c>$$
>![[Pasted image 20240520181222.png]]

>[!example] **例1**
>$$A=\{1,2,3\}$$
>$$R_{1}=\{<a,b>|a \leq b \ \ a,b \in A\}$$
>$$R_{1}=\{<1,1>,<2,2>,<3,3>,<1,2>,<1,3>,<2,3>\}$$
>![[Pasted image 20240520181841.png]]

>[!example] **例2**
>$$B=\{1,2,3,4,6\}$$
>$$R_{2}=\{<a,b>|\ a \ | \ b \ \ a,b \in A\}$$
>$$\begin{eqnarray}
> R_{2}&=&\{<1,1>,<2,2>,<3,3>,<4,4>,<6,6>\}\\
> &\cup& \{<1,2>,<1,3>,<1,4>,<1,6>,<2,4>,<2,6>,<3,6>\}
\end{eqnarray}$$
> ![[Pasted image 20240520182123.png]]