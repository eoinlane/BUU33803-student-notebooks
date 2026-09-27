# BUU33803 Business Analytics: student notebooks

Notebooks and datasets for **BUU33803 Business Analytics** (Trinity Business School, AY 2026-27).
Each notebook opens in Google Colab: nothing to install, and the data loads automatically.

In Colab, use **File → Save a copy in Drive** before you start, so your work is kept.

## Session 1, Introduction + working with Claude

| Notebook | Open |
|---|---|
| The Client Challenge (bike sharing), the in-class exercise | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/session1/Session1_Exercise_BikeSharing.ipynb) |
| Live demo: exploring Camac Drinks' advertising data with Claude | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/session1/Session1_Demo_Advertising.ipynb) |

## Session 2, Linear regression I: building and reading models

| Notebook | Open |
|---|---|
| Your turn: Armand's Pizza, the in-class exercise | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/session2/Session2_Exercise_ArmandsPizza.ipynb) |

## Session 3, Linear regression II: diagnostics and validation

| Notebook | Open |
|---|---|
| Your turn: Break the Model, the in-class exercise | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/session3/Session3_Exercise_BreakTheModel.ipynb) |
| The Central Limit Theorem, live from the room (the in-class demo) | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/session3/Session3_Demo_CLT_CountriesVisited.ipynb) |

## Tutorial 1, practice: a second regression, a second dataset

| Notebook | Open |
|---|---|
| Your turn again: bike rentals, practice for the Session 2 mechanics | [Open in Colab](https://colab.research.google.com/github/eoinlane/BUU33803-student-notebooks/blob/main/tutorial1/Tutorial1_Exercise_BikeSharing.ipynb) |

## Download the data

The notebooks load the data by themselves. To give a dataset to Claude, download it and upload it to
your chat (on each file's page, use the download button at the top right):

- [bike_day.csv](https://github.com/eoinlane/BUU33803-student-notebooks/blob/main/session1/data/bike_day.csv), bike sharing, 731 days
- [advertising.csv](https://github.com/eoinlane/BUU33803-student-notebooks/blob/main/session1/data/advertising.csv), Camac Drinks advertising and sales, 200 towns
- [armands_pizza.csv](https://github.com/eoinlane/BUU33803-student-notebooks/blob/main/session2/data/armands_pizza.csv), Armand's Pizza, 10 restaurants
- [broken_model.csv](https://github.com/eoinlane/BUU33803-student-notebooks/blob/main/session3/data/broken_model.csv), ad spend and new customers, 120 region-months
- [bike_rentals_tutorial1.csv](https://github.com/eoinlane/BUU33803-student-notebooks/blob/main/tutorial1/data/bike_rentals_tutorial1.csv), bike rentals vs temperature (°C), 731 days

## Data sources

- `session1/data/bike_day.csv`: Bike Sharing Dataset (daily counts), Capital Bikeshare,
  Washington DC, 2011–2012. Fanaee-T, H. & Gama, J. (2013), "Event labeling combining ensemble
  detectors and background knowledge", *Progress in Artificial Intelligence*. Distributed by the
  UCI Machine Learning Repository under CC BY 4.0.
- `session1/data/advertising.csv`: Camac Drinks, a fictional sparkling-water brand advertising in
  200 towns across Ireland and Britain: spend on TV, radio and newspaper (thousands of euros) and
  sales (thousands of cans). A teaching dataset, a variant of the Advertising data from
  James, Witten, Hastie & Tibshirani, *An Introduction to Statistical Learning*: the spend columns
  match the book, the sales figures differ.
- `session2/data/armands_pizza.csv`: Armand's Pizza Parlors, a hypothetical chain of 10 restaurants
  near college campuses (student population in thousands, annual sales in thousands of dollars).
  A textbook teaching example from Anderson, Sweeney & Williams, *Statistics for Business and
  Economics*.
- `session3/data/broken_model.csv`: a synthetic teaching dataset, generated for this course. Monthly
  ad spend (thousands of euros) and new customers for 120 region-months, built with diminishing
  returns and noise that grows with spend, so a straight line looks strong and is wrong.
- `session3/data/room_data.csv`: a synthetic stand-in for the class's "countries visited" poll, so
  the Central Limit Theorem demo runs before the poll or without it.
- `tutorial1/data/bike_rentals_tutorial1.csv`: the same Capital Bikeshare data as `session1/data/bike_day.csv`
  (see its citation above), trimmed to date, temperature and rentals, with temperature converted from
  the source's normalised 0–1 scale to real °C.
