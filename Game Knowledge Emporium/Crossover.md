__________________________________________________________________________
#### **Tags:** #Programming/AI 
###### *Date Of Creation: 2023-11-03*
__________________________________________________________________________
Every *Crossover* operator produces two new children $c_1$ and $c_2$ for two string by copying selected bits from each parent $p$.
## Single-Point Crossover

***First Child:***
$$\begin{align} p_1 = \pmb {\{11101\}} 001000\\ p_2 = 00001 \mathbb {\{010101\}} \\ \\ c_1 = \pmb {\{11101\}} \mathbb {\{010101\}}\end{align}$$
***Second Child:***
$$\begin{align} p_1 = 11101\pmb {\{001000\}} \\ p_2 = \mathbb {\{00001\}} 010101 \\ \\ c_2 = \mathbb {\{00001\}} \pmb {\{001000\}} \end{align}$$
## Two-Point Crossover

***First Child:***
$$\begin{align} p_1 = 11 \pmb {\{10100\}} 1000\\ p_2 = \mathbb {\{00\}} 00101 \mathbb {\{0101\}}  \\ \\ c_1 = \mathbb {\{00\}}\pmb {\{10100\}} \mathbb {\{0101\}}\end{align}$$
***Second Child:***
$$\begin{align} p_1 = \pmb {\{11\}} 10100 \pmb {\{1000\}} \\ p_2 = 00 \mathbb {\{00101\}} 0101  \\ \\ c_1 = \pmb {\{11\}}\mathbb {\{00101\}} \pmb {\{1000\}}\end{align}$$

#### Sources
__________________________________________________________________________
1. 