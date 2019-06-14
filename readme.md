I dunno, it's pretty good. Not a direct replacement for Castaway, but it does most things.

Chat Commands:

Code: Select all
Buff Commands: war, void, missile, heavy, light, finesse, two, trade, tink, xp, buffs, strength, lore, prots, baneshield, brill, weapon, wand.
Bot Commands: primary, secondary, mm, tn, stats, whereto, loc, cancel, reset
--reset command is disabled by default in the *** Edit Here *** state.

Options:
Listed from top to bottom of *** Edit Here *** state:
0. Version 1.8.1
0. SETTINGS
1. Silent Mode. Set to never or always to toggle silent mode (no spam)
2. Seconds Till Next Spam. The amount of seconds between spamming local chat. 1800 is 30 minutes, 300 per 5 minutes.
3. Seconds Till Next Buff. The amount of seconds until the bot wants to buff itself. 3300 is 55 minutes. 300 per 5 minutes.
4. No Begging, set to always to disable begging when components are low.
5. Seconds Till Next Beg. The amount of seconds until it begs for comps in local chat when below spell component thresholds (<250 tapers, <5 platinum scarabs, or <5 mana scarabs.)
6. Face Heading. Set to the heading you wish your bot to face normally. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
7. Idle Peace Mode always/never
8. Max Distance. the maximum distance a player can be from you and still receive buffs. (in meters)
9. Min Stamina, and Min Mana. The minimum of each vital before the bot attempts to regain said vital.
10. PortalBot, Set to always to enable the portal bot, never to disable it.
11. Summon Spell Level, set to 1, 2, or 3 to choose which level of summon spell you use.
12. Primary/Secondary tie names.
13. Primary and secondary headings for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
14. Create View - This creates the small 2 button interface for pause/resume and reset.
15. Allow Reset. Allows the use of the reset password. (Must set reset password in the line below.) 
16. Reset Password. Set your password to enact the reset state. (Only works if the line above is set to always.)

17. CHAT SETTINGS
18. Location name.
19. Spam One, you must escape special characters and digits with a \, but never the brackets ([])
20. Spam Two, you must escape special characters and digits with a \, but never the brackets ([])
21. Spam Three, you must escape special characters and digits with a \, but never the brackets ([])
22. Spam Four, you must escape special characters and digits with a \, but never the brackets ([])
23. Spam Five, you must escape special characters and digits with a \, but never the brackets ([])
24. Goodbye message, you must escape special characters and digits with a \, but never the brackets ([])

25. CONSUMABLE SETTINGS
26. Brilliance Bot. Set to never on the left side to disable casting brilliance.
27. Refill Focusing Stone. Set to never if you don't wish to refill the focusing stone upon each brill.
28. Refill Charge. Name of the Mana Charge you wish to use to refill the Focusing Stone.
29. Master Mage Gem usage. Set to always or never to enable/disable.
30. Master Mage Gem Name. Set to the name of the gem you wish to open. (Stock setting is Celdiseth's Portal Gem)
31. Town Network gem usage, set to never or always to enable/disable it.

32. SPELL SETTINGS
33. PreBuff, set to always to enable prebuffing (foc/self/creature of 1 lesser level before main self buff routine)
34. Recharge Vitals Other, set to always to allow the heal, stam, or mana commands
35. Secondary Combat Skills. Set to always to cast Dirty, Reck, Sneak, and Dual in main buff loop.
36. Assessment Skills. Set to always to cast Assess Person, Assess Creature, and Deception in the main buff loop.
37. BuffSelfSpellLevel, set to 6 7 or 8
38. BuffOtherSpellLevel, set to 6 or 7
39. BaneSpellLevel, set to 6 7 or 8
40. ItemSpellLevel, set to 6 7 or 8
41. RegainVitalsSelfSpellLevel, set to 6 7 or 8
42. RechargeVitalsOtherSpellLevel, set to 6 or 7

Requirements:
Vtank
Magtools

Notes:
1. does not respond to @tells while it is already in the chat handler, cycling the queue, or clearing variables after a completed buff cycle. All of these go by very fast, inevitably some @tells will be lost to them.
2. does not respond to @tells while casting brilliance, regaining vitals, or checking target distance, or spell components availability. Most of these go by very fast, inevitably some @tells will be lost to them.
3. double casts a buff when receiving @tells with a string length of less than 11 characters, or regaining vitals.
4. only gives thanks for gifts from the main loop. (while awaiting a command)
5. will cast brill, and/or summon portals in the middle of buffing someone else and then return to buffing to save time.
6. queue's up to 1 player being buffed, and 9 in line.
7. only supports buffing with level 6, 7, and 8 spells.