# Comparison of ERGM to ERNM

## Table of Contents
- [Introduction](#Introduction)
- [Abstract](#Abstract)
- [Contents of Files in the Respository](#Contents of Files in the Respository)
- [Installtion](#Installation)

## Introduction

This paper compared two classes of statistical models for social networks, exponential-family random graph models (ERGMs) and exponential-family random network models (ERNMs), so as to cope with the endogeneous nature of networks and nodal variables.

- For a further details of the paper, visit the
[Comparison of ERGM to ERNM](https://drive.google.com/file/d/1mPHLsypGwfLOGTBUS6GuZrEpxGjES_kV/view?usp=sharing)

## Abstract

The structure of many complex social networks is determined by nodal and dyadic covariates that are endogenous to the tie variables. While exponential-family random graph models (ERGMs) have been very successful in modeling social networks with exogeneous covariates, they are often misspecified for networks where the covariates are stochastic. Exponential-family random network models (ERNMs) are an extension of ERGM that retain the desirable properties of ERGM, but allow the joint modeling of tie variables. In this paper, we compare the models in situations where the covariates are stochastic. We use as a case-study a friendship network among students within a school from the National Longitudinal Study of Adolescent Health. Within this network, the student's smoking behavior is likely endogenous to their friendship ties. We compare ERGm to ERNM to show how conclusions of ERGM modeling are improved by consideration of the ERNM framework.
This analysis supports the notion that ERNM are preferred when networks have stochastic covariates.

## Contents of Files in the Respository

- [Data](): Raw data we used in our paper.
- [MCMC Diagnostic Plots](): MCMC diagnositc trace and distribution plots for ERNM and ERGM models fitted in the paper

## Installation

You could install tapeder ERGM and tapered ERNM directly from R with devtools:

```
install.packages("devtools")
devtools::install_github(, depedencies=T)
```



