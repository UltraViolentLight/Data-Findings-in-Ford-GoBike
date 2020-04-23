# Data-Findings-in-Ford-GoBike

> Fifth Project of the Udacity Data Analyst Nanodegree Program

> Python, Visualization, Jupyter, Udacity

---

## Table of Contents 

- [Description](#description)
- [Summary](#summarty)
- [Remarks](#remarks)
- [Example](#example)
- [Installation](#installation)
- [Credits](#credits)

## Description

This Notebook provides a a viualzation approach on said dataset the Ford Bike Sharing System in the Bay-Area.

The dataset to be analyzed it Bay Wheels's trip data for public use.  This data is provided according to the Bay Wheels License Agreement. Each trip is anonymized and includes:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
---

## Summary

### Univariate Conclusions for 2019
- Most rentals happen in the morning or in the evening when people are about to start work or get home from work
- Most rentels happen on weekdays when people have to go to work
- There is no real seasonal impact on the rentals observable, this might be because the weather in the bay area is always quite mild
- There are 3 regions for the stations
    - San Francisco
    - Oakland
    - San Jose
- On average people ride about 1km
- On average people ride about 10 min
- Distributions for the distance and the rental time were highly right skewed. Therefore a log scale made the result more understandable.

### Bivariate Conclusions for 2019
- A medium correlation (r~0.5) indicates that long rental duration comes with somewhat longer rides
- In contrast to the amount of rentals over the months a clear seasonal influence can be observed
- People rent bikes for a longer period of time in the summer
- People rent bikes on the weekend for a longer period of time

### Multivariate Conclusions
- The seasonal impact of more longer rentals in the summer is more noticable for the customer group
- When the service launched in 2017 a spike in car rentals is very noticable for the customer group and probabily an indication of good advertisement
- On the weekend both user_types rent bikes for a longer period of time. This has not been changed compared to 2017.
- On average customers rent bikes way shorter in 2019 compared to the beginning of the service in 2017
- On average subscribers rent bikes in 2019 for a similar amount of time compared to the beginning of the service in 2017

### Recommendation for GoBike
- There is potential of customers, which are not yet subscribers and could be targeted by advertisment. These 20% did not change much compared back to 2017. 

- GoBike should schedule their maintanance hours towards the Winter or the night but not nessacarly on the weekend. Since technically less rentels happen on the weekend but these rentals last much longer. A shortage of bikes could lead unsatisfied customers.

- In General the amount of bike trips increased vastly over the years, which indicates a successful/profitable service offer and acceptence by the customer.

---

## Remarks

Due to to the Data Visualization in Folium the Jupyter Notebook size increased to > 100 MB. To handle this filesize the notebook had to be zipped in `exploration.ipynb.zip`.

The result are presented within the slide_deck.ipynb. The html was extracted with the following code using the template files.

```shell
$ jupyter nbconvert slide_deck.ipynb --to slides --post serve --template template_files/output_toggle
```

---

## Example

```shell
$ jupyter notebook
```

> open `exploration.ipynb` in browser
> open `slide_deck.ipynb` in browser

---

## Installation

### Clone

- Clone this repo to your local machine using `git https://github.com/UltraViolentLight/Data-Findings-in-Ford-GoBike`

### Setup
> update and install the following python packages/software first

- Jupyter Notebook
- Python 3.6
- pandas
- numpy
- ramdom
- matplotlib
- seaborn
- folium

---

## Credits

- All Data was provided by the Udacity Data Analyst Nanodegree Program and [Lyft](https://www.lyft.com/bikes/bay-wheels/system-data). The template file is obtain from [Damianavilas GIT Repo](https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb).


