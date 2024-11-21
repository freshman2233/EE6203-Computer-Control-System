# EE6203-Computer Control System

## 1.Content 

1.Reference answers to final examination questions

2.PPT Example reference answer

## 2.Find out a mistake

As there is no standard answer, if you detect any error in the answer, it is due to my limited knowledge level. 

Please leave a message or send an email or some Wechat messages to me and I will update the version as soon as possible. 

My Email: freshmanfreshman0011@gmail.com

My Wechat: freshman2233

## 3.Declare

This resource is for learning and communication only. It is strictly prohibited for commercial use. Please delete it within 24 hours.

## 4.GitHub Sponsors

If you like this project, please consider supporting us through GitHub Sponsors! Thank you for your support!



## 5. Exam scope: All

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



## 6.Statistics of previous test centers

The 6203 exam questions are relatively fixed, and we can find the rules of solving the questions from the past 19 to 23 years.

