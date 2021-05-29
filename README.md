# Hawkes-Process-2021

Master’s project for MS in statistics at OSU

Prequel to Hawkes Processes: An Overview of Spatial, Temporal and Spatio-Temporal Point Processes and Some Simulations

Frances Lin

Major Professor: James Molyneux

Committee Members: Lisa Madsen & Charlotte Wickham

Description: Events such as earthquake epicenters, crime patterns, forest wildfires, financial transcations, etc. often exhibit triggering and clustering behavior. The ability to capture events with such behavior gives Hawkes (or self-exciting) processes the potential to become a powerful predictive tool for a wide variety of applications. In this project, we give brief introductions, review definitions, discuss properties and applications of selected spatial and temporal point processes leading up to spatio-temporal self-exciting processes, and simulate some of the processes in 1D and 2D in hope of interested readers have the background knowledge to read and comprehend existing literature as well as explore the field further.

Main report can be found [here](https://github.com/franceslinyc/Hawkes-Process-2021/blob/main/analysis/Lin_Masters_Project.pdf), presentation slides can be found [here](https://github.com/franceslinyc/Hawkes-Process-2021/blob/main/analysis/Lin_Presentation.pdf), and the algorithm  in particular the thinning algorithm and **spatstat** package of `R` used for simulating some of the processes in 1D or 2D can be found [here](https://github.com/franceslinyc/Hawkes-Process-2021/blob/main/analysis/Lin_Appendix.pdf).

Other reports are in the [analysis](https://github.com/franceslinyc/Hawkes-Process-2021/tree/main/analysis) folder:  

01_proc_HPP.Rmd simulates HPP

03_proc_Hawkes.Rmd simulates Hawkes process

04_proc_using_spatstat.Rmd simulates HPP, NPP, Cox and cluster processes in 2D using the **spatstat** package of `R`

Lin_Appendix.Rmd contains the algorithm in particular the thinning algorithm and **spatstat** package of `R` used for simulating some of the processes in 1D or 2D

Lin_Presentation.Rmd contains codes that produce slides for the [presentation](https://github.com/franceslinyc/Hawkes-Process-2021/blob/main/analysis/Lin_Presentation.pdf)

