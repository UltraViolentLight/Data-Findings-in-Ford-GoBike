# Data-Findings-in-Ford-GoBike

> Fifth Project of the Udacity Data Analyst Nanodegree Program

> Python, Visualization, Jupyter, Udacity

---

## Table of Contents 

- [Description](#description)
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


