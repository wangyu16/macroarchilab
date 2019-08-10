---
layout: page
#
# Content
#
subheadline: "ATRP Kinetic Simulator Lite"
title: "Jupyter Notebook ATRP Kinetic Simulator Lite Version"
teaser: "This program runs in Jupyter notebook, provides fast kinetic simulation for conventional radical polymerization and different types of ATRP. The output includes concentration changes of all species but no molecular weight distribution information is provided."
categories:
  - simulation
tags:
  - Radical polymerization
  - ATRP
  - Kinetic
  - Simulation
#
# Styling
#
header: no
image:
    title: ATRP_Kinetic_Simulator_Lite.svg
    thumb: ATRP_Kinetic_Simulator_Lite.svg
    homepage: 
    caption: ATRP Kinetic Simulator Lite Version
    caption_url: https://github.com/wangyu16/PolymerScienceEducation
mathjax: true
---

## To Start


## Inputs and Outputs


## Rate Coefficients


## Examples

* Reactions in atom transfer radical polymerization
*; Initiation
*: $$\begin{array}{ll}
{\color{Blue}\ce R}{-}{\color{Red}\ce X} + {\color{Green}\ce{Cu^{I}}}{\color{Red}\ce X}/\ce{L}\ \overset{k_{a,0}}\underset{k_{d,0}}\ce{<<=>}\ {\color{Green}\ce{Cu^{II}}}{\color{Red}\ce{X2}}/\ce{L} + {\color{Blue}\ce R}^\cdot & K_\ce{ATRP,0} = \frac{k_{a,0}}{k_{d,0}}\\
{\color{Blue}\ce R}^\cdot \ce{+ M ->[k_\ce{add}]} {\color{Blue}\ce R}\ce{-P1^.}\\
2{\color{Blue}\ce R}^\cdot \ce{->[k_{t,0}]} \begin{Bmatrix} {\color{Blue}\ce R}{-}{\color{Blue}\ce R} \\ \ce{or} \\ {\color{Blue}\ce R}^= + {\color{Blue}\ce R}\ce{H} \end{Bmatrix}
\end{array}$$
*; Quasi-steady state
*: $$\begin{array}{ll}
{\color{Blue}\ce R}\ce{-P_\mathit{n}}{-}{\color{Red}\ce X} + {\color{Green}\ce{Cu^{I}}}{\color{Red}\ce X}/\ce{L} \ \overset{k_{a}}\underset{k_{d}}\ce{<<=>}\ {\color{Green}\ce{Cu^{II}}}{\color{Red}\ce{X2}}/\ce{L} + {\color{Blue}\ce R}\ce{-P_\mathit{n}^.} 
& \begin{array}{l} \ce{ATRP} \\ \ce{activation/deactivation} \\ \ce{equilibrium} \\ k_\ce{ATRP} = \frac{k_a}{k_d} \end{array}\\
\left.\begin{align} 
{\color{Blue}\ce R}\ce{-P_\mathit{n}^.} + \ce{M}\ &\ce{->[k_p]} {\color{Blue}\ce R}\ce{-P^._{\mathit{n}+1}} \\ 
2{\color{Blue}\ce R}\ce{-P_\mathit{n}^.}\ &\ce{->[k_t]} \begin{Bmatrix} {\color{Blue}\ce R}\ce{-P_\mathit{n}-P_\mathit{n}}{-}{\color{Blue}\ce R} \\ \ce{or} \\ {\color{Blue}\ce R}\ce{-P_\mathit{n}^=} + {\color{Blue}\ce R}\ce{-P_\mathit{n}-H} \end{Bmatrix} \quad
\end{align} \right\} 
& \begin{array}{l} \text{Same as conventional} \\ \text{radical polymerization} \end{array}
\end{array}$$
* Other chain breaking reactions ($k_{tx}$) should also be considered.
