maam 1st player have control over bullet1group 2nd player on bullet2group and 3rd and 4th player on 3 and 4 bullet group respectivley.so maam coming for 1st player to get count value we are not dependent any if condition we would always get count value and i am udating count when any of the groups is touching dino so maam when system works for 1st player the cinditoin to update count would be true becaus he can shoot bullet1group and o on for other players so if 1st player shot 15 buleets or bullet1group 15 times is touching dino and value of count updates in database then other players should directly get valu of count from database because to get value of count is not dependent upn any if condition so wheen count is 15 in database it would 15 for all players so all the players dino should destroy but it doesnt happens like this.

it happens like when 1st player shot 15 bullets then atleast 1 bullet should be shot by other players too to get the value of count then only count would shown 15 in database.



Rules 

when the game is in gamestate 1 dino should get killed with 15 bullets and gamestate should turn to 2 for all the players and the players would get killed when they touch the dino 

in gamestate 2 when each player has pressed the next button  then only they should go to next gamestate so i used counter for that 

in gamestate 3 it is same as gamestate 1 but enstead of dino i am having enemy and that enemy would be killed when 30 bullets touch him