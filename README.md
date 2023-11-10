# Pro-Bono-Legal-Services-Optimization

## Overview
This project focuses on optimizing the pro bono legal services offered by the American Bar Association (ABA) through a comprehensive analysis. The data for this project is sourced from the ABA. In strict adherence to the privacy and security policy, actual data files are *neither uploaded nor displayed* in the outputs. Instead, only data dictionaries are provided for reference. The datasets, totaling approximately 800 MB, consist of files with a maximum of 400,000+ rows each. For additional details, please refer to the accompanying data dictionary. 

## Project Structure
The analysis is divided into three key parts:

### 1. Exploratory Data Analysis (EDA)
This section aims to gain insights into the relationship between locations and the demand for pro bono legal services. The following aspects are explored:

- **Number of Clients vs. Attorneys in the Same State:** Analyze the distribution and relationship between the number of clients and attorneys within the same state.

- **Active Clients & Attorneys in Each State:** Understand the distribution of active clients and attorneys in each state to identify potential areas of improvement.

- **Response Rate in Each State:** Evaluate the response rates of attorneys in each state to assess the efficiency of the pro bono legal services.

- **Attorneys' Responses to Clients from the Same State:** Investigate whether attorneys tend to reply more promptly to clients from the same state.


### 2. Time Series Analysis
This section involves analyzing the temporal trends in the usage of pro bono legal services. Key analyses include:

- **General Trend of Question Posts Each Year & Each Month of the Year:** Examine the overall trend in the number of question posts on a yearly and monthly basis.
  
- **Rolling Averages:** Smooth out short-term fluctuations and identify long-term trends by calculating rolling averages for both monthly and yearly data.


### 3. NLP Processing & Text Analysis
In this section, Natural Language Processing (NLP) techniques are employed to enhance the understanding of client experiences. I employed techniques such as machine learning, text processing, text vectorization, and word cloud visualization to uncover and understand topics within the pro bono legal service context.
Tasks include:

- **Text Classification:** Employ machine learning techniques for classifying and categorizing text data related to pro bono legal service inquiries.
  
- **Text Clustering with Word Cloud:** Utilize clustering algorithms to group similar text data, and visualize key themes using word clouds.
  
- **Topic Modeling:** Identify key themes using advanced statistical models, uncover hidden patterns, and enhance decision-making by categorizing and organizing text data into distinct topics.
  
These techniques help optimize service offerings and gain insights into the most frequently discussed legal issues, concerns, and inquiries, facilitating data-driven enhancements to the services provided.


## How to Use the Project
This project contains three Jupyter notebooks:

**Part 1 - Exploratory Data Analysis (EDA):** Navigate to the EDA section to explore visualizations and insights related to the relationship between locations and demand

**Part 2 - Time Series Analysis:** Explore the temporal trends in pro bono legal service usage in the Time Series Analysis section.

**Part 3 - Text Analysis (NLP):** Dive into the NLP section to understand the key topics, classifications, and clusters within the text data related to pro bono legal service inquiries.
