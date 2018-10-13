I dunno, it's pretty good. Not a direct replacement for Castaway, but it does most things.

Chat Commands:

Code: Select all
Buff Commands: war, void, missile, heavy, light, finesse, two, trade, tink, xp, buffs, strength, lore, prots, baneshield, brill, weapon, wand.
Bot Commands: primary, secondary, stats, whereto, loc, cancel, reset
--reset command is disabled by default in the *** Edit Here *** state.


Options:
Listed from top to bottom of *** Edit Here *** state:
1. Primary and secondary headings for summoning portals. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
2. Seconds Till Next Spam. The amount of seconds between spamming local chat. 1800 is 30 minutes, 300 per 5 minutes.
3. Seconds Till Next Buff. The amount of seconds until the bot wants to buff itself. 3300 is 55 minutes. 300 per 5 minutes.
4. Seconds Till Next Beg. The amount of seconds until it begs for comps in local chat when below spell component thresholds (<250 tapers, <5 platinum scarabs, or <5 mana scarabs.)
5. Face Heading. Set to the heading you wish your bot to face normally. 0 = North, 90 = East, 180 = South, 270 = West and everything in between
6. Max Distance. the maximum distance a player can be from you and still receive buffs. (in meters)
7. Min Stamina, and Min Mana. The minimum of each vital before the bot attempts to regain said vital.
8. Primary/Secondary tie names.
9. Location name.
10. Brilliance Bot. Set to never on the left side to disable casting brilliance.
11. Refill Focusing Stone. Set to never if you don't wish to refill the focusing stone upon each brill.
12. Refill Charge. Name of the Mana Charge you wish to use to refill the Focusing Stone.
13. Self Eights. Buffs self with 8's if set to always.
14. Bane Eights. Casts level 8 banes on shields if set to always.
15. Item Eights. Use level 8 item spells to buff players if set to always. (Not currently functional on Reefcull)
16. Allow Reset. Allows the use of the reset command. This is disabled by default because it is abusable.
17. Set State Main Loop, don't touch this line.

Notes:
1. does not respond to @tells while it is already in the chat handler, cycling the queue, or clearing variables after a completed buff cycle. All of these go by very fast, inevitably some @tells will be lost to them.
2. does not respond to @tells while casting brilliance, regaining vitals, or checking target distance, or spell components availability. Most of these go by very fast, inevitably some @tells will be lost to them.
3. double casts a buff when receiving @tells with a string length of less than 11 characters, or regaining vitals.
4. only gives thanks for gifts from the main loop. (while awaiting a command)
5. will cast brill, and/or summon portals in the middle of buffing someone else and then return to buffing to save time.
6. queue's up to 1 player being buffed, and 5 in line.