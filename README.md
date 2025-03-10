# Employee Performance Data Project

## Overview
This project focuses on analyzing employee performance data using an ETL pipeline. The data is extracted from a CSV file, transformed for accuracy and consistency, and loaded into a database. The final output includes insightful visualizations on employee performance trends.

## Project Components
1. **Data Extraction**: The dataset contains employee performance metrics such as efficiency, task completion rate, and peer reviews.
2. **Data Transformation**: Cleaning and formatting data, handling missing values, and normalizing scores.
3. **Data Loading**: Storing the cleaned data in a relational database (SQLite).
4. **Visualization & Analysis**: Creating dashboards and charts to display performance trends.

## Dataset Description
The dataset contains the following fields:
- `Employee_ID`: Unique identifier for each employee.
- `Name`: Employee name.
- `Department`: Department of the employee.
- `Performance_Score`: A numerical rating of performance.
- `Tasks_Completed`: Number of completed tasks.
- `Peer_Review_Score`: Average peer review score.
- `Attendance_Rate`: Percentage of days attended.

## Technologies Used
- **Python** (Pandas, SQLite, Matplotlib, Seaborn)
- **Streamlit** for dashboard visualization
- **SQL** for database management

## How to Run the Project
1. Clone the repository.
2. Install required dependencies using:
   ```bash
   pip install pandas matplotlib seaborn streamlit sqlite3
   ```
3. Run the ETL script to process the data:
   ```bash
   python etl_script.py
   ```
4. Start the Streamlit dashboard:
   ```bash
   streamlit run dashboard.py
   ```

## Visualizations Included
- **Performance Score Distribution** 📊
- **Task Completion Trends** 📈
- **Top Performing Employees** 🏆
- **Department-wise Analysis** 📌

## Future Improvements
- Implement machine learning to predict employee performance.
- Integrate real-time data updates.
- Enhance dashboard UI with more interactive elements.

---
### Author
Thato Matsimela 
📧 Contact: thatomatsimela480@gmail.com.com

