# Weather Status Forecasting for Saudi Arabia Cities

<br>

This tutorial is a simple application that used [weather data](https://github.com/EsraaMadi/KSA-weather-scraping) we've collected early.

In this tutorial, we used Recurrent Neural Networks (RNNs) to build time series forecast model. This is covered in three parts:

Part No. |Google Colab | GitHub |
--- | --- | --- |
1. Forecast weather temperature of one city. | <a href="https://colab.research.google.com/drive/1Hh3abwhZrIJWOpySLWnhsMPX94AP9JL3?usp=sharing"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />  Run in Google Colab</a> | <a href="https://github.com/EsraaMadi/Saudi-Arabia-weather-forecasting/blob/master/forecasting_city's_weather_temperature.ipynb"><img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" /> View source on GitHub</a> |
2. Forecast weather info (barometer, humidity, temperature, visibility, wind) for any Saudi city.| <a href="https://colab.research.google.com/drive/10x1P0ptobYKdKOrr6-VWrbq7tAsn7H--?usp=sharing"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />  Run in Google Colab</a> | <a href="https://github.com/EsraaMadi/Saudi-Arabia-weather-forecasting/blob/master/forecasting_city's_weather_info.ipynb"><img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" /> View source on GitHub</a> |
3. Forecast weather temperature for multiple Saudi cities on a certain date.| <a href="https://colab.research.google.com/drive/1sCguUuYC_gdQ2w1cfsmm2kF9yIM_SHLp?usp=sharing"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />  Run in Google Colab</a> | <a href="https://github.com/EsraaMadi/Saudi-Arabia-weather-forecasting/blob/master/forecasting_weather_temperature_of_multiple_cities.ipynb"><img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" /> View source on GitHub</a> |

<br>


## Weather Data
This tutorial uses [Saudi weather dataset](https://github.com/EsraaMadi/KSA-weather-scraping) which is an hourly weather data from **2017** to **2019**

for all kingdom main cities:
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

This dataset contains 8 different features such as:
- Date
- Time
- Temperature
- Weather description ( clear - sunny - .... )
- Wind speed
- Humidity
- Barometer (atmospheric pressure)
- Visibility (how much be able to see or be seen)


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
The requirements.txt file contains all Python dependencies. You can install them by running this command:

```
pip3 install -r requirements.txt
```

### Built With
-  [D-tale](https://pypi.org/project/dtale/)  - Library to provide an easy way to view & analyze Pandas data structures.
- [Tensorflow](https://www.tensorflow.org/) - Open source library to develop and train ML models.
