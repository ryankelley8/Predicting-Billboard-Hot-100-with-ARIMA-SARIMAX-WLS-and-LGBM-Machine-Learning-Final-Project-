Billboard and its charts have 
become the industry standard for measuring commercial music
success in the United States. The Billboard Hot 100, in
particular, serves as a weekly benchmark of a song’s
popularity based on streaming, radio play, and sales data.
This project aims to predict a song’s future position on the
Hot 100 chart, specifically forecasting its rank one to three
weeks ahead. To achieve this, I applied a combination
of time series models (ARIMA and SARIMAX) and
machine learning techniques (Gradient Boosted Decision
Trees) to a culmination of weekly charts from 2000-2021.
Preliminary results indicate that AR(3)IMA(3) performed
the best of all the time series models, working well for
short-term stable trajectories. These models were difficult
to interpret and sensitive to the noisy non-normally
distributed chart data. Therefore, gradient boosting was
a better option for capturing the nonlinear patterns of
rapidly changing ranks, explaining 97% of the variance
in the dataset. These predictive models offer insights
into chart dynamics and could support decision-making
in music marketing, promotion, and talent scouting by
anticipating how songs will perform in the near future.
