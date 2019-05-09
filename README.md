# Players
Players are organized in clubs. The folder clubs includes one text file (.txt) for each of the 20 clubs competing in the EPL 2013/14.
Each file is named after the corresponding club, e.g., Arsenal-FC.txt. Each line of the file describes an individual player as follows:

- Player name (String)
- Role (String)
- Age (Integer)
- Initial market value in M Euro (Real)
- Club (String)
- Can be sent on a loan? (Boolean)
- Can be sold? (Boolean) 

# Targets

Each club has a list of target players. Target players are organized in five groups, A through E. Each club is assigned a group of targets
as follows (the procedure is described in Pantuso (2017)):

| Team | Targets Group |

|Arsenal FC | A|
| --- |:---·|:---:| 
|Chelsea FC| A|
|Manchester City| A|
|Manchester United| A|
|Tottenham Hotspur| B| 
|Liverpool FC |B |
|Everton FC |B| 
|Newcastle United | B|
|Fulham FC |C| 
|Stoke City | C|
|Sunderland AFC |C| 
|West Ham United | C|
|Aston Villa |D|
|Norwich City |D|
|Southampton FC |D|
|Swansea City |D|
|Cardiff City |E|
|Crystal Palace |E|
|Hull City |E|
|West Bromwich Albion |E|

The folder [targets](./targets) contains one text file (.txt) for each target group (e.g., targetsA.txt).
Each line of a targets file describes a target player as follows:
- Player name (String)
- Age (Integer)
- Initial market value in M Euro (Real)
- Role (String)
- Can be also taken on a loan? (Boolean)

# Ratings

Three versions of ratings are provided:
- R1: Hvattum & Saebo, file ratingsR1.txt
- R2:..., file ratingsR2.txt
- R3:
The structure of the ratings file is
PlayerName(String)  rating(Float)

# Budgets
Each club has an available budget to spend on the transfer market. According to Pantuso (2017) this value is set as the maximum between 0 and the net speending of the club in the transfer market of summer 2014. The [budgets file](budgets.txt) contains the budget of each club as follows:
- Club name (String)
- Budget in M Euro (Real)

# Other parameters

The remaining parameters are provided in the file default_parameters.txt
This file contains, separated by spaces, the following information:
- Number of players that can be registered for competitions (Integer)
- Maximum number of players a club can own (Integer)
- Default retirement age (Integer)
- Ratio purchase price/initial value (Real)
- Ratio selling price/initial value (Real)
- Ratio loan fee/initial value (Real)
- Ratio salary/initial value (Real)
- Discount rate (Real)
