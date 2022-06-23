# SQL-World-Statistics-Analysis

## Introduction

This project will seek to analyze the CIA World Factbook as it relates to different countries. This database contains different statistics and demographics about countries around the globe.

## Usage

The factbook database can be downloaded [here](https://github.com/factbook/factbook.sql/releases). Once there, click on `factbook.db`. This will download the database.

Once downloaded, run the following code to connect to it:

`%%capture`<br>
`%load_ext sql`<br>
`%sql sqlite:///factbook.db`<br>

To run SQL queries in Jupyter Notebook, you must add `%%sql` at the start of every of cell.<br>

The dataset will be explored using Jupyter Notebook. To run the project you will want to install Jupyter Notebook. The easiest way to do this is by installing Anaconda Navigator. This link will direct you on how to install for your appropriate operating system: Windows, Mac OS, Linux, etc. Once installed, you should have access to several applications, one of them being Jupyter Notebook.

## Brief Overview

Here are some important columns to note:

* `name` — the name of the country.<br>
* `area`— the country's total area (both land and water).<br>
* `area_land` — the country's land area in square kilometers.<br>
* `area_water` — the country's waterarea in square kilometers.<br>
* `population` — the country's population.<br>
* `population_growth`— the country's population growth as a percentage.<br>
* `birth_rate` — the country's birth rate, or the number of births per year per 1,000 people.<br>
* `death_rate` — the country's death rate, or the number of death per year per 1,000 people.<br>
