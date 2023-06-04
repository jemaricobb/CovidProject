# COVID-19 Data Analysis README

This repository contains code for analyzing COVID-19 data including deaths and vaccinations. The code is written in SQL and performs various queries and transformations on the data. Below is an overview of the different SQL queries and views used in this project:

## Queries

- **Sorting COVID Deaths Data**: The code sorts the COVID deaths data by date and location.
- **Sorting COVID Vaccinations Data**: The code sorts the COVID vaccinations data by date and location.
- **Updating Date Format**: The code updates the date format in both the COVID deaths and vaccinations data to YYYY/MM/DD.
- **Total Cases and Deaths by Location**: The code retrieves data on total cases, total deaths, and death percentages for each location.
- **Total Cases vs Population**: The code calculates the percentage of the population that has contracted COVID-19 for each location.
- **Highest Infection Rates**: The code identifies countries with the highest infection rates compared to their population.
- **Highest Death Count per Population**: The code identifies countries with the highest death count per population.
- **Continent with the Highest Death Count per Population**: The code identifies the continent with the highest death count per population.
- **Total New Cases vs Total Deaths by Date Worldwide**: The code shows the total new cases, total deaths, and death percentages worldwide on each date.
- **Total Cases vs Total Deaths Worldwide**: The code shows the total cases, total deaths, and death percentages worldwide.
- **Joining the Tables**: The code joins the COVID deaths and vaccinations data on location and date.
- **Population vs Vaccinations**: The code retrieves data on population and new vaccinations for each location and date.
- **Population vs Current People Vaccinated**: The code calculates the cumulative number of people vaccinated for each location and date.
- **CTE (Common Table Expression)**: The code creates a CTE to store data on population, vaccinations, and the percentage of the population vaccinated.
- **Creating Views**: The code creates several views to store data for visualization purposes.

## Views

- **CurrentPeopleVaccinated**: A view containing data on the current number of people vaccinated for each location and date.
- **DeathPercentage**: A view showing the death percentage for each location and date.
- **TotalDeathCount**: A view displaying the total death count for each location.
- **InfectionPercent**: A view presenting the percentage of the population infected in each location.
- **InfectionPercentbyDate**: A view showing the percentage of the population infected in each location by date.
- **TotalCasesandDeaths**: A view displaying the total cases, total deaths, and death percentage worldwide.
- **TotalVaccinations**: A view showing the total number of vaccinations worldwide.
- **TotalVaccinationsbyDate**: A view displaying the total number of vaccinations by date.
- **AsiaTotalDeaths**: A view showing the total death count in Asia.

## Views for Visualization

To facilitate data visualization, several views have been created to store specific data. These views can be utilized to generate visualizations and gain insights into the COVID-19 data.

Please note that this README provides a high-level overview of the code and its functionality. For detailed information on each query and view, please refer to the comments within the SQL code.


