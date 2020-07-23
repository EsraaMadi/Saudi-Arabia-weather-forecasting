# Historical Weather Status for Saudi Arabia Cities

<br>

## Overview
Are you planning a vacation, trip, party or any other event in Saudi Arabia? Do you want to know how the weather looks like in there, so that your money does not go wasted?

Weather status is crucial for road safety as it directly affects the number of road accidents. Hospitals have precautions when the weather is not great as they expect that the number of emergency cases will be at its peak. 

Being able to forecast the weather for the next couple of years is also crucial for individuals. For example, suppose you are planning a big outdoor wedding for spring 2022 or you are planning a class reunion for next winter, you absolutely want to be aware of the weather status in advance.

Here, we are trying to collect historical weather patterns for Saudi Arabia in order to use it for future weather forecasting.

<br>


## Weather Data
We use this [weather website](https://www.timeanddate.com/weather/) to collect hourly weather data from **2017** to **2019** for all kingdom main cities:
- Qassim
- Hail
- Madina
- EP
- Riyadh
- Mecca
- Tabuk
- Assir
- Northern boarder
- Jazan
- Najran
- Baha
- Jawf

![](assets/weather.png)

<br>

## Weather Scraper
Weather scraper is a python script for downloading weather status such as :
- Date
- Time
- Temperature
- Weather description ( clear - sunny - .... )
- Wind speed
- Humidity
- Barometer (atmospheric pressure)
- Visibility (how much be able to see or be seen)

-----

<br>

### Prerequisites
The requirements.txt file contains any Python dependencies. You can install them by running this command:

```
pip3 install -r requirements.txt
```

### Built With
-  [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)  - Library to scrape information from web pages (HTML or XML parser).
- [selenium](https://pypi.org/project/selenium/) - Automated web browser interaction from Python

### Other Notes
If you're looking for the collected data in years 2017 - 2019 directly, you can find it without running this script uploaded as [Kaggle dataset](https://www.kaggle.com/esraamadi/saudi-arabia-weather-history)
