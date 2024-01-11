# Trading-model - 3 PM
DATA is used of NSE: NIFTY 50 only  (widely used Indian Index)
Firstly, I made some data rows according to the direction and aggressiveness of momentum in the market. It is based on the famous 3 pm setup in markets.


Why 3 pm setup -- This is a major time when option/futures buyers and sellers are exiting their positions and making new positions for upcoming days, which results in major moves and market inefficiencies.

# Deep Learning model
I created a DL model that can tell the aggressiveness of markets at the time range of 2:45 - 3:00 and it should be applied when a doji(indecision) candle is formed and it predicts whether a trade should be taken or not.

For the Deep Learning model, I have used ANN along with principal component analysis(PCA) with data cleaning and data handling techniques 
