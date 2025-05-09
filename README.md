% COVID-19 Data Analysis Project
\name{COVID-19 Data Analysis Project}
\alias{COVID-19 Data Analysis}
\title{📊 COVID-19 Data Analysis Project 🚀}
\description{
  Welcome to the COVID-19 Data Analysis Project! This project provides an in-depth analysis of COVID-19 cases and deaths across counties in California, using data from Johns Hopkins University CSSE. 🌐
}

\details{
  ## 🚀 Project Overview
  COVID-19 has impacted the world in an unprecedented way, and this project provides a detailed analysis of the pandemic's impact on California counties. By leveraging data from Johns Hopkins University CSSE, this analysis helps you:
  
  - Understand the spread of COVID-19 in different counties.
  - Compare case and death rates between counties.
  - Track trends using time-series and 7-day moving averages.
  
  ## 🛠️ Features
  - ✅ Data Cleaning & Preprocessing: Ensures data integrity by handling missing and erroneous values.
  - ✅ Population Normalization: Calculates cases and deaths per million for fair comparison.
  - ✅ 7-Day Moving Average: Smooths data for clearer trend visualization.
  - ✅ Top Counties Analysis: Easily view the top 10 counties by case and death rates.
  - ✅ Interactive Visualization: Modify counties or the number of top counties directly from the code.
}

\usage{
  ## 📥 Installation
  1. Clone the Repository:
     git clone https://github.com/your-username/covid-19-data-analysis.git
     cd covid-19-data-analysis
  
  2. Install Required Packages:
     pip install -r requirements.txt
  
  3. Run the Project:
     - Ensure you have access to the required data files.
     - Open the Jupyter Notebook:
       jupyter notebook covid-19-data-analysis.ipynb
}

\examples{
  ## ⚡ Usage
  # 🌐 Analyzing Specific Counties
  selected_counties <- c("Alameda", "San Francisco", "San Mateo", "Santa Clara")
  
  # 🚀 Viewing Top Counties
  plot_data(cases_pm_7d, "Top 10 Counties by 7-Day Avg New Cases Per Million", top_n=10)
  
  # 📊 Available Visualizations:
  # - Total Cases & Deaths: View cumulative counts.
  # - 7-Day Average New Cases & Deaths: See trends without daily fluctuations.
  # - Per Million Analysis: Compare normalized data across counties.
}


\references{
  ## 📊 Data Sources
  - COVID-19 Case and Death Data: \href{https://github.com/CSSEGISandData/COVID-19}{Johns Hopkins University CSSE}
  - California Population Data: \href{https://gist.github.com/Nillsf}{Gist by Nillsf}
}

\keyword{COVID-19}
\keyword{Data Analysis}
\keyword{Visualization}
