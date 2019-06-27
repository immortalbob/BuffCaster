Chat Commands:

Code: Select all
Buff Commands: war, void, missile, heavy, light, finesse, two, trade, tink, xp, buffs, strength, lore, prots, baneshield, brill, weapon, wand.
Bot Commands: primary, secondary, mm, tn, stats, whereto, loc, cancel, reset
--reset command is disabled by default in the *** Edit Here *** state.

Options:
Listed from top to bottom of *** Edit Here *** state:
1. Version
2. General Settings
3. Seconds Till Next Buff. The amount of seconds until the bot wants to buff itself. 3300 is 55 minutes. 300 per 5 minutes.
6. Face Heading. Set to the heading you wish your bot to face normally. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
7. Idle Peace Mode always/never
8. Max Distance. the maximum distance a player can be from you and still receive buffs. (in meters)
9. Min Health The minimum of each vital before the bot attempts to regain said vital.
10. Min Stamina The minimum of each vital before the bot attempts to regain said vital.
11. Min Mana. The minimum of each vital before the bot attempts to regain said vital.
12. Create View - This creates the small 2 button interface for pause/resume and reset.
13. Allow Reset. Allows the use of the reset password. (Must set reset password in the line below.)
14. Reset Password. Set your password to enact the reset state. (Only works if the line above is set to always.)

15. Portal Bot Settings
16. PortalBot, Set to always to enable the portal bot, never to disable it.
17. Summon Spell Level, set to 1, 2, or 3 to choose which level of summon spell you use.
18. Primary tie name
19. Secondary tie name
20. Primary heading for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
21. Secondary heading for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between

22. CHAT SETTINGS
23. Silent Mode. Set to never or always to toggle silent mode (no spam)
24. Seconds Till Next Spam. The amount of seconds between spamming local chat. 1800 is 30 minutes, 300 per 5 minutes.
25. No Begging, set to always to disable begging when components are low.
26. Seconds Till Next Beg. The amount of seconds until it begs for comps in local chat when below spell component thresholds (<250 tapers, <5 platinum scarabs, or <5 mana scarabs.)
27. Location name.
28. Spam One, you must escape special characters and digits with a \, but never the brackets ([])
29. Spam Two, you must escape special characters and digits with a \, but never the brackets ([])
30. Spam Three, you must escape special characters and digits with a \, but never the brackets ([])
31. Spam Four, you must escape special characters and digits with a \, but never the brackets ([])
32. Spam Five, you must escape special characters and digits with a \, but never the brackets ([])
33. Goodbye message, you must escape special characters and digits with a \, but never the brackets ([])

25. CONSUMABLE SETTINGS
34. Brilliance Bot. Set to never on the left side to disable casting brilliance.
35. Refill Focusing Stone. Set to never if you don't wish to refill the focusing stone upon each brill.
36. Refill Charge. Name of the Mana Charge you wish to use to refill the Focusing Stone.
37. Master Mage Gem usage. Set to always or never to enable/disable.
38. Master Mage Gem Name. Set to the name of the gem you wish to open. (Stock setting is Celdiseth's Portal Gem)
39. Town Network gem usage, set to never or always to enable/disable it.
40. Use Healing Kits to regain health, always/never

41. SPELL SETTINGS
42. PreBuff, set to always to enable prebuffing (foc/self/creature of 1 lesser level before main self buff routine)
43. Recharge Vitals Other, set to always to allow the heal, stam, or mana commands
44. Secondary Combat Skills. Set to always to cast Dirty, Reck, Sneak, and Dual in main buff loop.
45. Assessment Skills. Set to always to cast Assess Person, Assess Creature, and Deception in the main buff loop.
46. Buff Self Spell Level, set to 6, 7, or 8
47. Buff Other Spell Level, set to 6, 7, or 8
48. Bane Spell Level, set to 6, 7, or 8
49. Item Spell Level, set to 6, 7, or 8
50. Regain Vitals Self Spell Level, set to 6, 7, or 8
51. Recharge Vitals Other Spell Level, set to 6, 7, or 8

Notes:
1. does not respond to @tells while it is already in the chat handler, cycling the queue, or clearing variables after a completed buff cycle. All of these go by very fast, inevitably some @tells will be lost to them.
2. does not respond to @tells while checking target distance, or spell components availability. These go by very fast, inevitably some @tells will be lost to them.
3. double casts a buff when lag strikes.
4. only gives thanks for gifts from the main loop. (while awaiting a command)
5. will cast brill, open master mage gems, and/or summon portals in the middle of buffing someone else and then return to buffing to save time.
6. queue's up to 1 player being buffed, and 9 in line.
7. only supports buffing with level 6, 7, and 8 spells.

Requirements:
1. Vtank
2. Magtools https://github.com/Mag-nus/Mag-Plugins/releases