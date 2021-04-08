#  Flights Project

 **by Eloisa Judith Rios Mtz**


## Dataset

This dataset reported 1539 flights in United States in december 2020. The data attributes are carriers, arrival and departure delays, and reasons for delays, year, moth flights cancel and other factors. Dataset was downloaded https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1.

Below is displayed columns' meaning.



Variable    |   Description
:----------- | :-----------
**year** | 2020
**month** | 12
**carrier** | Company name acronym (airline carrier abbreviation)
**carrier_name** | Company name
**airport** | Airport Code 
**airport_name** | Whole airport name
**arr_flights**| Total number of arriving flights in the observation
**arr_del15** | Total number of delayed flights in the observation  
**carrier_ct** | Number of flights delayed due to air carrier (e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc.).
**weather_ct** | Number of flights delayed due to weather.
**nas_ct** | Number of flights delayed due to National Aviation System (e.g. non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control).
**security_ct** | Number of flights delayed due to security (e.g. evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas).
**late_aircraft_ct**| Number of flights delayed due to a previous flight using the same aircraft being late.
**arr_cancelled**|Arrival cancelled, in minutes 
**arr_diverted** | Arrival diverted (Number of flights diverted) , in minutes
**arr_delay** | Arrival delay, in minutes
 **carrier_delay** | In minutes, retraso del operado 
**weather_delay**| Weather delayed in minutes
**nas_delay** | National Aviation System in minutes (subset of arr_delay),in minutes
**security_delay**| Security delay in minutes (subset of arr_delay) 
**late_aircraft_delay** | Aircraft delay in minutes (subset of arr_delay)
**Unnamed** | 21

Mainly target is obtain which airports have more arrives, arrive delay, security delay, weather_ct,carrier_ct, arr_cancelled during december. This analysis will help me to provide information to passangers. So, they can prevent their trips according to the airline they choose. In addition, I will plot on time performance National during december 2020.

## Summary

During whole analysis and visualization. I did some graphs the airports with more arrive flights, with more issues such as weather delay, carrier, air delay, security delay and arrives canceled. As a result, I found that ATL ( Hartsfield–Jackson Atlanta International Airport) got 12420 flights and 1214.2 hours in arrive delay.

In addition, this airport also had 6.06 h delayed due to security and 414.32 min delay due to air carrie. Finally, 74.0 min due to arrive canceled. However, this airline didn't have any issues with weather.

Secondly, DFW International Airport (Dallas/Fort Worth International Airport) had a lot problems during december and at the same time received a lot flights during this month. For instance, 7959 flights arrived and 1318.96 h arrived delay. However, it had 3.6 h as security delay which is almost half in compare with ATL airport. On the other hand, 4917 min as delay due to weather and 279.7 min due to air carrier. Finally, It had 75 min arrived cancel.

Thirdly,CLT (Charlotte Douglas International Airport) arrived 5890 flights and 639.4 h delays. However, It didn't figure in security andweather delays, air carrier issues and arrive cancels.

These airports had setbacks during december and those issues are frequently found at international airports.

Nevertheless, there are international airports which do not have any kind of problem during this month. For instance, I found JAN (Jackson-Medgar Wiley Evers International Airport) which had just 1 arrive flight and any issues due to air carrier. In fact, there are a lot international airports which do not have just one arrive flighs such as: FLL, MYR SC, VT and MSY. In addition, some airports do not have arrive delay for instance:

CID Cedar Rapids/Iowa City, IA: The Eastern Iowa
JAX Jacksonville, FL: Jacksonville International
LIH Lihue, HI: Lihue Airport
MCI Kansas City, MO: Kansas City International
MIA Miami, FL: Miami International
PWM Portland, ME: Portland International Jetport
Below I list the airports without any delay problem due to security.

ABE Allentown/Bethlehem/Easton, PA: Lehigh Valley ...
CID Cedar Rapids/Iowa City, IA: The Eastern Iowa
CHS Charleston, SC: Charleston AFB/International
CHA Chattanooga, TN: Lovell Field
As well airports without any setbacks with weather delays:

ABE Allentown/Bethlehem/Easton, PA: Lehigh Valley ...
ERI Erie, PA: Erie International/Tom Ridge Field
EWN New Bern/Morehead/Beaufort, NC: Coastal Caroli...
EWR Newark, NJ: Newark Liberty International
FAY Fayetteville, NC: Fayetteville Regional/Granni...
Of course, there are some airports which didn't have air carrier issues to name few of them: MSN, MFE, MBS and BNA. In addition, it did not have arrived cancel during december in some airports.

ABE 0.0
MOT 0.0
MRY 0.0
MSO 0.0
MSY 0.0
ORF 0.0
OGD 0.0
As I could observed, ABE (Lehigh Valley International Airport) was one of the best airport which did not have any problem. Nevertheless, it is the airport with least arrive, so this could be the reason that it doesn't present delays or setbacks. Therefore, whole analysis indicated that ATL, DFW AND CLT are the airports with more air traffic and popular. Then, this could be the main problem of arrive cancel, air carrier, security delay and so on.

Finally, I found that on time arrival performance are:

arr_flights 60.9%
carrier_ct 2.8%
weather_delay 33.5%
security_delay 1.1%
late_aircraft_ct 1.4%
arr_diverted 0.09%

On the other hand, I found some airlines such as Allegiant Air (G4) got 60.80% more arrive flights in compare with MQ y OO. However, SkyWest Airlines (OO) had 59.88% follow by Envoy Air (MQ) with 43.5% in delays due to weather. So, some airlines looks that have good services but two of them have more troubles with weather.

I conclude that more than half of the scheduled flights arrive on time and some problems delay is due to weather and NAS. Few retarded were on air carrier and security.

## Key Insights for Presentation

1. A pie chart of arrive flights is presented. 
2. Arrrive delay were transformed to hours for better interpretation.
3. On time performace section was to compares the best performance during december. 
5. Allegiant Air, SkyWest Airlines  and Envoy Air airlines were plotted and I found their performance and that they has few issues but the first one was due to weather.
6. The heatmap I saw some correlations. However, I will nice if I have day data to plot. 


Finally, If the website provide hours and days will provide useful information to gather which airline could have more troubles and which are the best.



```python

```
