## <span style="color:rgb(255, 192, 0)"><span style="color:rgb(255, 192, 0)">Definició</span></span> <span style="color:rgb(255, 192, 0)">de</span> <span style="color:rgb(255, 192, 0)">formes</span> <span style="color:rgb(255, 192, 0)">multilineals</span>

Recordem que en $\mathcal{L}(\mathbb{R}^n,\mathbb{R}^m)$ denota l'espai vectorial d'aplicacions lineals $L:\mathbb{R}^n \to \mathbb{R}^m$, el qual és isomorf a l'espai de matrius $\mathbb{M}_{n \times m}(\mathbb{R})$, i per tant té dimensió $mn$. En particular, si $m=1$, l'espai $\mathcal{L}(\mathbb{R}^n,\mathbb{R}^m)$ admet la base $\{ w_{1}, \dots, w_{n} \}$, on tenim que $w_{i}: \mathbb{R}^{n} \to \mathbb{R}$ ve determinat per $w_{i}(e_{j})=\delta_{ij}$.

Per extensió, $\mathcal{L}^2(\mathbb{R}^n,\mathbb{R}^m)$ denota l'espai de formes bilineals. Una forma bilineal és una aplicació $\mu: \mathbb{R}^{n}\times \mathbb{R}^{n} \to \mathbb{R}$ tal que per a tot $u,v,w \in \mathbb{R}^n$ i $\lambda \in \mathbb{R}$ es compleix que 
$$
\begin{align*}
\mu (u, v+w)&= \mu(u,v) + \mu(u,w)\text{, i per la l'esquerra també}\\
\mu (\lambda u,w)&=\lambda \mu(u,w)\text{, i per la dreta també}
\end{align*}
$$
Altre cop, $\mathcal{L}^2(\mathbb{R}^n,\mathbb{R}^m)$ té estructura d'espai vectorial real. Aquest cop, però, una possible base de $\mathcal{L}^2(\mathbb{R}^n,\mathbb{R}^m)$ és $\{ w_{i} \times w_{j}\}_{i,j=1,\dots n}$, on definim $$
w_{i} \times w_{j} : \mathbb{R}^{n}\times \mathbb{R}^{n} \to \mathbb{R}
$$ com l'única aplicació bilineal tal que $w_{i} \times w_{j} (e_{p}, e_{q})= \delta_{ip}\delta_{jq}$. En particular, $\mathcal{L}^2(\mathbb{R}^n,\mathbb{R}^m)$ té dimensió $n^{2}$. 
De la mateixa manera podem generalitzar fins a $\mathcal{L}^k(\mathbb{R}^n,\mathbb{R}^m)$, amb una construcció similar. 

aaaaa