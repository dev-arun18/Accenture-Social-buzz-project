

# Social Buzz Data Analysis Project

## Project Overview

This repository contains the work done for the **Social Buzz** data analysis project, aimed at identifying the top 5 content categories with the largest aggregate popularity on their platform. The project was conducted to assist Social Buzz in preparing for an IPO and to improve their data management practices.

## Client Information

- **Client Name:** Social Buzz
- **Industry:** Social Media & Content Creation
- **Founded:** 2010
- **Location:** San Francisco, USA
- **Employees:** 250

Social Buzz is a rapidly growing social media platform that emphasizes content over user profiles by maintaining user anonymity. The platform allows for over 100 types of user reactions to content, making content, not users, the focal point of engagement.

## Project Objectives

1. **Audit Social Buzz's Big Data Practices:** Evaluate the current data management processes.
2. **IPO Preparation:** Provide recommendations and best practices for a successful IPO.
3. **Content Category Analysis:** Identify and analyze the top 5 content categories with the highest popularity.

## Project Structure

This project is structured as follows:

1. **Accenture Project Presentation** (`Accenture project ppt- Task 3_final.pptx`)
   - A presentation summarizing the analysis and recommendations.
   
2. **Client Brief** (`Data_Analytics Client Brief (1).pdf`)
   - Detailed client background and project expectations.

3. **Main Dataset** (`Reaction base table cleaned dataset.xlsx`)
   - The cleaned dataset used for final analysis.

4. **Raw Datasets** (`datasets.zip`)
   - Original datasets provided by the client.

## Data Analysis Workflow

### 1. Requirements Gathering
- **Objective:** Identify the necessary datasets for answering the business question.
- **Process:** Selected the relevant datasets (`Reaction`, `Content`, and `Reaction Types`) based on the client’s request to analyze the top 5 categories by popularity.

### 2. Data Cleaning
- **Objective:** Prepare the data for analysis.
- **Process:** Cleaned the `Reaction` table to ensure all data was accurate and relevant for merging and analysis.

### 3. Data Modeling
- **Objective:** Combine datasets and derive insights.
- **Process:**
  - Merged `Reaction`, `Content`, and `Reaction Types` tables using a VLOOKUP formula.
  - Calculated the total scores for each content category using a SUMIF formula to determine the top 5 categories.

### 4. Final Output
- **Deliverable:** A cleaned dataset with the top 5 performing content categories.

## Presentation Structure

Before building the final presentation, we followed a structured approach to ensure all business questions were addressed:

1. **Agenda:** Overview of what the presentation covers.
2. **Project Recap:** Summary of the project objectives and tasks.
3. **Problem Statement:** Description of the business problem solved by the analysis.
4. **Team Introduction:** Introduction of the analysis team, including roles.
5. **Process Overview:** Step-by-step description of the analysis process.

## How to Use This Repository

1. **Clone the Repository:**  
   ```
   git clone https://github.com/yourusername/social-buzz-data-analysis.git
   ```
2. **Explore the Files:**  
   Navigate through the datasets, client brief, and presentation files to understand the project.

3. **Run Your Analysis:**  
   Utilize the cleaned dataset provided to conduct further analysis or reproduce the results.

4. **Modify and Present:**  
   Use the provided presentation template to create your own version of the final presentation.

## Contact Information

For any queries or further information, feel free to contact maheshwariarun983@gmail.com.

---

This README provides a comprehensive overview of the project and guides users on how to navigate and utilize the repository.
