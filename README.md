# Finance

Projects: Simple Finance Dashboard

Dashboard was created as a way to practice python programming skills, data analytics, and track personal finances with a number of helpful visualizations.

 	Dash_Investment_Portfolio.gif :: .GIF file to illustrate launching the Dash app and look of the Finance Dashboard
    
	Dash_Investment_Portfolio.ipynb :: Jupyter Notebook code to walk thru creation of Dash app
    
	Dash_Investment_Portfolio_Pandas.ipynb :: Jupyter Notebook code to load, tidy, and visualize investment data
    
	Finance_Dashboard.db :: SQLite database to write and load data for Dash app
    
	dummy_cost_unit.csv :: Schema for working with investment data (symbol, transaction type, number of shares, principal, etc)
    
	dummy_quotes.csv :: Daily Market Close of investments to benchmark with mutual fund / ETF / stock purchases and sells
    
Data Workflow to create Finance Dashboard

    1. Pulling daily stock data from an API and loading it into a SQLite database
    2. Add in your own Finance data: dummy_cost_unit shows the schema to load transactional data from investment accounts
    3. Pandas to tidy data
    4. Plot views of tables to create: Unit-Cost graph, Monthly performance, and Cash flow.
    5. Write code for Plotly Dash app (R equivalent to Shiny) and display tables/charts
