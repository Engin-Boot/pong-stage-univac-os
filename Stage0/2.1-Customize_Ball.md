# 2.1-Customize Pong Ball

## Feature

Display all features like radius, color, motion, velocity

### Scenario: Set ball radius,color

  Given the player is in menu and goes into settings

  When the player press "ball Radius/Color" option on settings

  Then the player is able to choose colors(some need to be,
  unlocked based on points)

### Scenario: how to change vector animation of ball

  Given the player is in menu and goes into settings

  When the player press "motion animation" option on menu

  Then it allows player to choose options with predefined options
  (like snake motion,etc)
  
### Scenario: how to change Velocity of the ball

  Given  the player is in menu and goes into settings

  When the player press "Velocity" option on menu

  Then it allows player to have customized speed(like slow mo,
  fire)
