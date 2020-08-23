# 0-GAME STARTING

## Feature

player can opt for playing(single mode,multiplayer mode[ONLINE,LOCAL],
Rate the game ,choose Difficulty,game settings, shop and exit

## Acceptance Criteria

Player/players with a mobile/pc having the game can play
and stable internet for multiplayer mode.

### Scenario: Background

  Given the background and dimensions

  When game launched

  Then the background is setup.

### Scenario: how to select the level of difficulty

  Given the player in menu option.

  When the player press "Difficulty" option.

  Then it allows player to choose with difficulty using AI
  low,medium,hard,custom
  
### Scenario: how to start game

  Given the player in menu option

  When the player press "PLAY"

  Then ball, paddle and background are rendered for game to start
