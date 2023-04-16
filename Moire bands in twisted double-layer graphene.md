# Moiré bands in twisted double-layer graphene

双层石墨烯出现转角时, 在整体层面会出现摩尔纹.

## Abstract
>A moiré pattern is formed when two copies of a periodic pattern are overlaid with a relative twist. 
We address the electronic structure of a twisted two-layer graphene system, showing that in its continuum Dirac model the moiré pattern periodicity leads to moiré Bloch bands.
The two layers become more strongly coupled and the Dirac velocity crosses zero several times as the twist angle is reduced.
For a discrete set of magic angles the velocity vanishes, the lowest moiré band flattens, and the Dirac-point density-of states and the counterflow conductivity are strongly enhanced.

译:

当一个周期性图案的两个副本以相对扭曲的方式叠加在一起时, 就会形成摩尔纹图案.
我们讨论了扭曲的两层石墨烯系统的电子结构, 表明在其连续的狄拉克模型中, 摩尔纹的周期性导致了摩尔布洛赫带.
两层石墨烯变得更加强烈的耦合, 并且随着扭曲角度的减小, 狄拉克速度多次过零.
对于一组离散的魔角, 速度消失, 最低的摩尔带变平, 迪拉克点状态密度和逆流电导率强烈增强.

>Low-energy electronic properties of few layer graphene (FLG)
systems are known (1–8) to be strongly dependent on stacking
arrangement. 
In bulk graphite 0° and 60° relative orientations of the individual layer honeycomb lattices yield rhombohedral and Bernal crystals, but other twist angles also appear in many samples (9). Small twist angles are particularly abundant in epitaxial graphene layers grown on SiC (10, 11), but exfoliated bilayers can also appear with a twist, and arbitrary alignments between adjacent layers can be obtained by folding a single graphene layer(12, 13)

译:

众所周知（1-8）, 少层石墨烯（FLG）系统的能量电子特性在很大程度上取决于堆叠排列.
在散装石墨中, 单个层蜂窝状晶格的0°和60°相对方向产生斜方体和贝纳尔晶体, 但其他扭曲角也出现在许多样品中（9）.在SiC上生长的外延石墨烯层中, 小扭曲角特别多（10, 11）, 但剥离的双层也会出现扭曲, 而且相邻层之间的任意排列可以通过折叠单个石墨烯层获得（12, 13）.

>**贝纳尔晶体**
>
>是一种液体流体现象, 它在一定条件下会形成有规律的细胞状结构, 这些细胞状结构有明确的界限, 形状规则, 大小一致, 并且呈现出有序的排列.

>Recent advances in FLG preparation methods have attracted theoretical attention (14–20) to the intriguing electronic properties of systems with arbitrary twist angles, usually focusing on the two-layer case.
The geometry of the bilayer system is characterized by a twist angle θ and by a translation vector d. 
Commensurability is determined only by θ.
Sliding one layer with respect to the other in a commensurate structure modifies the unit cell but leaves the bilayer crystalline. 
In this work we find it convenient to regard the AB stacking as the aligned configuration. The positions of the carbon atoms in the two misaligned layers labeled by R and R' are then related by $\vec{R'}=M(θ)(\vec{R}-τ)+\vec{d}$, where M is a 2-D rotation matrix within the graphene plane, and τ is a vector connecting the two atoms in the unit cell.

译:

最近FLG制备方法的进展, 吸引了理论界对任意扭曲角下系统的有趣电子特性的关注(14-20).(特别是双层系统的情况)
双层系统的几何特征是由扭曲角θ和平移矢量d决定的.在这项工作中, 我们发现将AB堆叠视为对齐的配置是很方便的.
在两个错位的层中, 碳原子的位置由R和R'标记, 然后由$\vec{R'}=M(θ)(\vec{R}-τ)+\vec{d}$公式进行关联, 其中M是石墨烯平面内的2维旋转矩阵, τ是连接单元格中两个原子的矢量.

>The problem is mathematically interesting because a bilayer forms a two-dimensional crystal only at a discrete set of commensurate rotation angles; 
for generic twist angles Bloch’s theorem does not apply microscopically and direct electronic structure calculations are not feasible. 
For twist angles larger than a few degrees the two layers are electronically isolated to a remarkable degree, except at a small set of angles which yield low-order commensurate structures (16, 19). 
As the twist angles become smaller, interlayer coupling strengthens, and the quasiparticle velocity at the Dirac point begins to decrease.

译:

这个问题在数学上是有趣的, 因为双层晶体只在一组**离散的**相称旋转角下形成；对于一般的扭转角, 布洛赫定理在显微镜下并不适用, 直接的电子结构计算是不可行的.对于大于几度的扭转角, 除了在一小部分产生低阶相称结构的角度外, 两层的电子隔离程度很高（16, 19）.随着扭曲角的变小, 层间耦合加强, 迪拉克点的准粒子速度开始下降.

~~人话:~~

~~θ减小的时候,层间相互作用增强,狄拉克点就是能带的零点,零点向动量原点移动,也就是对应的准速度降低了.~~

>Here we focus on the strongly coupled small twist angle regime. We derive a low-energy effective Hamiltonian valid for any value of d and for θ ≲ 10° irrespective of whether or not the bilayer structure is periodic. We show that it is meaningful to describe the electronic structure using Bloch bands even for incommensurate twist angles and study the dependence of these bands on θ.

译:

在此, 我们重点讨论强耦合的小扭曲角机制.
我们推导出了一个低能量条件下的有效哈密顿量(对任何d值和θ≲10°都有效,无论双层结构是否是周期性的).
我们证明, 即使对于不相称的扭转角, 用布洛赫带描述电子结构也是有意义的, 并研究了这些能带对θ的依赖性.

---
## Model 模型

>We construct a low-energy continuum model Hamiltonian that consists of three terms: two single-layer Dirac–Hamiltonian terms that account for the isolated graphene sheets and a tunneling term that describes hopping between layers. The Dirac–Hamiltonian (21) for a layer rotated by an angle θ with respect to a fixed coordinate system is
$v_k=$
>$$vk\begin{bmatrix}
0 & e^{i(θ_{k}-θ)}\\
e^{i(θ_{k}-θ)} & 0\\
\end{bmatrix}$$
>where v is the Dirac velocity, k is momentum measured from the layer’s Dirac point, θk is the momentum orientation relative to the x axis, and the spinor Hamiltonian acts on the individual layer’s A and B sublattice degrees-of-freedom. We choose the coordinate system depicted in Fig. 1 for which the decoupled bilayer Hamiltonian is $|1>h(θ/2)<1|+|2>h(-θ/2)<2|$, where $|i><i|$ projects onto layer $i$.

译:

我们构建了一个低能连续模型下的哈密顿量, 它由三个项组成：两个单层狄拉克-哈密顿项(代表孤立的石墨烯层), 一个"Tunneling"项(~~TUNNEL可以理解为隧穿的过程~~), 描述层间的跳跃.相对于固定坐标系, 旋转一个角度θ的层的狄拉克-哈米顿项（21）为$v_k=$ 
$$vk\begin{bmatrix} 
0 & e^{i(θ_{k}-θ)}\\
e^{i(θ_{k}-θ)} & 0\\ 
\end{bmatrix}$$
其中v是狄拉克速度,k是从层的狄拉克点测得的动量, θk是相对于X轴的动量方向, 自旋体哈密尔顿作用于各个层的A和B子晶格自由度.
我们选择图1中描述的坐标系, 对于该坐标系, 解耦双层哈密顿式为
$|1>h(θ/2)<1|+|2>h(-θ/2)<2|$, 
其中$|i><i|$ 投射到层 $i$

>We derive a continuum model for the tunneling term by assuming that the interlayer tunneling amplitude between π-orbitals is a smooth function $t(r)$ of spatial separation projected onto the graphene planes.
The matrix element
$T_{\vec{k}\vec{p'}}^{αβ}=<Ψ_{\vec{k}}^{(1)}|H_{T}|Ψ_{\vec{p'}β}^{(2)}>$
of the tunneling Hamiltonian HT describes a process in which an electron with momentum $\vec{p'}=M\vec{p}$ residing on sublattice β in one layer hops to a momentum state $\vec{k}$ and sublattice α in the other layer. 
In a π-band tight-binding model the projection of the wave functions of the two layers to a given sublattice are
$|\Psi_{\vec{k}α}^{(1)}=\frac{1}{\sqrt{N}}∑_{\vec{R}}e^{i\vec{k}(R+\tau_{α})}|\vec{R}+τ_{α}>$
and
$|\Psi_{\vec{p}β}^{(2)}=\frac{1}{\sqrt{N}}∑_{\vec{R'}}e^{i\vec{p}(R'+\tau_{β}')}|\vec{R'}+τ_{β}>$

译:

我们假设π轨道之间的层间跃迁振幅是投射到石墨烯平面上的空间分离的平滑函数$t(r)$, 
从而得到了层间跃迁项的连续模型.
层间跃迁项哈密顿量
$H_{T}$
的矩阵元素

$T_{\vec{k}\vec{p'}}^{αβ}=<Ψ_{\vec{k}}^{(1)}|H_{T}|Ψ_{\vec{p'}β}^{(2)}>$

描述了一个过程, 其中一个具有
$\vec{p'}=M\vec{p}$
动量的电子在一层的子晶格β上跳到另一层的动量态
$\vec{k}$
和子晶格α上. 
在一个π带紧-结合模型中, 两层的波函数对一个给定的子晶格的投射为

$|\Psi_{\vec{k}α}^{(1)}=\frac{1}{\sqrt{N}}∑_{\vec{R}}e^{i\vec{k}(R+\tau_{α})}|\vec{R}+τ_{α}>$ and $|\Psi_{\vec{p}β}^{(2)}=\frac{1}{\sqrt{N}}∑_{\vec{R'}}e^{i\vec{p}(R'+\tau_{β}')}|\vec{R'}+τ_{β}>$

>Here $τ_{A}=0$,$ τ_{B}=τ$, and $\vec{R}$ is summed over the triangular Bravais lattice.
Substituting Eqs. 2 and 3 in Eq. 1 and invoking the twocenter approximation,
$<\vec{R}+\tau_{α}|H_{T}|\vec{R'}+τ_{α}-\vec{R'}-τ'_{β}>$
for the interlayer hopping amplitude in which t depends on the difference between the positions of the two carbon atoms we find that
>
>$T_{\vec{k}\vec{p'}}^{αβ}=∑_{\vec{G_{1}}\vec{G_{2}}}\frac{t_{\overline{k}+\vec{G}}}{Ω}e^{i[\vec{G_{1}}τ_{α}-\vec{G_2}(τ_{β}-τ)-\vec{G'_{2}}\vec{d}]}δ_{\overline{k}+\vec{G_{1}},\overline{p'}+\vec{G'_{2}}}$
>
>Here Ω is the unit cell area, 
$t_{\vec{q}}$
is the Fourier transform of the tunneling amplitude 
$t(\vec{r})$, the vectors 
$\vec{G_{1}}$
and $\vec{G_{2}}$ are summed over reciprocal lattice vectors, and 
$\vec{G'_{2}}=M\vec{G_{2}}$.
The bar notation over momenta in Eq. 5 indicates that momentum is measured relative to the center of the Brillouin zone and not relative to the Dirac point. 
Note that crystal momentum is conserved by the tunneling process because 
$t$
depends only on the difference between lattice positions.

译:

这里Ω是单位晶胞面积, 
$t_{\vec{q}}$
是层间跃迁振幅
$t(\vec{r})$
的傅里叶变换, 向量
$\vec{G_{1}}$
和
$\vec{G_{2}}$
是倒数晶格向量的总和, 
$\vec{G'_{2}}=M\vec{G_{2}}$.
公式5中动量的上划线表示:动量是相对于布里渊区的中心而不是相对于狄拉克点(能带零点)测量的. 
注意:晶体动量在层间跃迁过程中是守恒的, 因为$t$只取决于晶格位置的差异.

>The continuum model for 
$H_{T}$ 
is obtained by measuring wave vectors in both layers relative to their Dirac points and assuming that the deviations are small compared to Brillouin-zone dimensions. 
The model’s utility rests centrally on the observation that, although 
$t_{q}$ 
is not precisely known, 
it should nevertheless fall to zero very rapidly with $q$ on the reciprocal lattice vector scale. 
This behavior follows from the property that the graphene layer separation 
$d_{\perp}$ 
exceeds the separation between carbon atoms within the layers by more than a factor of 2.

译:

$H_{T}$
的**连续模型**就可以通过测量两层中相对于其狄拉克点的波矢量(同时假设它与布里渊区尺寸相比偏差很小)得到. 
该模型的效用集中体现在这样的观察上：
即使$t_{q}$并不精确, 但它应该随着倒格子矢量尺度上的$q$增大而迅速下降到零.
这一行为来自于石墨烯层的分离度
$d_{\perp}$
超过层内碳原子之间分离度2倍以上的特性.

>Because the two-center integral 
$t(r)$ 
varies with the three-dimensional separation 
$R = \sqrt{r^2+d_{\perp}^2}$ 
the strong small $r$ hopping processes vary with $r$ on the scale of 
$d_{\perp}$. 
For this reason 
$t_{q}$ 
begins to decline rapidly for 
$qd_{\perp} > 1$. 
Fig. 2 plots 
$t_{q}$ 
values obtained numerically from the π-band tight-binding models proposed in refs.19, 22, and 23. 
The largest 
$t_{q}$ 
values that enter the tunneling near the Dirac point have 
$q=k_{D}$, 
the Brillouin-zone corner (Dirac) wave vector magnitude, 
and correspond to the three reciprocal vectors 
$\vec{0}$, $\mathcal{G}^{(2)}$ and $\mathcal{G}^{(3)}$ 
where the latter two vectors connect a Dirac point with its equivalent first Brillouin-zone counterparts (See Fig. 1).

译:

由于两中心积分(指的是计算两个中心之间的积分, 比如原子核或者分子之间.需要用到密度泛函理论)
$t(r)$
随三维分离度
$R=sqrt{r^2+d_{perp}^2}$
的变化而变化, 所以强的小的$r$跳跃过程在
$d_{perp}$
的尺度上随$r$变化.
因此, 
$t_{q}$
在
$qd_{\perp}> 1$
时开始迅速下降.
图2显示了π带的紧束缚模型(参考文献19、22和23中提出的)中以数值方式计算而来的
$t_{q}$
值. 
在狄拉克点附近进入层间跃迁的最大的
$t_{q}$值是$q=k_{D}$, 
即布里渊区角(狄拉克)波矢量大小, 对应于三个倒格子矢量
$vec{0}$、$\mathcal{G}^{(2)}$
和
$\mathcal{G}^{(3)}$, 
其中后两个矢量分别连接狄拉克点和其等同的第一布里渊区对应点(参见图1).

>When only these terms are retained,
>
>$T^{αβ}(\vec{r})=w∑_{j=1}^{3}e^{-i\vec{q_{i}}\cdot\vec{r}}T_{j}^{αβ},$
>
>where $w=t_{k_{D}}/Ω$ 
is the hopping energy,
>
>$$
T_{1}=\begin{bmatrix} 
1 & 1\\
1 & 1\\ 
\end{bmatrix},
T_{2}=
e^{-i\mathcal{G}^{(2)'}\cdot\vec{d}}\begin{bmatrix} 
e^{-iϕ} & 1\\
e^{iϕ} & e^{-iϕ}\\ 
\end{bmatrix},
T_{3}=
e^{-i\mathcal{G}^{(3)'}\cdot\vec{d}}\begin{bmatrix} 
e^{iϕ} & 1\\
e^{-iϕ} & e^{iϕ}\\ 
\end{bmatrix},$$
>
>and ϕ = 2π∕3. The three 
$\vec{q_{j}}$’s in Eq. 6 are 
Dirac model momentum transfers that correspond to the three interlayer hopping processes.

译:

当只保留这些项时,
$T^{αβ}(\vec{r})=w∑_{j=1}^{3}e^{-i\vec{q_{i}}\cdot\vec{r}}T_{j}^{αβ}$,
其中
$w=t_{k_{D}}/Ω$
是跃迁动能,

$$
T_{1}=\begin{bmatrix} 
1 & 1\\
1 & 1\\ 
\end{bmatrix},
T_{2}=
e^{-i\mathcal{G}^{(2)'}\cdot\vec{d}}\begin{bmatrix} 
e^{-iϕ} & 1\\
e^{iϕ} & e^{-iϕ}\\ 
\end{bmatrix},
T_{3}=
e^{-i\mathcal{G}^{(3)'}\cdot\vec{d}}\begin{bmatrix} 
e^{iϕ} & 1\\
e^{-iϕ} & e^{iϕ}\\ 
\end{bmatrix},$$

并且
$ϕ = 2π∕3$。
公式6中的三个
$\vec{q_{j}}$
是狄拉克模型的动量转移，对应于三种层间跃迁过程。

>For $\vec{d}=0$ and a vanishing twist angle the continuum tunneling matrix is 
$3wδ_{αA}δ_{βB}$, 
independent of position. 
By comparing with the experimentally known (24) electronic structure of an AB stacked bilayer we set $w ≈ 110 meV$ for exfoliated samples, 
however experiments suggest (25) that $w$ may be smaller in some epitaxial graphene samples. 
As we show below the spectrum is independent of $\vec{d}$ for $\theta\neq 0$. In the following we therefore set $\vec{d}=0$.

译:

对于
$\vec{d}=0$
和扭转角度为零的情况，连续隧穿矩阵为
$3wδ_{αA}δ_{βB}$,
并且这个量与位置无关。
通过与已知的"AB-堆叠"方式的双层材料的电子结构 (24) 进行比较，
我们设 $w\approx 110\text{ meV}$ 用于剥落的样品，
然而实验表明 (25) 在一些外延石墨烯样品中 $w$ 可能更小。
正如我们下面所展示的，当
$\theta\neq 0$，
光谱与 $\vec{d}$ 无关。因此，在接下来的讨论中，我们不妨设 $\vec{d}=0$。

---
## Results

### Moiré Bloch Bands

>In the continuum model hopping is local and periodic, allowing Bloch’s theorem to be applied at any rotation angle irrespective of whether or not the bilayer is crystalline. 
We solve numerically for the moiré bands using the plane wave expansion illustrated in Fig. 1. 
Convergence is attained by truncating momentum space at lattice vectors of the order of 
$w/\hbar v$. 
The dimension of the matrix, which must be diagonalized numerically, is roughly 
$∼10 \theta^{-2}$ for small
$\theta$ (measured in degrees), compared to the $∼10^{4} \theta^{-2}$ matrix dimension of microscopic tight-binding models (14, 16).

译:

在连续模型中，跃迁具有局域性(或者说定域性)和周期性，这使得布洛赫定理在任何旋转角下都能应用，无论双层膜是否具有晶体结构。 
如图一所示,我们使用**平面波级数展开**的方式对摩尔纹带进行数值求解。 
通过将动量空间截断在大小为 $w/\hbar v$ 的晶格矢量处，可以实现收敛.
对于小的 $\theta$ (单位为度),
该矩阵(数值求解对角化,从而得到摩尔纹带的能带结构)的维数大约为 $∼10 \theta^{-2}$，相比于微观紧束缚模型下的 
$∼10^{4} \theta^{-2}$ 的矩阵维数更小 (14, 16)。

>Up to a scale factor the moiré bands depend on a single parameter 
$\alpha=w/vk_{\theta}$. 
We have evaluated the moiré bands as a function of their Brillouin-zone momentum $k$ for many different twist angles; 
results for $w = 110 meV$, and 
$θ = 5°$, $1.05°$, and $0.5°$ are summarized in Fig. 3. 
For large twist angles the low-energy spectrum is virtually identical to that of an isolated graphene sheet, except that the velocity is slightly renormalized. 
Large interlayer coupling effects appear only near the high energy van Hove singularities discussed by Andrei and coworkers (26). 
As the twist angle is reduced, the number of bands in a given energy window increases and the band at the Dirac point narrows. 
This narrowing has previously been expected to develop monotonically with decreasing $θ$.

译:

只要不超过某个比例因子,摩尔纹带都将仅取决于唯一参数
$\alpha=w/vk_{\theta}$。 
我们将摩尔纹带视为其布里渊区动量$k$的函数,
并且对这个函数在许多不同扭曲角下的情况进行了评估.
图3总结了
$w=110 meV$，且
$θ=5°$,1.05°$和0.5°$的结果。 
如果旋转角很大，低能带几乎与单层石墨烯相同，只是速度需要略微重整化。 
大的层间耦合效应只会出现在高能范霍夫奇点附近(这一观点由Andrei及其合作者讨论得出(26))。 
随着扭转角的减少，在一个给定的能量窗口中，带的数量增加，在狄拉克点的带变窄。
这种变窄以前被认为是随着$θ$的减少而单调地发展。

>**范霍夫奇点**
>
>晶格的布里渊区边界处的特殊点，此时电子的态密度会发生突变。这种突变可以是因为在此处出现了能带的极值点，也可以是因为能带的疏密程度在此处发生了变化。

>As illustrated in Fig. 3, we instead find that the Dirac-point velocity vanishes already at $θ ≈ 1.05°$, and that the vanishing velocity is accompanied by a very flat moiré band which contributes a sharp peak to the Dirac-point density-of-states (DOS).
At smaller twists the Dirac-point velocity has a nonmonotonic dependence on $\theta$, vanishing repeatedly at the series of magic angles illustrated in Fig. 4.

译:

如图3所示，我们发现狄拉克点速度在
$θ≈1.05°$
时就已经消失了，而且速度的消失伴随着一个非常平坦的摩尔带，为狄拉克点态密度贡献了一个尖锐的峰值。 
在更小的旋转角下，狄拉克点速度对
$\theta$
有一个非单调的依赖(实际上就是反复波动,只能看出有多个零点)，
在图4所示的一系列魔角处反复为0(也就是所谓的"消失")。

>Partial insight into the origin of these behaviors can be achieved by examining the simplest limit in which the momentum-space lattice is truncated at the first honeycomb shell. 
Including the sublattice degree of freedom, this truncation gives rise to the Hamiltonian
>
>$$
\mathcal{H}_{\vec{k}}=\begin{bmatrix} 
h_{\vec{k}}(\theta/2) & T_{b} & T_{tr} & T_{tl}\\
T_{b}^{\dagger} & h_{\vec{k}_{b}}(-\theta/2) & 0 & 0\\
T_{tr}^{\dagger} & 0 & h_{\vec{k}_{tr}}(-\theta/2) & 0\\
T_{tl}^{\dagger} & 0 & 0 & h_{\vec{k}_{tl}}(-\theta/2)\\ 
\end{bmatrix}
>$$,
>
>where $\vec{k}$ is in the moiré Brillouin-zone and 
$\vec{k}_{j}=\vec{k}+\vec{q}_{j}$. 
This Hamiltonian acts on four two-component spinors 
$\Psi=(\psi_{0},\psi_{1},\psi_{2},\psi_{3})$. 
The first ($\psi_{0}$) is at a momentum near the Dirac point of one layer and the other three $\psi_{j}$ are at momenta near $\vec{q}_{j}$ and in the other layer. 
The dependence of $h(\theta)$ on angle is parametrically small and can be neglected. 
We have numerically verified that this approximation reproduces the velocity with reasonable accuracy down to the first magic angle (Fig. 4, Inset).

译:

如果采用最简单的截断方法(即选取动量空间晶格中的第一个蜂巢壳处)来取极限, 
我们可以对这些特性的起源有部分了解. 
将子晶格的自由度也考虑在内，这种截断就产生了哈密顿量的表达式

$$
\mathcal{H}_{\vec{k}}=\begin{bmatrix} 
h_{\vec{k}}(\theta/2) & T_{b} & T_{tr} & T_{tl}\\
T_{b}^{\dagger} & h_{\vec{k}_{b}}(-\theta/2) & 0 & 0\\
T_{tr}^{\dagger} & 0 & h_{\vec{k}_{tr}}(-\theta/2) & 0\\
T_{tl}^{\dagger} & 0 & 0 & h_{\vec{k}_{tl}}(-\theta/2)\\ 
\end{bmatrix}
$$,

其中
$\vec{k}$
处于摩尔布里渊区，
$\vec{k}_{j}=\vec{k}+\vec{q}_{j}$。 
这个哈密顿量作用于四个双分量自旋子
$\Psi=(\psi_{0},\psi_{1},\psi_{2},\psi_{3})$。 
第一个（$\psi_{0}$）是在一个某层石墨烯狄拉克点附近的动量，
其他三个
$\psi_{j}$
则是在
$\vec{q}_{j}$
附近的动量,
位置则是在另一层石墨烯中。 
$h(\theta)$
对角度的依赖性在参数上很小,所以可以忽略不计。 
我们已经用数值验证了,这种近似方法直到第一个魔转角都能以合理的精度重现了速度.（图4，插图）。

>The renormalized velocity $v^{\star}=\partial_{\vec{k}}\epsilon_{\vec{k}}^{\star}|_{\vec{k}=0}$ follows from the spectrum 
$\epsilon_{\vec{k}}^{\star}$ 
of the twisted bilayer. 
The Hamiltonian is expressed as a sum of the $\vec{k}=0$ term 
$\mathcal{H}^{(0)}$ 
and the k-dependent term $\mathcal{H}_{\vec{k}}^{(1)}$ and solved to leading order in $\vec{k}$. 
Consider the $\vec{k}=0$ term in the Hamiltonian. 
We assume that 
$\mathcal{H}^{(0)}$ 
has zero energy eigenstates and prove our assumption by explicitly finding these states. 
The zero energy eigenstates must satisfy
>
>$\psi_{j}=-h_{j}^{-1}T_{j}^{\dagger}\psi_{0}$.

译:

我们可以从转角双层石墨烯的能谱
$\epsilon_{\vec{k}}^{\star}$
得到重整化后的速度
$v^{\star}=\partial_{\vec{k}}\epsilon_{\vec{k}}^{\star}|{\vec{k}=0}$。
该哈密顿量被表示为
$\vec{k}=0$
的项
$\mathcal{H}^{(0)}$
以及依赖于$k$的项
$\mathcal{H}{\vec{k}}^{(1)}$
的和，并在
$\vec{k}$
的级数展开上求解。
我们考虑哈密顿量中的
$\vec{k}=0$
项.
我们假设
$\mathcal{H}^{(0)}$
有零能量的本征态(我们将找到这些态以证明这个假设)。
零能量本征态必须满足:

$\psi_{j}=-h_{j}^{-1}T_{j}^{\dagger}\psi_{0}$。[9]

>Because
>
>$T_{j}h_{j}^{-1}T_{j}^{\dagger}=0$
>
>the equation for the 
$\psi_{0}$ 
spinor is $h_{0}\psi_{0}=0$, i.e., 
$\psi_{0}$ is one of the two zero energy states 
$\psi_{0}^{(1)}$ and $\psi_{0}^{(2)}$ of the isolated layer. 
The two zero energy eigenstates of 
$\mathcal{H}^{(0)}$ 
then follow from Eq. 9. 
Given that $|\psi_{0}^{(j)}|=1$, the wave functions should be normalized by 
$|\Psi|^{2}=1+6\alpha^{2}$. 
The effective Hamiltonian matrix to leading order in $k$ is therefore
>
>$\langle\Psi^{(i)}|\mathcal{H}_{\vec{k}}^{(1)}|\Psi^{(j)}\rangle=$
>
>$\frac{-v}{1+6\alpha^2}\psi_{0}^{(j)\dagger}[\sigma\cdot\vec{k}+w^2\sum_{j}T_{j}h_{j}^{-1\dagger}\sigma\cdot\vec{k}h_{j}^{-1}T_{j}^{\dagger}]\psi_{0}^{(j)}$
>
>$=-v^{\star}\psi_{0}^{(j)\dagger}\sigma\cdot\vec{k}\psi_{0}^{(j)}$.

译:

由于

$T_{j}h_{j}^{-1}T_{j}^{\dagger}=0$，

因此
$\psi_{0}$ 的自旋轨道满足 $h_{0}\psi_{0}=0$，
即 $\psi_{0}$ 是孤立层的两个零能态 $\psi_{0}^{(1)}$ 和 $\psi_{0}^{(2)}$ 之一。
然后，根据式子[9]，可以得到 $\mathcal{H}^{(0)}$ 的两个零能量本征态。
考虑到 $|\psi_0^{(j)}|=1$，波函数应当通过 $|\Psi|^{2}=1+6\alpha^2$
进行归一化。因此，在$k$的一阶导数方面的有效哈密顿矩阵为：

$\langle\Psi^{(i)}|\mathcal{H}_{\vec{k}}^{(1)}|\Psi^{(j)}\rangle=$
$\frac{-v}{1+6\alpha^2}\psi_{0}^{(j)\dagger}[\sigma\cdot\vec{k}+w^2\sum_{j}T_{j}h_{j}^{-1\dagger}\sigma\cdot\vec{k}h_{j}^{-1}T_{j}^{\dagger}]\psi_{0}^{(j)}$
$=-v^{\star}\psi_{0}^{(j)\dagger}\sigma\cdot\vec{k}\psi_{0}^{(j)}$.

>Aside from a renormalized velocity
>
>$\frac{v^{\star}}{v}=\frac{1-3\alpha^2}{1+6\alpha^2}$
>
>the Hamiltonian is identical to the continuum model Hamiltonian of single-layer graphene. 
The denominator in Eq. 11 captures the contribution of the $\Psi_{j}$ ’s to the normalization of the wave function whereas the numerator captures their contribution to the velocity matrix elements. 
For small $\alpha$, Eq. 11 reduces to the expression $v^{\star}/v=1-9\alpha^2$, first obtained by Lopes dos Santos et al. (15). 
The velocity vanishes at the first magic angle because it is in the process of changing sign. 
The eigenstates at the Dirac point are a coherent combination of components in the two layers that have velocities of opposite sign.

译:

除了一个经过重整化的速度

$\frac{v^{\star}}{v}=\frac{1-3\alpha^2}{1+6\alpha^2}$，

哈密顿量与单层石墨烯的连续模型哈密顿量相同。
在方程式11中，分母体现的是 $\Psi_j$ 对波函数归一化的贡献，而分子体现的是到它们对速度矩阵元的贡献。
对于小的 $\alpha$，方程式11简化为 $v^\star/v=1-9\alpha^2$(该式由Lopes dos Santos等人首次得到)。
在第一个魔转角处速度降为0，因为它正在变号。
在Dirac点处的本征态是两个石墨烯层中速度具有相反符号的组分的相干组合。

~~人话:~~

~~每个石墨烯层中只有一个态,而两个石墨烯层进行比较的时候,两个态的速度异号,~~
~~在Dirac点处的本征态是这两个态的线性组合.~~

### Counterflow Conductivity.

>**Counterflow Conductivity**
>
>当两个电子系统在相反方向移动时，它们之间的电导率。在材料物理学中，常常通过测量两个相反方向移动的电子系统之间的电导率来研究电子的输运性质。当两个电子系统的速度相等但方向相反时，它们之间的电导率通常会非常小，这种现象被称为“counterflow conductivity suppression”。这种效应在石墨烯等二维材料中经常被观察到，并且对于研究这些材料的电子输运性质非常重要。

>The distribution of the quasiparticle velocity between the two layers implies exotic transport characteristics for separately contacted layers. 
Consider a counterflow geometry in which currents in the two layers flow antiparallel to one another. 
We focus on twist angles $θ ≳ 2°$ for which the eightband model is valid and to the semiclassical regime in which $\epsilon_{F}\tau >1$ and find the counterflow conductivity $\sigma_{CF}$. 
We assume that the Fermi momentum is much smaller than $k_{\theta}$ and that $1/\tau_{0}<\hbar vk_{\theta}$, where $\tau_{0}$ is single particle lifetime. 
Using the Kubo formula we find that
>
>$\sigma_{CF}=\frac{4e^{2}}{\pi}\sum_{\vec{k}\mu}|\langle\psi_{k}|v_{VF}^{x}|\psi_{k}\rangle|^2[Im\{G_{k\mu}^{r}(\epsilon_{F})\}]$
>
>where
>
>$$
v_{CF}^{x}=-v\begin{bmatrix} 
\sigma_{x} & 0 & 0 & 0\\
0 & -\sigma_{x} & 0 & 0\\
0 & 0 & -\sigma_{x} & 0\\
0 & 0 & 0 & -\sigma_{x}\\
\end{bmatrix},
>$$
>
>is the x component of the counterflow velocity operator (we set the electric fields along the x axis), $G_{k\mu}^{r}(\omega)=(\omega-\epsilon_{k\mu}^{\star}+i/2\tau_{0})^{-1}$ is the retarded Green function with $\mu$ labeling the two Dirac bands, and $\epsilon_{k\mu}^{\star}=\mu v^{\star}k$ is the energy dispersion of the twisted bilayer at small momenta.

译:

在两层之间准粒子速度的分布意味着分别接触的层具有奇特的输运特性。
考虑一种反流几何形状，其中两层中的电流彼此反向流动。
我们关注扭转角 $θ ≳ 2°$，其中八带模型有效且处于半经典状态，此时 $\epsilon_{F}\tau >1$，并找到了反流电导 $\sigma_{CF}$。

>**八带模型**
>
>“八带模型”是一种用于描述扭曲双层石墨烯的理论模型。在这个模型中，每个石墨烯层的两个Dirac点之间的相互作用被考虑在内，因此会出现四个价带和四个导带，共计八个带。相比于单层石墨烯的两个带（一个价带和一个导带），八带模型提供了更为准确的描述扭转双层石墨烯的方式。在八带模型中，每个带的色散关系（即能量与动量的关系）由一组非常复杂的解析式给出。八带模型的具体公式实际上就是本文所给出的 $\sigma_{CF}$ 的表达式.

我们假设费米动量远小于 $k_{\theta}$，并且 $1/\tau_{0}<\hbar vk_{\theta}$，其中 $\tau_{0}$ 是单粒子寿命。使用Kubo公式，我们得到：

$\sigma_{CF}=\frac{4e^{2}}{\pi}\sum_{\vec{k}\mu}|\langle\psi_{k}|v_{VF}^{x}|\psi_{k}\rangle|^2[Im\{G_{k\mu}^{r}(\epsilon_{F})\}]$

其中，

$$
v_{CF}^{x}=-v\begin{bmatrix} 
\sigma_{x} & 0 & 0 & 0\\
0 & -\sigma_{x} & 0 & 0\\
0 & 0 & -\sigma_{x} & 0\\
0 & 0 & 0 & -\sigma_{x}\\
\end{bmatrix},
$$

是反流速度算符的x分量(我们将电场设置在x轴上)，
$G_{k\mu}^{r}(\omega)=(\omega-\epsilon_{k\mu}^{\star}+i/2\tau_{0})^{-1}$ 是带有 
$\mu$ 标签的逆变换格林函数，表示两个Dirac带的能量色散，
$\epsilon_{k\mu}^{\star}=\mu v^{\star}k
$是小动量条件下转角双层石墨烯的能量色散。