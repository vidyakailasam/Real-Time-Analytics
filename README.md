# Real-Time-Analytics

This particular project relies on a streaming dataset called the New York Yellow Taxi trip data. The dataset includes detailed records of taxi trips in New York City, capturing information like pick-up and drop-off dates/times, locations, distances, fares, rate and payment types, and passenger counts. However, it lacks latitude and longitude data, which will be supplemented later by loading it from a blob container and merging it with the streaming data.

Real-Time Analytics offers a range of streaming and querying capabilities to address various inquiries regarding trip statistics, taxi demand across different New York boroughs, and other related insights. It also facilitates the creation of Power BI reports.

Microsoft Fabric serves as a fully managed big data analytics platform specially optimized for processing streaming and time-series data. It leverages a highly efficient query language and engine capable of effectively searching structured, semi-structured, and unstructured data with exceptional performance.

The process for this project entails several steps:
1. Establishing a KQL (Kusto Query Language) database.
2. Enabling data copying to OneLake.
3. Creating an event stream.
4. Streaming data from the event stream to the KQL database.
5. Obtaining additional historical data.
6. Exploring the data using KQL and SQL.
7. Constructing a KQL queryset.
8. Utilizing advanced KQL queries.
9. Generating a Power BI report.


