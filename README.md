# Team 5 Mist 4610 Group Project 1

## Team Name: 
21484 Group 5 

## Team Members:

1. Grace Conn [@graceconn](https://www.github.com/graceconn)
2. Rhea Sabat [@rheasabat](https://www.github.com/rheasabat)
3. Bryce James [@brycejam](https://www.github.com/brycejam)
4. Adam Lebrun [@adam4l](https://www.github.com/adam4l)
5. Josh Horwitz [@Josh-Horwitz-1219](https://www.github.com/Josh-Horwitz-1219)

## Problem Description:

Our data model mirrors that of a high school soccer club. The central entity of our model is the club’s teams. These teams will have varying amounts of players, which is their main distinction from one another. In addition to teams, the club relies heavily on other entities such as its staff, coaches, players, matches, tournaments, sponsors, training facilities, and training sessions. We have been charged with modeling these relationships while also storing the data associated with these entities and relationships in a clear, readable, and accurate manner. Furthermore, we would like to use these relationships between the entities to gain insight and statistics about the club and its performance in different areas mentioned before such as matches and sponsors. 

## Data Model

Explanation of data model: 
TBD

## Data Dictionary:

TBD

## Queries:

### Query 1  
This query lists the player's full name, name of the team they are on, and their team’s number of players for teams that have 5 or more wins.

<img width="613" alt="Screenshot 2024-03-27 at 4 57 14 PM" src="https://github.com/Josh-Horwitz-1219/MIST-4610-Project-1-/assets/163042495/2bb9df91-a4c4-4431-9f4f-520faf2fd590">

Including the number of players on each team in the query enables analysis of team composition and roster management practices. Teams with varying numbers of players may have different dynamics, strengths, and strategies. By examining the team size alongside their performance, coaches and team managers can assess the impact of roster decisions, player rotations, and recruitment strategies on team success.

2.

3.

4.

5.

6.

7.

8.

9.

10.

## Database information:

Name of the database: ns_Sp24_21484_Group5

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Q#();
