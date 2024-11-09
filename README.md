Coffee Shop Sales Analysis

Daily Transaction Count by Day • Visualization: Line Chart • Details: Shows the count of transactions for each day. • Fields: o Axis: date o Values: DailyTransactionCount (count of transactions for each date)

Sales Over Time • Visualization: Line or Area Chart • Details: Displays sales trends over a selected period (daily, weekly, or monthly). • Fields: o Axis: date (drill down into day, week, month as required) o Values: TotalRevenue (sum of money for each date)

Frequency of Coffee Purchases • Visualization: Bar Chart • Details: Counts how often each type of coffee is purchased to identify popular coffee types. • Fields: o Axis: coffee_name o Values: TransactionCount (count of coffee_name)

Revenue per Coffee Type by Payment Method • Visualization: Stacked Bar Chart • Details: Shows revenue contribution per coffee type, split by payment method (cash or card). • Fields: o Axis: coffee_name o Legend: cash_type (payment method) o Values: TotalRevenue (sum of money for each coffee type)

Top-Selling Coffee Types • Visualization: Bar Chart • Details: Displays coffee types ranked by revenue to show top sellers. • Fields: o Axis: coffee_name o Values: TotalRevenue (sum of money for each coffee type) • Sort: By TotalRevenue in descending order

Sales Distribution by Time of Day • Visualization: Column Chart • Details: Displays sales distribution across different times of day (morning, afternoon, evening). • Fields: o Axis: TimePeriod (a calculated column that categorizes datetime into Morning, Afternoon, Evening) o Values: TotalRevenue (sum of money)

Transaction by Day of the Week • Visualization: Column Chart • Details: Shows the number of transactions for each day of the week to identify peak days. • Fields: o Axis: DayOfWeek (a calculated column that extracts the day from date) o Values: TransactionCount (count of date for each day of the week) • Sort: By DayOfWeekNumber to display days in logical order (Monday, Tuesday, etc.)

Sales by Payment Type • Visualization: Pie or Donut Chart • Details: Shows the percentage split of total sales by payment method (cash vs. card). • Fields: o Legend: cash_type o Values: TotalRevenue (sum of money for each payment type)

Additional Notes • Dynamic Filtering: Add slicers for Week days and Cash Type to allow for further filtering by date and coffee type.

• Title & Formatting: Label each chart clearly and use consistent colors and fonts for a cohesive report. Add descriptive titles for each section, e.g., "Daily Transaction Count," "Top-Selling Coffee Types."

• Tooltips: Customize tooltips for each visual to show additional information, like the exact sales or transaction count when hovering over data points.

This report layout provides a comprehensive view of coffee shop sales trends, customer preferences, and revenue insights across various dimensions.
