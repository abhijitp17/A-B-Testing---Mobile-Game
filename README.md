# A-B-Testing---Mobile-Game
Conducted A/B test to analyze the player retention for Cookie Cats, a popular mobile puzzle game.

Cookie Cats is popular mobile puzzle game developed by Tactile Entertainment. It is a "connect-three" puzzle game where the player connect tiles of same color to clear the board and win the level.

As the game progresses through the levels, the player cencounters gates that ofrces the player to wait an amount of time or make an in-app purchase. These gates also gives the players an enforced break from playing the game resulting in an increase in the enjoyment of the game.

But where the gates should be places? Initially the gates was placed at level 30, but here we are analyzing an AB-test wherewe moved the first gate in the game from level 30 to level 40. We are looking at the impact on player retention.

The variables are:

**userid** - a unique number that identifies each player<br/>
**version** - whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40)<br/>
**sum_gamerounds** - the number of game rounds played by the player during the first 14 days after install<br/>
**retention_1** - did the player come back and play 1 day after installing?<br/>
**retention_7** - did the player come back and play 7 days after installing?<br/>
