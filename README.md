# AA End-Game Practice
Practice Datapack and Seed List for the End-Game Split of an All Advancements Speedrun.  

![image](https://github.com/Quidvio/AA-End-Game-Practice/assets/105707614/d728d3bc-f70a-4683-a67c-4ffaa943b769)  

## Features

- Spawn in with all of the items you would have and need for End-game.
- Spawns a shulker in a boat on top of you.
- 2 "Free Nether Portal" Spawn Eggs.
   - Given because you'd normally have 2 from the any% section.
- Placing a nether portal in the ring[^1] puts you in a Stronghold.
   - The Portal is lit of course.
   - The Dragon is already dead, go through to get The End Again Advancement.

![image](https://github.com/Quidvio/AA-End-Game-Practice/assets/105707614/9b4faf83-7b28-4a9d-a2a6-ff70eba0f34b)

---

## Seed List

The Seed List is filtered for a typical AA spawn[^2], with an Outpost within 32RD of spawn, and a Monument and Village within 32RD of the Outpost.  

![image](https://github.com/Quidvio/AA-End-Game-Practice/assets/105707614/82752b52-767d-411e-80a1-67d6a4da7288)
> Here is an example seed. The Village won't be on your spawnpoint, just close.

---

### Customizing

It *is* possible to change the layout of the kit items/shulker box, but it is not very user friendly.  
You would need to...
1. Open the kit.mcfunction file.  
2. Copy the execute... setblock command for the chest.  
3. Paste it into a command block and run it.  
4. Edit the chest content/locations to your liking.  
5. Use F3+I on the chest to generate a setblock command with its blockdata..  
6. Replace the setblock command with the new one generated.  
   - Note that you must make sure you keep the execute portion of the original command.  
   - Note that the coordinates should stay the same as the original setblock command as well.  
7. Save the datapack and that should be all.  

I may make a tutorial or find a way to make it easier to change in the future.


[^1]: Stronghold ring. 160 blocks out in the nether, or 1280+ blocks out in the overworld.
[^2]: Desert near spawn. Spawn itself will never be a jungle, taiga, or forest biome. Not necessarily a nearby body of water.
