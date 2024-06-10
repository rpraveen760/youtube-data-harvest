YouTube Data Harvesting and Warehousing using SQL and Streamlit.

Problem Statement: The problem statement is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels.

The application should have the following features:

$ Ability to input a YouTube channel ID and retrieve all the relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video) using Google API.

$ Option to store the data in a MySQL database. Ability to collect data for up to 10 different YouTube channels and store them in a DB by clicking a button.

$ Ability to search and retrieve data from the MySQL database using different search options, including joining tables to get channel details.

$ YouTube API: You'll need to use the YouTube API to retrieve channel and video data. You can use the Google API client library for Python to make requests to the API.

$ Query the SQL data warehouse: You can use SQL queries to join the tables in the SQL data warehouse and retrieve data for specific channels based on user input.

$ Display data in the Streamlit app: Finally, you can display the retrieved data in the Streamlit app. Overall, this approach involves building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MySQL database, querying the data with SQL, and displaying the data in the Streamlit app.

Configuration:

1.Open the main.py file in the project directory.

2.Set the desired configuration options:

3.Specify your YouTube API key.

4.Choose the database connection details (SQL).

5.Get the Youtube Channel ID from the Youtube's sourcepage

6.provide the Youtube Channel ID data to be harvested.

7.Set other configuration options as needed.

Usage:

1.Launch the Streamlit app: streamlit run main.py

2.The app will start and open in your browser. You can explore the harvested YouTube data and visualize the results.

