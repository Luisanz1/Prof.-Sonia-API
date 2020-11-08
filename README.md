## PROF.SONIA API
This handles all of

Usually this includes
- Splashes
- Pokemon Game
- Character Game
- "Hush" / Secret Achievements
- Patreon handling (Receive pledge data, refresh pledges)


The rest of the inter-node and inter-bot communication is done in Redis.


### Game data 
The data for the Pokemon and Character game is not shared here and is not gonna be made public as this leads to userbot abuse (say, match the image url to a pokemon and answer automatically). Don't ask for it.

To be fair, it's just a text file with the following, repeated a few thousand times:
```
imageurl,name
```
