# Financial


Automation using Technology in Trading & Exchanges is considered as de-facto principle nowadays. Financial applications require low latency and high throughput to cope with the demands of the market, this is the reason that the financial sector is a prominent user of High Performance Computing facilities. Implementations of hardware financial accelerators on reconfigurable logic are perfect candidates for this sector, because they can achieve those requirements through the use of parallelization techniques. Three commonly used algorithms for financial application, such as Risk Valuation, are Black & Scholes, Black-76 and Binomial algorithms. 

The Black & Scholes model gives a theoretical estimate of the price of European-style options and can also be used for American-style call options. The Black-76 model is a variant of the Black & Scholes model that supposes the underlying is lognormal but the underlying price is the future prices, not the spot price. The Binomial option pricing model discretize time and price of an underlying asset, and mapping both onto a binary tree, thus can handle American put options that can be exercised at any time. 

In this project, we investigate those three algorithms:
* The Black & Scholes method for American call options based on spot prices for stock options.
* The Binomial method, without dividends, for American put options based on spot prices for stock options.
* The Black-76 method for European options based on future prices for index options.

This repository hosts the hardware accelerators that have been developed in VINEYARD project in the SDAccel framework. 
The binary files are used for the AlphaData KU3 FPGA card.

For more information: http://vineyard-h2020.eu/en/ 
