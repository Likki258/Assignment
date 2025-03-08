**Movie Ratings Analysis**
**Analysis Steps**
Generate data with the schema: MovieID, UserID, Rating, and Timestamp.
Load the dataset into a PySpark DataFrame.
Convert the Timestamp column to a human-readable date format.
Find the average rating for each movie.
Identify users who have rated more than 5 movies.
Determine the top 5 highest-rated movies.
Visualize the number of movies rated by each user using a suitable chart.
**Trip Data Analysis**
**Analysis Steps**
Generate data with the schema: TripID, StartTime, EndTime, Distance, and Fare.
Load the dataset into a PySpark DataFrame.
Calculate the trip duration for each trip.
Compute the average fare per mile.
Identify the top 3 longest trips based on distance.
Group trips by the hour of the day and calculate the total number of trips per hour.
Visualize the hours of the day versus the number of trips with a suitable chart.
**Log Analysis**
**Analysis Steps**
Load the log file into a PySpark DataFrame using spark.read.text.
Extract the timestamp, log level (INFO, ERROR, etc.), and message.
Count the number of occurrences of each log level.
Filter and display only the ERROR logs.
Group logs by hour and count the number of logs in each hour.
**Results**
The analysis results include:
A count of occurrences for each log level.
A filtered list of ERROR logs.
The number of logs grouped by hour.
**Visualization**
The analysis results are visualized using matplotlib. The number of logs per hour is represented using a pie chart.
**How to Run**
Clone the repository:
git clone https://github.com/Likki258/Assignment.git
Navigate to the project directory:
cd Assignment
Run the analysis script:

python log_analysis.py
**Dependencies**
PySpark
Matplotlib
Pandas

Make sure to install the required dependencies before running the analysis script.

**Contact**
For any questions or feedback, please reach out to udumulalikhitha2005@gmail.com.
