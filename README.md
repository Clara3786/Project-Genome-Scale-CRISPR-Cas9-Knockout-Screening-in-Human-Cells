# Project-Genome-Scale-CRISPR-Cas9-Knockout-Screening-in-Human-Cells
*Project in CB2330 - Tove Brunell & Clara Carlborg* 

This is a project that aims to simulate an experiment and fit a model to data from a scientific paper. 
Here, we have chosen the paper Genome-Scale CRISPR-Cas9 Knockout Screening in Human Cells by Shalem et al. 
The idea is that the binomial distribution can explain the phenomenon of a frameshift vs. an in-frame mutation, given that an indel has occurred after the lentiCRISPR targeting of the EGFP gene. 

**The forward simulation** was performed using Monte Carlo, where we used the estimated sample mean of frameshifts as the condition for success. By doing this simulation, the authors could obtain more datasets like the actual one. 

**In the backward simulation**, we used the negative log-likelihood (NLL) to estimate p in the binomial distribution and obtained p̂ = 0.435 ± 0.0202. 

If you want to run our program, you only need to run the file Project.ipynb. 

