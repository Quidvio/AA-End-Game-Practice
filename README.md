# AA End-Game Practice
Practice Datapack and Seed List for the End-Game Split of an All Advancements Speedrun.

## Info  
Datapack is self-explanatory, but I'll explain two features:

If you place a nether portal in the ring[^1] and go through, you will spawn in a Strongold with only the Portal Room with a lit End Portal.  

Use this to get into the end to do The End Again Advancement. 

---

## Seed List

The Seed List is filtered for a typical AA spawn[^2], with an Outpost within 32RD of spawn, and a Monument and Village within 32RD of the Outpost.  

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
