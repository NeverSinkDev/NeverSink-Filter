[comment]: <> ( https://github.com/NeverSinkDev/NeverSink-Filter )
----------------------------------
## **CHANGELOG - NeverSink's Filter**
----------------------------------

Every 4 hours we generate a "economy-updated" version of the filter based on the current meta and league economy. These filters are based on the latest version of the filter, but their "tiering" of currencies, uniques, cards (and ~25 other sections) are much more precise.

The "economy-based" versions are available through [FilterBlade](www.filterblade.xyz) and on the [PoE filter ladder](https://www.pathofexile.com/item-filter/ladder/follower). Major thanks to all patreon supports to help us fund the continious development. [Patreon](https://www.patreon.com/Neversink) supporters also receive a Patreon-exclusive [Filter-Auto-Updater](https://youtu.be/i8RJx0s0zsA).

----------------------------------
## **UPDATE INSTRUCTIONS**
----------------------------------

Update instructions

[comment]: <> ( LATEST VERSION START )
----------------------------------
## **VERSION 8.6.0** - Sentinel League
----------------------------------

## SHORT OVERVIEW

Say hi to your Sentinel! The filter incorporates all of the new league features and a bunch of precedural upgrades!

## NEW FEATURES
- EXPEDITION reroll currencies are now economy-tiered
    - Their display depends on the current market price and on the dropped stack. The algoritms currently has special safeguards in place to prevent them from ever dropping below alchemy tier.

## CRAFTING
- Adjusted the highlight level and selection of synthesised and factured items
    - With the introduction of eldritch influences certain fractured and synthesised items have gained or lost in price and popularity. Generally speaking fractured boots/gloves/shields/helmets have become beter, while their synthesised counterparts lost in power
- Any identified uncorrupted amulet with the +1 to all skills mod is now highlighted

## TIERING
- All tierlists have been adjusted to better reflect the ingame economy using poe.ninja
- UNIQUE 5 links highlight nerfed. They no longer produce a T2 sound.
    - This has more often than not resulted in in disapointment.
- INFLUENCED tiering has been made much more precise 
    - When tiering itemlevel 80-84 influenced items, the algorithm checks if the economy data for the same base/influence at ilvl 85/86 is at least as high and also matches the threshhold. This prevents random misspriced items and crafted items to be overtiered and highlighted as expensive for no reason. I've been observing this adjustment over the past month and it seems to cause overwhelmingly positive effects by reducing the chances of accidental bamboozels.
- DIVINATION CARD tiering for later league stages has been improved. 
    - Many low value/popularity cards will now drop into lower tiers in later phases of the league (based on price). This only affects low value cards that mostly grant single uniques. Cards with random outcomes are mostly unaffected.
- CLUSTER JEWEL tiering during the first 3-4 days of new leagues will be using the same tiering as at the end of the last league. 
    - This is not perfect, but likely better than not doing anything or accepting highly noisy early league data. I have a better algorithm in mind, but that one will take more time to develop
- FRAGMENT-lures are now economy-tiered, but are disallowed from being hidden as a safeguard
- Did a lot of general clean up to the source code of the tiering algorithm. Improved a few niches and calculations

----------------------------------
## NeverSink's itemfilter - version 8.5.3 - Archnemesis Finetuning and Eco-Update
----------------------------------

## SHORT OVERVIEW

- Fine-tuned endgame flask highlight and strictness a little bit. It's a bit tricky to end up with a distribution that works well for most strictnesses and use cases here, but I think we're getting there. Added back quality requirements for high level life/mana flask to prevent them spamming lower strictnesses.
- Fragment splinter tiering has been entirely reworked. It now only has 2 tiers instead of 3 and these are economy tiered.
- Improved the eco-tiering of stacked currency shards by making it more precise. Previously, the algorithm was using the base price of the orb, divided by 20 to get the shard price and added a very minor value ('click value' for saving time by clicking a stack instead of a single item) per stack size to calculate the stacked currency price. This algorithm was working great for normal orbs, but for shards some orbs have dropped so much in price, that the "time saving click value bonus" was exceeding the full orb price (looking at you orb of binding). This could cause 6 binding shards to be valued higher than a single orb of binding. This is now corrected.
- Adjusted the tiering algorithm for divination cards a bit.
- Reduced highlight for T5 currency divination cards on strict.
- Moved amethyst ring base from T2 rare to T1 rare.
- ID Mod Section: Improved identified mod filtering sections for ES helmets and caster weapons.
- ID Mod Section: Spellslinger Wands - increased tier requirements.
- ID Mod Section: BodyArmour 2x Defense + 4x Aux - enforced "corrupted false" status.
- ID Mod Section: Added new Body Armour Recipe: 2x Defense + 1x Life + 4x Aux (any corrupted state).
- Unique timeless and large cluster jewels (voices) have been moved from T1 to T2. They are still brightly notified on all strictnesses, but most of them don't warrant the T1 notification anymore due to their plummeting price.
- Adjusted some edge cases where the unique tiering has been placing items into the "T3" tier, instead of the "T4" tier (such as Bramblejack).
- Alchemy tier currencies lose their highlight (sound, icon, beam) on uber-strict, but are still visible. They're hidden on uber-plus strict, same as before.
- Hollowpoint Arrowhead is now correctly classified as the T2 heist tool, instead of Fragmenting Arrowhead.
- Loreweave recipe now overrides T3 rings highlight.
- The internal structure of the filter is now correctly enumerated. Thanks to LordBlick for notifying us of that. This has no gameplay impact, but improves code readability and fixes bug in filterblade's advanced screen.


----------------------------------
## **OLDER CHANGELOGS:**
----------------------------------

The old non-markdown formatted 2000+ lines of changelogs can be found in the ["ADDITIONAL-FILES"](https://github.com/NeverSinkDev/NeverSink-Filter/blob/master/ADDITIONAL-FILES/changelog.json) folder.

These changelogs include changes from version 3.X.X to 8.5.3

----------------------------------
## **SPECIAL THANKS:**
----------------------------------

- GGG for the awesome game
- Bex for the assistance and the patch notes
- Chris for being awesome and answering questions about the item font corruption problem (note: it's not fixed)
- Tobnac/Haggis for the constant help and support + support on the FilterBlade project (will be released during the next monthes)
- My awesome stream viewers, who helped while I was updating the filter. A special thanks to the supporters.
- C4pture for being C4pture
- You