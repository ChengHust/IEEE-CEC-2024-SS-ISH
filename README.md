# IEEE-CEC-2023-Competition
The Platform for CEC 2023 Competition on "Large-scale Continuous Optimization for Non-contact Measurement"

## Overview & Aim:
***
Evolutionary algorithms (EAs) have been a popular optimization tool for decades, showing their promising performance in solving various benchmark optimization problems. Nevertheless, using EAs on continuous optimization with over 100 decision variables (large-scale optimization problems, LSOPs) remains challenging due to the "curse of dimensionality". This phenomenon is more significant for those LSOPs in emerging applications, e.g., lightweight vehicle design, industrial power delivery and scheduling, smart grid optimization, and data sensitivity analysis. Specifically, LSOPs in emerging applications are challenging due to the enormous search space, irregularity in variable interactions and objective functions, and the existence of massive local optima. Conventional EAs may cost unbearable function evaluations (FEs) and computation time to obtain acceptably converged/diverse results. In extreme scenarios, most EAs fail to converge to the optima no matter how many FEs are consumed, or may fail to obtain enough diversity information for decision-making. The design of practical EAs for solving LSOPs in real-world applications is urgent and meaningful.
***
IntelliSense is an emerging topic in recent years, which plays a crucial part in intelligent sensing for modern industry and society, e.g., Internet of Things (IoT), smart grids, and intelligent robots. Among various IntelliSense scenarios, the non-contact measurement in electronic engineering has shown its great potential and importance. As the most extensive man-made system in the world, the modern electric system requires the measurement of voltages and currents accurately and safely in real time. How to non-contact measure voltages and currents in a bundle of conductors enclosed in a structure has been an emerging topic in power distribution, power electronics, and power quality evaluation, to mention just a few fields of interest. The use of computational intelligence techniques, especially evolutionary computation, starts a new direction for non-contact measurement. Specifically, the black-box measurement task can be solved by EAs only, and the system can access real-time information with the assistance of effective and efficient EAs. Also, the non-contact measurement can be extended to other areas for intelligent sensing.
***
In this competition, there are two tracks: large-scale continuous single- and multi-objective optimization in two non-contact measurement cases. We carefully select six LSOPs for each track from two tasks, i.e., non-contact voltage measurement for multiconductor systems (NVM) and non-contact current measurement for multiconductor systems (NIM).

- The NVM takes advantage of the electric field around the conductors for estimating the ground truth voltage values. This NVM problem includes two types of decision variables, i.e., fixed positions of the conductors and time-varying ground truth voltage values. Generally, the variable interactions are complex in the NVM problem. First, the six position variables interact with each other. Second, the voltages in each phase interact with each other sequentially but do not interact with the voltages in other phases. Third, all the voltages are directly interacting with the positions. An illustrative example of the principle for NVM problems is given in Fig. 1.


%Fig. 1 The principle of the NVM problems.   |  % Details.
:-------------------------:|:-------------------------:
![](https://github.com/ChengHust/IEEE-CEC-2023-Competition/blob/main/NVM.png) | (a) Cross section of three-phase systems and sensors; (b) the distribution of the measured electric field (EF) and the measured and calculated EF intensities around the housing; (c) the three-phase voltages obtained by minimizing the EF intensities in (b).
