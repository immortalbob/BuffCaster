Chat Commands:

Buff Commands: war, void, missile, heavy, light, finesse, two, trade, tink, xp, buffs, strength, lore, prots, baneshield, brill, weapon, wand.
Bot Commands: primary, secondary, mm, tn, stats, whereto, loc, cancel, reset, heal, stam, mana
--reset command is disabled by default in the *** Edit Here *** state.

Options:
Listed from top to bottom of *** Edit Here *** state:
1. Version
2. General Settings
3. Seconds Till Next Buff. The amount of seconds until the bot wants to buff itself. 3300 is 55 minutes. 300 per 5 minutes.
4. Face Heading. Set to the heading you wish your bot to face normally. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
5. Idle Peace Mode always/never
6. Max Distance. the maximum distance a player can be from you and still receive buffs. (in meters)
7. Min Health The minimum of each vital before the bot attempts to regain said vital.
8. Min Stamina The minimum of each vital before the bot attempts to regain said vital.
9. Min Mana. The minimum of each vital before the bot attempts to regain said vital.
10. Create View - This creates the small 2 button interface for pause/resume and reset.
11. Allow Reset. Allows the use of the reset password. (Must set reset password in the line below.)
12. Reset Password. Set your password to enact the reset state. (Only works if the line above is set to always.)

13. Portal Bot Settings
14. PortalBot, Set to always to enable the portal bot, never to disable it.
15. Summon Spell Level, set to 1, 2, or 3 to choose which level of summon spell you use.
16. Primary tie name
17. Secondary tie name
18. Primary heading for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
19. Secondary heading for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between

20. CHAT SETTINGS
21. Silent Mode. Set to never or always to toggle silent mode (no spam)
22. Seconds Till Next Spam. The amount of seconds between spamming local chat. 1800 is 30 minutes, 300 per 5 minutes.
23. No Begging, set to always to disable begging when components are low.
24. Seconds Till Next Beg. The amount of seconds until it begs for comps in local chat when below spell component thresholds (<250 tapers, <5 platinum scarabs, or <5 mana scarabs.)
25. Location name.
26. Spam One, you must escape special characters and digits with a \, but never the brackets ([])
27. Spam Two, you must escape special characters and digits with a \, but never the brackets ([])
28. Spam Three, you must escape special characters and digits with a \, but never the brackets ([])
29. Spam Four, you must escape special characters and digits with a \, but never the brackets ([])
30. Spam Five, you must escape special characters and digits with a \, but never the brackets ([])
31. Goodbye message, you must escape special characters and digits with a \, but never the brackets ([])

32. CONSUMABLE SETTINGS
33. Brilliance Bot. Set to never on the left side to disable casting brilliance.
34. Refill Focusing Stone. Set to never if you don't wish to refill the focusing stone upon each brill.
35. Refill Charge. Name of the Mana Charge you wish to use to refill the Focusing Stone.
36. Master Mage Gem usage. Set to always or never to enable/disable.
37. Master Mage Gem Name. Set to the name of the gem you wish to open. (Stock setting is Celdiseth's Portal Gem)
38. Town Network gem usage, set to never or always to enable/disable it.
39. Use Healing Kits to regain health, always/never

40. SPELL SETTINGS
41. PreBuff, set to always to enable prebuffing (foc/self/creature of 1 lesser level before main self buff routine)
42. Recharge Vitals Other, set to always to allow the heal, stam, or mana commands
43. Secondary Combat Skills. Set to always to cast Dirty, Reck, Sneak, and Dual in main buff loop.
44. Assessment Skills. Set to always to cast Assess Person, Assess Creature, and Deception in the main buff loop.
45. Buff Self Spell Level, set to 6, 7, or 8
46. Buff Other Spell Level, set to 6, 7, or 8
47. Bane Spell Level, set to 6, 7, or 8
48. Item Spell Level, set to 6, 7, or 8
49. Regain Vitals Self Spell Level, set to 6, 7, or 8
50. Recharge Vitals Other Spell Level, set to 6, 7, or 8

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