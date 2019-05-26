# CAPM-FF-STOCK-ANALYSIS
In this project I have analysed two main stocks ,one is from PSX-100 i.e Netsol and the other is from NYSE i.e Tesla. 

The way I analysed was quite simple, I took the data from the internet and tried to combine all of the dataframes.
Afterwards I tried to visulize the data and then tried to compare the distribution of returns of these stocks and saw which perform better.

However, the main main part of this project was running Capital Asset Pricing Model and Famma-French Model on this stock and calculating their respective betas and then trying to predict their future returns.
<h1> CAPM Model </h1>
The CAPM is a model for pricing an individual security or portfolio. For individual securities, we make use of the security market line (SML) and its relation to expected return and systematic risk (beta) to show how the market must price individual securities in relation to their security risk class. The SML enables us to calculate the reward-to-risk ratio for any security in relation to that of the overall market. Therefore, when the expected rate of return for any security is deflated by its beta coefficient, the reward-to-risk ratio for any individual security in the market is equal to the market reward-to-risk ratio, thus:

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/0c9bd79589a7b9a957151f62b5dc2fcb285173a6">

The market reward-to-risk ratio is effectively the market risk premium and by rearranging the above equation and solving for <img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/2b8d0c80160be29edf676943cdef56b08bbcaa01">, we obtain the capital asset pricing model (CAPM).



<h2> FF Model </h2>

The traditional asset pricing model, known formally as the capital asset pricing model (CAPM) uses only one variable to describe the returns of a portfolio or stock with the returns of the market as a whole. In contrast, the Fama–French model uses three variables. Fama and French started with the observation that two classes of stocks have tended to do better than the market as a whole: (i) small caps and (ii) stocks with a high book-to-market ratio (B/P, customarily called value stocks, contrasted with growth stocks).

They then added two factors to CAPM to reflect a portfolio's exposure to these two classes:

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/7dc24d4bef80ffec0eb510514d0a5de782fc92f4">


Here r is the portfolio's expected rate of return, Rf is the risk-free return rate, and Rm is the return of the market portfolio. The "three factor" β is analogous to the classical β but not equal to it, since there are now two additional factors to do some of the work. SMB stands for "Small [market capitalization] Minus Big" and HML for "High [book-to-market ratio] Minus Low"; they measure the historic excess returns of small caps over big caps and of value stocks over growth stocks.

These factors are calculated with combinations of portfolios composed by ranked stocks (BtM ranking, Cap ranking) and available historical market data. Historical values may be accessed on Kenneth French's web page. Moreover, once SMB and HML are defined, the corresponding coefficients bs and bv are determined by linear regressions and can take negative values as well as positive values.


<h3> Please note that the xlsx files are the data used in this project.</h3>
