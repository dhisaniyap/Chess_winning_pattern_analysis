Chess Winning Pattern Analysis Dashboard

Project Overview:

This project focuses on analyzing chess winning patterns using data analytics and interactive Power BI visualizations. The dashboard explores player rating 
relationships, winning trends, game types, opening strategies, and gameplay behavior to uncover meaningful insights from chess match data.

Dataset Information:

The dataset contains detailed information about chess matches, player ratings, openings, and match outcomes.

Dataset Columns

* **id** → Unique identifier for each chess game
* **rated** → Indicates whether the match was casual or competitive
* **created_at** → Start time of the game
* **last_move_at** → Time when the game ended
* **turns** → Total number of turns played during the game
* **victory_status** → Describes how the game ended
* **winner** → Indicates which color won the match
* **increment_code** → Time control provided for the game
* **white_id, black_id** → Unique identifiers assigned to players
* **white_rating, black_rating** → Player ratings before the game started
* **moves** → Sequence of moves played during the match
* **opening_eco** → ECO code representing the opening strategy
* **opening_name** → Name of the opening method used
* **opening_ply** → Number of standard opening moves played before custom gameplay started

Feature Engineering:

Several new features were created to improve analysis and visualization.

Created Columns

* **game_duration_mins** → Calculated using the difference between game start and end time
* **base_time** and **increment_time** → Extracted from increment code to analyze time controls
* **hour** → Extracted from game start time to identify playing patterns based on time of day
* **rating_diff** → Difference between white and black player ratings
* **game_type** → Categorized matches into Bullet, Blitz, Rapid, and Classic based on base time


Tools & Technologies Used:

* Python
* Pandas
* Power BI
* Data Cleaning
* Feature Engineering

Dashboard Insights:

* White players win slightly more games than black players due to the first-move advantage
* Identified the most frequently used opening moves by winning players
* Most players follow standard chess theory for the first 2–5 moves before creating their own strategies
* Rapid game type was the most preferred format among winners
* Most players were matched against opponents with similar ratings, indicating balanced matchmaking
* Most games ended through resignation, suggesting players recognized losing positions before checkmate

Dashboard Features:

* Interactive Power BI dashboard
* Chess-themed UI design
* Winning pattern analysis
* Player rating correlation analysis
* Opening strategy insights
* Matchmaking analysis
* Dynamic filtering using slicers

Conclusion:

This project demonstrates how data analytics and visualization techniques can be used to uncover player behavior, winning trends, matchmaking balance, and 
strategic gameplay insights from chess match data.
