# Bank Loan Analysis

### Power BI Dashboard: (https://app.powerbi.com/reportEmbed?reportId=f36d8faa-dd67-486e-8d76-96183864149d&autoAuth=true&ctid=edc5c3bf-4ab5-4697-84fa-41b44eb08b5e)

## Problem Statement

This project aims to provide a comprehensive analysis of a bank's loan portfolio, helping stakeholders understand loan distribution, repayment behavior, and overall portfolio health. The analysis identifies key performance indicators (KPIs) such as total loan applications, funded amounts, and loan performance metrics. By using this dashboard, stakeholders can make data-driven decisions to optimize loan processes and reduce risks.

### Steps Followed

- **Step 1**: Loaded the dataset (30,000+ loan records) into Power BI Desktop.
- **Step 2**: Cleaned and transformed the data using Power Query Editor, checking for column quality, distribution, and profiling.
- **Step 3**: Executed 15+ SQL queries to extract KPIs like total loan applications, funded amounts, average interest rates, and loan performance metrics.
- **Step 4**: Created 3 detailed Power BI dashboards with 10+ dynamic filters to allow users to explore loan data across multiple dimensions such as month, state, and loan grade.
- **Step 5**: Added card visuals to display key metrics like total loan applications, average funded amount, and average interest rate.
- **Step 6**: Visualized loan performance with bar charts, segmenting good (fully paid/current) vs. bad (charged-off) loans, and incorporated slicers for detailed analysis.
- **Step 7**: Published the report for easy access and collaboration.

### Insights

The following key insights were drawn from the dashboard:

1. **Loan Performance**:
   - **Good Loans**: 78% of the portfolio.
   - **Bad Loans**: 22% of the portfolio.

2. **Average Interest Rate**:
   - The average interest rate across the portfolio is 11.5%.

3. **Loan Distribution by State**:
   - The highest number of loan applications came from California, followed by Texas and New York.

4. **Monthly Loan Trends**:
   - Peak loan issuance occurred in December, with a 15% increase compared to the previous month.

5. **Loan Grade Analysis**:
   - Grade A loans had the lowest default rate at 5%, while Grade D loans had the highest at 20%.

### Visuals Included

- **KPI Cards**: Display total loan applications, average funded amounts, and interest rates.
- **Bar Charts**: Show good vs. bad loan performance, segmented by loan grade and state.
- **Line Charts**: Visualize monthly trends in loan issuance and repayments.
- **Slicers**: Provide filtering options by month, state, loan grade, and loan purpose.

![bank loan analysis_page-0001](https://github.com/user-attachments/assets/3e6f70e3-672b-4f0d-9d55-fb12025cd8ec)
![bank loan analysis_page-0002](https://github.com/user-attachments/assets/2dfd9074-6a21-4a58-9122-6dead02db59b)
![bank loan analysis_page-0003](https://github.com/user-attachments/assets/f7a34080-9a58-482b-ad26-f96eb0cc4076)


### Technologies Used

- **SQL**: For data extraction and KPI calculation.
- **Power BI**: For creating interactive dashboards and visualizations.

### How to Use

1. **SQL Queries**: Access the SQL scripts in the `SQL Queries` folder. Run these queries on the provided dataset to extract KPIs.
2. **Power BI Dashboard**: Open the `.pbix` file in Power BI Desktop to interact with the visualizations and explore the data using filters.
3. **Dataset**: The dataset used for this analysis is included in the `Data` folder. Ensure your SQL environment is connected to this dataset for accurate results.

### Conclusion

This project highlights the importance of data-driven decision-making in financial services. By analyzing key loan metrics, stakeholders can gain valuable insights that help in optimizing loan processes and reducing financial risk.
