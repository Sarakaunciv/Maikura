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
