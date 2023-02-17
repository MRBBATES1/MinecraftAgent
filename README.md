# MinecraftAgent

__Version:__ 1.17.20 to 1.19.10

__By:__ MRBBATES1

__Description:__

This is the pack that was made/showcased to demostrate how to spawn in and use Minecrafts Agent for Minecraft Bedrock edition without the need of using the education edition of minecraft.

This also includes the UI seen in the showcase.

__Agent Commands:__

```
agent move [direction]
agent turn [turnDirection]
agent attack [direction]
agent destroy [direction]
agent drop [int:slotNum] [int:quantity] [direction]
agent dropall [direction]
agent inspect [direction]
agent inspectdata [direction]
agent detect [direction]
agent detectredstone [direction]
agent transfer [int:srcSlotNum] [int:quantity] [int:dstSlotNum]
agent create
agent tp [coordinates]
agent collect [string:item]
agent till [direction]
agent place [int:slotNum] [direction]
agent getitemcount [int:slotNum]
agent getitemspace [int:slotNum]
agent getitemdetail [int:slotNum]
```

**Please note** If you wish to use on a version higher than 1.19.10 then you will need to change the execute command as this has changed, so for example the original dialogue file, the command used to spawn an agent:

```/execute @initiator ~ ~ ~ agent create```

should be changed to:

```/execute as @initiator run agent create```

Do this for all commands and it should be compatible with version greater than 1.19.10

__Featured In:__

[How To Spawn and Use The Agent in Minecraft Bedrock Edition](https://youtu.be/-eS3WZufCRc)
