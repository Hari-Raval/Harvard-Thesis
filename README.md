# Harvard Masters Thesis

## Title:

One Shot Transfer Learning of Linear and Ordinary Partial Differential Equations

## Advisor:

Dr. Pavlos Protopapas

## Abstract:

Differential equations are prevalent in many areas of science and engineering and often times, applications require rapidly solving variants of the same equations with differing conditions. There is growing interest in generating approximate solutions to these equations with neural networks, which provide continuous and differentiable solutions. Specifically, physics informed neural networks (PINNs) have attracted researchers as an avenue through which both data and studied physical constraints can be leveraged in learning solutions to differential equations. Despite the benefits that PINNs offer, they are currently limited by the computational costs needed to train such networks on different but related tasks. To address this drawback, we turn to transfer learning differential equation solutions generated from PINNs.

In this thesis, we present a generalizable and robust methodology to perform ``one-shot transfer learning" on linear systems of ordinary and partial differential equations. First, we describe a process to train PINNs on vectorized representations of equations with varying conditions, leveraging a multi-headed approach. Second, we show how this multi-headed training process can be used to yield a latent space representation of a particular equation form. Third, we produce a derivation of closed-form formulas which represent a set of generalized network weights, for both ordinary and partial differential equations. Finally, we demonstrate how the learned latent space representation and derived network weights can be used to rapidly transfer learn solutions to various equations. We apply our novel methodology to a suite of linear systems, illustrating no limitation by the order of the equations, the number of equation, or the time-dependence of equation coefficients.