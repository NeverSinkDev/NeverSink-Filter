# **CHANGELOG - NeverSink's Filter**
----------------------------------

Every 4 hours we generate a "economy-updated" version of the filter based on the current meta and league economy. These filters are based on the latest version of the filter, but their "tiering" of currencies, uniques, cards (and ~25 other sections) are much more precise.

The "economy-based" versions are available through [FilterBlade](www.filterblade.xyz) and on the [PoE filter ladder](https://www.pathofexile.com/item-filter/ladder/follower). Major thanks to all patreon supports to help us fund the continious development. [Patreon](https://www.patreon.com/Neversink) supporters also receive a Patreon-exclusive [Filter-Auto-Updater](https://youtu.be/i8RJx0s0zsA).

----------------------------------
# **VERSION 8.6.3a** - PREVIEW - Lake of Kalandra League - NOT YET LIVE
----------------------------------

## SHORT OVERVIEW

FilterBlade received a bunch of small and large upgrades. Most notably a much faster workflow: We made a 4 min video about it - https://www.youtube.com/watch?v=RA27aUdWQb8 . Highly recommended to watch.

## MAJOR FEATURES / SUMMARY
- Introduced all the new items added from the Mirror of Kalandra league ***
- Reworked the filter generation in regards to how Divine/Exalted orbs are treated. At the start both orbs will be in T1. My filters used a fraction of the ex-orb price to scale the tier thresholds in all tierlists. Instead my filter will now be calculating that fraction based on the higher of the two prices (exalted or divine orb). 
- Most exotic high orbs are also no longer tied to their tiers. That means Exalted Orbs, Divine Orbs, Conqueror Orbs and Domination orbs etc. could now also theoratically drop into T2, if their price drops low enough. None of the aformentioned orbs is allowed to drop beyond T2 to prevent scenarios where automation potentially fails. This does not include Mirrors and Mirror Shards
- The filter generation algorithm now attempts to 'resolve' divination card prices. It looks at the current price of the card, stacksize, rewardcount and compares it to the price of the actual reward. If there's a significant difference, it will prefere the reward price, as divination card seem to contain a lot of faulty economy and there's way more price fixing going on as well.
- Massive changes and improvements to the FilterBlade workflow (details below)
- Reworked gem tiering. Details below.
- Reworked flask highlight. Details below.

## ECONOMY BASED GEM TIERING REWORK
- Redefined the gem threshholds. The gem T2 threshhold is higher that that of most sections, since gem economy is more fluctuating. Valid prices are confirmed at 2-3 listings, depending on the section:
    - T1-price is around 32c + 10% of EXprice
    - T2-price is around 12c + 04% of EXprice
- The rework focuses on the following gem level/quality combinations: 20/20, 21/20, 20/23, X/23 and X/20/Vaal. Alt-quality/awakened/exceptional gems are not affected by htis.
- These gems have become a much more accessable over the course of the past leagues. Their highlight has been reduced to compensate for that, but they're tested against economy-based lists to find expensive drops.
- Gems that pass the T2-price test get higlight with the "red gem pattern".
- Additionally there's a rule that tests if a 20%Q vaal gem of any level is expensive (0.75 * T1price) at level 20 to warrant leveling it to sell it.
- The goal is to alert the user that they found a valuable ~15c+ gem.
- Gems that don't pass the test receive the the blue gem highlight pattern - the same appearance as 20% qual gems receive.

## NEW FILTERBLADE WORKFLOW
- The general filterblade workflow has been completely redesigned. The new workflow is much more straight forward and faster. 
- FilterBlade now merges the concepts of 'saves' and 'filters'. Whenever you sync/download a filter it also updates your save. This means you don't have to save manually anymore, you won't accidently override the wrong save etc. It's also just much more intuitive.
- The save/load tab has been renamed to 'my filters'. It's also opened by default if you have any saves already.
- Saves now remember your 'sync target'. This makes saving by syncing a much faster and straightforward process
- All features still exist and work. We did remove the 'save' button though, as it's not really needed anymore and we don't want users to think that they should.

## OTHER NEW FILTERBLADE FEATURES:
- FilterBlade presets are now compatible with 'locks'. This allows advanced users to save their tiering in a preset and publish and/or reuse it in multiple filters.
- FilterBlade basetype matrixes can now be 'locked' similary to tierlists. All locked (and moved) items will stay in their tier. Meaning your changes have priority over the the filter updates.
- FilterBlade basetype matrixes now have 'sets' of items, such as 'Atlas' items and 'Minion' items. These items come with tiny icons to signalize them and you can also show all items in a set.
- Introducing the "ItemBuilder". You can find it at the bottom of the simulate screen and it allows you to build any item ingame to test how your filter responds to it.
- Vastly improved the item tests on the download screen. The filter will be tested for more items, the tests are split into 'notice', 'warning' and 'error'. Errors stop the filter from working, warnings hide expensive items, notices inform you that potentially expensive items are hidden often due to high strictness
- A glowing chaos orb icon is shown next to sections that are economy-tiered. Hovering over it provides more insights.
- Improved/fixed some tierlist behaviors and tiers/hide tiers generation.
- Improved displayed message, when a loaded save receives an update.

## FLASK SECTION CHANGES:
- The endgame flask rules have been restructured. This might cause a few invalidations in your saves, but overall the goal is to keep strictness transparent and simple
- The rules that highlight utility flasks now include *all* utility flasks. This (also somewhat sadly) means gold and corrundum flasks, but it seems all flasks find their niches in the endgame (even if some are somewhat tiny) and at least most flasks are somewhat useful. These are very easily editable on FilterBlade
- ILVL 85 util flask highlight: disabled on uber-plus-strict (technically only enables highest movementspeed tier)
- ILVL 84 util flask highlight: disabled on uber-plus-strict
- ILVL 82 util flask highlight: disabled on uber-strict
- Any utility flask in endgame areas between 68-75: disabled on uber-strict (designed as a entry-tier rule)
- Any other utility flask in the endgame: disabled on very strict
- Removed several extra rules to highlight specific utility flasks by quality in the endgame to reduce complexity. The availability of glassblowers in the endgame is high enough to ignore that. The deciding factor is the flask and the itemlevel.


## STRICTNESS
- Reduces the strictness on T3 fragments (uber plus strict reduces their highlight now, instead of hiding)
- The high level agnerod staff rule is now disabled by default as vinktar square is no longer interesting for the atlas.

## MISC
- Added a new section that highlights stacks of divination cards. It overrides the tiers T5/T4/T4currency and requires a stacksize of 3+ to be highlighted.
- Merged the Labyrinth offering items with the generic fragment tierlist. These items are now economy tiered. Removed the old secetions.
- Move the anchored divination cards "Chaotic Disposition" "The Void" from T2 to T3.
- Improved replica jewel highlighting
- Removed Poacher's Mark from the +1 fire gems recipe list... I'm not sure how it got there.
- Set the +1 recipe list to be an exact list
- Cleaned up the github repository, deleted a lot of old and outdated files, improved descriptions and readme files
- Added a misc rule to highlight heist quest contracts
- The filter now uses the enum-rarity format instead of the operator rarity format. This simplifies filterblade handling and is more precise.

----------------------------------
# **VERSION 8.6.3** - Identified sentinels, Tiering
----------------------------------

## SHORT OVERVIEW

Insted of boring you with changelogs: here are some pictures of what the update does: https://imgur.com/a/T19KhOs

Text version: This update expands on the existing sentinel filtering and identified mod filtering. It adds filtering for items with multiple select T1 mods, detect worthwhile stalker and pandemonium sentinel, adds optional rules for oil-extractor targets and improves the general tiering! This is likely the last stable update for this league. The economy based filters will continue receiving updates every 4 hours.

## NEW LEAGUE FEATURES
- Added a new section for "identified sentinels"
    - The T1 rule highlights Stalker and Pandemonium sentinels that grant scarab, expedition, fossil or sentinel rewards
    - The T2 rule highlights Stalker and Pandemonium sentinels that grant any tier of currency, metamorph, heist or divination card rewards. It also highlights T1 rules for increased reward chances and quantity.
    - Note that it's impossible for the filter to distinguish between different tiers of individual specific rewards, such as t1-currency and t2-currency.

## IDENTIFIED MOD FILTERING
- Added and modified a few additional rules for detecting valuable items for recombination
    - Arrow quiver rule (any rarity, non-corrupted)
    - Double T1 elemental damage weapon rule (any rarity claws, bows, wands)
    - Added 4 rules to search for caster weapons with T2 exceptional elemental mods (any rarity)
        - All 4 rules search for +1 to all gems, T1 spell damage, T1 hybrid spell damage
        - The fire rule also searches for T1 fire% damage, T1 fire dot, T1 dot and +1 fire
        - The cold rule also searches for T1 cold% damage, T1 cold dot, T1 dot and +1 cold
        - The lightning rule also searches for T1 lightning% damage and +1 lightning
        - The phys rule also searches for +1 phys, T1 phys dot and T1 dot
    - Double T1 rolls for boots, gloves, helmets, rings - include T1 stat rolls, T1 life, T1 chaos res.
        - Boots additionlly search for 35% MS
        - Gloves additionally search for T1 attack speed
        - Rings additionally search for T1 WED
- The T1 phys damage rule now also searches for hybrid T1 phys damage

## TIERING
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.
- Added an exception rule to detect double influenced impresence amulets dropped by the ooba-ooba-elder fights
- Cleaned up the code on the backend side and improved some niche tiering scenarios.

## STRICTNESS
- Enchanted helmets are now hidden on uber-plus strict
- Identified mod filtered body armors are hidden on uber-plus strict

## FILTERBLADE
- Added an optional rule (disabled by default) to show enchanted rings (from blight) that yield a gold or silver oil upon using the oil extractor. Thank you to /u/developershins for compiling these.
- Added UIs for all new features
- Readded arealevel sliders for map hiding (CHECK!)

----------------------------------
# **VERSION 8.6.2** - Recombinator Mod Filtering, Sentinel Strictness Adjustments, Tiering Finetuning
----------------------------------

## SHORT OVERVIEW

This update focuses on 2 topics: sentinel strictness and recombinator gear.

**SENTINELS:** I've made the magic sentinel filtering way less strict. There seems to be two different view-points on this problem, with half of the community finding magic sentinel identification not worthwhile, due to rares being more than easily sustainable and the second half capitalizing on chances of rolling high value magic rolls for recombination (particullary the Grimro gang is in a bit of a 'goldrush'). Personally I find the first approach more efficient, due to the somewhat expensive rolls having an average total chance of ~1.5% to appear and the common ones in this group are worth around-ish 10c, an effort I don't find worthwhile on higher strictnesses. The higher tiers of rolls appear once every few hundred IDs.

That being said, I see value in recombinding other magics and it's certainly fun, since it adds a bit more dynamic to the league gameplay and power cores are very abundant anyway. In order to support both strategies I've revamped the strictness progression on sentinels once again. You can find the full new progression in the changelog. I've also hidden normal sentinels in the endgame. I'll reevaluate this in the future (if sentinels stay in that form, which is unlikely), but this will likely be the strategy for the remainder of the league.

**RECOMBINATION**: Recombinators likely changed the crafting meta more than than the last year combined and have an impact similar to harvest. On top of that they are fun. To support the usage of recombinators, I've added a new special section that looks for rare items with high tier mods. Most rules require the item to be uncorrupted (with the exception of ultra-rare mods, such as +1 to all spell gems or +2 arrows, that also accept corrupted items). These rules will occasionally trigger with strongboxes, certain heist mods, ritual rewards and many cases.

The full list of mods can be found in the changelogs. If you can think of other mods I should filter for, please let me know, ideally on the discord.

## NEW LEAGUE FEATURES
- Reviewed strictness setup
    - T1 - highlights RARE obsidian and special basetypes. Has a special textcolor. Shown on all strictnesses
    - T2 - highlights RARE emberstone basetypes.
    - T3 - highlights all (other) rare basetypes. Disabled on uber-plus-strict.
    - T4 - highlights all (other) magic basetypes. Disabled on uber-plus-strict.
    - Normal rarity sentinels are hidden in the endgame
    - leveling - all sentinels are shown until level 68. Disabled on uber-strict.

## IDENTIFIED MOD FILTERING
- Added a large new identified mod filtering section for recombinator bases. It looks for really rare single mods on ided bases on both magic and rare items. Most rules only look for non-corrupted items, while some very rare/mods include corrupted items. Here's a rundown:
    - +1 to all spell gem wand - includes corrupted
    - +1 to all minion gem wand - includes corrupted
    - +1 to all spell gem amu - includes corrupted
    - +2 to all projectile bow - includes corrupted
    - +1 to specific tag wand - excludes corrupted
    - T1 spell damage wand (runic) - excludes corrupted 
    - +1 to specific tag amu - excludes corrupted
    - +2% to all max resistances - excludes corrupted
    - T1 spell suppression gloves, boots and helmets - excludes corrupted
    - T1 phys dot or general dot wand - excludes corrupted
    - T1 fire dot or general dot sceptre - excludes corrupted
    - T1 flat fire, cold, light damage weapon (foil, claw, wand, bow) - excludes corrupted
- Identified mod filtering *combinations* now include more tiers of suppression rolls

----------------------------------
# **VERSION 8.6.1** - Sentinel League Finetuning
----------------------------------

## SHORT OVERVIEW
This patch implements better sentinel filtering in the endgame, improvements to fractured items treatment, essence items treamtent and all the retiering required!

## NEW LEAGUE FEATURES
- Expanded the sentinel section. Each of the 3 sentinels (non-unique) has 5 rules:
    - T1 - highlights RARE obsidian and special basetypes. Has a special textcolor.
    - T2 - highlights RARE emberstone basetypes. Disabled on uber-strict.
    - T3 - highlights all rare basetypes. Disabled on strict.
    - T4 - highlights all magic basetypes. Disabled on semi-strict.
    - leveling - all sentinels are shown until level 68. Disabled on uber-strict.
    - Author's note: *I could make the section more elegant, but changing that will reset all existing filterblade customizations in this section, so I'm moving a restructure to the end of the league, if sentinel will stay*
- Intentionally did not touch the tiering on the power cores or recombinators yet. The current setup seems good and I'd like more feedback.

## TIERING
- Introduced all new uniques into the tiering
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.
- Increased the breakpoint for T2 cluster jewels to be marked as valuable

## IDENTIFIED MOD FILTERING
- Items with an essence mod have less highlight now
- Items with an essence mod are not highlighted starting with strict, unless...
- Essence mods are now always treated as an auxillary mod for identified item checks.
    - Example: a helmet rule requires 1x core and 4x aux mods. The core mod could be T1 life, T1-T3 res are aux mods. If an item is dropped with an essence mod, such as mana reservation or one of the corrupted essences the item will pass the test and will be highlighted. This is particullary useful to players who have specced into the essence tree, but discovered that 99% of the essence-modded items are trash.
- Veiled mods (both prefixes and suffixes) are now always treated as an auxillary mod for identified item checks.

## CRAFTING AND RARES
- Fractured items have a bit more highlight
- Poor fractured item bases are now hidden on uber-strict instead of strict.

----------------------------------
# **VERSION 8.6.0** - Sentinel League
----------------------------------

## SHORT OVERVIEW
Say hi to your Sentinel! The filter incorporates all of the new league features and a bunch of precedural upgrades!

## NEW LEAGUE FEATURES
- Added all new divination cards
- Added the reworked divination cards
- Added unique adjustments where necessary to minimize chances of hiding new uniques
- Added a simple section to highlight sentinels. For now I'm keeping it simple, but I'll release a more sophisticated version, once we know more about the league. All sentinels currently have a purplish background and an easily distinguishable text color that represents rarity. They're shown on the minimap with the teal "pentagon" icon
- Aded all new currencies.
- Removed all the old archnemesis sections

## CRAFTING AND RARES
- Reviewed all higlighted rares in all tiers. Improved my algorithms and tooling to make the selection more accurate and to make better and more informed decisions
- Reviewed crafting bases as well
- Adjusted the highlight level and selection of synthesised and factured items
    - With the introduction of eldritch influences certain fractured and synthesised items have gained or lost in price and popularity. Generally speaking fractured boots/gloves/shields/helmets have become beter, while their synthesised counterparts lost in power
- Any identified uncorrupted amulet with the +1 to all skills mod is now highlighted
- Quality based flask rules have all been reduced in their priority and are disabled in lower strictnesses
- Very slightly adjusted the appearance of T2, T3 and T4 rares

## TIERING
- All tierlists have been adjusted to better reflect the ingame economy
- EXPEDITION reroll currencies are now economy-tiered
    - Their display depends on the current market price and on the dropped stack. The algoritms currently has special safeguards in place to prevent them from ever dropping below alchemy tier.
- UNIQUE 5 links highlight nerfed. They no longer produce a T2 sound.
    - This has more often than not resulted in in disapointment.
- INFLUENCED tiering has been made much more precise 
    - When tiering itemlevel 80-84 influenced items, the algorithm checks if the economy data for the same base/influence at ilvl 85/86 is at least as high and also matches the threshhold. This prevents random misspriced items and crafted items to be overtiered and highlighted as expensive for no reason. I've been observing this adjustment over the past month and it seems to cause overwhelmingly positive effects by reducing the chances of accidental bamboozels.
- DIVINATION CARD tiering for later league stages has been improved. 
    - Many low value/popularity cards will now drop into lower tiers in later phases of the league (based on price). This only affects low value cards that mostly grant single uniques. Cards with random outcomes are mostly unaffected.
- CLUSTER JEWEL tiering during the first 3-4 days of new leagues will be using the same tiering as at the end of the last league. 
    - This is not perfect, but likely better than not doing anything or accepting highly noisy early league data. I have a better algorithm in mind, but that one will take more time to develop
    - Cluster jewels also receive a slight artifical bias at the start of the league
- FRAGMENT-lures are now economy-tiered, but are disallowed from being hidden as a safeguard
- Did a lot of general clean up to the source code of the tiering algorithm. Improved a few niches and calculations
- Improved Oil tiering, it's a bit less strict for lower tier oils and moves certain oils higher at the start of the league
- Improved the collection of early league uniques (with twitch chats support!)
- Elderslayer fragments are now tierable by the economy
- The basic maven invitation is now anchored to T3 and won't change it's tier
- Abyssal incubators now have more priority if they have a high item level

## LEVELING
- The general weapon progression (not the custom one defined in filterblade) requires 3+ sockets on items. This will decrease the amount of clutter, while giving the player still enough items to through an essence or an alch on.
- Adjusted some keylevels for leveling progressions.
    - Random 3-socket gear will be shown until level 9, instead of 8
    - Internal act 1 level changed from 15 to 16
- Added two-stone ring highlight to earlier sections

## MISC
- T2 heist gear is now hidden on uber-strict instead of uber-plus-strict
- Changed the background on identified mod items from dark blue to dark purple to prevent confusion with the sentinel color-space
- Adjusted chancing bases ("Heavy Belt" "Leather Belt" "Elegant Round Shield" "Ezomyte Dagger" "Champion Kite Shield" "Fiend Dagger" "Prophecy Wand")

## ARCHITECTURE
- The filter now consistently considers ItemLevels or AreaLevels of 68 or higher as endgame ( >= 68 operator ). FilterBlade rules and descriptions have been adjusted as well.
- The filter now consistently considers ItemLevels or AreaLevels 67 or below as leveling ( <= 67 operator ). FilterBlade rules and descriptions have been adjusted as well.

## FilterBlade and technical improvements
- IMPROVED BASETYPE MATRIX: These have become a central tool of FilterBlade and we've invested effort to enhance these with new options
    - Matrixes are now available for many more sections, such as rare jewelery, synthesised, fractured bases and others
    - Their display has been optimized and now better presents data on one sight
    - The matrix for endgame rares now no longer handles the T3 by droplevel, this allows you to finetune T3 rares much better
    - Improved the general visualization strategy
    - You now have the option to show all items at once grouped by tier. This is very useful if you want to remove specific items from a specific tier
    - You can now rightclick to set all visible items in the matrix to a certain tier
    - You can now rightclick to copy and paste the visible tiering. Yes you can finally sync your rares with your crafting stuff etc.
- ADDED +1 SKILL RECIPE SECTION: 5 new (optional) gem sections to show specific quality gems for specific +1to all gems recipes. These can be enabled in filterblade easily
- ADDED GLOBAL STYLE EDITS SECTION: A new tool in the style section. It enables global edits across the whole filter.
    - It allows you to remove all backgrounds, borders (etc), scale font sizes, minimize and maximize item fonts, edit sound options and many more. 
    - It also edits 'the base filter' and doesn't cause your customizer to become "fully blue"
    - It's great for large style modifications of the filter
- Significantly improved the filter deployment and release pipeline. It now has a dozen of utiltiy steps to ensure version number consistency, better changelogs, better github releases, auto-refreshes my token to prevent the system requiring manual cranking every month etc. 
- Reworked the attached changelog. It's now stored in markdown format and is much more structured. 
- Added ad-related cookie consent UI and improved privacy policy. We don't collect any personal data on FilterBlade (or want it), but we're legally bound to show the UI, since ads might do that.

## FilterBlade breaking changes
Either PoE or the architectue behind the following filterblade sections has been adjusted massively and you will have to redo your changes in FilterBlade in the following sections:
- Rare Tiering - T3 (so that you can move individual bases now and not just adjust droplevels)
- Archnemesis mods (being removed)
- Expedition rerolls (being merged into normal currencies)

----------------------------------
# **OLDER CHANGELOGS:**
----------------------------------

The old non-markdown formatted 2000+ lines of changelogs can be found in the ["ADDITIONAL-FILES"](https://github.com/NeverSinkDev/NeverSink-Filter/blob/master/ADDITIONAL-FILES/changelog.json) folder.

These changelogs include changes from version 3.X.X to 8.5.3

----------------------------------
# **SPECIAL THANKS:**
----------------------------------

- GGG for the awesome game
- Bex for the assistance and the patch notes
- Chris for being awesome and answering questions about the item font corruption problem (note: it's not fixed)
- Tobnac/Haggis for the constant help and support + support on the FilterBlade project (will be released during the next monthes)
- My awesome stream viewers, who helped while I was updating the filter. A special thanks to the supporters.
- C4pture for being C4pture
- You