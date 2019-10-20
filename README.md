# moonshot_mission
This is a Time Series Forecasting Project developed in 24 hours during Algothon 2019


### Running instructions
Before running this code make sure you followed the instructions on [1] first.

[1]: https://github.com/unit8co/u8timeseries-viscon


## Inspiration
How to benefit from combining multiple predictive, perhaps less complex, models?

## What it does
It makes forecasting of stock prices.

Timeseries forecasting using simple models in order to reduce noise and then we used ensembling to combine these models to get a more precise and predictive timeseries forecast.

## How we built it
We used the following datasets:
- End of the Day Stock Prices from Quandl,
- Social media Analytics from Quandl,
- Oil price.

## Challenges we ran into
Challenging to take advantage of external data on top of the timeseries itself. Additionally, we ran into myriad bugs because of our ambitions to get the framework to run on top of u8timeseries.

## Accomplishments that we're proud of
Developping a framework to combine different models, i.e. ensembling, and empirically observe substantial loss reduction compared to the individual models.

## What we learned
We learned how to coordinate and split up the tasks in order to use our scarce time as efficient as possible. Also, on a technical point of view, this was a very intense experience. 

## What's next for Moonshot Mission
Multivariate models to run on a portfolio simulation. Use our highly scalable framework to expand the portfolio to a much bigger universe.
