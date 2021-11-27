# shf_portfolio

This project takes a position and daily balance csv file from your broker and creates a mosaic of performance 
and risk metrics.  This is for an equity portfolio.


## Technologies (pip list)###
This project uses Python 3.7
Pandas 1.2.4
Jupyter lab 3.0.14
pyviz 2.1.0
hvplot 0.7.3
SQLAlchemy 1.4.7
numpy 1.20.1


#Features of code:
sourcing data: 
downloaded prices for all positons (yahoo finance data reader)

risk metrics:
Betas for every single name position across multiple frequencies 
Sharpe ratios 
Correlation matrix with heatmap
Volatility of of portfolio (ytd)
VaR using historical, parametric and monete carlo methods

plots:
ytd pnl 
AUM
Boxplots for each position

#Installation Guide
Dependencies:
Python 
hvplot
numpy
sqlAlchemy


#License
GNU 

#Contributors 
Jason Muenzen www.linkedin.com/in/jason-muenzen-mba-frm