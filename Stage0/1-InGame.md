# 1-In the Game

## Acceptance Criteria

Player/players with a mobile/pc having stable internet for multiplayer

### Scenario: players waiting time

  Given players in menu bar

  When the player press " Single player mode" option on menu

  Then a timer of 10 seconds is shown the settings of game and stats
  of player

### Scenario: Sart of ball from which side

  Given the player at start of game

  When the game shows the settings and stats of player

  Then the game starts from left side(cause i am lefty)

### Scenario: Who will get WINNER WINNER chicken DINNER

  Given players are already in game

  When any player score the number as mentioned in settings

  Then declare the player as WINNER WINNER chicken DINNER
  with animation

### Scenario: Displaying scores of players in Multiplayer mode

  Given the players in online mode

  When any of the player wins the game

  Then the display function will show the scores with animation
  and update the stats
