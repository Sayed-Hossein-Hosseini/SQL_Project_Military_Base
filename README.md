# SQL_Project_Military_Base 

## Description  
This project is a database system designed for managing military base information, including soldiers, missions, equipment, and tasks. The project includes a structured database schema and optimized SQL queries to retrieve relevant information.  

## Features  
- Stores military base data including locations, commanders, and equipment.  
- Tracks soldier details such as rank, age, and mission participation.  
- Logs permissions and leaves taken by soldiers.  
- Records mission details, including start and end dates, targets, and casualties.  
- Provides optimized SQL queries for retrieving essential military data.  

![Database Schema](https://github.com/Sayed-Hossein-Hosseini/SQL_Project_Military_Base/blob/master/Database%20Schema/military.png)  

## Files Included  
- `military database.sql`: SQL script for creating the database schema.  
- `Queries.txt`: A collection of SQL queries for retrieving specific information from the database.  
- `military project.pdf`: Project documentation detailing the schema and required queries.  

## SQL Queries Overview  
The project includes several queries that extract valuable insights from the database, such as:  
1. Listing bases in Virginia with air defense systems.  
2. Calculating the total age of soldiers with the rank of Major.  
3. Finding soldiers stationed at bases with commanders holding the rank of Colonel.  
4. Identifying soldiers on annual leave in California.  
5. Extracting details of bases using tank equipment.  
6. Identifying pending tasks assigned to soldiers operating helicopters.  
7. Listing soldiers and their commanders who were on leave in April 2024.  
8. Retrieving reports on missions targeting terrorists.  
9. Identifying missions using tanks and soldiers older than 25 years.  
10. Finding soldiers absent on mission days with high casualties.  
11. Listing missions with high unit losses using helicopters.  
12. Analyzing casualty percentages in Texas bases.  
13. Identifying missions involving soldiers under 28 years old.  
14. Finding soldiers with the highest number of annual leaves.  
15. Counting soldiers in bases with ongoing missions.  
16. Calculating the average age of soldiers participating in supply missions.  

### Bonus Queries  
- Analyzing the percentage of soldiers taking sick leave in air-defense bases.  
- Extracting details of tasks assigned to older soldiers with specific equipment constraints.  
- Identifying bases with Captains participating in high-casualty missions.  
- Listing equipment used in enemy-targeted missions from non-air-defense bases.  

## How to Use  
1. Import the `military database.sql` file into a MySQL or PostgreSQL database.  
2. Use the queries from `Queries.txt` to retrieve necessary data.  
3. Modify or extend the queries based on specific requirements.  

## Requirements  
- MySQL or PostgreSQL database  
- SQL knowledge to modify or extend queries  

## License  
This project is licensed under the MIT License.

## Authors  
- Sayyed Hossein Hosseini DolatAbadi
- Amir Feiz  
