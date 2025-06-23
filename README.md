# Group 1 final project for AAI-510

This project is a part of the AAI-510 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

-- Project Status: [Planned, Active, On-hold, **Completed**]

#### Installation
Clone repo and run notebooks

#### Project Intro/Objective
Our project aims to forecast the unemployment rate for the San Diego Metropolitan Statistical Area. This is a time series problem and we will use ARIMA to model the problem, training on data available starting Jan first, 1990, through present. We will attempt to optimize the model via hyper parameter tuning. We will also consider other models other than ARIMA to determine if a different model may be better suited for this specific problem. From a business standpoint, the unemployment rate is an indicator of overall purchasing power: the higher the unemployment rate, the lower the purchasing power. As such, we can imagine a company that is looking to expand it’s business into the San Diego MSA. The business has other branches and can sustain less than optimal performance from the new store for a short period but would need the new location to be profitable within the first year or risk bleeding the entire company dry trying to support the new location. As such, it is pertinent to do as much due diligence as possible, including forecasting the likelihood of the area having enough purchasing power to support the business at the new location.

#### Partner(s)/Contributor(s)
* Dean P. Simmer
* [https://github.com/mojodean](https://github.com/mojodean)
* Gaius J. Thomas
* [https://github.com/jeffiThomas](https://github.com/jeffiThomas)
* Johnathan Kelsey
* [https://github.com/mr-kelsey](https://github.com/mr-kelsey)

#### Methods Used
* Machine Learning
* Deep Learning
* Data Visualization
* Data Manipulation

#### Technologies
* Python
* Time Series
* ARIMA
* DeepAR

#### Project Abstract
The unemployment rate of any given area can be viewed as the purchasing power of that area, and it is inversely proportional to the purchasing power. In other words, the higher the unemployment rate, the lower the purchasing power. If a company is looking to expand into an area, it behooves that company to perform market research about the area as part of the due diligence process. Being able to forecast unemployment rates in the area would be quite advantageous to the company as it could help shed light on how much discretionary funds can be expected to be floating around the area, ready to be spent on the company's products or services.  To this end, this project explores the unemployment rate of the San Diego Metropolitan Statistical Area and attempts to forecast future unemployment rates by modeling the unemployment rate data for the area beginning January 1st, 1990 through the present.  In an effort to generalize unemployment forecasting, this project also employs DeepAR in an effort to forecast the unemployment rate of an area using the data from multiple MSAs throughout the state of California.

#### License
GNU GENERAL PUBLIC LICENSE Version 3
