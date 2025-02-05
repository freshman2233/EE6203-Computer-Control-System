#  EE6203-Computer Control System

# 1.Introduction

**EE6203: Computer Control System** course provides a comprehensive foundation in understanding and designing **systems**, emphasizing both theoretical concepts and practical applications.

Drawing on years of established exam patterns and materials, the course delves into the fundamentals of discrete-time system modeling and analysis (using **Z-transforms, difference equations, and stability criteria**), explores various controller design methods (including **traditional z-domain designs, frequency-response approaches, and state-space techniques**), and addresses **optimal control strategies**. 

With a focus on the implementation of digital controllers and deeper topics such as pole placement, controllability, and observability, **EE6203** equips graduate students with the knowledge and skills to excel in designing advanced computer-controlled systems.

The 6203 exam questions are relatively fixed, and we can find the rules of solving the questions from the past 15 to 23 years.

This repository serves as a comprehensive resource for students and enthusiasts alike. 

1. **Personal Solutions to Past Exams** – Detailed, step-by-step write-ups of previously tested questions to guide your revision and deepen conceptual understanding.
2. **PPT Example References** – Walkthroughs of example problems and exercises presented in the lecture slides, clarifying key ideas and methodologies.
3. **Analysis of Challenging Topics** – In-depth discussions and breakdowns of complex areas, helping you navigate common pitfalls and master advanced concepts.

Accompanying the lectures is a curated GitHub repository offering step-by-step solutions to past examinations, example problems drawn from lecture PPTs, and in-depth discussions of challenging areas. Students can use these resources to reinforce their understanding, prepare for exams, and develop proficiency in every aspect of computer control system design.

If you happen to have a GitHub account and find this repository helpful, **please consider giving it a star⭐**.	

![2-min](./README.assets/2-min.jpg)

# 2.**Course Aims**

Control systems exist everywhere in our society. 

Practically all control systems that are implemented today are based on computer control. It is therefore important to understand computer-controlled systems well. 

The purpose of the subject is to provide a thorough background for understanding, analyzing and designing of computer-controlled systems. 

Graduate students who need to be equipped with the control theory that is relevant to the analysis and design of computer-controlled systems should take this course.



# 3.**Course Content**

Topic 1 Discrete-time system modelling and analysis. 

Topic 2 State-space design methods. 

Topic 3. Optimal control.

Topic 4. Design based on transfer functions.

Topic 5. Implementation of digital controllers



# 4.**Reading and References**

**Textbook:**

1. K. Ogata, Discrete-Time Control Systems, 2nd Edition, Prentice Hall, 1995.
2. Fadali, M. Sami; Visioli, Antonio, Digital Control Engineering - Analysis and Design (e-book), Elsevier, 2013.

**References:**

1. Kannan M. Moudgalya, Digital Control, John Wiley & Sons, Ltd, 2007
2. Computer Controlled Systems : Theory and Design By Karl J Astrom and Bjorn Wittenmark, Dover Publications Inc, 2012, 3rd Edition. (1st Edition, 1984 Published by Prentice Hall)

3. Digital Control Systems by Benjamin C Kuo, Oxford University Press, 2 nd edition, 1995.
4. Digital Control Systems Analysis and Design by Charles L Philips and H Troy Nagle, Pearson Education, 4th edition, 2015.

# 5. Exam scope: All

## 5.1 English

Chapter 1: Introduction to discrete time control systems

1.1 This section describes the discrete time control system

1.2 Type of signal

1.3 Digital control system



Chapter 2: Z-transformation

2.1 Introduction

2.2 Z transformation

2.3 Z-transform of elementary function

2.4 Important properties and theorems of z transformation

2.5 Inverse Z transform

2.6Z Z-transform method for solving difference equations





Chapter 3: Modeling of digital control systems

3.1 Introduction

3.2 Pulse sampling and data retention

3.2.1 ADC pulse sampler

3.2.2. DAC Model

3.3 Pulse transfer function

3.4 Pulse transfer function of digital PID controller





Chapter 4: Analysis of traditional methods for discrete-time control systems

4.1 Introduction

4.2 Mapping between the s and z planes



4.3 Stability analysis of Z-plane closed-loop system

4.3.1Jury stability test

4.3.2 Bilinear transformation and Routh stability criterion are used for stability analysis



4.4 Transient and steady-state response analysis

4.4.1 Technical specifications of transient response

4.4.2 Steady-state error analysis

4.4.3 Static position error constant

4.4.4 Static velocity error constant

4.4.5 Static acceleration error constant

4.4.6 Response to interference



Chapter 5: Design of discrete time controller based on transfer function

5.1 Introduction

5.2 Digital realization of analog controller design

5.2.1 General Process

5.2.2 Mapping method from G(s) to GD(z)

5.2.2.1 Reverse difference Method

5.2.2.2 Forward difference Method

5.2.2.3 Bilinear transformation Method

5.2.2.4 Pole-zero matching



5.3 Direct z domain digital controller design - frequency response design

5.3.1 Frequency response design method

5.3.2 Review of compensator

5.3.3 Review - Frequency domain design for continuous systems

5.3.4 Frequency domain design of digital controllers - Examples



5.4 Direct control design

5.5 Single degree of freedom feedback controller

5.6 Two degrees of freedom feedback controller

5.7 Pole placement controller





Chapter 6: Implementation of digital controller

6.1 Introduction

6.2 General form of transfer function

6.3 Direct Programming

6.4 Standard Programming

6.5 Sources of Error

6.6 Quantization sensitivity analysis of controller coefficients

6.7 Reduce the quantization error of the filter

6.7.1 Series programming

6.7.2 Parallel programming





State space design method and optimal control

1 State variable analysis

1.1 Review continuous time state space representation

1.2 Transfer function of a given state-space model

1.3 Solution of the state vector x(t)





2 Discrete time state space model

2.1 Output of zero-order holder

2.2 Input Matrix

2.3 Φ(t) : State transition matrix

2.4 Discretization of state transition matrix

2.5 Solution of input matrix Θ(T)

2.6 Discretization of the output equation



3 Transfer function, pole, zero

3.1 Poles of discrete-time systems

3.2 Zero point of a discrete-time system

3.3 Transfer function



4 State transition equation

4.1 State transition equation

4.2 Recursive solution

4.3 General solution



5 Similar conversion

5.1 State space model

5.2 Similarity transformation

5.3 Derivation process of the new state space model

5.4 Characteristic polynomial + transfer function unchanged





6 Standard form

6.1 Controllable standard form CCF

6.2 Observable Standard Form (OCF)

6.3 Standard form of transfer function



7 Controller Design

Step 1: Design the status feedback controller

Step 2: Design an observer to estimate the state of the system from available measurements



8 Controllability

1.x(N) : indicates the status when N occurs

2.Wc controllability matrix

3. Controllable pairs: Definitions and theorems



9 Observability

9.1. Given u and y, require x (0)

9.2. The observability matrix Wo has rank n

9.3. Observability definition



10 Relation between controllability, observability and transfer function

10.1 Theorem

10.2 Loss of controllability and/or observability due to sampling



11 State feedback design: K

11.1 Problem Statement

11.2 Pole placement method

11.3 Characteristic polynomial of closed-loop system

11.4 (A, B) The poles can only be placed if a controllable K exists

11.5 Zero points before and after status feedback remain unchanged



12 Ackermann's formula: K method 2

12.1 Ackermann's formula



13 Quick End control

13.1 Non-quick End control

13.2 Quick End Control



14 Observer design

14.1 Motivation

14.2 Problem formulation



15 Predictive observers

15.1(1) Open loop viewer

15.2(2) Closed loop viewer



16 Ackermann formula calculates observer gain Lo

1. L0 = alpha 0 (A) [W0] [01] ^ - 1 ^ T



17 Dimension reduction observer

17.1 Motivation

17.2 Full Order Observer

17.3 Reduced order Observer: Formula

17.4Lr: Calculation formula 1, reduced observer gain

17.5Lr: Calculation formula 2, Ack



18 Current observer

18.1 Introduction

18.2 Estimator Gain Lc: ACK

18.3 Estimation error

18.4 Characteristic polynomials



19 Combination of control law and observer

19.1 Combination of control law and observer

19.2 Transfer functions for combining the controller and the current estimator



20 System with input

20.1r (k) is a scalar system input

20.2 Transfer function of closed loop system



21 integral control

21.1 Integrator

21.2e (k) state vector



22 Optimal control

22.1 Dynamic planning

22.2 Principle of optimality for discrete-time systems

22.3 Discrete linear quadratic regulator based on dynamic programming



23 Solution of discrete Riccati difference equation

23.1K(k): difference equation

23.2S(k) : difference equation

23.3 Discrete Riccati equation

23.4 Infinite Time problem

23.5 Recursive methods



## 5.2 Chinese

章节1：介绍离散时间控制系统 

1.1 介绍离散时间控制系统 

1.2 信号的类型 

1.3 数字控制系统 



章节2：Z变换

2.1 简介 

2.2 Z变换 

2.3初等函数的Z变换 

2.4z变换的重要性质和定理 

2.5逆Z变换 

2.6 Z 求解差分方程的Z变换方法 





章节3：数字控制系统的建模 

3.1 介绍

3.2 脉冲采样和数据保持 

3.2.1 ADC 脉冲采样器 

3.2.2. DAC Model

3.3 脉冲传递函数 

3.4数字PID控制器的脉冲传递函数 





章节4：离散时间控制系统的传统方法分析 

4.1介绍 

4.2 s和z平面之间的映射 



4.3 z平面闭环系统稳定性分析 

4.3.1Jury稳定性测试

4.3.2利用双线性变换和Routh稳定性判据进行稳定性分析 



4.4瞬态和稳态响应分析 

4.4.1瞬态响应技术指标

4.4.2稳态误差分析 

4.4.3静态位置误差常数 

4.4.4静态速度误差常数 

4.4.5静态加速度误差常数 

4.4.6对干扰的响应 



章节5：基于传递函数的离散时间控制器的设计 

5.1介绍

5.2模拟控制器设计的数字化实现

5.2.1一般流程

5.2.2 G(s)到GD(z)的映射方法

5.2.2.1反向差分法

5.2.2.2正向差分法

5.2.2.3双线性变换方法

5.2.2.4极点-零点匹配



5.3直接z域数字控制器设计-频率响应设计

5.3.1频率响应设计方法

5.3.2补偿器的回顾

5.3.3回顾-连续系统的频域设计

5.3.4数字控制器的频域设计—举例



5.4直接控制设计

5.5单自由度反馈控制器

5.6二自由度反馈控制器

5.7极点放置控制器





章节6：数字控制器的实现

6.1介绍

6.2传递函数的一般形式

6.3直接编程

6.4标准编程

6.5误差来源

6.6控制器系数量化敏感性分析

6.7减少滤波器的量化误差

6.7.1系列编程

6.7.2并行编程





状态空间设计方法与最优控制 

1 状态变量分析 

1.1回顾连续时间状态空间表示 

1.2给定状态空间模型的传递函数 

1.3状态向量 x(t)的求解 





2 离散时间状态空间模型 

2.1 零阶保持器的输出 

2.2 输入矩阵 

2.3 Φ(t)：状态转移矩阵

2.4 状态转移矩阵的离散化 

2.5 输入矩阵  Θ(T)的求解 

2.6 输出方程的离散化 



3 传递函数、极点、零点

3.1 离散时间系统的极点

3.2 离散时间系统的零点

3.3 传递函数



4 状态转移方程 

4.1状态转移方程 

4.2 递推解法

4.3一般解法 



5 相似转换 

5.1状态空间模型

5.2相似变换

5.3新状态空间模型的推导过程 

5.4特征多项式+传递函数不变





6 标准形式 

6.1 可控标准形式  CCF 

6.2 可观察标准形式  (OCF)

6.3 传递函数的标准形式 



7 控制器设计 

步骤1:设计状态反馈控制器 

步骤2:设计一个观测器，从可用的测量中估计系统状态 



8 可控制性 

1.x(N)：N时候的状态

2.Wc 可控性矩阵 

3.可控对：定义和定理 



9 可观察性 

9.1.已知u和y，要求x (0)

9.2.可观察性矩阵Wo的秩为n 

9.3.可观察性定义



10 可控性、可观察性与传递函数的关系 

10.1定理

10.2由于采样导致的可控性和/或可观测性的丧失 



11 状态反馈设计：求K

11.1问题表述 

11.2极点布置法 

11.3闭环系统的特征多项式

11.4（A，B）可控K才存在，才能放置极点

11.5 状态反馈前后的零点不变



12 阿克曼的公式 ：求K 法2

12.1 阿克曼的公式 



13 快速终结控制

13.1非快速终结控制

13.2快速终结控制



14 观测器设计 

14.1动机

14.2问题公式化 



15 预测的观察器 

15.1(1)开环观察器

15.2(2)闭环观察器



16 阿克曼公式计算观测器增益Lo

1.L0=α0(A)[W0]^-1[01]^T



17 降维的观察器

17.1动机

17.2全阶观测器

17.3降阶观测器：公式

17.4Lr：计算公式1，降阶观测器增益

17.5Lr：计算公式2，Ack



18 现任观察器

18.1介绍

18.2估计器增益Lc：ACK

18.3估计误差

18.4特征多项式



19 控制律与观测器的组合

19.1控制律与观测器的组合

19.2组合控制器和当前估计器的传递函数



20 带输入的系统

20.1r (k)是一个标量系统输入

20.2闭环系统传递函数



21 积分控制

21.1积分器

21.2e（k）状态向量



22 最优控制 

22.1动态规划

22.2离散时间系统的最优性原理

22.3基于动态规划的离散线性二次型调节器 



23 离散 里卡蒂Riccati 差分方程的解

23.1K(k):差分方程

23.2S(k)：差分方程

23.3离散Riccati方程

23.4无限时间问题

23.5递归方法

# 6.List of GitHub

`````
├─1.final examination questions
│      15-S1-Q1.pdf
│      17-S1-Q1-v4.pdf
│      18-S1-Q1.pdf
│      18-S1-Q2.pdf
│      18-S1-Q3.pdf
│      18-S1-Q4.pdf
│      18-S1-Q5-v2.pdf
│      19-S1-Q1.pdf
│      19-S1-Q2-v7.pdf
│      19-S1-Q3-v7.pdf
│      19-S1-Q4.pdf
│      19-S1-Q5.pdf
│      20-S1-Q1.pdf
│      20-S1-Q2-v5.pdf
│      20-S1-Q3-v2.pdf
│      20-S1-Q4.pdf
│      21-S1-Q1-v4.pdf
│      21-S1-Q2-v6.pdf
│      21-S1-Q3-v3.pdf
│      21-S1-Q4-v2.pdf
│      21-S1-Q5-v6.pdf
│      22-S1-Q1-v4.pdf
│      22-S1-Q2-v5.pdf
│      22-S1-Q3-v6.pdf
│      22-S1-Q4-v8.pdf
│      22-S1-Q5-v8.pdf
│      23-S1-Q1-v10.pdf
│      23-S1-Q2-v5.pdf
│      23-S1-Q3-v4.pdf
│      23-S1-Q4-v4.pdf
│      
├─2.PPT Example
│  ├─1.WCY_Ch1 - 6
│  │      Example2.1.pdf
│  │      Example2.10.pdf
│  │      Example2.11.pdf
│  │      Example2.14.pdf
│  │      Example2.15.pdf
│  │      Example2.16.pdf
│  │      Example2.17.pdf
│  │      Example2.2.pdf
│  │      Example2.3.pdf
│  │      Example2.4.pdf
│  │      Example2.5.pdf
│  │      Example2.6.pdf
│  │      Example2.7.pdf
│  │      Example2.8.pdf
│  │      Example3.1.pdf
│  │      Example3.2.pdf
│  │      Example3.3-v4-答案错了.pdf
│  │      Example3.4.pdf
│  │      Example3.5.pdf
│  │      Example3.6.pdf
│  │      Example4.1-v2.pdf
│  │      Example4.1.2-v2.pdf
│  │      Example4.2-v2.pdf
│  │      Example4.3-v2.pdf
│  │      Example4.4-v2.pdf
│  │      Example4.5-v2.pdf
│  │      Example4.6.pdf
│  │      Example4.7.pdf
│  │      Example4.8-v2.pdf
│  │      Example4.8-v3.pdf
│  │      Example4.9-v2.pdf
│  │      Example4.9-v3.pdf
│  │      Example5.1-v4.pdf
│  │      Example5.10-v2.pdf
│  │      Example5.11-v2.pdf
│  │      Example5.12-v2.pdf
│  │      Example5.13-v3.pdf
│  │      Example5.2-v2.pdf
│  │      Example5.3-v2.pdf
│  │      Example5.4-v2.pdf
│  │      Example5.5-v5.pdf
│  │      Example5.6-v5.pdf
│  │      Example5.7-v3.pdf
│  │      Example5.8-Q.pdf
│  │      Example5.8-v2.pdf
│  │      Example5.9-v2.pdf
│  │      
│  └─2.Ch 5-8 Lee Peng Hin
│          Lect1-Example1.1.pdf
│          Lect1-Example1.2-version2.pdf
│          Lect1-Example1.2.pdf
│          Lect1-Example1.3-version1.pdf
│          Lect1-Example1.3-version2.pdf
│          Lect1-Example1.4-version2.pdf
│          Lect1-Example1.4-version3.pdf
│          Lect1-Example1.4.pdf
│          Lect1-Example1.5-version2.pdf
│          Lect1-Example1.5-version3.pdf
│          Lect1-Example1.5.pdf
│          Lect1-Example1.6-version2.pdf
│          Lect1-Example1.6.pdf
│          Lect1-Example1.7.pdf
│          Lect2-Example2.1.pdf
│          Lect2-Example2.2.pdf
│          Lect2-Example2.3.pdf
│          Lect2-Example2.4.pdf
│          Lect2-Example2.5-Q.pdf
│          Lect2-Example2.6.pdf
│          Lect2-Example2.7.pdf
│          Lect2-Example2.8.pdf
│          Lect3-Example3.1.pdf
│          Lect3-Example3.10.pdf
│          Lect3-Example3.11.pdf
│          Lect3-Example3.12-v2.pdf
│          Lect3-Example3.12.pdf
│          Lect3-Example3.13.pdf
│          Lect3-Example3.2.pdf
│          Lect3-Example3.3.pdf
│          Lect3-Example3.4.pdf
│          Lect3-Example3.5.pdf
│          Lect3-Example3.6.pdf
│          Lect3-Example3.7.pdf
│          Lect3-Example3.8-v2.pdf
│          Lect3-Example3.9.pdf
│          Lect4-Example4.1.pdf
│          Lect4-Example4.2.pdf
│          Lect4-Example4.3.pdf
│          Lect4-Example4.4.pdf
│          Lect4-Example4.5.pdf
│          Lect4-Example4.6.pdf
│          Lect4-Example4.7.pdf
│          Lect4-Example4.8-Q.pdf
│          Lect5-Example5.1.pdf
│          Lect5-Example5.2.pdf
│          Lect5-Example5.3.pdf
│          Lect5-Example5.4.pdf
│          Lect5-Example5.5-Q.pdf
│          
├─3.Understand
│      1.ess 和 est的区别-v3.pdf
│      10.basic function.pdf
│      11.continuous time signal.pdf
│      12.Z transform.pdf
│      13.规格要求.pdf
│      2.带输入系统，传递函数的推导.pdf
│      3.Table3-3的证明，3.3.7.pdf
│      4.终值定理.pdf
│      5. z平面转s平面，damping ratio-v2.pdf
│      6.洛必达使用条件.pdf
│      7.部分分式展开(PFE)方法-为什么X(z)下面要除z.pdf
│      8.系统是type0，1还是2.pdf
│      9.why x拔(0)=0？.pdf
│      EE6203-热门考点分析.xlsx
│      考试附录Appendix.pdf
│      
└─4.Resource
    │  EE6203_OBTL (Abridge).pdf
    │  
    ├─1.BOOK
    │      Katsuhiko Ogata - Discrete-Time Control Systems (Pie)-Pearson Education (1994).pdf
    │      数字信号处理教程 第4版 [程佩青] 2013年版(OCR).pdf
    │      数字图像处理（第三版）(OCR).pdf
    │      离散时间控制系统（第二版） (OCR) (Katsuhiko ； Ogata).pdf
    │      计算机控制系统（第二版）(OCR).pdf
    │      
    ├─2.计算机控制系统
    │  ├─1.东北大学
    │  │  └─1.PPT
    │  │          1.1计算机控制系统课程导学.pdf
    │  │          1.2计算机控制系统内容简介.pdf
    │  │          1.3计算机控制实验系统简介.pdf
    │  │          1.3计算机控制系统的过程通道和总线接口技术.pdf
    │  │          1.4模拟与数字信号之间的相互转换.pdf
    │  │          2.1 信号转换与z变换导学.pdf
    │  │          2.2信号变换分析.pdf
    │  │          2.3z变换与z反变换.pdf
    │  │          2.4信息转换的工程化技术.pdf
    │  │          2.5扩展 z 变换.pdf
    │  │          3.1 计算机控制系统数学描述与性能分析导学.pdf
    │  │          3.2 脉冲传递函数模型的建立.pdf
    │  │          3.3 计算机控制系统的稳定性分析.pdf
    │  │          3.4 计算机控制系统的稳态与暂态性能分析.pdf
    │  │          4.1模块导学.pdf
    │  │          4.2连续控制器的离散化方法.pdf
    │  │          4.3数字PID控制器.pdf
    │  │          4.4Smith预估控制.pdf
    │  │          5.1 数字控制器的直接设计方法导学.pdf
    │  │          5.2 最小拍控制器的设计方法.pdf
    │  │          5.3 最小拍控制器的工程化改进.pdf
    │  │          5.4 大林算法控制器的设计.pdf
    │  │          6.1 基于状态空间模型的极点配置设计方法导学.pdf
    │  │          6.2 离散系统状态空间模型的建立.pdf
    │  │          6.3 状态可测时按极点配置设计控制规律.pdf
    │  │          6.4 按极点配置设计状态观测器.pdf
    │  │          6.5 状态不可测时控制器的设计.pdf
    │  │          
    │  └─2.期末帮
    │          【期末帮】计算机控制系统讲义.pdf
    │          【期末帮】计算机控制系统题库及答案.pdf
    │          
    ├─3.自动控制原理
    │  ├─1.BOOK
    │  │      知识点.pdf
    │  │      自动控制原理（第六版） 胡寿松.txt
    │  │      
    │  ├─2.卢京潮
    │  │      【推荐教材】1.【卢京潮】自动控制原理.pdf
    │  │      【推荐教材】2.【卢京潮】自动控制原理习题解答.pdf
    │  │      卢京潮老师讲义.pdf
    │  │      控制88合并.pdf
    │  │      自控手写笔记.pdf
    │  │      
    │  ├─3.自动控制原理讲义
    │  │  │  自动控制原理期末考试卷与答案.pdf
    │  │  │  
    │  │  ├─课时1
    │  │  │      1结构图化简.pdf
    │  │  │      课时1结构图有注释.pdf
    │  │  │      
    │  │  ├─课时2
    │  │  │      课时2 时域分析含注释.pdf
    │  │  │      
    │  │  ├─课时3
    │  │  │      课时3 根轨迹注释.pdf
    │  │  │      
    │  │  ├─课时4
    │  │  │      第四节bode图练习.pdf
    │  │  │      练习题照片1.png
    │  │  │      练习题照片2.png
    │  │  │      练习题照片3.png
    │  │  │      课时4 频域分析带注释.pdf
    │  │  │      
    │  │  ├─课时5
    │  │  │      校正习题.pdf
    │  │  │      课时5校正含注释.pdf
    │  │  │      
    │  │  └─课时6
    │  │          期末复习带笔记版.pdf
    │  │          自控期末带答案.pdf
    │  │          
    │  └─4.猴博士速成
    │          3 自动控制原理 笔记.pdf
    │          
    ├─4.信号与系统
    │  ├─1.Signal and Systems_MIT_2011
    │  │  ├─1.网上资料
    │  │  │      MIT6_003F11_lec01.pdf
    │  │  │      MIT6_003F11_lec02.pdf
    │  │  │      MIT6_003F11_lec03.pdf
    │  │  │      MIT6_003F11_lec04.pdf
    │  │  │      MIT6_003F11_lec05.pdf
    │  │  │      
    │  │  └─2.笔记
    │  │          MIT6_003F11_lec01.pdf
    │  │          MIT6_003F11_lec02.pdf
    │  │          MIT6_003F11_lec03.pdf
    │  │          MIT6_003F11_lec04.pdf
    │  │          MIT6_003F11_lec05.pdf
    │  │          
    │  ├─2.信号与系统速成
    │  │      信号与系统期末复习.pdf
    │  │      
    │  └─3.西安电子科技大学——信号与系统（郭宝龙）
    │      │  信号与线性系统分析-第五版-吴大正、郭宝龙等(OCR).pdf
    │      │  信号与线性系统分析-第五版-吴大正、郭宝龙等.pdf
    │      │  信号与线性系统分析全程导学及习题全解-第四版-苗明川、高静波(OCR).pdf
    │      │  信号与线性系统分析全程导学及习题全解-第四版-苗明川、高静波.pdf
    │      │  
    │      └─《信号与线性系统分析》郭宝龙老师_课件
    │          │  信号与系统笔记_作者唐维康_李学武版本.pdf
    │          │  
    │          ├─01. 第一章 信号与系统概述
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第1讲  信号的基本概念和分类
    │          │  │      Z1.01-信号的分类-确定与随机-离散与连续.pdf
    │          │  │      Z1.02-信号的分类-周期与非周期.pdf
    │          │  │      Z1.03-信号的分类-能量与功率信号，因果与反因果.pdf
    │          │  │      Z1.04-信号的分类-信号的matlab表示与绘图.pdf
    │          │  │      Z1.05-信号的分类-阶跃函数.pdf
    │          │  │      
    │          │  ├─第2讲  基本信号
    │          │  │      Z1.06-信号的分类-冲激函数.pdf
    │          │  │      Z1.07-冲激函数的广义函数定义.pdf
    │          │  │      Z1.08-冲激函数的取样性质.pdf
    │          │  │      Z1.09-冲激函数的导数.pdf
    │          │  │      Z1.10-冲激函数的尺度变化.pdf
    │          │  │      
    │          │  ├─第3讲  信号的运算
    │          │  │      Z1.11 单位脉冲序列与单位阶跃序列.pdf
    │          │  │      Z1.12 信号的加减乘运算.pdf
    │          │  │      Z1.13 信号的反转.pdf
    │          │  │      Z1.14 信号的平移.pdf
    │          │  │      Z1.15 信号的尺度变化.pdf
    │          │  │      
    │          │  └─第4讲  系统的概念和分类
    │          │          Z1.16 系统定义与典型系统举例.pdf
    │          │          Z1.17 线性系统与非线性系统.pdf
    │          │          Z1.18 时变系统与时不变系统.pdf
    │          │          Z1.19 因果与非因果系统.pdf
    │          │          
    │          ├─02. 第二章 连续系统的时域分析
    │          │  ├─第5讲  LTI连续系统的描述
    │          │  │      Z2.01 连续系统的描述：电路图建立微分方程.pdf
    │          │  │      Z2.02 微分方程的模拟框图.pdf
    │          │  │      Z2.03 微分方程的经典解法.pdf
    │          │  │      Z2.04 连续系统的初始值.pdf
    │          │  │      
    │          │  ├─第6讲  LTI连续系统的响应
    │          │  │      Z2.05.pdf
    │          │  │      Z2.06.pdf
    │          │  │      Z2.07.pdf
    │          │  │      Z2.08.pdf
    │          │  │      Z2.09.pdf
    │          │  │      Z2.10.pdf
    │          │  │      Z2.11.pdf
    │          │  │      
    │          │  ├─第7讲  卷积积分的定义和性质
    │          │  │      Z2.12.pdf
    │          │  │      Z2.13.pdf
    │          │  │      Z2.14.pdf
    │          │  │      Z2.15.pdf
    │          │  │      Z2.16.pdf
    │          │  │      Z2.17.pdf
    │          │  │      
    │          │  ├─第8讲  卷积积分的应用
    │          │  │      Z2.18.pdf
    │          │  │      Z2.19.pdf
    │          │  │      Z2.20.pdf
    │          │  │      Z2.21.pdf
    │          │  │      Z2.22.pdf
    │          │  │      Z2.23.pdf
    │          │  │      Z2.24.pdf
    │          │  │      Z2.25.pdf
    │          │  │      
    │          │  └─第9讲  连续系统的微分算子
    │          │          Z2.26-对通信信道的不利影响进行建模.pdf
    │          │          Z2.27-多径传输中的失真问题.pdf
    │          │          Z2.28-微分算子P的定义.pdf
    │          │          Z2.29-微分算子的性质.pdf
    │          │          Z2.30-传输算子H(P).pdf
    │          │          Z2.31-RLC微分算子模型及算子方程建立.pdf
    │          │          
    │          ├─03. 第三章 离散系统的时域分析
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第10讲 差分方程的建立和经典解法
    │          │  │      Z3.01-离散系统的解析描述—建立差分方程.pdf
    │          │  │      Z3.02-差分方程的模拟框图.pdf
    │          │  │      Z3.03-差分方程的经典解法.pdf
    │          │  │      Z3.04-零输入响应的定义和求解.pdf
    │          │  │      Z3.05-零状态响应的定义和求解.pdf
    │          │  │      Z3.06-菲波那契（Fibonacci）数列问题..pdf
    │          │  │      
    │          │  ├─第11讲 离散系统的描述和基本信号
    │          │  │      Z3.07-简单空运控制系统..pdf
    │          │  │      Z3.08-RC取样输入和输出关系.pdf
    │          │  │      Z3.09-Matlab求解离散系统的零状态响应.pdf
    │          │  │      Z3.10-离散信号表示.pdf
    │          │  │      Z3.11-单位脉冲序列.pdf
    │          │  │      Z3.12-单位阶跃序列.pdf
    │          │  │      
    │          │  ├─第12讲 基本响应与卷积和的定义
    │          │  │      Z3.13-单位脉冲响应的定义和求解.pdf
    │          │  │      Z3.14-单位阶跃响应的定义和求解.pdf
    │          │  │      Z3.15-单位阶跃响应与单位脉冲响应的关系.pdf
    │          │  │      Z3.16-Matlab求解单位脉冲响应.pdf
    │          │  │      Z3.17-序列的时域分解.pdf
    │          │  │      Z3.18-卷积和公式.pdf
    │          │  │      Z3.19-卷积和的图解法.pdf
    │          │  │      
    │          │  └─第13讲 卷积和计算与差分算子描述
    │          │          Z3.20-卷积和的不进位乘法运算.pdf
    │          │          Z3.21-卷积和的性质.pdf
    │          │          Z3.22-卷积和的MATLAB求解.pdf
    │          │          Z3.23-差分算子E的定义.pdf
    │          │          Z3.24-离散系统的差分算子方程.pdf
    │          │          Z3.25-传输算子.pdf
    │          │          
    │          ├─04. 第四章 傅里叶变换与频域分析
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第14讲 周期信号的傅里叶级
    │          │  │      Z4.01-矢量的正交分解.pdf
    │          │  │      Z4.02-信号的正交分解.pdf
    │          │  │      Z4.03-帕斯瓦尔定理.pdf
    │          │  │      Z4.04-三角形式的傅里叶级数.pdf
    │          │  │      Z4.05-周期信号波形对称性和谐波特性.pdf
    │          │  │      
    │          │  ├─第15讲 周期信号的频谱
    │          │  │      Z4.06-指数形式的傅里叶级数.pdf
    │          │  │      Z4.07-两种傅里叶级数展开形式的关系.pdf
    │          │  │      Z4.08-周期信号的频谱.pdf
    │          │  │      Z4.09-单边谱和双边谱的关系.pdf
    │          │  │      Z4.10-周期信号频谱的特点.pdf
    │          │  │      
    │          │  ├─第16讲 周期信号频谱的特点
    │          │  │      Z4.11-周期信号的功率.pdf
    │          │  │      Z4.12-应用案例：DC-to-AC转换器.pdf
    │          │  │      Z4.13-非周期信号的频谱.pdf
    │          │  │      Z4.14-傅里叶变换.pdf
    │          │  │      
    │          │  ├─第17讲 傅里叶变换及性质（1）
    │          │  │      Z4.15-常用函数的傅里叶变换.pdf
    │          │  │      Z4.16-线性性质.pdf
    │          │  │      Z4.17-奇偶性.pdf
    │          │  │      Z4.18-对称性.pdf
    │          │  │      Z4.19-尺度变换特性.pdf
    │          │  │      Z4.20-时移性质.pdf
    │          │  │      
    │          │  ├─第18讲 傅里叶变换及性质（2）
    │          │  │      Z4.21.pdf
    │          │  │      Z4.22.pdf
    │          │  │      Z4.23.pdf
    │          │  │      Z4.24.pdf
    │          │  │      Z4.25.pdf
    │          │  │      
    │          │  ├─第19讲 周期信号的傅里叶变换
    │          │  │      Z4.26.pdf
    │          │  │      Z4.27.pdf
    │          │  │      Z4.28.pdf
    │          │  │      Z4.29.pdf
    │          │  │      Z4.30.pdf
    │          │  │      
    │          │  ├─第20讲 LTI系统的频域分析
    │          │  │      Z4.31.pdf
    │          │  │      Z4.32.pdf
    │          │  │      Z4.33.pdf
    │          │  │      Z4.34.pdf
    │          │  │      Z4.35.pdf
    │          │  │      Z4.36.pdf
    │          │  │      
    │          │  ├─第21讲 无失真传输和理想低通滤波器
    │          │  │      Z4.37-无失真传输.pdf
    │          │  │      Z4.38-理想低通滤波器.pdf
    │          │  │      Z4.39-物理可实现系统的条件.pdf
    │          │  │      Z4.40-案例：二次抑制载波振幅调制接收系统.pdf
    │          │  │      
    │          │  └─第22讲 取样定理
    │          │          Z4.41-信号的取样.pdf
    │          │          Z4.42-取样定理(时域).pdf
    │          │          Z4.43-取样定理(频域).pdf
    │          │          Z4.44-Matlab实现Sa信号的采样和恢复.pdf
    │          │          Z4.45-应用案例：CD数字录音系统.pdf
    │          │          
    │          ├─05. 第五章 离散傅里叶变换
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  └─第23讲 离散傅里叶变换简述
    │          │          Z5.01-傅里叶变换中连续到离散的演化.pdf
    │          │          Z5.02-五种傅里叶变换的比较.pdf
    │          │          Z5.03-离散傅里叶变换的定义.pdf
    │          │          
    │          ├─06. 第六章 拉普拉斯变换与复频域分析
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第1讲 常见信号的拉普拉斯变换
    │          │  │      K1.01-双边拉普拉斯变换的定义.pdf
    │          │  │      K1.02-收敛域.pdf
    │          │  │      K1.03-单边拉氏变换的定义.pdf
    │          │  │      
    │          │  ├─第2讲 拉普拉斯变换的性质
    │          │  │      K1.04-单边拉氏变换与傅里叶变换的关系.pdf
    │          │  │      K1.05-常见信号的拉普拉斯变换.pdf
    │          │  │      K1.06-拉普拉斯变换的性质—线性、尺度变换.pdf
    │          │  │      K1.07-拉普拉斯变换的性质—时移、复频移特性.pdf
    │          │  │      K1.08-拉普拉斯变换的性质—时域和复频域的微积分特性.pdf
    │          │  │      K1.09-拉普拉斯变换的性质—卷积定理.pdf
    │          │  │      K1.10-拉普拉斯变换的性质—初值、终值定理.pdf
    │          │  │      
    │          │  ├─第3讲 拉普拉斯变换应用于电路分析
    │          │  │      K1.11-拉普拉斯反变换.pdf
    │          │  │      K1.12-拉普拉斯变换的Matlab求解.pdf
    │          │  │      K1.13-电路元件和定理的s域模型.pdf
    │          │  │      
    │          │  ├─第4讲 系统函数
    │          │  │      K1.14-电路系统的s域分析方法.ppt.pdf
    │          │  │      K1.15-微分方程的变换解.pdf
    │          │  │      K1.16-连续系统函数H(s)的定义和求解.pdf
    │          │  │      K1.17-H(S)的零极点分布与时域特性.pdf
    │          │  │      
    │          │  ├─第5讲 频率特性
    │          │  │      K1.18-连续系统稳定性判别.pdf
    │          │  │      K1.19-Matlab绘制零极点图、判断稳定.pdf
    │          │  │      K1.20-系统函数与系统的频率特性.pdf
    │          │  │      K1.21-Matlab求频率响应函数，判断稳定.pdf
    │          │  │      
    │          │  ├─第6讲 连续系统的信号流图
    │          │  │      K1.22-连续系统的s域框图.pdf
    │          │  │      K1.23-连续系统的信号流图.pdf
    │          │  │      K1.24-梅森（Mason) 公式.pdf
    │          │  │      
    │          │  └─第7讲 连续系统的模拟
    │          │          K1.25-连续系统的模拟：直接形式.pdf
    │          │          K1.26-连续系统的模拟：级联形式.pdf
    │          │          K1.27-连续系统的模拟：并联形式.pdf
    │          │          K1.28-零点配置的作用.pdf
    │          │          K1.29-低通,带通,带阻滤波器中零极点的配置.pdf
    │          │          
    │          ├─07. 第七章 z变换分析
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第10讲 离散时间系统的Z变换分析法
    │          │  │      K2.11-差分方程的z变换解.pdf
    │          │  │      K2.12-系统函数H(z).pdf
    │          │  │      K2.13-系统函数与系统特性.pdf
    │          │  │      K2.14-离散系统稳定性判据.pdf
    │          │  │      
    │          │  ├─第11讲 离散系统的信号流图
    │          │  │      K2.15- 系统的方框图.pdf
    │          │  │      K2.16-系统的z域信号流图.pdf
    │          │  │      K2.17-离散系统的模.pdf
    │          │  │      
    │          │  ├─第12讲 频率特性和数字滤波器概念
    │          │  │      K2.18-系统对正弦序列的响应.pdf
    │          │  │      K2.19-LTI离散系统的频率响应.pdf
    │          │  │      K2.20-Matlab绘零极点图.pdf
    │          │  │      K2.21-应用案例.pdf
    │          │  │      K2.22-系统函数零极点的配置.pdf
    │          │  │      K2.23-数字滤波器的分类.pdf
    │          │  │      K2.24-冲激响应不变法设计IIR滤波器.pdf
    │          │  │      K2.25-双线性变换法设计IIR滤波器.pdf
    │          │  │      
    │          │  ├─第8讲 序列的Z变换定义
    │          │  │      K2.01-z变换定义及收敛域.pdf
    │          │  │      K2.02-常用序列的z变换.pdf
    │          │  │      K2.03-z变换性质-线性、移序、反折.pdf
    │          │  │      K2.04-z变换性质－ z域尺度特性、微分.pdf
    │          │  │      
    │          │  └─第9讲 Z变换的性质
    │          │          K2.05-z变换性质-时域卷积.pdf
    │          │          K2.06-z变换性质－部分和.pdf
    │          │          K2.07-初值定理和终值定理.pdf
    │          │          K2.08-逆z变换：幂级数和部分分式展开.pdf
    │          │          K2.09-z变换MATLAB计算.pdf
    │          │          K2.10-z变换与拉普拉斯变换的关系.pdf
    │          │          
    │          ├─08. 第八章 系统的状态空间分析
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第13讲 连续系统的状态方程
    │          │  │      K3.01-连续系统状态方程与输出方程.pdf
    │          │  │      K3.02-连续系统状态方程的建立-由RLC电路.pdf
    │          │  │      K3.03-连续系统状态方程的建立-由微分方程.pdf
    │          │  │      K3.04-连续系统状态方程的建立-由框图流图.pdf
    │          │  │      
    │          │  └─第14讲 离散系统的状态方程
    │          │          K3.05-离散系统状态方程和输出方程.pdf
    │          │          K3.06-离散系统状态方程的建立.pdf
    │          │          K3.07-系统状态方程的变换域求解.pdf
    │          │          K3.08-利用MATLAB求解系统状态方程.pdf
    │          │          K3.09-系统函数矩阵与系统稳定性分析.pdf
    │          │          K3.10-线性系统的可控制性和可观测性.pdf
    │          │          
    │          ├─09. 第九章 小波分析理论简介
    │          │  ├─0.考研昆明理工大学《817信号与系统》的进
    │          │  │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │          │  │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │          │  │      考研昆明理工大学《817信号与系统》交流群.pdf
    │          │  │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │          │  │      
    │          │  ├─第15讲 短时傅里叶变换
    │          │  │      K4.01-平稳信号与非平稳信号.pdf
    │          │  │      K4.02-短时傅里叶变换.pdf
    │          │  │      
    │          │  └─第16讲 小波概述
    │          │          K4.03-连续小波变换.pdf
    │          │          K4.04-离散小波变换.pdf
    │          │          K4.05-小波变换工程应用.pdf
    │          │          
    │          └─10.各高校信号考研资料
    │              ├─1.考研昆明理工大学《817信号与系统》的进
    │              │      昆明理工大学2021年硕士研究生拟录取公示名单.pdf
    │              │      昆明理工大学通信考研(817信号与系统)_初试参考书.jpg
    │              │      考研昆明理工大学《817信号与系统》交流群.pdf
    │              │      附件1-昆明理工大学2022年硕士研究生一志愿考生复试名单.pdf
    │              │      
    │              ├─10.后续更新其他高校考研资料
    │              ├─2.考研桂林电子科技大学《806电路、信号与系统》的进
    │              │      2023年自命题科目考试大纲-806电路、信号与系统.pdf
    │              │      806参考书.jpg
    │              │      桂林电子科技大学通信考研群.pdf
    │              │      
    │              └─3.考研大理大学《871信号与系统》的进
    │                      专业课参考书.jpg
    │                      大理大学2023年硕士研究生招生简章.pdf
    │                      大理大学通信考研群.pdf
    │                      
    ├─5.复变函数与积分变换
    │  │  复变函数与积分变换.pdf
    │  │  
    │  └─1.例题
    │          Example1.1.pdf
    │          Example1.2.pdf
    │          
    └─6.电路分析基础
        ├─1.南邮考研
        │  ├─1.课本
        │  │      电路分析基础 第5版 刘陈主编.txt
        │  │      
        │  ├─2.PPT
        │  │  ├─南京邮电大学MOOC PPT
        │  │  │  └─南京邮电大学PPT
        │  │  │          1-1.pdf
        │  │  │          1-2.pdf
        │  │  │          1-3.pdf
        │  │  │          1-4.pdf
        │  │  │          1-5.pdf
        │  │  │          1-6.pdf
        │  │  │          11 习题解答.pdf
        │  │  │          11-1.pdf
        │  │  │          11-2.pdf
        │  │  │          1习题课（基）.pdf
        │  │  │          2-1.pdf
        │  │  │          2-2.pdf
        │  │  │          2-3.pdf
        │  │  │          2-4.pdf
        │  │  │          2-5.pdf
        │  │  │          2-6.pdf
        │  │  │          2习题.pdf
        │  │  │          2习题课（等）.pdf
        │  │  │          3-1.pdf
        │  │  │          3-2.pdf
        │  │  │          3-3.pdf
        │  │  │          3-4.pdf
        │  │  │          3习题课（线）.pdf
        │  │  │          4-1.pdf
        │  │  │          4-2.pdf
        │  │  │          4-3.pdf
        │  │  │          4-5.pdf
        │  │  │          4-6.pdf
        │  │  │          4-7.pdf
        │  │  │          4习题课（网）.pdf
        │  │  │          5习题课（网、暂）.pdf
        │  │  │          6-1.pdf
        │  │  │          6-2.pdf
        │  │  │          6-3.pdf
        │  │  │          6-4.pdf
        │  │  │          6-5.pdf
        │  │  │          6-6.pdf
        │  │  │          6-7.pdf
        │  │  │          6习题课（暂）.pdf
        │  │  │          7-1.pdf
        │  │  │          7-10.pdf
        │  │  │          7-11.pdf
        │  │  │          7-12.pdf
        │  │  │          7-13.pdf
        │  │  │          7-14.pdf
        │  │  │          7-14习题解答.pdf
        │  │  │          7-15.pdf
        │  │  │          7-2 .pdf
        │  │  │          7-3 .pdf
        │  │  │          7-4.pdf
        │  │  │          7-5.pdf
        │  │  │          7-6.pdf
        │  │  │          7-7.pdf
        │  │  │          7-8.pdf
        │  │  │          7-9.pdf
        │  │  │          7-9习题解答.pdf
        │  │  │          8-1.pdf
        │  │  │          8-2.pdf
        │  │  │          8-3.pdf
        │  │  │          8-4.pdf
        │  │  │          8-5.pdf
        │  │  │          8-6.pdf
        │  │  │          8-7.pdf
        │  │  │          8-8习题解答.pdf
        │  │  │          8习题解答.pdf
        │  │  │          9-1.pdf
        │  │  │          9-2.pdf
        │  │  │          9-3.pdf
        │  │  │          9-4.pdf
        │  │  │          9-5.pdf
        │  │  │          9-6.pdf
        │  │  │          9习题解答.pdf
        │  │  │          专题一 带你认识电路元件.pdf
        │  │  │          
        │  │  └─南邮本科电路ppt（全）
        │  │      └─南邮电路ppt（全）
        │  │              电路分析基础课件第1章-电路基本概念.ppt
        │  │              电路分析基础课件第2章-电路分析中的等效变换.ppt
        │  │              电路分析基础课件第3章-线性网络的一般分析方法.ppt
        │  │              电路分析基础课件第4章-网络定理.ppt
        │  │              电路分析基础课件第5章-一阶电路分析.ppt
        │  │              电路分析基础课件第6章-正弦稳态分析.ppt
        │  │              电路分析基础课件第7章-正弦稳态分析.ppt
        │  │              电路分析基础课件第8章-耦合电感和变压器电路分析.ppt
        │  │              电路分析基础课件第9章-电路的频率特性.ppt
        │  │              
        │  └─3.考研串讲
        │          考研大串讲-电路  孙立山 杨旭强 霍炬 金钊主编 2006年 科学出版社.pdf
        │          考研大串讲答案详解.pdf
        │          
        └─2.例题
                Example6.1.pdf
                Example6.2.pdf
                Example6.3.pdf

`````

# 7.Disclaimer

All content in this  is based solely on the contributors' personal work, Internet data.
All tips are for reference only and are not guaranteed to be 100% correct.
If you have any questions, please submit an Issue or PR.
In addition, if it infringes your copyright, please contact us to delete it, thank you.



#### Copyright © School of Electrical & Electronic Engineering, Nanyang Technological University. All rights reserved.
