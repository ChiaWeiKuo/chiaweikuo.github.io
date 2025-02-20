---
permalink: /Publications/
---

The journal/conference papers I have published are shown below.  


# (2022) A maximum entropy formalism model for the breakup of a droplet
Chia-Wei Kuo and Mario F. Trujillo, "A maximum entropy formalism model for the breakup of a droplet", <i>Physics of Fluids</i>. Vol. 34, 013315, 2022.

[Access the paper](https://aip.scitation.org/doi/10.1063/5.0076910)

A model for the prediction of the size and velocity distribution of daughter droplets created by the breakup of an unstable parent droplet is proposed. The basis of the model is the maximum entropy formalism, which states that the most probable joint probability density function (JPDF) for the daughter droplet population is the one that maximizes the Bayesian entropy conditional on the enforcement of a set of constraints, which are the conservation laws for the problem. The result is a closed-form expression for the JPDF. Validation against experimental and Direct Numerical Simulations data over the bag, multimode, and sheet-thinning breakup regimes is included. Predictions from the model show that the daughter droplet velocity distribution widens as the droplet size decreases. This result is due to a heightened sensitivity to drag force with lower droplet inertia and coincides with spray behavior. The velocity distribution is found to be near Gaussian. The model does not treat size and velocity as independently distributed, as generally assumed in the literature. In fact, marginal conditional densities derived from JPDF show that the distribution of size and velocity are interrelated.


<p align="center">
<img src='https://github.com/ChiaWeiKuo/chiaweikuo.github.io/blob/master/images/breakUp1.png' width="50%">
<img src='https://github.com/ChiaWeiKuo/chiaweikuo.github.io/blob/master/images/breakUp2.png' width="50%">
</p>


&nbsp;
&nbsp;

---


# (2021) An analysis of the performance enhancement with adaptive mesh refinement for spray problems
Chia-Wei Kuo and Mario F. Trujillo, "An analysis of the performance enhancement with adaptive mesh refinement for spray problems", <i>International Journal of Multiphase Flow</i>. Vol. 140, 103615, 2021.

[Access the paper](https://www.sciencedirect.com/science/article/abs/pii/S030193222100063X?via%3Dihub)

Adaptive mesh refinement (AMR) provides an attractive means of significantly reducing computational costs while simultaneously maintaining a high degree of fidelity in regions of the domain requiring it. In the present work, an analysis of the performance of AMR supported by simulations is undertaken for liquid injection and spray formation problems. These problems are particularly challenging from a computational cost perspective since the associated interfacial area typically grows by orders of magnitude, leading to similar growth in the number of highly refined cells. While this increase in cell numbers directly contributes to a declining performance for AMR, a second less obvious factor is the decaying trend for the cell-based speedup...

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/AMR_1.png' width="75%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/AMR_2.png' width="50%">
</p>


&nbsp;
&nbsp;

---

# (2020) A maximum-entropy-formalism for secondary droplet nreakup
Chia-Wei Kuo and Mario F. Trujillo, "A maximum-entropy-formalism for secondary droplet nreakup", <i>ILASS-Americas Annual Conference on Liquid Atomization and Spray Systems</i>. 2020.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/publications/2020-breakUp.pdf)

In Lagrangian-Eulerian spray simulations, the secondary breakup of the atomized droplets is typically han- dled by an atomization model, such as the Kelvin-Helmholtz Rayleigh-Taylor model or the Taylor Analogy Breakup model . This problem is revisited in this paper by imposing a joint probability density function (JPDF) over the size and velocity spaces of the droplets and enforcing the conservation constraints of mass, momentum, and energy. Five different models are proposed and tested. In the first three models, the size distribution is given in the form of the Nukiyama-Tanasawa, diameter-dependent Rosin-Rammler, and mass-dependent Rosin-Rammler distri- butions. For droplet velocity, a Dirac delta function centered on the parent droplet is assumed. The results show poor agreement with the experimental measurements. The next two models are based on the Maximum Entropy Methodology (MEM), which is contingent upon maximizing the Shannon entropy of the JPDF. In the first MEM model, the MEM is only applied to the size distribution while the velocity distribution is assumed to be a Dirac delta function. In the second MEM model, the size and velocity distributions are assumed to be fully coupled. Only the second MEM model agrees with the experimental measurements over a wide range of Weber numbers. Also, the second MEM model confirms the expected trend of a reduction of droplet size as the degree of droplet breakup intensity increases.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2020-breakUp-1.png' width="45%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2020-breakUp-2.png' width="45%">
</p>


&nbsp;
&nbsp;

---

# (2019)  Evaluation and validation of large-eddy simulation sub-grid spray dispersion models using high-fidelity volume-of-fluid simulation data and engine combustion network experimental data
Chi-Wei Tsang, Chia-Wei Kuo, Mario Trujillo, Christopher Rutland, "Evaluation and validation of large-eddy simulation sub-grid spray dispersion models using high-fidelity volume-of-fluid simulation data and engine combustion network experimental data," <i>International Journal of Engine Research</i>. Vol. 20(6), pg. 583-605, 2019.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/files/2018-Tsang-IJER.pdf)

A sub-grid model accounting for the interaction of spray and sub-grid turbulence was developed and tested. The model predicts the sub-grid scale dispersion velocity used for calculating the slip velocity in Lagrangian–Eulerian Large-eddy simulation spray models. The dispersion velocity is assumed to be decomposed into a deterministic and a stochastic part, and it is updated in every turbulence correlation time for each computational parcel. The model was validated against two datasets: volume-of-fluid simulations and Engine Combustion Network experiments. The volume-of-fluid data showed that dispersion velocities at the centerline are anisotropic. This qualitative feature is well captured by the current model. For the Engine Combustion Network Spray A cases, it was found that sub-grid scale dispersion has profound impact on the prediction of the spatial distribution of liquid mass. Neglecting the sub-grid scale dispersion model results in underprediction of the width of the lateral projected liquid mass density profiles. Also, the prediction of the projected liquid mass density is sensitive to the two model constants determining the sub-grid scale dispersion velocity magnitude and turbulence time scale. However, the predictions of resolved gas-phase statistics are relatively insensitive to different sub-grid scale dispersion model setups. The primary reason for this was investigated. It was found that the motion of high-momentum liquid blobs in the near-nozzle region leading to air entrainment and subsequent gas jet development is minimally influenced by sub-grid scale dispersion. The importance of sub-grid scale dispersion inversely correlates with drag force magnitude: the larger the drag force, the less critical the sub-grid scale dispersion. Moving further downstream, quasi-equilibrium between the two phases is established, resulting in relatively small slip velocity and drag force.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/IJER-1.png' width="80%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/IJER-2.png' width="80%">
</p>

&nbsp;
&nbsp;

---

# (2018)  Benefits of AMR for Atomization Calculations
Chia-Wei Kuo and Mario Trujillo, "Benefits of AMR for Atomization Calculations," <i>ICLASS 2018, 14th Triennial International Conference on Liquid Atomization and Spray Systems</i>. 2018.


[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/files/2018-CFD.pdf)

Adaptive mesh refinement (AMR) has been introduced as an attractive means of significantly improving com- putational efficiency for a variety of two-phase flow problems. In the current study, the benefits of AMR are investigated for the case of liquid jet atomization. The evaluation consists of a systematic analysis of results from the interDymFoam (AMR octree) and interFoam (static octree) codes, both of which form part of the family of solvers distributed within the open source OpenFOAM C++ Toolbox. The two-phase flow treatment is based on an algebraic VoF methodology. As a preliminary set of exercises, cases for pure advection, stationary wave dynamics, and Rayleigh-Plateau breakup of a cylindrical liquid element are considered. The results from these exercises confirm the expected trend of higher numerical efficiency in AMR, while still retaining essen- tially the same level of accuracy as the fixed embedded mesh solutions. However, for the liquid jet atomization, the behavior is a bit more complicated. First, at lower levels of Weber number, we observe a similar trend as the preliminary exercises. At higher Weber numbers, due to a noticeable increase in interfacial area density, sub- stantial inhomogeneities are formed in the underlying grids yielding slower solutions of pressure Poisson equa- tion, thereby potentially offsetting the benefits of this approach. In fact, at much higher Weber numbers, for instance, those pertaining to Diesel injection, the results suggest that a fixed embedded mesh would provide better computational efficiency. However, this conclusion depends on the target lowest level of numerical resolution, Δxmin. The current work shows how the efficiency of AMR suffers from increasing interfacial area density, and how this can be alleviated via a decrease in Δxmin. Various test cases are presented to illustrate this effect.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2018-CFD-figure.png' width="100%">
</p>


&nbsp;
&nbsp;

---



# (2015) In-situ measurements of solar diffuse fraction in southern Taiwan
Chia-Wei Kuo and Keh-Chin Chang, "In-situ measurements of solar diffuse fraction in southern Taiwan", <i>Journal of the Chinese Institute of Engineers</i>. Vol. 38(6), pg. 723-730, 2015.

[Access the paper](https://www.tandfonline.com/doi/abs/10.1080/02533839.2015.1016880?journalCode=tcie20)

Information on diffuse fraction is vital for solar energy applications using concentrating techniques such as concentrating photovoltaic and concentrating solar power. To provide this information for Taiwan, in situ measurements of solar diffuse fraction have been conducted at the Kuei-Jen campus of the National Cheng Kung University, Tainan since 2011. Calculations of the daily, monthly, and annual average diffuse fractions were made with five various sunshine durations centered at the solar noon in the years of 2011 and 2012. It was found that the mean value of annual diffuse fractions of these two years counting from sunrise to sunset is 0.543, while this value is reduced, to a small extent (<6%), with use of shorter duration in the calculation. A more confident information of diffuse fraction in Taiwan remains to be made through use of a database of a typical meteorological year, which is as yet unavailable.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/JCIE-2.png' width="50%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/JCIE-1.png' width="50%">
</p>


&nbsp;
&nbsp;

---

# (2015) Fin designs of TEFC motor heat dissipation enhancement
Chia-Wei Kuo and Mei-Jiau Huang, "Fin designs of TEFC motor heat dissipation enhancement", <i>The 22th National Computational Fluid Dynamics Conference, New Taipei City, Taiwan</i>. 2015.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/publications/2015-CFD.pdf)

Literature on the study of fins for heat transfer enhancement mainly focused on the low speed airflow for small electronic devices. For heat removal from large devices such as TEFC motors, studies were limited. In this work, several fin designs based on the dimensions of the TECO TEFC motor were attempted and studied numerically in use of the commercial software ANSYS. The simulation system consists of flat-plate fins periodically mounted on the frame and a wind shield; Fig.1 shows one period of the system. Cold air of 298K at speed Uin = 20m/s is directed into the flow channels between fins to cool the hot area maintained at 333K of the frame, which has an area of L X P . The remaining part of the frame is insulated. The RNG k-epsilon model was used, in conjunction with the standard wall function, to capture the turbulent effect. A 3D hybrid mesh composed of structured as well as unstructured grids was employed for spatial discretization. No-slip boundary conditions were imposed at all solid walls.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/2015-CFD-image.png' width="90%">
</p>


&nbsp;
&nbsp;


---

# (2014) Modeling the hourly solar diffuse fraction in Taiwan
Chia-Wei Kuo, Wen-Chey Chang, and Keh-Chin Chang, "Modeling the hourly solar diffuse fraction in Taiwan", <i> Renewable Energy</i>. Vol. 66, pg. 56-61, 2014.

[Access the paper](https://www.sciencedirect.com/science/article/abs/pii/S0960148113006605)

Using the data for global and diffuse radiation in Tainan, Taiwan, for the years of 2011 and 2012, respectively, four correlation models with five predictors: the hourly clearness index (kt), solar altitude, apparent solar time, daily clearness index and a measure of persistence of global radiation level, are constructed to relate the hourly diffuse fraction on a horizontal surface (d) to the clearness index. Two models use a single logistic equation for all kt values, Eqs. (6), (7), and the other two models use a set of piece-wise linear equations for four kt intervals, Eqs. (8), (9). The proposed models are compared respectively with the fourteen models available in the literature, in terms of the four statistical indicators: the mean bias error, the root-mean-square error, the t-statistic and the Bayesian Information Criterion, using the out-of-sample dataset for Tainan, Taiwan. It is concluded from the analysis that the proposed piece-wise linear models perform well in predicting the diffuse fraction, while the performances of the proposed logistic models are more case-dependent. Among those fourteen models considered in this study, the models developed by Erbs et al., Chandrasekaran and Kumar, and Boland et al. have competitive performances as the proposed piece-wise linear models do, when applying to the prediction of diffuse fraction in Tainan, Taiwan.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/Renewable-1.png' width="80%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/Renewable-2.png' width="100%">
</p>


&nbsp;
&nbsp;

---


# (2014) The design and optical analysis of compound parabolic collector
Chia-Wei Kuo, Pei-Shan Yen, Wen-Chey Chang, and Keh-Chin Chang, "The design and optical analysis of compound parabolic collector,"<i> Procedia Engineering</i>. Vol. 79, pg. 258-262, 2014.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/files/2014-CWK-Procedia-Engineer.pdf)

---
For various applications of solar thermal energy, the compound parabolic collector (CPC) is frequently used. To overcome the major limits of a traditional CPC, including a rapid increase in height for a larger aperture width and a low concentration ratio, a modified design was proposed in this paper. This research follows the recent study of Jadhav et al., which used only the region below the common focus of parabolas. Through optical analysis, a design modification was achieved by adjusting the vertical position of the receiver. From the results, setting the height of the receiver to 0.46 times the aperture width was found to permit a greater collection range of incident rays. In addition, a better method for evaluating the performance of the CPC was proposed using an intercept factor to account for the total reflection phenomenon caused by the receiver. By applying the approach to different cases of focal length, it was shown that the concentration ratio was not strongly affected by an increasing focal length owing to the low correlation between the concentration ratio and focal length.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/CPC-1.png' width="45%">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/CPC-2.png' width="100%">
</p>


&nbsp;
&nbsp;

---

# (2014) Distribution of solar diffuse fraction in Taiwan
Chia-Wei Kuo, Wen-Chey Chang, and Keh-Chin Chan, "Distribution of solar diffuse fraction in Taiwan", <i> Energy Procedia</i>. Vol. 57, pg. 1120-1129, 2014.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/files/2014-CWK-Energy-Procedia.pdf)

A simple polynomial model of the sky clearness index as predictor was proposed in this paper, for estimating the hourly solar diffuse fractions in Taiwan. The error analysis was performed through two statistical indicators, the mean bias error and the root-mean-square error. The out of database validation was also made to confirm the model generality. Next, regressions between monthly averaged conditions and geographical parameters of places (latitude, longitude, and elevation above sea level) were discussed, using the model's estimates and the updated data sets of typical solar radiation year. Based on the results, diffuse fraction maps for two observation periods were presented in 1-km resolution via an aid of linear interpolation.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/Diffuse-Map.png' width="85%">
</p>


&nbsp;
&nbsp;

---


# (2013) Modeling of heat transfer in an industrial electric oven
Chia-Wei Kuo, Yu-Cheng Liu, and Wen-Chey Chang, "Modeling of heat transfer in an industrial electric oven", <i> The 20th National Computational Fluid Dynamics Conference, Nantou, Taiwan</i>. 2013.

[Access the paper](https://phxiranter.github.io/chiaweikuo.github.io/files/2013-CFD.pdf)

The thermal dissipation performance of an industrial electric oven is studied. It is shown from the experimental measurements that the temperature variations inside the oven can reach 20 K, which is determinantal to the thermal collection efficiency of the oven. We employ ANSYS Fluent to establish a 3D computational fluid dynamics (CFD) model to cope with the problem. The simulation results show that the poor thermal insulation at oven door slots is the main reason behind this uneven temperature distribution problem. A modified oven design is then proposed using the CFD model. Compared with the original design, a more uniform temperature distribution could be reached using the modified design.

<p align="center">
<img src='https://phxiranter.github.io/chiaweikuo.github.io/images/oven_design.png' width="60%">
</p>
