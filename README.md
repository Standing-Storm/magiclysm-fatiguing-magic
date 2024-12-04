# Magiclysm: Fatiguing Magic

This mod is mostly a proof of concept. It changes Magiclyms's magic to use weariness (and over time, sleepiness) instead of mana.  You'll thus never run out of mana, but using magic will gradually make you more and more exhausted until you sleep it off.

It implements the following changes:

1) All spells' cost is reduced to 0 mana.
2) Instead, spells cost weariness equal to the equivalent of 60 calories burned per point of Difficulty. No actual calories are burned.
3) The various mana mutations (Mana Efficiency etc) instead lower the effective calorie cost.
4) Higher spell levels also reduce the effective calorie cost, to a max of halving it at level 15.
5) There is a small chance that spells also add sleepiness when used.

This has some limitations. Among them is that there is no way to restore weariness, so the mana regeneration mutations (and mana potions etc) now do nothing. Also, the methods used to reduce the cost of spells also reduces spells that don't use mana to zero. Still, it mostly works. 
