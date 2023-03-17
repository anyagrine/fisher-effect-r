# fisher-effect-r
# Observation of inflation rates in CH and US.

Description: This is a study project I have done as a homework for the course "Programming for Data Science" in the University of Bern.
All code is written in R

1. The data set CH_US_DATA.xls contains the inflation rate for Switzerland and the US. The SNB has the goal to keep inflation between 0% and 2%. Mark this region in the plot, with two horizontal lines. Mark all periods for which the goal was not achieved. 

![Screen Shot 2023-03-17 at 13 27 20](https://user-images.githubusercontent.com/104497242/225892213-18d606ec-df24-43dc-aaa1-ab7e5155aa6a.png)
                                
                                         
2. Compute the expected change in △CHF/USD given CH and US Inflation.
Configure 2 plots: one for the expected change in △CHF/USD due to PPP, 2d to the the level of the observed exchange rate CHF/USD.

![Screen Shot 2023-03-17 at 13 31 13](https://user-images.githubusercontent.com/104497242/225892967-08c7a31c-d28c-420a-827f-0599d1a85a11.png)

3. The file USA.xls contains the real interest rate and the consumer price index (CPI) in the US. Compute the annualized inflation rate based on the CPI index.Drop the CPI and keep only the years with no missing values for both variables. Merge the data set with the FED Funds Rates from task 1 and export it as a csv file.  
Calculate the real interest rate as expected by the fisher effect. Plot this expected real interest rate together with the observed real interest rate.

![Screen Shot 2023-03-17 at 13 25 45](https://user-images.githubusercontent.com/104497242/225891859-8fc8a3a8-6893-4584-894a-9a5b94711c5d.png)
