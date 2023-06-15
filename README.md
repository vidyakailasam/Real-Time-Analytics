# Real-Time-Analytics

This project is based on a streaming data called New York Yellow Taxi trip data. The dataset contains trip records of New York's yellow taxis, with fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. This data doesn't contain latitude and longitude data, which will be loaded from a blob container and joined together with the streaming data in a later step.

Various streaming and query capabilities of Real-Time Analytics are used to answer key questions about trip statistics, taxi demand in the boroughs of New York, and related insights and build Power BI reports.

Microsoft Fabric is a fully managed big data analytics platform optimized for streaming and time-series data. It utilizes a query language and engine with exceptional performance for searching structured, semi-structured, and unstructured data with high performance.

Steps:

1. Create a KQL database
2. Enable data copy to OneLake
3. Create an eventstream
4. Stream data from Eventstream to your KQL database
5. Get additional historical data
6. Explore data with KQL and SQL
7. Create a KQL queryset
8. Use advanced KQL queries
9. Create a Power BI report


