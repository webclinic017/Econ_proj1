<p align="center"><img width=50% src="https://github.com/hilsdsg3/Econometric_data_and_sector_strength/blob/master/media/logo.png"></p>
<p align="center"><img width=40% src="https://github.com/hilsdsg3/Econometric_data_and_sector_strength/blob/master/media/name.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
[![GitHub Issues](https://img.shields.io/github/issues/hilsdsg3/Econometric_data_and_sector_strength.svg)](https://github.com/hilsdsg3/Econometric_data_and_sector_strength/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Sector, Index, and Econometric Overview
A current look at how the 11 different US market sectors are performing with regards to relative strength along with the dividend information. Also a graphical look at the S&P's bollinger bands, 50 day MA , and 200 day MA. The last graph is important econometric FRED data like risk-free rate, unemployment data, 30-yr mortgage rate, leading economic indicator, Core CPI, 10-2mo yield rate.
<p align="center"><img width=60% src="https://github.com/hilsdsg3/Econometric_data_and_sector_strength/blob/master/media/Bull_bear.jpg"></p>

<br>


## Strategy suggestions
### Market chart
A bullish sign for the S&P occurs when the 50-day moving average (MA 50 - blue line) rises above the 200-day (MA 200 - purple line). This event is called the Golden Cross.
Conversely, the Death cross event occurs when the 50-day MA decreases below the 200-day MA and would be considered bearish. Genrally, a bullish sign are prices that rise and bearish sign would be a decrease in prices.    
<img src="https://github.com/hilsdsg3/Econometric_data_and_sector_strength/blob/master/media/Golden_Death_cross.jpg" width=50%>

<br>

## Display improvements - pending features
1. Make the charts homogenous (same scale, dimensions and look)
2. Combine the S&P market chart and the bollinger bands chart  
3. Use an algorithm to detect a golden vs a death cross in the market chart  

## Latest Development Changes
```bash
git clone https://github.com/anfederico/Clairvoyant
```

## Disclaimer
My content is intended to be used and must be used for informational purposes only. It is important to do your own analysis before making any investment based on your own personal circumstances. You should seek independent financial advice from a professional in connection with, or independently research and verify, any information that you find on this page, whether for the purpose of making an investment decision or otherwise.


Remember, more is not always better!
```python
variables = ["SSO"]                            # 1 feature
variables = ["SSO", "SSC"]                     # 2 features
variables = ["SSO", "SSC", "RSI"]              # 3 features
variables = ["SSO", "SSC", "RSI", ... , "Xn"]  # n features
```

## Contributing
Please take a look at our [contributing](https://github.com/anfederico/Clairvoyant/blob/master/CONTRIBUTING.md) guidelines if you're interested in helping!
#### Pending Features
- Export model
- Support for multiple sklearn SVM models
- Visualization for models with more than 2 features
