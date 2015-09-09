# Javascript RPG Elements v0.0.1
designed by Jeffrey Jean-Pierre

Table of Contents:
- 1 [HP Stats](#hp-stats)
- 2 [Attack Function](#attack-function)
- 3 [Healing Function](#healing-function)
- 4 [Auto Healing Function](#auto-healing-function)
  
  
<a name="hp-stats"></a>
##1 HP Stats
  ```HP Stats are calculated using the baseLife and the currentLife objects. At the time of writing this, baseLife has been set to 200. The currentLife is what is displayed as "HP" and always begins as the player's baseLife stat. When damage is taken, it is currentLife that is recalculated and is displayed.```
  
<a name="attack-function"></a>
##2 Attack Function
  `The attack function will cause damage based on the dmgAmount object. It is set to challenge the currentLife object. Improvements can be made to create a better calculation for how damage should be taken. Currently, if dmgAmount is 3, only 3 points will affect the currentLife.`
  
<a name="healing-function"></a>
##3 Healing Function
  `The healing function will restore currentLife based on the amout of the heal object. Currently, I've added some calculations to test rounding of the healing amount, but it is not founded in any particular healing logic calculation (I merely made one up). Feel free to change this to suit your needs.`
  
<a name="auto-healing-function"></a>
##4 Auto Healing Function
  `The auto healing function will continue to heal a player until his baseLife has been reached. Future improvements could limit how long the auto healing will last (to seconds, or even to a specified amount of healing points).`
