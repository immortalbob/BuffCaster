1.6.0
-Added in secondary combat skills (reck, sneak, dual, and dirty) to the main buff loop, must be enabled in edit here state.
-Added in assessment skills (assess person, assess creature, and deception) to the main buff loop, must be enabled in edit here state.

1.5.0
-Bugfix: Responds to the correct person now while summoning portals and @tells are received.
unknown spell checking
-Bugfix: No longer double casts fletching in the "trade" cycle.
-Feature: Checks if spell is learned before casting, should skip unknown spells and move on.

Version 1.4.0
-Added most alternate commands that match up with Castaway
-Can now queue up to 9, with 1 buffing!
-added a check in case recharging vitals fails to return on its own

Version 1.3.2
-Now supports ALL versions of Light Weapons Mastery Other VI/VII and Missile Weapons Mastery Other VI/VII (16)
-If brilliance is NOT cast within 5 seconds, bot will ask for the Refill Charge necessary to refill the mana stone, and return to what it was doing prior.
-There is now configurable goodbye messages found at the bottom of the *** Edit Here *** state

Version 1.3.1
-delays fixed for summoning portals, it should switch headings again before summoning.
-added ability to set your summon spell level to 1, 2, or 3 (default 1)

Version 1.3
-Buffing system overhaul part 1, "variable-ized" the buff ID's to allow for expanding to lesser level buff sets.
-Can now cast 6's, 7's, and 8's.
-Regaining vitals can now be set to 6's 7's or 8's (there is no stamina to mana 8)
-The Buff-Self state has been cleaned up substantially, and has been made more efficient.
-Now will attempt to regain stamina/mana when necessary while self buffing.
-New PreBuff option added, it will cast the next level lower foc/self/creature spells before doing its main buff routine.
-Will now check for Pyreal Scarabs for level 6 self buffs, as well as Gold Scarabs if PreBuff is enabled.
-No Begging mode added, when turned on, it will not beg for comps when low.
-When begging for comps, it now begs for the specific component it is running low on.
-Will only beg for components it is set to use, for instance if you are using sixes to buff, it wont beg for plats.
-Now supports both possible Missile Weapon Mastery Other VII spells. (old arwic professors vs new)

Version 1.2.1
-fixed bug that caused the macro to lock up when receiving a command while summoning a portal. This functionality was removed, and replaced with a chat response.

Version 1.2:
-will now choose either Nuhmudira's Enlightenment, or Arcanum Enlightenment VII depending on which you have in your spell book
-you can now enable/disable the portal bot by setting the appropriate variable to always/never in the *** Edit Here *** state
-silent mode (no spam) can now be enabled/disabled in the *** Edit Here *** state
-can now make use of Town Network Portal Gems, enable/disable in the *** Edit Here *** state
-speaks in open chat when summoning a portal now

Version 1.1:
-now @tells portal requester the name of the location requested (Egg Orchard, Town Network, etc) along with the trigger word (primary/secondary).
-now disables the brilliance bot if there is no focusing stone in your inventory, regardless of brillbot setting.
-now casts loyalty and leadership self buffs
-master mage gem usage, will open a portal to the master mage (gem selected by bot owner in the edit here state)
-60 second timer between mm gem uses to prevent trolls from burning your gems too fast...but they still can...slowly
-disables master mage gem usage if no gems in inventory

Version 1.0:
-Initial Release
-Responds to various buff related commands (listed in post above)
-Buffs self, and manages it's own vitals
-Queue's up to 5 players
-Casts brilliance
-Summons portals
-Randomized local chat spam
-more