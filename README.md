# Implementation-of-ADX-FT
Implementation of ADX and FT indicators 

Closing price Chart:
![image](https://user-images.githubusercontent.com/107173414/225479788-69c74af2-0945-4de6-8b37-221a4e26e4c2.png)

The Average Directional Index (ADX) is a technical indicator that helps to determine the strength of a trend in the financial markets. 

<img width="325" alt="image" src="https://user-images.githubusercontent.com/107173414/225479650-10393dff-a796-4c5b-98a5-1e86e321e0ef.png">

ADX is plotted as a single line with values ranging from a low of zero to a high of 100. ADX is non-directional. When the +DMI is above the -DMI, prices are moving up, and ADX measures the strength of the uptrend. When the -DMI is above the +DMI, prices are moving down, and ADX measures the strength of the downtrend. The chart above is an example of an uptrend reversing to a downtrend. Notice how ADX rose during the uptrend, when +DMI was above -DMI. When price reversed, the -DMI crossed above the +DMI, and ADX rose again to measure the strength of the downtrend.

ADX with +DI & -DI: 
![image](https://user-images.githubusercontent.com/107173414/225479823-a5ebbd26-1698-482e-9978-adcbd3f8e819.png)

The Fisher Transform is a technical indicator that normalizes asset prices, thus making turning points in price clearer. The Fisher Transform indicator is unbounded, which means extremes can occur for a long time. An extreme is based on the historical readings for the asset in question. For some assets, a high reading may be seven or eight, while a low reading may be -4. For another asset, these values may differ. An extreme reading indicates the possibility of a reversal. This should be confirmed by the Fisher Transform changing direction. For example, following a strong price rise and the Fisher Transform reaching an extremely high level, when the Fisher Transform starts to head lower that could signal the price is going to drop, or has already started dropping. The Fisher Transform frequently has a signal line attached to it. This is a moving average (MA) of the Fisher Transform value, so it moves slightly slower than the Fisher Transform line. When the Fisher Transform crosses the trigger line, it is used by some traders as a trade signal. For example, when the Fisher Transform drops below the signal line after hitting an extreme high, that could be used as a signal to sell a current long position.

FT:
![image](https://user-images.githubusercontent.com/107173414/225480028-2778fa10-f13e-47b1-9a78-6f76d5ece0e9.png)
