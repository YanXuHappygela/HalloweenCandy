# Make best Halloween Candy in TPOT with LIME

What makes a great Halloween candy? Let's use some ML trick and find our best version of Halloween candy and most importantly, use TPOT (auto machine learning) and LIME (explaining any complex ML model).

The original data can be downloaded at:
https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking

You can install TPOT here:
https://github.com/EpistasisLab/tpot

and LIME here:
https://github.com/marcotcr/lime

In this experiment, we shall first build two baseline models: linear ridge regression and gradient boosting trees. Then we try out automatic machine learning (TPOT), which will automatically generate the python scrip for the best pipeline.

Next, we explain our model with LIME to reason behind why this candy gets this score.

Finally, we make our recommendation for best Halloween candy!
