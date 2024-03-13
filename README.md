# EconomicDataAnalysis
In my introductory economics class, I learnt about inflation. <br/>
Simply put, inflation is the rise in price levels of goods and services above the normal price. <br/>
This happens when there is the current ouput of a country's output exceeds the full-employment output(thus, at this point there is more spending or consumption than production of goods and services in the economy) <br/>
The theoretical framework for inflation is derived from the velocity of money equation, MV= PQ (where M=money supply, V =velocity of money/rate at which it is being spent/circulated, P=price level of goods and services, Q=quantity of goods and services being produced) <br/>
At the full-employment output, MV must be equal to PQ. <br/>
Assuming V is held constant, and more money is being supplied into the economy(M), if the quantity of goods and services provided by a country remains the same, the proce level would have to increase in order to balance both sides of the equation. <br/>
This would mean that consumers would be paying higher prices for the same amount of goods and services. <br/>
Thus, inflation is associated with higher prices(or higher consumer price index) <br/>

Aside from inflation, I'm also interested in understanding foreign exchange markets: specifically, why the exchange rate for a particular country would increase or decrease. <br/>
In the dataset, the exchange rates of all countries were with respect to the American dollar, since it is the most widely used currency in currency markets. <br/>
Hence, the exchange rate for a country would be how much value of the country's currency that can be exchanged for a U.S. dollar. <br/>
Another way to put it would be the price of a U.S. dollar in the particular country's currency. <br/>
Several factors such as high imports from another country(such as U.S.) could raise the exchange rate because consumers would have to use more U.S. dollars in buying U.S. goods <br/>
Hence, the increased demand for U.S. dollars raises the price of a dollar in that particular country <br/>
From the export lens, countries that would want industries to expand their export markets could possibly benefit from depreciation of a currency,because foreign consumers would be able to buy or import goods from that country at a lower cost. <br/>

In this notebook, I try to analyse the inflation(through the annual consumer price index) and the USD exchange rates of a number of African countries(between 2000 and 2014) to explore possible correlations between exchange rates and inflation <br/>
For this analysis, I used linear regression (assuming a possible linear relationship between these two variables) and calculate the r^2 values for the different countries to see if this relationship holds true for all countries or if it deviates in other countries. <br/>
