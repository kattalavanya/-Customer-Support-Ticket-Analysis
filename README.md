# Customer Support Ticket Analysis

## Project Overview

Customer Support Ticket Analysis is a data analytics project focused on understanding customer support operations through data cleaning, exploratory data analysis (EDA), visualization, and dashboard development.

The project analyzes customer support ticket data to identify patterns in ticket priorities, communication channels, ticket statuses, response and resolution information, and customer satisfaction.

The objective is to transform raw customer support data into meaningful insights that can support better decision-making and improve customer support operations.

## Project Objectives

- Perform data cleaning and data quality checks.
- Identify missing values, duplicate records, and inconsistent data.
- Conduct exploratory data analysis (EDA).
- Analyze ticket distribution across different priorities and communication channels.
- Examine ticket status patterns.
- Analyze response and resolution information availability.
- Evaluate customer satisfaction ratings.
- Develop an integrated dashboard and generate actionable recommendations.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
Customer-Support-Ticket-Analysis/
│
├── Batch6_DIET_Path2.ipynb
├── README.md
└── customer_support_tickets.csv  (if permitted for sharing)
```

## Project Workflow

The project is divided into five major analytical sections:

**1. Data Cleaning and Quality Audit**
- Missing value analysis
- Duplicate record identification
- Data type validation
- Data quality checks
- Preparation of a cleaned dataset

**2. Exploratory Data Analysis**
- Understanding dataset structure
- Statistical analysis
- Identifying patterns and trends
- Data visualization

**3. Ticket Priority and Channel Analysis**
- Ticket distribution by priority
- Communication channel analysis
- Ticket status comparisons
- Priority and channel cross-tabulation
- Open and pending ticket analysis

**4. Response, Resolution and Satisfaction Analysis**
- Response and resolution field coverage
- Timestamp validation
- Customer satisfaction distribution
- Satisfaction analysis by ticket type, priority, and age group

**5. Integrated Dashboard and Reporting**
- Executive summary metrics
- Ticket status and category analysis
- Integrated SUPPORT SCOPE dashboard
- Key findings and recommendations
- Metric traceability and reconciliation

## Key Findings

Some important findings from the analysis include:

- A total of 8,469 customer support tickets were analyzed.
- Medium priority recorded the highest ticket volume, with 2,192 tickets.
- Email was the most frequently used communication channel, with 2,143 tickets.
- Medium priority tickets received through Phone represented the largest priority-channel combination, with 595 tickets.
- Social media had the highest Open/Pending ticket percentage among communication channels, at 67.75%.
- A total of 2,769 valid customer satisfaction ratings were available.
- The average recorded customer satisfaction rating was 2.99 out of 5.

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Ensure the required dataset, `customer_support_tickets.csv`, is available in the project folder (if you have permission to access it).
4. Open the terminal in the project directory.
5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Batch6_DIET_Path2.ipynb`.
7. Run the notebook cells sequentially.

## Important Note

The analysis is descriptive and based on the available dataset. Response and resolution durations and SLA performance are not calculated where the available fields do not establish valid start/end pairs or explicit elapsed durations.

## Conclusion

This project demonstrates the application of Python-based data analytics techniques to customer support operations. Through data cleaning, exploratory analysis, statistical summaries, and dashboard development, the project provides insights into ticket distribution, support channels, ticket statuses, and customer satisfaction.

The findings can help identify areas that may require further operational investigation and support data-driven decision-making.

---

**Project:** Customer Support Ticket Analysis  
**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook
