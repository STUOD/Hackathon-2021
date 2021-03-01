# ERC Stochastic Transport in Upper Ocean Dynamics Hackathon March 29-31 2021
![stuod logo](https://www.imperial.ac.uk/ImageCropToolT4/imageTool/uploaded-images/erc-stuod-logos--tojpeg_1572609986634_x2.jpg)
## Challenge 3: Machine Learning with Weather and Climate Data

### Task 1: Predicting the rainfall in Basel, Switzerland during the period 2019-2021
Rainfall intensity can be categorized as follows:

- No rain (0 mm)
- Very light rain (0.01 - 2.5mm)
- Light rain (2.5 - 7.5mm)
- Moderate rain (7.5 - 35.5mm)
- Rather heavy rain (35.5 - 64.5mm)
- Heavy rain (>64.5mm)

Your task is to predict the hourly rainfall (based on the 6 categories) in Basel, Switzerland during the period 03/2019-03/2021 from various weather attributes such as temperature, wind velocity and pressure (pre-downloaded dataset can be found in the `datasets` folder. More details below).

Data from [meteoblue](https://www.meteoblue.com/en/weather/archive/export/basel_switzerland_2661604?daterange=2019-02-01%20to%202021-03-01&domain=NEMSAUTO&params%5B%5D=temp2m&params%5B%5D=precip&params%5B%5D=relhum2m&min=2020-02-01&max=2021-03-01&utc_offset=1&timeResolution=hourly&temperatureunit=CELSIUS&velocityunit=KILOMETER_PER_HOUR&energyunit=watts&lengthunit=metric&degree_day_type=10%3B30&gddBase=10&gddLimit=30).

### Task 2 (open-ended): Using data from the Met office to tackle climate change

Some ideas include predicting renewable energy sources such as solar irradiance and wind power.

### Datasets

- Lorenz models (63/96)
- Meteoblue dataset
- Met office data

### Tutorials

In the `tutorials` folder, you can find a three-part tutorial series on machine learning to get you started with the hackathon.
This includes a discussion on:

- Solving classification tasks with ML taking the Lorenz 63 model as a case study
- Regression study with Lorenz 96 model
- Handling real data with `pandas` using a simplified version of the meteoblue data

This tutorial series is aimed at those who are new to machine learning or are just getting started.

Todo: Convert it to binder or colab format to make it interactive

### Submissions

### Acknowledgements
