# Moiré bands in twisted double-layer graphene

双层石墨烯出现转角时，在整体层面会出现摩尔纹。

## Abstract
>A moiré pattern is formed when two copies of a periodic pattern are overlaid with a relative twist. 
We address the electronic structure of a twisted two-layer graphene system, showing that in its continuum Dirac model the moiré pattern periodicity leads to moiré Bloch bands.
The two layers become more strongly coupled and the Dirac velocity crosses zero several times as the twist angle is reduced.
For a discrete set of magic angles the velocity vanishes, the lowest moiré band flattens, and the Dirac-point density-of states and the counterflow conductivity are strongly enhanced.

译:

当一个周期性图案的两个副本以相对扭曲的方式叠加在一起时，就会形成摩尔纹图案。
我们讨论了扭曲的两层石墨烯系统的电子结构，表明在其连续的狄拉克模型中，摩尔纹的周期性导致了摩尔布洛赫带。
两层石墨烯变得更加强烈的耦合，并且随着扭曲角度的减小，狄拉克速度多次过零。
对于一组离散的魔角，速度消失，最低的摩尔带变平，迪拉克点状态密度和逆流电导率强烈增强。

>Low-energy electronic properties of few layer graphene (FLG)
systems are known (1–8) to be strongly dependent on stacking
arrangement. 
In bulk graphite 0° and 60° relative orientations of the individual layer honeycomb lattices yield rhombohedral and Bernal crystals, but other twist angles also appear in many samples (9). Small twist angles are particularly abundant in epitaxial graphene layers grown on SiC (10, 11), but exfoliated bilayers can also appear with a twist, and arbitrary alignments between adjacent layers can be obtained by folding a single graphene layer(12, 13)

译:

众所周知（1-8），少层石墨烯（FLG）系统的能量电子特性在很大程度上取决于堆叠排列。
在散装石墨中，单个层蜂窝状晶格的0°和60°相对方向产生斜方体和贝纳尔晶体，但其他扭曲角也出现在许多样品中（9）。在SiC上生长的外延石墨烯层中，小扭曲角特别多（10，11），但剥离的双层也会出现扭曲，而且相邻层之间的任意排列可以通过折叠单个石墨烯层获得（12，13）。

>**贝纳尔晶体**
>
>是一种液体流体现象，它在一定条件下会形成有规律的细胞状结构，这些细胞状结构有明确的界限，形状规则，大小一致，并且呈现出有序的排列。

>Recent advances in FLG preparation methods have attracted theoretical attention (14–20) to the intriguing electronic properties of systems with arbitrary twist angles, usually focusing on the two-layer case.
The geometry of the bilayer system is characterized by a twist angle θ and by a translation vector d. 
Commensurability is determined only by θ.
Sliding one layer with respect to the other in a commensurate structure modifies the unit cell but leaves the bilayer crystalline. 
In this work we find it convenient to regard the AB stacking as the aligned configuration. The positions of the carbon atoms in the two misaligned layers labeled by R and R' are then related by $\vec{R'}=M(θ)(\vec{R}-τ)+\vec{d}$, where M is a 2-D rotation matrix within the graphene plane, and τ is a vector connecting the two atoms in the unit cell.

译:

最近FLG制备方法的进展, 吸引了理论界对任意扭曲角下系统的有趣电子特性的关注(14-20).(特别是双层系统的情况)
双层系统的几何特征是由扭曲角θ和平移矢量d决定的。在这项工作中，我们发现将AB堆叠视为对齐的配置是很方便的。
在两个错位的层中，碳原子的位置由R和R'标记，然后由$\vec{R'}=M(θ)(\vec{R}-τ)+\vec{d}$公式进行关联，其中M是石墨烯平面内的2维旋转矩阵，τ是连接单元格中两个原子的矢量。

>The problem is mathematically interesting because a bilayer forms a two-dimensional crystal only at a discrete set of commensurate rotation angles; 
for generic twist angles Bloch’s theorem does not apply microscopically and direct electronic structure calculations are not feasible. 
For twist angles larger than a few degrees the two layers are electronically isolated to a remarkable degree, except at a small set of angles which yield low-order commensurate structures (16, 19). 
As the twist angles become smaller, interlayer coupling strengthens, and the quasiparticle velocity at the Dirac point begins to decrease.

译:

这个问题在数学上是有趣的，因为双层晶体只在一组**离散的**相称旋转角下形成；对于一般的扭转角，布洛赫定理在显微镜下并不适用，直接的电子结构计算是不可行的。对于大于几度的扭转角，除了在一小部分产生低阶相称结构的角度外，两层的电子隔离程度很高（16，19）。随着扭曲角的变小，层间耦合加强，迪拉克点的准粒子速度开始下降。

~~人话:~~

~~θ减小的时候,层间相互作用增强,狄拉克点就是能带的零点,零点向动量原点移动,也就是对应的准速度降低了.~~

>Here we focus on the strongly coupled small twist angle regime. We derive a low-energy effective Hamiltonian valid for any value of d and for θ ≲ 10° irrespective of whether or not the bilayer structure is periodic. We show that it is meaningful to describe the electronic structure using Bloch bands even for incommensurate twist angles and study the dependence of these bands on θ.

译:

在此，我们重点讨论强耦合的小扭曲角机制。
我们推导出了一个低能量条件下的有效哈密顿量(对任何d值和θ≲10°都有效,无论双层结构是否是周期性的)。
我们证明，即使对于不相称的扭转角，用布洛赫带描述电子结构也是有意义的，并研究了这些能带对θ的依赖性。

## Model 模型

>We construct a low-energy continuum model Hamiltonian that consists of three terms: two single-layer Dirac–Hamiltonian terms that account for the isolated graphene sheets and a tunneling term that describes hopping between layers. The Dirac–Hamiltonian (21) for a layer rotated by an angle θ with respect to a fixed coordinate system is
$v_k=$
>$$vk\begin{bmatrix}
0 & e^{i(θ_{k}-θ)}\\
e^{i(θ_{k}-θ)} & 0\\
\end{bmatrix}$$
>where v is the Dirac velocity, k is momentum measured from the layer’s Dirac point, θk is the momentum orientation relative to the x axis, and the spinor Hamiltonian acts on the individual layer’s A and B sublattice degrees-of-freedom. We choose the coordinate system depicted in Fig. 1 for which the decoupled bilayer Hamiltonian is $|1>h(θ/2)<1|+|2>h(-θ/2)<2|$, where $|i><i|$ projects onto layer $i$.

译:

我们构建了一个低能连续模型下的哈密顿量，它由三个项组成：两个单层狄拉克-哈密顿项(代表孤立的石墨烯层)，一个"Tunneling"项(~~TUNNEL可以理解为隧穿的过程~~)，描述层间的跳跃。相对于固定坐标系，旋转一个角度θ的层的狄拉克-哈米顿项（21）为$v_k=$ 
$$vk\begin{bmatrix} 
0 & e^{i(θ_{k}-θ)}\\
e^{i(θ_{k}-θ)} & 0\\ 
\end{bmatrix}$$
其中v是狄拉克速度,k是从层的狄拉克点测得的动量，θk是相对于X轴的动量方向，自旋体哈密尔顿作用于各个层的A和B子晶格自由度。
我们选择图1中描述的坐标系，对于该坐标系，解耦双层哈密顿式为
$|1>h(θ/2)<1|+|2>h(-θ/2)<2|$，
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

我们假设π轨道之间的层间跃迁振幅是投射到石墨烯平面上的空间分离的平滑函数$t(r)$，
从而得到了层间跃迁项的连续模型。
层间跃迁项哈密顿量
$H_{T}$
的矩阵元素
$T_{\vec{k}\vec{p'}}^{αβ}=<Ψ_{\vec{k}}^{(1)}|H_{T}|Ψ_{\vec{p'}β}^{(2)}>$
描述了一个过程，其中一个具有
$\vec{p'}=M\vec{p}$
动量的电子在一层的子晶格β上跳到另一层的动量态
$\vec{k}$
和子晶格α上。 
在一个π带紧-结合模型中，两层的波函数对一个给定的子晶格的投射为
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

这里Ω是单位晶胞面积，
$t_{vec{q}}$
是层间跃迁振幅
$t(\vec{r})$
的傅里叶变换，向量
$vec{G_{1}}$和$vec{G_{2}}$
是倒数晶格向量的总和，
$vec{G'_{2}}=Mvec{G_{2}}$。
公式5中动量的上划线表示:动量是相对于布里渊区的中心而不是相对于狄拉克点(能带零点)测量的。 
注意:晶体动量在层间跃迁过程中是守恒的，因为$t$只取决于晶格位置的差异。

>