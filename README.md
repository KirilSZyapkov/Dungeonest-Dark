# Dungeonest-Dark
As a young adventurer, you seek gold and glory in the darkest dungeons there are. 

You have initial health 100 and initial coins 0. You will be given a string, representing the dungeons rooms. Each room is separated with '|' (vertical bar): "room1|room2|room3…" 

Each room contains item or a monster and a number, separated by space. ("item/monster number") 

If the first part is "potion": you are healed with the number in the second part. But your health cannot exceed your initial health (100). Print: "You healed for {0} hp." 

After that, print your current health: "Current health: {0} hp." 

If the first part is "chest": You've found some coins, the number in the second part. Print: "You found {0} coins." 

In any other case you are facing a monster, you are going to fight.  

The second part of the room, contains the attack of the monster. You should remove the monster's attack from your health.  

If you are not dead (health <= 0) you've slain the monster, and you should print ("You slayed {monster}.") 

If you've died, print "You died! Killed by {monster}." and your quest is over.  

Print the best room you`ve manage to reach: "Best room: {room}". 
