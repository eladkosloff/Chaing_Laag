Consider the fundamental representation $V$ of $\mathrm{SL}(2, \mathbb{C})$. Projectifying, we obtain an action of $\operatorname{SL}(2, \mathbb{C})$ on $\mathbb{C} P^1=\mathbb{P}(V)$. Taking the $d$-fold symmetric product, we obtain an action of $\operatorname{SL}(2, \mathbb{C})$ on $\operatorname{Sym}^d \mathbb{C} P^1=\mathbb{C} P^d$. Equivalently, we can consider the $d$-fold symmetric power $S^d V$ and projectify to obtain an action of $\mathrm{SL}(2, \mathbb{C})$ on $\mathbb{P}\left(S^d V\right)=\mathbb{C} P^d$.

Fix $d = 3$, and a configuration $C$ of $d$ distinct points in $\mathbb{C} P^1$. Then, the $\operatorname{SL}(2, \mathbb{C})$-orbit of $C$ in Sym ${ }^d \mathbb{C} P^1 \cong \mathbb{P} S^d V$ is a three-dimensional complex submanifold, of which the $\operatorname{SU}(2)$-orbit is a threedimensional totally real submanifold. The stabilizer of $C$ in $\operatorname{SL}(2, \mathbb{C})$ is a finite subgroup of $\operatorname{SU}(2)$ which we denote by $\Gamma_C$. In [1], Aluffi and Faber identify those configurations $C$ for which the SL(2, $\mathbb{C}$ )orbit has smooth closure $X_C$ in $\mathbb{P} S^d V$. the vertices of an equilateral triangle on a great circle in $\mathbb{C} P^1$, which we denote by $\Delta$.

The restriction of the $\operatorname{SU}(2)$-action to $X_C$ with the Fubini- Study Kähler form is Hamiltonian with the moment map $m: \mathbb{P S} S^d V \rightarrow \mathfrak{s u}(2)^*$ which is defined by

$$
\langle m([z]), \xi\rangle=\frac{i}{2} \frac{z^{\dagger} \varphi(\xi) z}{z^{\dagger} z}, \quad \xi \in \mathfrak{s u}(2)
$$

where $\varphi: \mathfrak{s u}(2) \rightarrow \operatorname{Mat}_{(d+1) \times(d+1)}(\mathbb{C})$ is given by the representation $S^d V$. The $\operatorname{SU}(2)$-orbits of the configuration $\Delta$ lie in the zero sets of the  moment maps, so this is a Lagrangian. We denote these orbits by $L_{\Delta}$.

The Chiang Lagrangian is $L_{\Delta} \subset X_{\Delta}=\mathbb{P} S^3 V \cong \mathbb{C} P^3$. It is the space of all the equilateral triangles on great circles in $\mathbb{C} P^1$. Topologically, $L_{\Delta}$ is the quotient of $\operatorname{SU}(2)$ by the binary dihedral subgroup $\Gamma_{\Delta}$ of order 12.

To work with the Chiang Lagrangian, we will need the following additional notations. Let $W_{\Delta}$ denote the Zariski open $\operatorname{SL}(2, \mathbb{C})$-orbit in $\mathbb{C} P^3$, and let $Y_{\Delta}$ denote its complement. $Y_{\Delta}$ consists of those 3-point configurations in $\mathbb{C} P^3$ where at least 2 of the points coincide. Let $N_{\Delta} \subset Y_{\Delta}$ be the subvariety consisting of those configurations where all 3 points coincide. If $\left[z_0: \ldots: z_3\right]$ are standard coordinates on $\mathbb{P} S^3 V$, then the roots of the polynomial

$$
f(T):=\sum z_j(-T)^j
$$

correspond (with multiplicity) to the 3 -tuple of points obtained by viewing $[z]$ as a point of $\operatorname{Sym}^3 \mathbb{C} P^1$. We count $\infty$ as a root with multiplicity $3-\operatorname{deg} f$. Consequently, $Y_{\Delta}$ is defined by the vanishing of the discriminant $\Delta(f)$ of $f$.

 Orientation and spin structure

Let $\alpha, \beta, \gamma$ be a basis of $\mathfrak{s u}(2)$ corresponding to infinitesimal right-handed rotations about a right-handed set of orthonormal axes. The infinitesimal group action gives rise to a frame for $T L_{\Delta}$,

$$
\alpha \cdot z, \beta \cdot z, \gamma \cdot z,
$$

where $z \in L_{\Delta}$. Let $\mathfrak{o}_{\Delta}$ be the orientation on $L_{\Delta}$ such that this frame is positively oriented. Let $\mathfrak{s}_{\Delta}$ be the spin structure on $L_{\Delta}$ such that this frame can be lifted to the associated double cover of the frame bundle.

5.2. Axial disks

The following is Definition 2.1 from [43].
Definition 5.7. If $X$ is a complex manifold carrying an action of a compact Lie group $K$ by holomorphic automorphisms, and $L$ is a totally real submanifold which is an orbit of the $K$-action, then we say $(X, L)$ is $K$-homogeneous.
Example 5.8. The pair ( $\mathbb{C} P^3, L_{\Delta}$ ) is $\mathrm{SU}(2)$-homogeneous as explained in Section 3.1.
The following is Definition 2.3 from [43].
Definition 5.9. Let ( $X, L$ ) be $K$-homogeneous. If $u:(D, \partial D) \rightarrow(X, L)$ is a holomorphic disk, and there exists a smooth group homomorphism $R: \mathbb{R} \rightarrow K$ such that (possibly after reparametrizing $u$ ) we have $u\left(e^{i \theta} z\right)=R(\theta) u(z)$ for all $z \in D$ and all $\theta \in \mathbb{R}$, then we say $u$ is axial. Let $\xi \in \mathfrak{f}=\operatorname{Lie}(K)$. We say that $u$ is axial of type $\xi$ if $\dot{R}(0)$ belongs to the orbit of $\xi$ under the adjoint action of $K$.

Thinking of $\mathbb{C} P^1$ as $\mathbb{C} \cup\{\infty\}$, we identify $\mathbb{C} P^1 \simeq S^2$ by stereographic projection from the north pole. Thus, the complex structure on the 2-sphere is given by left-handed rotation around the outward normal by an angle of $\pi / 2$.

For concreteness, we choose $\Delta$ to be the triangle with vertices

$$
c_1=(0,0,1), \quad c_2=\left(\frac{\sqrt{3}}{2}, 0,-\frac{1}{2}\right), \quad c_3=\left(-\frac{\sqrt{3}}{2}, 0,-\frac{1}{2}\right) .
$$


By abuse of notation, we also denote by $\Delta$ the point $\left[c_1, c_2, c_3\right] \in \operatorname{Sym}^3 \mathbb{C} P^1$.
Let $\xi_v \in \mathfrak{s u}(2)$ be the infinitesimal right-handed rotation about the $z$ axis and let $\xi_f \in \mathfrak{s u}(2)$ be the infinitesimal right-handed rotation about the $y$ axis scaled so that for $\xi=\xi_v, \xi_f$, we have $\left\{t \in \mathbb{R}: e^{2 \pi \xi t} \cdot \Delta=\Delta\right\}=\mathbb{Z}$. Thus, $\xi_v, \xi_f$, are generators of rotations about the vertex $c_1$ and the center of the face of the triangle, respectively, as shown in Figure 1.
Example 5.10 (Axial Maslov 2 disk). Consider the homomorphism

$$
R: \mathbb{R} \rightarrow \mathrm{SU}(2)
$$

given by

$$
R(\theta)=e^{\theta \xi_v}
$$


Let $u:(D, \partial D) \rightarrow\left(\mathbb{C} P^3, L_{\Delta}\right)$ be given by $u(z)=e^{-i \xi_v \log z}$. $\Delta$. See below for more explicit formulas. Then $u$ satisfies $u\left(e^{i \theta} z\right)=R(\theta) u(z)$, so it is an axial disk of type $\xi_v$.

Recall we denote by $c_1, c_2, c_3$ the vertices of the triangle $\Delta$. The stereographic projection from the north pole

$$
p: S^2 \rightarrow \mathbb{C} \cup\{\infty\}
$$

is given by

$$
p(x, y, z)= \begin{cases}\frac{x+i y}{1-z}, & z \neq 1 \\ \infty, & z=1\end{cases}
$$

We have

$$
\bar{c}_1:=p\left(c_1\right)=\infty, \quad \bar{c}_2:=p\left(c_2\right)=\frac{1}{\sqrt{3}}, \quad \bar{c}_3:=p\left(c_3\right)=\frac{-1}{\sqrt{3}} .
$$


Since $\xi_v$ is the generator of a rotation about the vertex $c_1$, the flow of $\xi_v$ is given by

$$
\varphi_{\xi_v}^t(w):=e^{\xi_v t} \cdot w=e^{\chi i t} w, \quad w \in \mathbb{C} \cup\{\infty\}
$$

for some $\chi \in \mathbb{R}$. Since $\xi_v$ is normalized so that

$$
\mathbb{Z}=\left\{t \in \mathbb{R}: e^{2 \pi \xi_v t} \cdot \Delta=\Delta\right\}=\left\{t \in \mathbb{R}: \varphi_{\xi_v}^{2 \pi t}\left(\bar{c}_2\right)=\bar{c}_2 \text { or } \bar{c}_3\right\}=\{t \in \mathbb{R}: 2 \pi \chi t \in \pi \mathbb{Z}\}
$$

we have $\chi=\frac{1}{2}$ and

$$
\varphi_{\xi_v}^t(w)=e^{\frac{1}{2} i t} w, \quad w \in \mathbb{C} \cup\{\infty\}
$$


Hence, for $z \in D$, we get

$$
\begin{aligned}
u(z) & =e^{-i \xi_v \log z} \cdot \Delta \\
& =\left[\left[1: \varphi_{\xi_v}^{-i \log z}\left(\bar{c}_1\right)\right],\left[1: \varphi_{\xi_v}^{-i \log z}\left(\bar{c}_2\right)\right],\left[1: \varphi_{\xi_v}^{-i \log z}\left(\bar{c}_3\right)\right]\right] \\
& =\left[[0: 1],\left[1: \sqrt{\frac{z}{3}}\right],\left[1:-\sqrt{\frac{z}{3}}\right]\right] \in \operatorname{Sym}^3\left(\mathbb{C} P^1\right)
\end{aligned}
$$


Hence, we can write $u(z)=\left[0: 1: 0:-\frac{z}{3}\right] \in \mathbb{C} P^3$.
We can describe $u$ geometrically as follows. The boundary of $u$ is obtained by the action of $R(\theta)$ on $\Delta$. Call an isosceles triangle narrow if the congruent sides are longer than the base. A point in the interior of $u$ is described by a narrow isosceles triangle on a great circle where the north pole is the apex. For example, the triangle $c_1 d_2 d_3$ in Figure 2 represents a point in the interior of $u$. Note that as $z \rightarrow 0$, the vertices $c_2$ and $c_3$ move toward the south pole, so $u$ intersects $Y_{\Delta}$ in a single point. So, $[u] \cdot\left[Y_{\Delta}\right] \geq 1$. The proof of Lemma 3.8 in [43] shows that equality holds. Hence, by Lemma 5.5, $u$ is a Maslov 2 disk.

Example 5.11 (Axial Maslov 4 disk). Consider the homomorphism

$$
R: \mathbb{R} \rightarrow \mathrm{SU}(2),
$$

given by

$$
R(\theta)=e^{\theta \xi_f}
$$


The disk $u:(D, \partial D) \rightarrow\left(\mathbb{C} P^3, L_{\Delta}\right)$ given by $u(z)=e^{-i \xi_f \log z} \cdot \Delta$ satisfies $u\left(e^{i \theta} z\right)=R(\theta) u(z)$, so it is axial of type $\xi_f$.

We can describe $u$ geometrically as follows. The boundary of $u$ is obtained by the action of $R(\theta)$ on $\Delta$. The interior of $u$ is given by all the equilateral triangles on northern lines of latitude if we take $r:=(0,-1,0)$ for the north pole. For example, the triangle $s_1 s_2 s_3$ in Figure 3 represents an interior point of $u$. Since $u$ intersects $N_{\Delta}$ at the unique point $[r, r, r]$, it follows by Lemma 5.6 that $[u] \cdot\left[Y_{\Delta}\right] \geq 2$. The proof of Lemma 3.8 in [43] shows that equality holds. Hence, by Lemma 5.5, $u$ is a Maslov 4 disk.
