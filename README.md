execute if entity @s[y_rotation=45..135] run tp @s ~ ~ ~ 90 0

kill @e[type=minecraft:small_fireball]

kill @e[type=minecraft:fireball]

kill @e[type=minecraft:firework_rocket]

rotten_flesh

cooked_porkchop

cooked_beef

scoreboard objectives add saraka_c trigger

scoreboard objectives setdisplay sidebar saraka_c

scoreboard players set SarakaMaikura saraka_c 0

give SarakaMaikura minecraft:chest{BlockEntityTag: {Items: [{Slot: 0b, id: "minecraft:command_block", Count: 64b, tag: {BlockEntityTag: {conditionMet: 1b, auto: 1b, CustomName: '{"text":"@"}', powered: 0b, Command: "fill ~ ~-1 ~ ~ ~ ~ air destroy", id: "minecraft:command_block", SuccessCount: 0, TrackOutput: 1b, UpdateLastExecution: 1b}, display: {Name: '{"text":"Destroy"}'}}}]}}

/fill ~-2 ~-2 ~-2 ~2 ~2 ~2 minecraft:diamond_block{} replace minecraft:dispenser{CustomName:'{"text":"Diamond"}'}
