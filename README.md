# Import Penetration and Protection  
### What looks Unusual : Steel Industry's High Protection Compared to Its Relative Import Volume
- Why are the ratio of steel-related antidumping orders are too high given its relatively low import volume?
![](./myplot2)
![](./myplot1.jpg)


## Literature
Models are mainly arguing over the negative/postivie correlation between `import penetration ratio` and `protection level`
- Theoretical Modelling: 
    1) Deductively designed model that supports the author's argument
    2) No actual data (observation) is used. 
  - [Protection for sale (Grossman and Helpman, 1994; 5855)](https://sci-hub.st/https://www.jstor.org/stable/2118033) 
    - a.k.a GH model
    - **"(If the industry is organized; Reprsented by the lobby) Trade protection decreases with import penetration"** 
    - **"(If the industry is non-organized; Reprsented by the lobby) Trade protection increases with import penetration"**
  - [Import penetration and the politics of trade protection (Maggia, 2000; 113)](https://sci-hub.st/https://www.sciencedirect.com/science/article/pii/S002219969900029X)
    - **"Trade protection increases (strictly) with import penetration."**
  - Many other papers are generally supporting "protection tends to be higher in higher import penetration"
- Emprical Validation
  - [Protection for Sale: An Empirical Investigation (Goldberg & Maggi, 1997; 1056)](https://www.nber.org/papers/w5942.pdf)
    - data used only contains one-year annual data (1983; NBER data) 
    - SIC 3digit level 
    - not stricitly and directly validates the GH model. 
    - used NTB (Non-tariff Barrier) data (because tariff-rates are determined "cooperatively" in the GATT-WTO regime.
    - used manufacturing sector's data only
    - Observations: 107
<img src="./econometric_model.png" width="500">

- I is for organized sector (Measured by "exisitence" of the PAC contribution)
- e is for import elasticity
- t is for protection
- X/M Inverse penetraion ratio where X is export and M is import

## Questions
- Literature above cited is fairly outdated.. any recent re-visit about this subject? 
  - is this subject still attractive to political scientist?
  - maybe I could re-visit this subject with more data (absolutely more than 107 observations, moreover in monthly level)

- I'd like to use the Federal Register's data as a proxy for the Protection Level (Count of how many times those product mentioned in the federal register for given period of time)
<img src="./federal-register.png">
- For the model part, I could try linear regression as above, or 
- I could try to use With UNComtrade data, I could try ablation study 
