# Financial_Planner

![financial image](financial-planner-image.png)

This Financial_Planner repository is made up of two financial analysis tools inside one jupyter notebook. It consists of a fianacial planner for emergencies, and another one for retirement. I have leveraged Pandas and the data analysis tools available to visualize if the user has enough reserve funds for and emergency and then I go on to create a financial planner for retirement. This tool will forecast the performance of a retirement portfolio for 30 years. We do this by making an Alpaca API Call via the Alpaca SDK to get historical price data and use this data in a few Monte Carlo simulations.


## Technologies
---
This Analysis uses Python 3.7 with the following packages:

``` pandas ```

``` requests ```

``` json ```

``` os ```

``` dotenv ```

``` alpaca_trade_api ```

``` MCForecastTools ```


## Installation Guide
---
This Analysis was done with ``` Pandas ``` on ``` Jupyter Lab ```  To run the functions and interact with the notebook, first install the following:

``` pip jupyter lab ```

``` pip install python 3.7 ```

``` conda install -c anaconda requests ```

``` conda install -c mcmurray json ```

``` pip install python-dotenv ```

``` pip install alpaca-trade-api ```


## Usage
---
The file of interest is ``` financial_planning_tools.ipynb ```
If someone wanted to replicate the functions with different data, it can be done, it would require going to 
[Alpaca API](https://app.alpaca.markets/login) to signup for a free API Key and Secret Key and then saving those keys into a .env file in the working folder.
Then with the ``` load_dotenv ``` function, we are able to pull the keys from a hidden .env file and that way our sensitive info stays hidden.


## Contributors
---

Stephen Thomas

[Trilogy Education Services](https://www.trilogyed.com/)

[UC Berkeley Extension ](https://extension.berkeley.edu/)


## License
---

MIT
