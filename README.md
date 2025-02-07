# Football Tournament Managament System

## Description

This system is designed to store and manage information about football tournament seasons. It includes detailed records for various entities involved in the tournament, such as clubs, players, coaches, referees, and stadiums.

The system tracks information about the clubs participating in the tournament. For each club, you can retrieve data about the players, including whether they play officially for the club or on loan. The system also stores the duration of these players' contracts with the club, whether as official players or loaned players. Additionally, detailed data about each match during the season, such as match results, goals scored, goals conceded, and overall points, is also stored. Clubs are ranked based on their points, and the number of goals scored and conceded is recorded for every match in the tournament.

Each club is associated with a stadium, and the stadium details include the stadium's name, location, and seating capacity.

## Entities

### Clubs

- **Club Information**: Includes club details, such as the name, location, and the stadium they own.
- **Club Performance**: Tracks the club's performance in each season, including points, goals scored and conceded, ranking, and match results.
- **Loans**: Stores data on players that belong to the club but are loaned to other clubs, along with the duration of the loan.

### Players

- **Basic Information**: Includes player details such as name, age, position, and the number of yellow and red cards received.
- **Player History**: Tracks which clubs the player has played for, including the duration of their contract or loan with each club.
- **Player Performance**: Records the goals scored by the player, assists, yellow/red cards, substitutions, and match participation details (starting player, substitute, captain, etc.).
- **Transfer History**: Tracks the player's transfer status, whether they are officially part of the club or loaned out to another club.

### Coaches

- **Coach Information**: Includes the coach's name, position, years of experience, and certifications.
- **Coaching History**: Records the period the coach has been leading the club and the type of coach they are (technical coach or specialized coach).
- **Certifications**: Tracks the types of certifications the coach holds, including the certification name and expiration date.

### Referees

- **Referee Information**: Includes details about the referees who officiate matches, including their name, age, and position in the match.
- **Match Involvement**: Tracks which matches the referee has officiated and what positions they held (main referee, assistant, etc.).

### Matches

- **Match Information**: Stores data about each match in the tournament, including the match time, score, home and away teams, and the match's outcome (goals scored, red/yellow cards).
- **Match Statistics**: Includes detailed statistics for each match, such as goals scored, yellow/red cards, goal scorers, substitutions, and injury time.
- **Referee Data**: Tracks the referees involved in the match and their positions.
- **Substitutions**: Records the substitution events, including which players were substituted and when.

### Tournaments

- **Season Information**: Stores basic information about each tournament season, including the start and end dates.
- **Tournament Performance**: Tracks which clubs participated, the total number of goals scored, yellow/red cards, and player statistics (top scorers).
- **Winner Determination**: Identifies the winner of the tournament based on points, goal difference, and match results.

## Features

- **Club Management**: View and manage information about clubs, including players, coaches, and stadiums.
- **Player Performance**: Track player statistics such as goals, assists, cards, and match participation.
- **Coach Management**: Record details about the coaches, their certifications, and their coaching history.
- **Match Information**: Retrieve details about matches, including score, goals, cards, substitutions, and referees.
- **Tournament Overview**: Get detailed information about each season, including participating teams, top scorers, and the tournament winner.
