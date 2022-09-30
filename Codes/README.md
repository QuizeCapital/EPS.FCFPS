## `Codes`
In this directory, I store codes of this research project. 

Th code utilises a class function which is cosisits of child functions that 
call their own unique variables. 

The function get_eps connects to the financial modelling prep API and downloads earnings per share for as long as a company has existed and calculates the eps growth rate by utitlising the formula 

$$
\triangle eps = -[abs(\frac{eps^0}{eps^t})]
$$

where t = ending timeframe used for analysis

$$
growth = ((-[abs(\frac{eps^0}{eps^t})])^\frac{1}{t})-1
$$

The function get_eps_pctChange is where we group our eps into the respective market value quintiles. We do this by treating for extreme values (cutting off values at 95% and 0.5% ) respectively.We then find the percentage change in earnings and use the average of that as our quintile figures.

The function combiningEPSMarketValue combines these into a  dataframe where we get our output.

