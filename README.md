# COVID-19 DataViz Challenge

Webpage: [https://eric-han.com/covid-19/](https://eric-han.com/covid-19/)

Folder Structure:

```
.
├── covid.css
├── data
│   ├── preprocess-q1.py
│   ├── preprocess-q2.py
│   ├── preprocess-q3.py
│   ├── preprocess-q4.py
│   ├── preprocess-q5.py
│   ├── q1.csv
│   ├── q2.csv
│   ├── q3.csv
│   ├── q4.csv
│   ├── q5.csv
│   ├── raw
│   │   ├── continent.csv
│   │   ├── country_code.csv
│   │   ├── covid_19_data.csv
│   │   ├── COVID19_line_list_data.csv
│   │   ├── COVID19_open_line_list.csv
│   │   ├── goveff.csv
│   │   └── health.csv
│   └── world.geojson
├── Report.pdf
├── index.html
├── LICENSE
├── q1.html
├── q2.html
├── q3.html
├── q4.html
├── q5.html
└── README
```

1. `data`: Contains the data and python script used to preprocess data for our viz
2. `covid.css`: Common stylesheet for all q1-q5
3. `q1.html`... `q5.html`: The individual viz with their code written directly inside
4. `README`: This document
5. `Report.pdf`: Report as required

We did not include any additional dependencies here as they are referenced directly on each webpage.

## How to run

1. You can run each of the python3 Scripts by `python3 preprocess-q1.py` to preprocess data for q1. The processed data will be located in q1.csv.
2. You can start a http server in the root directory.
