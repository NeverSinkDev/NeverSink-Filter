# **CHANGELOG - NeverSink's Filter**
----------------------------------

Major thanks to all patreon supports to help us fund the continious development. [Patreon](https://www.patreon.com/Neversink) supporters.

----------------------------------
# **VERSION 8.18.1a** - Finetuning
----------------------------------

- Improved the treatment for the monochrome card
- Unique tinctures are now tiered correctly using economy data
- Added some missing old wands to the tiering that changed their base, such as Twyzel
- Reduced the large heist coin pile size from 500 to 400 to better account for locker contents
- Added some selected level 3 heist gear pieces to the T2 heist items to help guff out (and prevent level 3 items from costing half a divine)
- Hivebrain gland is now economy tiered (but not allowed to drop below T3)
- Other minor changes

----------------------------------
# **VERSION 8.18.1** - Keepers of the Flame League - Economy Update
----------------------------------

## SHORT OVERVIEW:

Economy only update, improved initial tiering and added correct handling to foulborn items to not mess with economy data.

## EXCHANGE BASED TIERING

The following items are now tiered using EXCHANGE data (preprocessed and provided by poe.ninja): Currency, scarabs, runegrafts, fossils, allflames, fragments, oils, omen and tattos.

I'll be monitoring the situation closely and adjust the tiering if needed.

Notably excluded are divination cards. My initial analysis showed that the data for the low value cards is very noise and prone to overtiering. I'll revisit this later in the league.

## KEEPERS RELATED CHANGES:

- Added tiering, economy integration, safeguards etc for foulborn currencies and implants.
- Retiered wombgifts slightly. Lavish and ancient are now the T2 wombgifts, rest T3.
- The new breach rings are now hidden earlier (depending on strictness). Higher itemlevel breach rings are hidden later.
- All new and added items are now tiered

I intend to revisit graft tiering and jewel tiering in the coming weeks and look into designing some identified rules for each.

## GENERAL BALANCE OF RARES, VEILED ITEMS, FRACTURED ITEMS

In this league groundloot related to regular gear is worth almost nothing. However, I don't want to adjust it midleague, when a lot of people have already created their filters, so the adjustments right now are minimal. If the genesis-tree crafting will stay in the game in a similar way longterm, I'll do a more thorough rework of rares and related items.

- Reduced the size of some endgame rares
- Veiled items highlight is a bit more strict now
- Memory strand items are now a bit more strict towards the worst bases on very strict and up
- Regular tinctures (ones without optimal itemlevel etc) are now hidden on very strict instead of uber strict

----------------------------------
# **VERSION 8.18.0** - Keepers of the Flame League
----------------------------------

## SHORT OVERVIEW:

This update adds all the keeprs of the flame data, prepares to use currency exchange (a couple of days into the league), adjusts leveling, adjusting identified mod filtering, does a lot of general tiering and a lot goodies on top of that! FilterBlade receives the Auto-Adjuster!

Have a great Keepers of the Flame league!

Major thanks (no particular order) to CDR, Rasmus, S1D3WYZ, Zoey, Haggis, Mellontoss, VenomAssassin for the suggestions, data, testing and development help they provided!

## KEEPERS OF THE FLAME CHANGES:
- Added a rule to highlight foulborn uniques.
- Added wombgifts, very minimal tiering for now, until economy data is available and some sort of meta emerges
- Added grafts, very minimal tiering for now, until economy data is available and some sort of meta emerges
- Added new divination cards
- Integrated new rings (increased their highlight for now until we know more)
- Added all the other misc. new items (currency, fragments etc)

## TIERING CHANGES:
- Major adjustments to the early-league exclusive settings to improve the filter during the first days of the league
- Done preparation to use poe.ninja's currency exchange API for the tiering of all currencies, fragments etc. The tiering via this APi will be enabled 2-3 days into the league once stability is ensured. Thanks to Rasmus for providing the amazing poe.ninja service!
- Added several new bits of logic to improve the economy-based tiering of items.
- Added advanced logic for early league tiering of currency and stacked currency
- Fossil tiering now comes with an extra tier and has had it's thresholds adjusted.
- Added a new economy based gem rule for qual23 gems with neglible level
- Added a new economy based gem rule for lvl21 gems with neglible quality
- Added a dedicated section for harvest lifeforce with individual visuals for different stacksizes. Larger stacksizes -> more dopamine!

## IDENTIFIED MOD FILTERING:
- Added 6 'blend' rules. These require the item to have 3 very high mods (usually T1-T2 all). Very helpful for kingsmarch
- Activated more single-mod identified rules. These are usually very desirable and rare recombination mods, such as +2 proj, T1 suppression etc.

## LEVELING IMPROVEMENTS:
- Reworked currency highlights during leveling. There's now stronger emphasis on Chance Orbs (whole campaign) and Transmutation and Alteration Orbs (first 3 acts). A lot of other small improvements related to leveling currency/stacked currency.
- Added a small new rule to highlight level exclusive incubators. Added some a balistic nuke type of code to purge the stupid leveling incubators from entering the normal tierlists. Seriously, they keep creeping back in into economy data in unexpected ways every single league.
- Added a new rule that highlights normal attack wands while leveling. This rule is disabled on strict.

## MISC:
- Added a rule that highlights ANY gear item with Quality 26% (disabled on very strict). This is in addition to the existing overquality rules that highlight actually useful bases
- Added a rule that highlights ANY gear item with Quality 21%+ (disabled by default)
- Added a new rule that highlights any unique of quality 27%+, if it's not already highlighted by the S,A or mulitbase rules (the goal is to catch otherwise near worthless uniques with quality). Disabled on uber-plus strict.
- Adjusted rare talisman items strictness. Random rare talismans are now hidden on Regular. Selected bases are now hidden on very strict. If this will be annoying, I'll put them back on strict
- Split Ultimatium and Incursion rules
- Added an optional rule to highlight specific T17 maps
- Added extra highlight to shaper wands
- Removed the mercenary unique section for now.
- Removed a bunch of old and outdated rules

----------------------------------
# **VERSION 8.17.3c** - Memory strand & cluster jewel tiering
----------------------------------

- Economy-based Cluster jewels are now correctly tiered using level ranges (eg. 68-74) instead of broad levels (68+). This matters in cases where a lower level jewel is more expenisve than a higher level one
- Adjusted the priority of memory strand and overquality gear to solve some niche priority issues
- Fixed related to cluster jewel economy based tiering

----------------------------------
# **VERSION 8.17.3b** - Minor Adjustments
----------------------------------

- The optional loreweave rule now has more priority than the mercenary unique rule
- Adjusted the strictness of memory strand gear rules and changed them to only highlight non corrupted items
- Further tiering finetuning

----------------------------------
# **VERSION 8.17.3a** - Tiering Improvements (Economy only)
----------------------------------

- Large scale adjustments for divination card tiering and unique tiering
- Divinatinon cards now have a slightly higher price threshold and treat cards with large stacksizes and low value rewards as even less valuable for the sake of tiering

----------------------------------
# **VERSION 8.17.3** - Fixed and improvements
----------------------------------

- Further improved the tiering of many items and added more safeguards
- Added a new optional rule to hide corrupted + magic/normal zana maps
- Added a rule for low tier zana maps
- Added economy based tiering for runegrafts and allflames
- Several filterblade specific improvements
- Several smaller itemlevel changes
- Improved the highlight of 6WhiteSocket weapons
- Mercenary modded items have more highlight now
- Adjusted several identified mod rules
- The conditional hide rules that activate as you progess further in maps now only affect armors (caused confusion when working with rare weapons on filterblade on very-strict)
- Low quality flasks now have more priority than some other early endgame flask rules
- Small gold piles are no longer shown on uberstrict and up

----------------------------------
# **VERSION 8.17.2** - Secrets of the Atlas - Economy & Stable Update
----------------------------------

This update focuses on improving tiering for all the new items, improves the strictness handling of certain rares and does some fixes here and there.

This is the stable tiering/economy version for this league. The stable filters will preserve their tiering for the rest of the league.

## SHORT OVERVIEW:

- Retiered all items (uniques, currency, divination cards etc)
- Fixed an issue where 'of Infamy' normal mods and merc mods shared the same name resulting in weapons with attack speed being highlighted way too hard (ggg probably forgot that they already used the mod name?). Added a new section for infamy weapons.
- Made mod-based veiled highlight a lot less strong and is treated like a normal veiled mod (except for elreon). You can enable specific highlights on filterblade.
- Done a lot of fixes and improvements to the tiering safeguards. The system has proven itself to be very powerful and useful so far.
- Added tiering for runegrafts
- Added tiering for allflames
- Adjusted strictnesses for veiled items

----------------------------------
# **VERSION 8.17.1** - Secrets of the Atlas - Economy Only Update
----------------------------------

## SHORT OVERVIEW:

Added economy based tiering for all new uniques and divination cards.
Additionally I've resolved some issues with identified mod filtering and vastly reduced the highlight for member-based veiled mod highlight.

This update only affects economy filters. Stable will receive an update over the next days, when the economy settles a bit more.

----------------------------------
# **VERSION 8.17.0** - Secrets of the Atlas
----------------------------------

This is a huge updated, involving massive changes for 'Secrets of the Atlas', identified tiering, rares, influenced bases, general economy based tiering and a lot of other changes! Good luck in the new league! Also a new style!

## HIGH LEVEL OVERVIEW OF CHANGES:

- Added a new style: COBALT. It's a gradient of blue, purple and red hues, with strong white texts, smaller and strongly standardized fontsizes and a lot of finetuning. Visually I think it's a stunning and very satisfying style to play with! This style has been designed for the filter's 10th birthday!
- Retiered EVERYTHING. Rares, uniques, divination cards, scarabs etc.
- Use a new set of 'safeguards' to improve early league tiering, while still considering economy (think of items being 'attracted' to certain tiers at the start of the league until eco-data is available)
- Added a new tier of uniques specifically designed for mercenary item highlight! Useful items (that don't carry much value otherwise) for your mercenaries will be highlighted by the unique tiering now!
- Most T5 and T3 scarabs have been put into T4 tier until the economy and meta is settled
- Added a lot of changes specifically for mercenary league and secrets of the atlas
- Overhauled rares (details below)
- Overhauled crafting bases, veiled items, overquality items (details below)
- Overhauled influenced bases (details below)

## RETIERING

- Retiered all currencies, uniques, scarabs, fragments, divination cards etc. using previous economy snapshots and carefully constructed safeguards.
- Adjusted tiering to represent mercenary equipment needs! Special thanks to Mellontoss & the filterblade team for helping with the aspect/tiering work!

## MEMORY STRAND GEAR

Memory strand tiering currently considers 2 factors: the basetype and the number of memory strands (itemlevel can be specified optionally). Memory-strand gear has significantly better rolls upon identifying (scaling with number of strands) and consumes strands to enhance crafting operations. 

The current implementation has 4 tiers, each with a 'high' (60+) and a 'low' number of strands (anything else) subtiers. It comes with a basetype matrix and reuses the combined crafting/rare tiering. It's likely worth identifying most stranded items as they roll significantly better, but likely only the good basetype are worth crafting on. Don't forget that you can (likely) chaos,  essence or scour-alch these bases to reroll them with better outcomes. You can expect a lot of changes and retiering to this system as we learn more about it.

The structure is built in a way that it can be adjusted quickly, so the visual differences and strictness config is currently minimal.

Additionally I added 2 extra rules to always highlight any stranded items that are veiled or fractured as I suspect those should be droppable.

## REWORKED RARE / VEILED / CRAFTING TIERING

As PoE changes, the filter needs to adjust. Normal rares lose most of their use after the first days and even high level crafting bases are rarely the bases you craft on nowdays (usually this is done via fractured, overquality, synthesised, influence items and stranded items in the next league specifically). I'm extensively reworking the rare/crafting tiering to reflect this state.

Rare tiering have been reworked and comes with and extra tier.
- T1 are 'exceptional rares'. These are the best atlas basetypes, such as the top armors added in 3.25.
- T2, T3, T4 and T5 correspond to the previous tiers - 1
- Removed the orange regal highlight (75+) from rares. Instead the orange highlight is now used when the rare can roll the best mods. You can find a table below that shows how this level is determined.

Veiled items have been reworked in this patch. The filter adresses the new veiled items by a mix of 3 approaches.
- 1. Veiled items have been more tightly integrated into the identified mod rules to detect worthwhile candidates
- 2. A list of lucrative member specific veiled mods (such as Elreon) still exists, because unveiled mods are inherently stronger than crafted ones
- 3. There's a veiled items tierlist that reuses the top tiers from the rare tiering to highlight other potentially interesting unveils. It has separate visibility/strictness controls, but shares the same tiering as the rare tiering. That being said, these items become hidden fairly quickly because the approaches 1 and 2 are better at finding interesting veiled items in a high pace gameplay.

Crafting bases have been reworked from the ground up.
They now have less priority than rares and focus on highlighting the very best bases in a class with the optimal itemlevel.
You can find the table used for base distribution below. Crafting bases come in 3 tiers (exclusive-bases, top-bases, niche-bases)

Their highlight has been also vastly reduced.

You can find the class/level distribution below
- ItemLevel 86: "Body Armours" "Boots" "Shields" "Bows" "Belts" "Quivers";
- ItemLevel 85: "Amulets" "Gloves" "Helmets";
- ItemLevel 84: "Rings" "Wands" "Staves" "Rune Daggers" "Sceptres";
- ItemLevel 83: "Daggers" "Claws" "Thrusting One Hand Swords" "One Hand Swords" "One Hand Maces" "One Hand Axes" "Warstaves" "Two Hand Swords" "Two Hand Axes" "Two Hand Maces";
- Note that amulets and rings have one more mod (WED and mana) that they can roll if you get them with an extra level, but due to pragmatic concerns I've put them a level lower

## INFLUENCED ITEM TIERING

The influenced tiering has been completely rewritten. It now has less rules (we're talking about influenced bases, so there's still a lot) and has the goal of being much simpler to understand, maintain and edit. Note that if/when these rules are disabled (such as on higher strictnesses), the rare/crafting sections can still pick up the bases.

The influenced item tiering comes in 3 layers:

Layer 1. ANY influence, Demanded bases. The influenced tiering has the following rules:
- T1 bases (any influence) - any atlas exclusive top tier or armor or jewellery. 
- T2 bases (any influence) - top tier shields & quivers, most rings, most amulets, select belts. Disabled on uberplus strict.
- T3 bases (any influence) - best crafting weapon bases and second grade armors. Requires itemlevel 84. Disabled on very strict

Layer 2. Class based filtering. This has 7 rules. All of these rules are disabled on Uber-Strict.
- ANY influence. Itemlevel 85. Highlights any: "Body Armours" "Helmets" "Rings" "Amulets" "Wands" "Sceptres" "Quivers"
- Shaper (Any itemlevel): "Rings" "Amulets" "Bows" "Gloves"
- Elder (Any itemlevel): "Rings" "Amulets" "Belts"
- Crusader (Any itemlevel): "Rings" "Amulets" "Belts"
- Hunter (Any itemlevel): "Rings" "Amulets" "Gloves" "Belts" "Boots" "Shields" "Quivers"
- Warlord (Any itemlevel): "Rings" "Amulets" "Gloves" "Boots"
- Redeemer (Any itemlevel): "Rings" "Amulets" "Boots" "Shields"

Layer 3: Low strictness filtering/other rules.
- Any itemlevel 86 influenced item (Disabled on very strict)
- Any random influence item (Disabled on strict)

## IDENTIFIED MOD IMPROVEMENTS

With mercs wearing identified gear, veiled items being identified, kingsmarch returning identified items and endgame mapping and ritual doing their part, I think it's time to revisit the statistical puzzle that is designing identified item filtering. The details are a bit hard to describe, as it's a hundreds of small modifications, but here's the general overview:

To understand the following notes, here is the core terminology you need to know. 
My implementation of identified mod crafting (considering PoE-filter limitations) searches for 1-2 core mods (from a list) on an item and 3-5 support mods. Usually those 2 overlap (every core mod is a support mod). For example on boots 30% and 35% movement speed are core mods. If they spawn, the boots additionally require three other relevant lower mods, such as 29% fire resistance to be highlighted.

1) Review minion items and some other underrepresented archetypes. Minion wands now have a dedicated rule
2) Better integration of veiled mods and incursion mods. Veiled mods are now always considered a 'support' mod and in some cases even a 'core' mod.
3) Integration of member specific veiled mods into select rules. Depending on the power they are treated as core or support.
4) General review of desired mods like chaos resistance and suppression and giving them appropriate priority when evaluating rare items. High tier chaos and suppression is now treated as core mods on certain items.
5) Jewels and abyss jewels received a major review and several mods have been added.
6) Reworked the bone ring rule
7) Most rules that focus on armors now only look for uncorrupted items

A huge thanks to Cdr and their contributions!

## OTHER NEW LEAGUE CHANGES

- The Trarthus gems are handled by the TransfiguredGem section (no change was doone, just noting, they've not been forgotten)
- Added a section to detect mercenary-exclusive mods
- Removed items that are leaving the game: memories, certian scarabs.
- Removed runes and added runegrafts
- Added allflames into the scarab tierlist (as they serve the same function)
- Added new orbs and fragments
- Added new and returning divination cards
- Put the Gold Flask and Vermillion Ring uniques into the S tier.

## MISC CHANGES, STREAMLINING AND SIMPLIFICATION

- Merged Brachstones into Fragments 
- The overquality section now has less rules
- Merged several rules in the overquality crafting section
- Merged the 29 and 30 quality rules in the overquality section
- Stacked Scarab rule has been moved
- Adjusted the quality threshold for high level and quality gems to be 13% instead of 14%
- The rules to highlight items with eldritch implicits are now disabled.
- Made the early endgame quality flask less strict (15%->10%)
- Streamlined a lot of filter configuration and structure
- Changed ideal heist gear level 81->83

----------------------------------
# **VERSION 8.16.0** - Legacy of Phrecia Support
----------------------------------

## SHORT OVERVIEW:

Idols dropping in the Legacy of Phrecia league have been added to the filter!

## NEW FEATURES:
- Added a rule for every of 6 idol types - Magic version
- Added a rule for every of 6 idol types - Rare version
- Added a rule for unique idols dropping
- Added a safety rule for normal idols dropping. Just in case.

## IMPORTANT TECHNICAL CHANGES:

I've massively improved my filter-generation tooling, this enables some new capabilities!

- I can now support even-specific filters: The legacy of phrecia - of Phrecia Event now has full economy support! FilterBlade will have 2 legacy of phrecia dedicated versions of the filter for the duration of the event. The stable filter supports both legacy/main league event gameplay.
- Added a new system to create whitelist/blacklist tiers for individual items during a specific league state. This helps with making better and safer tiering decisions at the start of new leagues!

----------------------------------
# **VERSION 8.15.4** - Kalguur League Finetuning
----------------------------------

## SHORT OVERVIEW:

I wanted to address a large number of small issues and QOL improvements in this update.

## NEW FEATURES
- Leveling gem rules now require arealevel of 2+ in order to exclude them from popping up in kingsmarch inventories.
- The rule for gems you receive at level 1, now requires the gems to have 0 quality and gem level 1. Additionally it requires the gem to be one of the active and support gems that can drop in twilight strand. This minimizes chances of them appearing in kingsmarch rewards.
- Removed corrundum flask from most utility flask lists.
- Normalized overquality rule treatment: pretty much any best basetype of 21%+ quality will not be hidden on any strictness now (tinctures, flasks, weapons, armors). This may show some items that are not worth much.
- Reduced the tiering of scouting reports in the stable version. Economy based versions should be tiered based on the economy correctly already.
- Added a new rule to highlight ILVL85 tinctures (disabled on uber-plus-strict)
- Gave explorer scouting reports an extra bonk, since they were still overtiered
- Increased the itemlevel offsets for generic rare items in the leveling section to prevent inconsistencies that could result in boss-drop rares being unintentionally hidden a few levels to early (this will likely receive a rework in the upcoming league). Thanks to CDR for pointing out the issue.

----------------------------------
# **VERSION 8.15.2c** - Of Dust, Omen and Perfection
----------------------------------

Made the perfection rules optinal as well

----------------------------------
# **VERSION 8.15.2b** - Of Dust, Omen and Perfection
----------------------------------

Fixed Dust tierlist being broken and showing wrong items. Oops.

----------------------------------
# **VERSION 8.15.2a** - Of Dust, Omen and Perfection
----------------------------------

Minor adjustments to the strictness progression of overquality items.

----------------------------------
# **VERSION 8.15.2** - Of Dust, Omen and Perfection
----------------------------------

## SHORT OVERVIEW:

This update adds much requested uniques-for-disenchanting-rules to the filter! These are disabled by default, but can be enabled on filterblade. This update further improves strictness balance, basetype tiering etc.

All the changes below affect both economy and stable filters. In addition the economy-based filters also have their tiers adjusted.

## NEW FEATURES
- Added 3 new OPTIONAL rules (can be enabled on FilterBlade): Unique items that are worth 5000+/2500+/1250+ dust-per-inventory slot. The content of these rules has been originally compiled by S1D3WYZ, I modified it further and added some additional bases. These are entirely separate and are not part of the unqiue tierlist and placed in a way that it will never override T1, T2 and valuable mutlibase drops.

## BASETYPES
- The expensive bases rule can now contain the new endgame armors, not just old atlas bases.
- Added a new rule to highlight high perfection new bases.

## TIERING
- Omen tiering has been improved
- Omen now have 5 tiers instead of 4.
- Made scarab rules strictness slighlty less strict
- T4 currency divination cards are now hidden on uber-plus strict instead of uber-strict

## MISC
- Corrupted abyss jewels have now more priority (hiding ilvl 86 jewels will no longer hide corrupted ones)
- Minor strictness and identified mod changes

----------------------------------
# **VERSION 8.15.1c** - Further Adjustments
----------------------------------

- Tinctures now have stricter filtering
- Sundering axe has been moved to a higher tier in multiple tierlists
- Reflecting Mist is now T1
- Fixed currency tiering being weird around the alchemy tiering and vastly prefering to put items into either chaos or chrom tier.
- Fixed relic tiering

----------------------------------
# **VERSION 8.15.1a** - Overquality Level Reduction
----------------------------------

## SHORT OVERVIEW:

Reduced the itemlevel requirement of all overquality bases to be 84 instead of the optimal level (84-86). This is done because the itemlevel can be then increased using recombination techniques to achieve the optimal level.

----------------------------------
# **VERSION 8.15.1** - Settlers Economy Update
----------------------------------

## SHORT OVERVIEW:

Tiered all the new uniques, economy findings and discoveries. Unless more things will be added, this will be the stable version for the rest of the league (economy based verisons will of course continue receiving updates). On top of that tinctures and gold received better integration.

## TIERING
- All tierlists have been adjusted:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.
    - Added all unique tinctures to uniques T3. These are not yet economy tiered.

## OTHER CHANGES:
- Removed the 1-useful mod requirement from the corrupted-rare standard-jewel section, because they now mostly drop unidentified.
- Added a tiny map icon to all gold drops
- Increased fontsize of T5 and T6 tier scarabs
- Stacked Scarab rule now correctly matches T4+T5+T6 rules
- Glassblower recipe rules now also look for quality tincutres
- Improved the tincture leveling rule by scoping on itemlevel
- Pinnacle and Collossal tower shields are now both T1 in the rare armor tierlist
- Fixed high level tincture fontsize being off by 3

----------------------------------
# **VERSION 8.15.0** - Settlers of Kalguur
----------------------------------

## SHORT OVERVIEW:

This is a HUGE update that includes a ton of changes related to the new basetypes, quality changes, new tierlists, general QOL and other adjustments. Note that it has an overhaul-nature, so expect a lot of finetunings over the next days and weeks!

## NEW ITEMS:
- Added prismatic oil (to the oil tierlist), maven's chisels, reflective mist (to the general currency),An Audience With The King (fragment)
- Added new divination cards and reintroduced some old ones.
- Added a rune tierlist
- Added a corpse tierlist (wow...)
- Renamed a ton of items according to the patch notes.

## TIERING
- All tierlists have been adjusted:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.
- Scarabs, fragments and similar items now have a slightly different color style to support larger tierlists.
- Scarabs now have 6 tiers instead of 4. Rebalanced the tiering of scarabs.
- Rebalanced the apperance and strictness of essences. 
- Oils now have 5 tiers instead of 4.
- Stacked Divination Card: Added a new rule for stacked divination card tiering
- Adjusted the tiering of Augmentation Orbs
- Lowest tier of fragments (usually only affectes sacrifice fragments) are now hidden on uber-strict
- Made stacked sacrifice fragment tiering more strict
- Increased the S-tier threshold for the Sacred Orb to be 1.5x higher.

## RARE, CRAFTING, NEW BASES QUALITY:
- Retiered all of the rares, crafting bases etc. It has much more focus on melee items and the major defense types are AR/EV->AR->EV->AR/ES->Rest
- A lot of sections have had their tiering adjusted due to the meta changes.
- Added a new section (currently included "Riveted Boots" "Steel Kite Shield") for high prospect omen of chancing targets. This section requires 29 quality or higher for items to get highlighted
- Entirely reworked the previous 'perfection' section:
    - Added 15 new rules to detect the best available shields, gloves, helmets, armors and boots (3x each) with optimal item levels (85-86) and high quality. The top rule also requires defense perfection level
    - Added 4 new rules to detect ilvl83+ weapons with 24+ and 29+ quality
- Due to the new basetypes introduced, quality changes and other adjustments I'm completely reworking the way rares and crafting bases are treated in the filter.
    - New endgame bases have been added into T1
    - Rare gear T1,T2,T3,T4 are now each 1 rule and not multiple rules as it was before
    - The rare section has been completely retiered
    - Added a new decorator that adds a special border to the current (itemlevel based) best bases (from those added in 3.25)
    - Added 4 new rules that are only active on higher strictnesses. These will hide the lower layers of armor-class drops as you progress further into the endgame.
    - Very Strict will hide ALL non-remarkable non-jewellery (fractured, 6l, 6s...) rares in alvl82 and higher areas except for bases with droplevel of 75 and higher. Note that this will also hide weapons.
    - Rare armours are now hidden on uber strict instead of very strict
- Changed the tiering of Whetstones and Armorers (both consistently a tier higher), due to higher usefulness and expected rarity
- Changed stacked armorer scrap tier appearance during the campaign
- High level, high quality magic corrupted flasks have an improved appearance now
- Adjusted the tiering of endgame crafting bases

## TINCTURES:
- These rules are HIGHLY temporary and will be adjusted once we know more about the rarity, mods and usefulness of tinctures
- Added a tincture leveling rule (it will highlight any tincture that drops while leveling)
- Added a tincture endgame rule: highly any tincture of quality 26%+
- Added a tincture endgame rule: highly any tincture of itemlevel 82+
- Added a tincture endgame rule: highly any tincture (disabled on uber strict)

## GOLD:
- Added several new rules to highlight gold depending on stack size
- Since gold is autpickup and doesn't take inventory slots, it's color, font size etc is designed to be more subtle

## MAP ADJUSTMENTS:
- Added a special rule to highlight 8-mod corrupted maps
- The Vaal Temple Map now has dedicated rule.
- Resorted the order of map rules
- Maps with any implicit and maps with 1 corrupted modifier rules are now disabled by default (they wil be shown if the map tier is shown)
- Added a decorator to highlight with any implicit and maps with 1 corrupted modifier (special border)

## MISC CHANGES:
- Added 2 new leveling rules for dedicated highlight for the following orbs: "Chromatic Orb" "Orb of Chance" "Orb of Alteration" "Blacksmith's Whetstone"
- Added a dedicated rule for stygian vise and stygian vise ilvl 86
- Split the rare weapon melee rules into 1h and 2h. 1h melee items have a yellow-orange-brown highlight (not super happy with the color), while 2h melee uses the old red one.
- Removed extractable ring annointments for gold oils and silver oils (as oil extractor has been removed)
- Added the new prefix-shield-block mods into the identified item tiering system
- Changed the campaign general-crafting rule from act3 start to act2 start.
- The rule that checks if the item is fractured AND veiled now checks for incursion mods as well.
- Chisel recipe now only accepts gavels.
- Added +1% max resist jewels to the ID mod section
- Unique non-corrupted jewels now have a diffrent map icon color
- Removed a lot of old and outdated bases
- Added prismatic ring to the list of synthesised unique exceptions 
- The 'all other' cluster jewel rule is set to hidden instead of disabled on higher strictnesses now
- Deleted a lot of old bases
- Adjusted +1 recipe gems
- A lot of smaller structure changes

----------------------------------
# **VERSION 8.14.4** - New Scarabs
----------------------------------

Just the new scarabs. They're also added into stable version without adjusting the tiering.

## SHORT OVERVIEW:

Just the new scarabs. They're also added into stable version without adjusting the tiering.

----------------------------------
# **VERSION 8.14.3a** - Tattoos and finetuning
----------------------------------

This version focuses on improving the tiering of allflames and polishing. It does not affect stable.

## SHORT OVERVIEW:

Tattoo tiering has been fixed and cleaned. I've also improved tiering for a lot of niche scenarios (looking at your Cloak of Tawm'r Isley pricefixers).

----------------------------------
# **VERSION 8.14.3** - Necropolis Finetuning
----------------------------------

This version focuses on improving the tiering of allflames and polishing. It affects stable as well, but only the allflame tiering is changed!

## NECROPOLIS CHANGES:

- Reviewed the tiering of allflames

## MISC CHANGES AND BUG FIXES:

- The new corrupted jewel section now correctly highlights all magic 1-corrupted-mod jewels.
- Added the flask class to high level life/mana flasks to prevent some niche bugs on filterblade
- Added deicide mask to the T1 perfection based items. 
- Added full dragonscale to the T1 perfection based items

----------------------------------
# **VERSION 8.14.2** - Necropolis Revamp Update
----------------------------------

Integrated the new allflames, retiered everything! Allflames are *not* economy tiered (yet), since everything has been revamped.

## NECROPOLIS CHANGES:

- Added new allflames
- Moved frogs and meatsacks to T2
- Added a leveling rule for allflames

## TIERING CHANGES:

- All tierlists have been adjusted:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.

----------------------------------
# **VERSION 8.14.1** - Economy Update
----------------------------------

## SHORT OVERVIEW

Integrated new uniques, scarabs are now economy tiered. All the good stuff :)

## TIERING CHANGES:

- All tierlists have been adjusted:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.

----------------------------------
# **VERSION 8.14.0** - Necropolis League
----------------------------------

## SHORT OVERVIEW

Necropolis has been integrated into the filter! On top of all of the necessary changes this update improves upon the existing strictness progression, revamps fractured bases, adds several new rules.

## IMPORTANT-TO-KNOW CHANGES:
- IMPORTANT: The bossdrop-unique-tier is now hidden on uber-plus strict! If you do some bossing on this strictness be sure to show hidden items with ALT.
- IMPORTANT: Low tier-base or corrupted non-unique six-links are hidden on uber-plus strict
- IMPORTANT: Unidentified rare corrupted items with 0 corrupted mods are now hidden. This excludes leveling, jewellery, high linked/socketed gear and 'exotic' cases (such as runic items and all kind of exceptions)

## NECROPOLIS LEAGUE RELATED CHANGES

- Added a low priority rule designed to highlight all items created in the necropolis (rare identified equip pieces of arealevel 1 items of itemlevel larger than 4)
- Added new scarabs and some basic tiering
- Added T17 maps
- Added allflames (and some very basic tiering)
- Added the new heist belt
- Migrated the Veiled Chaos Orb
- Added section to highlight items with necropolis craft mods
- Removed all obsolete items (invitations, sextants, compasses)
- Removed the beyond map rule
- All tierlists have been adjusted:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.
- Reviewed and adjusted all rare, fractured and crafting bases, thank you for all of your votes!

## MAP RELATED CHANGES:
- Added a new rule to highlight the T17 maps
- Added a new rule to highlight maps with corrupted implicits
- Removed the rule highlighting maps with the beyond mod (becuase the mod is gone)

## NEW FEATURES:
- Unidentified rare corrupted items with 0 corrupted mods are now hidden. This excludes leveling, jewellery, high linked/socketed gear and 'exotic' cases (such as runic items and all kind of exceptions)
- Added a new tier to the unique tierlist: high-multi-base uniques. This tier will contain uniques that have a chance to have highly expensive WORLDDROPS (important: NOT bosses!), such as Heavy Belts and Leather Belts. The minimum value requirement is 5x T1 price threshold. The purpose is to make unique tiering easier. The rule has the same appearance, but uses purple map colors and beams.
- Added a new rare decorator rule that gives 4linked rares a special border. This is useful early on in the league as these rares tend to sell much better. Higher strictnesses that hide rares won't be affected by it.
- Added a rule to detect fractured veiled items. This does not guarantuee that the fractured mod is the veil. If both align - you get a fractured veiled item - something potentially very valuable.
- Added detection of identified bone rings with a promising combinations of mods
- The reworked 'wraithlord' helmet unique with 4 abyss sockets received a special rule that detects it (by the abyss sockets)
- Added a new optional rule to highlight magic generic jewels with at least 1 corrupted modifier. These jewels are potentially useful for the adorned unique. These jewels will likely drop unidentified and most results will be not too useful. The rule is disabled on very strict. Experienced and interested players can reenable it of course.
- Reworked and refined the endgame flasks rules quite a bit, some old rules have been removed and a few exceptions have been revamped. Among others I've added a new rule to highlight 30% qual corrupted endgame magic flasks.
- Added a new rule for Forbidden Tomes of ILVL 83. This is pretty much just to simplify filterblade editing.

## HIGHLIGHT AND STYLE CHANGES:

- Strengthened the highlight of all utility-flasks
- Reworked the appearance of six-links. High tier six-links look like low tier six links before (crimson background, white accents), while low tier sixlinks use a new appearance. 
- Introduced a new appearance into the filter: a turquoise looking tierlist - this is currently used only by allflames and is intended to be used as a tierlist for new league items.

## STRICTNESS ADJUSTMENTS:

There are a lot of rules in the filter that have lost most of their pratical relevance for normal gameplay over the years. In this update, I disabled a whole bunch of these rules. The filterblade ruthless filter mode will be adjusted to reanable those.

- The bossdrop-unique-tier is now hidden on uber-plus strict! If you do some bossing on this strictness be sure to show hidden items with ALT.
- All chisel recipe rules are now disabled.
- Disabled some endgame low quality flasks rules (the flasks will still be highlighted, if they're useful, but the quality itself won't trigger a highlight)
- Low Level T2 crafting items are now disabled
- 84+ Level T3 crafting items are now disabled
- 86+ Level T3 crafting items are now hidden on semi-strict
- Increased the strictness of talisman filtering
- Cleaned up 'Perfection' bases (ilvl86 bases with perfect implicit defense roll, otherwise only changable with Sacred Orbs) to only have 2 tiers and recommend betters items. The second tier is disabled by default. The first tier is disabled on uber-strict.
- Poor non-unique 6links (corrupted, low level or not one of the higher bases) are now disabled on Uber-Plus-Strict.
- T5, T5currency, T4, T4currency cards are now filtered stricter.
- This is not a comprehensive list, there are more minor strictness adjustments

## IDENTIFIED MOD RULES:
- ES recharge rate and faster recharge start has been almost universally removed from the list of desirable mods.
- Identified gloves: properly split ES and life based gloves
- Identified boots: decreased the importance of defenses
- Identified quivers: now require 2 'core mods' instead of one. 
- Identified shields: removed a lot of the less valuable mods like %physical damage reduction and added new useful combinations
- Added a strictness gradient to the identified mod detection. Most identified mod rules are now disabled on uber-plus strict. Some rules are disabled on uber-strict (such as identified body armor rules). You can of course enable combinations you are interested in on FilterBlade.

## MISC CHANGES:
- Hinekora's Lock has been moved into the currency tier
- The reworked divination cards have been retiered
- Fixed a rare bug that would cause some cluster/abyss jewels to be highlighted, despite being hidden on filterblade
- Top tier life and mana flasks (no quality) are now shown up to T3 maps, not T2.

----------------------------------
# **VERSION 8.13.1** - Affliction League
----------------------------------

## SHORT OVERVIEW
Valdo's Puzzle Box is now part of the T1 tier. Affects both stable and economy. This is the stable version for this league, unless something major will need changes. All of the tiering and thresholds adjustments have been highly succesful. I found the tiering this league to be very accurate and I hope you did too. I'll be keeping a close eye on the economy and will adjust the thresholds if needed.

## CHANGES
- All tiers have been adjusted to the current economy
- Added Valdo's Puzzle Box to T1 (were never hidden, but now have appropriate tiers, instead of 'pink unknown item color')
- Added tiering to new uniques/divination cards (were never hidden, but now have appropriate tiers, instead of 'pink unknown item color')
- Disabled the random 28%+ quality rule by default (except for flasks) as it no longer holds any real value

----------------------------------
# **VERSION 8.13.0** - Affliction League
----------------------------------

## SHORT OVERVIEW
Affliction is upon us! This filter introduces all of the affliction related items, removes all enchantement/metamorph related things, introduces sanctum unique and memory tiering. It also completely revamps all tierlists and thresholds. We've introduced dozens upon dozens of architecture improvements. Find out more in the changelog!

## DIRECT CHANGES OF NEW LEAGUE
- Introduced new currency-like items relating to ultimatum (scarabs, incubators, delirium orbs)
- Added the new catalyst type
- Adjusted the heist experimental bases and added new ones
- Adjusted the Ultimatum Aspect section
- Introduced a new section to match any Charm, Corpse and Tincture. I don't know if they drop, but they'll be highlighted.
- Added new divination cards
- Metamorph and Ancestor uniques are now world-drops - aspects have been adjusted
- Removed the low level heist-experimental bases that no longer drop
- Removed all alt-gem type sections
- Removed all sections for helmet, glove and boot enchants
- All items relating to enchanted item rewards (incubator, delirium orbs etc.) have been removed from tierlists
- All sections relating to metamorph item rewards (incubator, delirium, orbs etc) have been removed from tierlists

## INDIRECT CHANGES OF NEW LEAGUE
- Increased the highlight and decreased the strictness of all quality-gem rules
    - Low quality gems are now highlighted up to and including Very Strict (1-13%). They now also have a higher textsize and come with a map icon (grey triangle, small) and a temporary grey beam.
    - Mid quality gems are now highlighted up to and including Uber Strict (14-19%)
    - Decreased the strictness of level 18-19 gems. I'm not sure if there is a practical use case for those in the lab/league, but I'd rather not risk those getting hidden too early.
    - I will keep a close eye on the usefulness of the gems over the next week and will potentially increase their strictness depending on the GCP demand and supply

## NEW FEATURES
- Added the PURPLE style!
- Atlas memories now have a economy-based T1 tier. That means memories that cost more than ~55chaos will ding on drop! Other memories are still highlighted on all strictness.
- ~~Helmet enchantments now come with an experimental economy-based tierlist.~~ This feature has been canceled due to the removal of enchantments from the game.
- The unique tierlist now includes economy-based Sanctum Relics tiering.
- Reworked the six-link highlight. It now has 2 tiers. One for a bunch of handpicked higher tier, non-corrupted six-links of ILVL 75+ and one for the rest.
- Added a small rule to highlight bricked corrupted rare versions of ornate quivers, kalandra rings and other special unique-exclusive basetypes. You'll hate it when it happens. You're welcome
- As part of the structural upgrade to turn most class-combinations into variables and using exact matching, lots of sections have been modernized and updated.

### TIERING OVERHAUL:
- Completely revamped the tiering algorithm. It now uses a more standardized set of thresholds, instead of having individual thresholds per tierlist.
- The thresholds scale with the progression of the economy.
- The higher tier thresholds are:
    - T1: 55c   (40c at league start)
    - T2: 14.9c (10c at league start) - lower for uniques and currency
    - T3: 4.9c  (3.1c at league start) - lower for uniques and currency
- Some exceptions apply: for instance awakened gems have 3x the T1 threshold, because finding a 100c awakened gem upon killing maven is much less exciting than fiding a 100c exceptional gem (such as empower).
- Added several new rules to unique and divination tiering, such as if all expensive versions of the unique are world drop ones and non-expensive ones are boss-drop ones, this unique is allowed to be added to T2. This currently only affects Hyrri's Ire (would've affected Rathpith Globe, a few weeks back)
- The 'aspect' (meta-information about individual items) system has been reworked and simplified. Meta-information (aspects) about uniques has been highly adjusted. High variety and uncommon uniques have been re-shuffled to be more accurate, multi-base tiering has been adjusted, lots of small and large improvements. Overall this should be much better now. Thanks to Melontoss for the help!
- Reworked the list of 'EarlyLeagueUniques'
- Divination card tiering and reward interpratation (system that calculates the price of the reward to check if the div-card price is pricefixed/off) has been vastly expanded
- Adjusted divination card tiering. Rasmuskl (poe.ninja author) has vastly improved the quality of the divination card economy data, so the divination card tiering is MUCH better now. Thanks Rasmuskl!
- Kaom's heart now has it's own section (marked as T2) since it can be detected by it's socketless-ness
- Added some experimental features to help early league tiering, such as cards that don't have value early on, limited-early league mode for certain currency (such as life catalysts) and more. I'll keep a close eye on those.
- 'Anchored' the gemcutter prisms into the annulment tier for now. I'm not sure if this is where they should live, but I'll keep an eye on it. I'll remove the pin after 2 days.
- Adjusted all rare, synthesised, chancing, crafting, fractured bases tiering based on the poll results during the filter release stream. Thank you twitch and twitter for your votes and support!

## IDENTIFIED ITEM HIGHLIGHT
- ID quivers: The engine is now better at seeking out good combinations.
- ID gloves, boots and helmets: ES variants require more solid ES rolls. Both life and es variants don't overvalue hybrid rolls anymore.
- ID rings: recoup is now valued as a valuable mod, T1 rarity prefix is valued as a solid mod. Increased the requirements for life and es rolls.
- ID amulets: T1 rarity prefix is valued as a solid mod.
- ID elemental weapons: Now consistently only use the following classes: bows, foils, wands, claws
- Added some additional abyss jewel mod combinations
- Added a new rule to detect daggers with multiple very high tier elemental attack mods and caster suffixes for the usage with the new blade blast

## LEVELING ADJUSTMENTS:
- The progressions for rare archer/melee weapons have been simplified and the level thresholds increased. They also now use Arealevel instead of itemlevel.

## MINOR CHANGES:
- Added a new rule that highlights all fractured items (indendent of base) for low strictnesses. This rule is disabled staring with strict and then the Tierlist applies.
- Added some low priority rules that highlight rares with RGB sockets.
- Added new optional sections to easily disable corrupted and mirrored (magic) maps

## MISC AND ARCHITECTURE CHANGES:
- The identified rule is now placed much higher in the internal sorting of conditions. This is a performance optimization and should have no effectr on the actual filtering.
- Replaced most class checks with exact matching (==), standardized the class checks to use specific variable sets. This should have a positive impact on performance and quality of potential updates.
- Added un-corrupted and un-mirrored requirements to veiled items and some other cases
- High level incubator exceptions are now disabled instead of hidden on high strictnesses.
- Removed the sentinel code and sections once again (after the event)
- Dozens of other small changes

## DELAYED (will be part of next update):
- [TODO] Add solution for RGB/Endgame rare compatibility
- [TODO] Flask progression now has more priority than quality flasks during leveling. Added a new decorator to highlight quality-progression flasks.

----------------------------------
# **VERSION 8.12.0** - Kalandra & Sentinel + incubator rework + minor changes
----------------------------------

## SHORT OVERVIEW

These filters reintroduce a whole bunch of kalandra-league and sentinel-league rules.

Additionally there's the large requested incubator tiering rework and some unique tiering improvements. All other larger changes (that are still WIP / testing) will be released during the December league. There's also some minor structural changes and improvements.

Important: This update does NOT change anything about unique/divination card tiering for the event. It usues exactly the same tiering as on the live league. You might want to fine-tune it for your strategy on FilterBlade.

## INCUBATOR REWORK:
- Reworked. No longer bad. Now good. This is a buff. (hopefully)

## TIERING ADJUSTMENTS:
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.
- Due to the nature of the structural update this update also affects the stable version

## FLASHBACK LEAGUE ITEMS
- Readded sentinel section
- Readded sentinel leveling rules
- Readded sentinel power core, special cores and recombinators
- Readded unique sentinels
- Activated ID-mod section for useful sentinel recombinations

## UNIQUE RETIERING:
- Lot's of aspects and rule adjustments thanks to the massive help of the filterblade team (special thanks to melontoss)

----------------------------------
# **VERSION 8.11.2** - New Tattoos
----------------------------------

## SHORT OVERVIEW
Added new tattoos into the tierlist. I intentionally did NOT do any tiering changes to the stable version. Economy-updated versions of course are retiered.

## TIERING ADJUSTMENTS:
- 6 New tattoos added (these were NOT hidden in the old filter, but were not tiered)
- The tierlists have NOT been adjusted on the stable filter. This is intentional. The economy-updated versions are retiered. In the future goal is to limit re-tiering processes on the stable filter to 2 per league (1 at release and 1 during first eco-update). This is experimental.

## MISC CHANGES:
- Synthesised unique rings are now highlight by basetype, instead of class
- Flasks are now consistently highlighted via class, instead of basetype
- Quality flasks for vendor recipe are highlighted started with 14 quality instead of 15 quality.

----------------------------------
# **VERSION 8.11.1** - First Economy Update
----------------------------------

## SHORT OVERVIEW
Tattoos and omens are now tiered. Adjusted tier tiering algorithm and updated the tiering for unique and unique map tierlists. This update affects the stable filter as well as the unique/currency tiering was pretty messy before that. 

## TIERING ADJUSTMENTS:
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas, Omen, Tattoos and Gems.
- The tattoos are now all economy tiered! (thanks Rasmus for the quick poe.ninja integration)
- The Omen are now all economy tiered! (thanks Rasmus for the quick poe.ninja integration - AGAIN)
- Changed the tiering threshholds on unique maps. In general higher tiers require higher prices now.
- Changed the tiering of T1 uniques. They now require a slightly higher price.
- Adjusted the early league tiering algorithm. It should no longer overprice stacks of sextants and similar items in future leagues.
- Added the new uniques into the tierlist
- Adjusted previous sanctum unique tiering

----------------------------------
# **VERSION 8.11.0** - Trial of the Ancestors League Update
----------------------------------

## SHORT OVERVIEW
Talamoana exile. This patch adds support for all that new and old trial of the ancestor items. Additionally it features large scale improvements to tiering, fractured items, influenced items, cluster jewels, jewels, gems, divination cards, uniques, currency and much more. It also features a bunch of architecture improvements and quite a few FilterBlade features.

We hope you'll enjoy the new league and the new filter!

## TRIAL OF THE ANCESTOR CHANGES:
- Added a new rule for silver coins. The appearance for the silver coins has been decided by a democratic election. Thanks twitch chat. They'll likely wander into the currency tierlist if trial goes core.
- Added a tierlist for all the tattoos (with safety section in case some were missed)
- Added a tierlist for all the omen (with safety section in case some were missed)
- Added a new rule for hinekor's locks. They'll likely wander into the currency tierlist if trial goes core.
- Added a rule to highlight forbidden tomes and related sanctum items
- Wiped the dust of the sanctum relic rules
- Added aspects to uniques that have a new unique attached to them to minimize the risk of them being hidden

## TIERING ADJUSTMENTS:
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas and Gems.
- Removed orbs that never drop in stacks or where the chance of an orb dropping in a stack is astronomically low from the 'stacked currency' section. These orbs are still highlighted in the 'currency' section.

> *NeverSink's notes: I'm aware that stacked currency tiering on filterblade is currently in a bad spot, we're looking for a good UI to improve that situation. We're looking for good UI/UX suggestions for that. If you have any, please approach us on our discord!*

- Anchored Exalted Orbs and Elevated Sextants to the T2 currency tier. This is to prevent economy anomalies early on in the league and them sometimes shifting to T1.
- ~~Moved ritual and crescent splinters into their own category out of currency~~ (Delayed until next patch, it was giving us too many technical difficulties with existing filterblade savestates)
- Removed the atlas base status from some atlas bases that are not used at all
- Trying out a new strategy to tiering divination cards. The strategy won't be active during the first days of the league, but will afterwards attempt to weight all cards down (because the economy data for it is super noisy) with an offset based on the stacksize.
- Expanded the selection of 'good' eater/exarch bases with the focus on gloves and boots, especially ones that can roll suppression. All other ones are hidden on semi-strict and up.
- Adjusted the list of early league uniques
- Adjusted the list of early league divination cards
- Adjusted early endgame crafting bases.

> *NeverSink's notes: In the future I'll likely rework the algorithm alltogether. That being said, I still count for influenced items to get reworked evenutally, with them barely seeing any use compared to fractured/eldritch bases, with some very few niche exceptions, such as some boots, helmets and gloves (usually elevated/awakened ultra-endgame bases). Maybe the atlas expansion will change them.*

## INFLUENCED ITEMS:

> *NeverSink's notes: Influenced basetype tiering has been frustrating to handle based on economy data alone. The main reasons are that there's a huge variety of basetype-itemlevel-influence-cost combinations. This results in weird items entering the economy. Additionally crafted item, chancing bases and people misspricing made the economy-data frustrating to handle.*
>
> *This is a bit of a move of desperation and I already have a better system planned, but I'm done playing idiot-whack-a-mole and I hope so are you. I'm introducing a double blacklist in the economy tiering. The 'T1' blacklist forbids a base to ever enter T1 or T2 of the influenced tierlist. 'T2' items will receive a major cut to their 'confidence' value when tiering. The blacklist is mostly used on super low level bases.*
>
> *I will closely monitor the situation*

- Influenced item tiering now employ a two-tier-black-list to prevent pointless items from entering the economy tiering.
- The general influenced item tiering algorithm has been improved

## FRACTURED ITEMS:

> *NeverSink's notes: Fractured items are some of the most important crafting bases in the game. Previously I've been using a 3-tier approach, where the first tier is filtering by specific bases, the second tier by class and the third tier everything else. This approach had a bunch of issues, such as making filterblade editing complicated and also merging armor-types. For instance when the second tier was highlighting ALL fractured gloves, it'd also highlight low level fractured ES gloves, which are significantly less useful than the low-evasion based gloves, which can roll suppression.*
>
> *To improve the tiering, I'm adding a second basetype-based tier. This allows for a lot more precision and gives filterblade users more capabilities as well. I'm keeping the class-based tier around for exotic items, such as fractured heist bases, maps etc.*
>
> *Below you'll find the logic employed when adjusting the tiers*

- Reviewed all T1 and T2 fractured bases. They have all been retiered
- Generally: gear that can roll suppression has more bases highlighted
- Generally: energy shield and armor bases require higher basetypes to be highlighted
- Generally: most boots are highlighted, but T1 focuses on the better bases
- Generally: many helmets/gloves are highlighted, but T1 focuses on the better bases
- Generally: all rings, belts and amulets are highlighted among the T1/T2 bases
- Nearly all one handed fractured caster weapons are highlighted among the T1 and T2 tier. T1 tier focuses on the bases with the better implicits
- Most attack weapons are only shown if they're one of the best/meta bases (with the exception of some best T2 maces, axes, claws and some others). - A lot of bows and quivers are highlighted as well. T1 focuses on the better bases as usual.

## REMOVED SECTIONS: 
- Crucible crafting section has been removed
- Crucible currency section has been removed

## STYLE IMPROVEMENTS:
- Items that previously had a black background (0 0 0) now have a SLIGHTLY non-black one (20 20 0). In practice the game renders things still EXACTLY 100% black, probably due to some postprocessing uniqueness in POEs implementation. However, when hovering/selecting the item it will receive a distinct slightly-golden background! This makes looting slightly easier as it's easier to spot the hovered item! This effect is being applied as a post-processing layer during filter generation and is not part of the filter files/style files. If this looks weird or off to you please let me know. I'm especially interested in console/macOS feedback as I don't know how their rendering works

## STRICTNESS ADJUSTMENTS:

> *NeverSink's notes: I'm treating atlas bases more and more like other base, as they've been losing their position to fractured/eldritch and synthesized bases. The changes to the strictness here are a preparation for a larger full scale rarity/endgame crafting base items rework.*

- Increased the strictness on the filtering of 'perfection-bases' (itemlevel 86 armours with perfect base defense multiplier)
- Increased the strictness of atlas base filtering. Random normal atlas bases below itemlevel 86 are now hidden in the endgame on strict and above. You'll still stumble across occasional rare bases.
- T3 fractured items are now hidden on strict instead of very strict

> *NeverSink's notes: Over the years, I've been adding a lot of different special cases for jewels, as both jewel types have had their mod-pool expanded several times. The goal now is to give them a consistent and clear treatment: very strict removes pretty much all*

- Revamped the strictness of generic and abyss jewel rules
- Generic Jewels: Magic jewels are hidden on strict (68+)
- Generic Jewels: Magic jewels ILVL 1-68 are hidden on very strict
- Generic Jewels: Rare jewels are hidden on uber strict
- Abyss Jewels: Magic jewels ILVL1-68 are hidden on very strict (for leveling)
- Abyss Jewels: Magic jewels ILVL68-81 are hidden on strict
- Abyss Jewels: Magic jewels ILVL86+ are hidden on uber-plus-strict
- Abyss Jewels: Rare jewels ILVL1-85 are hidden on uber strict
- Abyss Jewels: Rare jewels 86+ are hidden on uber-plus-strict
- The filter now highlights any ILVL84 12 node large cluster jewel (until uber-plus-strict) independent of the economy data
- Not new, but important for next changes: The filter now highlights any ILVL84 8 node large cluster jewel (until uber-plus-strict) independent of the economy data
- 8-Node Large Cluster jewels that were NOT matched by economy data are hidden on uber-strict
- Random Large Cluster jewels are hidden on very strict
- Random Medium Cluster jewels are now hidden on very strict
- Random Small Cluster jewels are now hidden on very strict

## LEVELING ADJUSTMENTS:

> *NeverSink's notes: I noticed some minor inconsistencies during the very early levels of the campaign. This should help it feel better by unifying highlights and sizes*

- Magic items until level 9 have now slightly higher font size than before
- Small chromatic (RGB) items while leveling now have  higher font size
- Wands and sceptres have been added to the list of early-items (until level 9) that receive extra highlight when 3 sockets. Previously this list only included gloves, shields, boots and helmets.
- Until level 9 all random non-tiny magic items have a slightly stronger border
- Low level flasks (small, medium, large) are now displayed until a higher zone level.

## IDENTIFIED MOD FILTERING:
- Many identified mod filtering rules now also filter for 'negative mods'. For instnace identified boots rules will not highlight boots anymore with 4 good mods, but low tier movement speed. Similary an identified physical damage weapon, won't be highlighted if it has a very low tier flat phys mods, even if it has other good mods (this has been already part of 8.10.5, but now also affects the stable branch)

## FILTERBLADE:
- This filter supports adds further support to one of FilterBlade's coolest systems - custom rules! We've added and expanded support for duplicating, reording, renaming rules and much more. This was released ahead of time to get it test well.
- FilterBlade currency, divination and unique tierlists now support 'tags'. You can ui-filter by those on filterblade! These tags are sourced from a public repository on my github
- Dozens of small improvements to filterblade, such as a general customizer cleanup, performance improvements, loot simulator improvements etc.

## MISC CHANGES:

- Removed engraved ultimatum rule as it was made completely redundant by the unique map tierlist
- Added new gems into the +1 recipe sections
- Expanded a lot of check for the item to be uncorrupted with a unmirror check as well.
- Removed "Infused Engineer's Orb" as it doesn't drop anymore
- Removed some outdated no-longer-dropping incubators from the tierlists
- Endgame low strictness quality flasks are now only highlighted when normal
- Added a sectino to highlight stacked scarabs
- Lots of other minor adjustments

## ARCHITECTURE IMPROVEMENTS:
> *NeverSink's notes: In the coming monthes and year we'll be doing a lot of architecture/infrastructre adjustments to support 3 filters (poe1,poe2,mobile or more!) in the future, it's a major part of our roadmap now, but we believe the improvements will allow for a whole number of general benefits as well!*

- Improved the structure of the 'aspect' files that are used to economy-tier the filters
- Reworked the 'Waypoint' system within the filter. This system enables FilterBlade to use a ton of different locations for custom rules that are forward compatible with future filter update versions.
- Further improvements to filter structure and generation

----------------------------------
# **VERSION 8.10.4** - architecture update
----------------------------------

## SHORT OVERVIEW
This update implements mostly technical preparations to enable some future features and also implements some improvements to tiering and performance.

## TIERING ADJUSTMENTS:
- re-enabled unique jewels tiering. This currently only applies to (some) unique cluster jewels and all abyss jewels
- divination cards that award fragments and unique jewels now attempt to use the economy information about the card reward (+ the stack size and some other data) to figure out the price of the card and detect potential cases of noisy data or pricefixing in the economy data

## ARCHITECTURE IMPROVEMENTS
- Turned over 100 sections that were checking for basetype into equal match sections ( using the  '==' operators ). This should have no impact on the actual filtering, but will improve performance and reduce ambiguity (Highlighting "Saintly Chainmails" won't highlight "Sai"s anymore etc). This might cause some filterblade savestates to throw errors, if non-exact wording has been used to do changes.
- Essences, Oils, Incubators and Contracts have received a dedicated hide section. This is to enable users to use conditional operators (such as arealevel and stacksize) in the rules, without the remaining items appearing pink. New and unknown items will still be highlighted.

----------------------------------
# **VERSION 8.10.3a** - finetunings, fixes and economy
----------------------------------

## SHORT OVERVIEW

This update mostly contains structural improvements, cleanups and minor fixes.

## NEW RULES:
- Added a rule to detect 4-white socket triad grip gloves.

## TIERING ADJUSTMENTS:
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas and Gems.

## MISC IMPROVEMENTS AND FIXES:
- Fixed a bug where early endgame 4links (arealevel 68-71) with 4links would also match uniques. This only affected soft and regular strictness.
- Most places that have been requiring an item to not be corrupted also now require the non-mirrored state
- The low tier quality flask rule now requires the flask to be normal


----------------------------------
# **VERSION 8.10.3** - split six sockets, corrupted rule bugfix and misc adjustments
----------------------------------

## SHORT OVERVIEW

The new ID mod rule to detect potentially useful quivers and gloves lacked the class scope and was accidently showing a bunch of random corrupted items. Sorry. Fixed.

## NEW RULES:
- Split the 6Socket rule into 6S-4height and 6S-3height. The 4 height rule is disabled on very strict, the 3 height one on uber-strict. This will hopefully help smoothen the transition a bit.

## TIERING ADJUSTMENTS:
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas and Gems.
- Six-link rewarding div cards no longer can drop below T4 (previously T3), but are now treated as currency type cards (as random late-league random six link cards have barely any value beyond the 20 fusings). This also includes tabula cards. These cards have the 'earlyleague' aspect, so they'll go back to T3 (or higher) during the first days of the league, when 6-links are in high demand
- Moved artillery quivers from T3 to T2 in the crafting bases

## MISC RULES:
- Increased the strictness of the newly introduced quiver and glove rules (both with id-mod checking and without)
- Fixed a bug with the new ID mod rule for quivers and gloves that was showing all classes, instead of scoping on the right one resulting in some needless clutter. 

----------------------------------
# **VERSION 8.10.2** - Economy Update, Jewels, Breachstones, Corruptions and Enhanced Efficiency
----------------------------------

## SHORT OVERVIEW

This update includes economy-based adjustments, eco-updated breachstone tiering, improved filtering of influenced items, lots of tiering improvements and updated quality flask checks. It also brings tailored rules for identified quivers and gloves and 3x abyss socket shrouds. Also dozens of architecture enhancements to improve performance and potential edge cases have also been implemented, with special thanks to Mellontoss for valuable contributions.

I may have used chatgpt to build the title & short description above.

## NEW RULES:
- Added a section to specifically search for identified quivers and gloves with a few useful mods AND a corrupted implicit. The number of mods required is lower than with the regular identified mod section. Quivers require ilvl 80+
- Added a rule to highlight ilvl 80+ rare corrupted quivers with 1+ corrupted implicit. This rule is designed to help players find those sweet sweet chain-corrupted-quivers. The rule is disabled on uber strict.
- Added a rule to highlight 3x abyss socket shrouds

## STRICTNESS, TIERING AND ECONOMY RELATED IMPROVEMENTS:
- Breachstones are now also economy-tiered
- All tierlists have been adjusted based on the current economy:
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Breachstones, Replicas and Gems.
- Increased the threshhold price for T1 splinters (this will result in Xoph, Esh, Tul and Templar splinter moving from T1->T2 and changes to stacked splinters)
- Adjusted the meta-aspects for a bunch of div cards. This has a lot of small results, but most notably around ~20 T3 cards were downgraded to T4 or T4currency to improve tiering accuracy.
- Increased the tiering of 'regular' jewels to the T2 tier as almost all of those are worth something, often a lot. Additionally the corrupted jewel section now also tests if the jewel has exactly 0 corrupted implicits. All corrupted jewels with 1 or more corrupted implicits are the 'regular' expensive jewels! Yes this means that the alva-temple 'roomba' boss and the heist boss that drop cheap jewels will be baiting players.
- Slightly increased the highlight of corrupted jewels
- Slightly decreased the threshold for T2 uniques.
- Disabled the 2 rules for influenced rare items that were highlighting "top-droplevel" and atlas basetyped items. Instead all of the influenced data is now economy driven to improve the filtering of influenced items. The rules can be manually enabled on FilterBlade. We'll keep the situation under observation and might re-enable them if they are still needed.
- Implemented a few overrides for start-of-league scenarios that will help prevent currency from being overtiered in the future.
- Minor adjustments to unique and currency aspects

## MISC IMPROVEMENTS:
- Fractured bases are now only highlighted if they're not corrupted. This is to prevent the filter from highlighting corrupted bases that are not worth anything.
- Added gloves and quivers to the list of favored double corrupted rare items
- Double corrupted rares now have a red color, instead of the teal one
- High level overquality flasks are now checked starting with 26%+ quality instead of 29%+. While 26-28% is creatable with betrayal, those are still a welcome find.
- High level flasks now also check for being non-mirrored 
- The identified item handling rule for rares between T2 and T3 rares is now disabled on semi-strict instead of very strict. It was created during ultimatum when the game used to roll well rolled rares and filter idented-mod checking capabilities were still quite limited. Right now I don't know anyone really liking this rule.

## ARCHITECTURE IMPROVEMENTS:
- Designed a system to detect and remove outdated basetypes from tierlists. This removes items that no longer drop (such as disabled divination cards).
- Standardized the show/hide/disable ruling in a lot of rules. Most crafting and exotic bases rule now tend to use disable, instead of hide to prevent accidental hiding of items that are actually worth something. This is an ongoing process.
- Done a large series of improvements related to filter parsing performance, filter generation and filterblade related changes. This usually includes changes like sorting of rules, usage of "==" operators and sorting of selectors within the rules.
- Most rules that check for "Corrupted False" now also check for "Mirrored False"
- Special thanks to Mellontoss for helping out with this update, he has collected a large number of various improvements!

----------------------------------
# **VERSION 8.10.1** - Economy Update
----------------------------------

## SHORT OVERVIEW
Improves the tiering of all tierlsits. Also fixed the filter economy update/generation scripts, that were broken by GGG's APIs changing.

## GENERAL
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.

## ARCHITECTURE
- Fixed the filter economy update/generation scripts, that were broken by GGG's APIs changing.
- Added additional checks to the filter economy update/generation scripts to prevent future issues.

----------------------------------
# **VERSION 8.10.0** - CRUCIBLE LEAGUE
----------------------------------

## SHORT OVERVIEW
All the crucible content has been added! Importantly: we added a new section that is specifically there to highlight some white/magic items in the endgame to have some food for the crucible forge/krangler. Currently this section contains generally good bases or bases that share a good unique (for the chance of a unique sell node). The current list is: "Convoking Wand" "Champion Kite Shield" "Spine Bow" "Imperial Claw" "Opal Sceptre" "Prophecy Wand" "Short Bow" "Siege Axe". You can customize it on FilterBlade. This rule is disabled on Very strict.

This patch contains MAJOR tiering improvements to unique, divination card and other tiering types and a TON of other changes (check the patch notes for more info). It also contains major improvements to the FilterBlade UI and FilterBlade meta data!

Good luck in the crucible league!

## NEW LEAGUE ITEMS
- Added the new crucible currencies
- Added a section to highlight items (rare or lower) with crucible trees (these should not drop by default, but I've learned that things tend to change over time, so it's good to be on the safe side)
- Added a section to highlight items (unique) with crucible trees (these should not drop by default, but I've learned that things tend to change over time, so it's good to be on the safe side)
- Added new divination cards
- Added a new section that is specifically there to highlight some white/magic items in the endgame to have some food for the crucible forge/krangler. Currently this section contains generally good bases or bases that share a good unique (for the chance of a unique sell node). The current list is: "Convoking Wand" "Champion Kite Shield" "Spine Bow" "Imperial Claw" "Opal Sceptre" "Prophecy Wand" "Short Bow" "Siege Axe". You can cusotmize it on FilterBlade. This rule is disabled on Very strict.
- Added special tiering to new uniques

## MAJOR FILTERBLADE IMPROVEMENTS
- Tierlists hover-information is vastly improved. It contains additional data, filters out relics and is much more concise.
- Tierlists now can show extra-data about a certain item or a specific unique. This is for instance used to visualize where a certain unique drops, the rewards of incubators etc. Also it just looks really rad.
- Reworked all hover-UIs on FilterBlade. These are much more concise and useful now

## LEAGUE RELATED ADJUSTMENTS
- Added a section to detect maps with 'implicit' mods that can drop under some circumstances (like the shadow shaping node)
- Removed the 'of Unwavering' abyss jewel ID detection mod
- Removed 'Serpent Wand' that was causing issues with the new patch for some reason
- Renamed 'The Iron Bard' divination card
- Moved breachstones to it's own tierlist

## MAP LIKE ITEM CHANGES
- Disabled the section for detecting nemesis+beyond maps as this combo no longer has any value after the last 2 leagues

## UNIQUE TIERING
- Made a ton of adjustments to the unique tiering aspects (meta-information).
- Reviewed and adjusted the tiering strategy for a lot of uniques. This includes over 50 aspect changes and will improve tiering in many cases!
- Removed a bunch of aspects from no-longer-dropping uniques. This will lead to a bunch of uniques that were previously landing in the "non-drop-category" to land into the hideable category
- Cleaned up and added special exceptions to handle no longer dropping basetypes and race rewards better.
- A huge thank you to @mellontoss for compiling tons of data and suggestions for the unique changes!
- Added an exception to highlight starforge/voidforge drops based on their influence! Note that we can't recommend disabling unique infernal sword drops as Echoforge can't be detected.
- Revamped the algorithm to be slightly more exclusive when it comes to 'semi-expensive' and 'multi-base' uniques. Items found in this section should be significantly better than the hidable uniques on average.
- Improved the 'early league unique tiering'. Cleaned up the list of early league uniques to be a bit more strict.
- Marked most abyss and most breach items as 'buffed'. They'll be tiered slightly better than their previous tiering was in the last league and are not allowed to enter the 'hideable' uniques during the first days of the league.
- Marked all sanctum items as 'non-drop'
- Slightly increased the divine price component of the price requirement for T1 uniques
- Slightly increased the price requirement for multibase uniques
- Slightly increased the price scaling for semi-expensive uniques

## DIVINATION CARD ALGORITHM
- I scrapped the old algorithm and rewrote it from scratch. Divination card tiering data coming from the economy is still dirtier than the infinite hunger fight, but the new algorthm seems be performing much better overall.
- Cleaned and improved the aspects (meta-information) of the divination cards. This should lead to some improved tiering in some niche cases.
- The Lingering Remnants Divination card is no longer allowed to drop below T4

## UNIQUE JEWEL TIERING
- [DISABLED, feature will be readded soon] Added minimal unique jewel tiering where possible. In the case of most jewels this does not work as too many jewels share the same base. However, some jewels such as abyss jewels are now economy-tiered.
- Rational doctrine drops are now highlighted as T1 (using the fact that they're the only synthesised jewel)
- Megalomaniac jewel moved to T2 from multibase

## OTHER TIERING CHANGES
- Standardized and clean up all tiering algorithms. This should lead to a more consistent tiering in the future.
- Breachstones and splinters have received some temporary adjustments to improve their tiering in regards to the 3.21 changes
- Further improved cluster jewel tiering. The tiering algorithm is now more reluctant to put cluster jewels into the T1 category during the early league (as the data is super hazy)

## MISC CHANGES
- Added a new section on FilterBlade (and a disabled by default rule in the filter) that highlights quality minion gems for +1 helmet recipes!
- Added 3.21 and 3.20 gems to the +1 recipe highlight sections
- Increased the stack size requirement on all simulacrum splinters to create high tier sounds/highlights.
- Removed a bunch of unique map bases that no longer drop
- Removed lures from the fragment tab as these no longer drop ingame.
- Added new abyss mods to the identified abyss jewel section

----------------------------------
# **VERSION 8.9.6** - Voidborne keys, Corrupted uniques and minor modifications
----------------------------------

## SHORT OVERVIEW

Added voidborne keys, improved the tiering of gems and corrupted uniques and made some minor modifications to the filter.

## GENERAL
- Added highlight for the voidborne reliquary keys.
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.

## UNIQUE TIERING
- Added a new rule to highlight corrupted uniques that would otherwise be caught by the T3/T4 uniques section. This rule is disabled on uber strict. The rule currently highlights the following classes:  "Amulets" "Belts" "Boots" "Gloves" "Helmets" "Rings" "Shields" "Quivers". Weapons/body armours are excluded - due to the low usage rate of random-non-expensive unique weapons with single corruptions and the need to 6socket/link these. Note that ALL double corrupted items were and are still highlighted, no matter the class

## GEM TIERING
- Improved the gem tiering algorithm in multiple was
- The gem tiering rule for 20/20 gems, now only highlights uncorrupted gems
- The gem tiering rule for 21/20+ and 20/23+ gems now includes gems that both pass and don't pass the 20/20 test
- Removed the 21/23 tiering rule as these gems don't drop naturally anymore. These gems are highlighted 
- Added a general 21/23 rule that highlights any 21/23 gem

## MISC CHANGES
- Further Improved the algorithms for divination card and stacked currency tiering.
- Increased the strictness of exarch/eater rares. They're now all hidden on very strict.

----------------------------------
# **VERSION 8.9.5** - Over-Quality Flasks (eco-update only)
----------------------------------

## SHORT OVERVIEW

Addresses the discovery of flasks now dropping naturally (from rares) with up to 30% quality.

This update only affects eco-updated filters. Stable version is not affected.

## GENERAL CHANGES
- Added a new rule that highlights the best life/mana and all util flasks of ilvl82 with 29%+ quality.

----------------------------------
# **VERSION 8.9.4** - Adjustments for weird 200+ divine economy (eco-update only)
----------------------------------

## SHORT OVERVIEW

This patch fixes some problems with economy updated filters, related to stacked and currencies and some anomalies related to the 200c+ economy. 

This update only affects eco-updated filters. Stable version is not affected.

## GENERAL CHANGES
- Reworked the handling of stacked currencies. They're now using exactly the same threshhold as the non-stacked currencies.
- Slightly increased the minimum threshhold for T1 currencies (50->60). This is mostly to prevent elevated sextants and single fracturing orbs from dinging on maven kills. If they rise even further - well, the economy has spoken :p.
- Increased the minimum threshhold for T3 currencies from 3.0c to 3.1c. While this may sound small, this will lead to currencies that claim to be 'exactly' 1c (but usually are below from experience), to not be able to reach the T3 tier if dropped in stacks of 3+
- Introduced a bunch of other improvements related to chaos prices rising over 200+ and causing tiering anomalies. If all fails, the generator will assume that the chaos price is 200c for the sake for tiering uniques and divination cards (only if the chaos price is above 200c).

----------------------------------
# **VERSION 8.9.3** - New Sanctum Items
----------------------------------

## SHORT OVERVIEW

This patch adds new unique relics and invocations dropped by Lycia at the end of the sanctum to the filter. For now they're all added with the exalted orb tier, but they're not hidden on any strictness

## GENERAL CHANGES
- Added new invocations to the filter
- Added a virtual tierlist to the invocations - the structure for the tierlist is already there, but it does not tier anything yet (until invocation economy data will be available)
- Added a section for the new unique relics
- Did nothing for the new original sin ring as it'll be already highlighted, just letting you know it's all good :)
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.

----------------------------------
# **VERSION 8.9.2** - Better fractured, influenced, unique and cluster jewel tiering
----------------------------------

## SHORT OVERVIEW

Sanctum has changed a lot of aspects in regards to droprates and economy. This update focuses on improving the economy tiering to reflect the new meta.

On top of general tiering improvement I've overhauled the treatment of: fractured items, cluster jewels, influenced items and boss-dropped uniques.

Feedback is always appreciated. Please let me know if you think something is wrong or missing or needs updating.

## GENERAL CHANGES
- Made all economy based T2 tiers slightly less strict (dominant orb scaling factor changed from 0.25 to 0.2). This will lead to a few more items being caught by the 'exalted orb tier' (prev. divine orb tier: the goonng, not the shwing sound).
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.

## FRACTURED ITEM TIERING OVERHAUL
- Motivation behind changes:
    - Fractured items drop fairly frequently in very large batches. Sorting through these is cumbersome
    - The previous handpicked bases valued the basetype tier too much over the basetype class.
- Reworked the tiering for fractured bases:
    - T1 - handpicked bases
        - Filter by basetype and are now more inclusive. These include most wands, sceptres and significantly more bases that can roll suppression. These also favour boots and shields over helmets, body armours and gloves (even though top items are still highlighted). They also now include amulets, belts and rings, which were previously only caught through the class based fractured tiering. They feature less staves and other mostly physically played bases.
        - Now have stronger highlighting
        - Shown on all strictnesses
    - T2 - class based filtering. Shows all bases as long as they're part of the class
        - Currently includes: "Amulets" "Belts" "Boots" "Bows" "Flask" "Gloves" "Heist" "Jewel" "Maps" "Shields" "Quivers" "Rings" "Rune Daggers" "Sceptres" "Wands". 
        - Shown on all strictnesses except on uber-plus-strict
    - T3 fractured bases - all other fractured items:
        - Now hidden on very strict
- While the system is flexible, it's not perfect by any means. I'm reliant on your feedback to get it right. Please let me know if you think something is wrong or missing or needs updating.

## UNIQUE TIERING
- Added special treatment to the internal 'HighVariety' tag on unqiues. If a unique that drops from a boss has this tag it will never be allowed to drop below the 'boss-drop-uniques' tier. This will prevent items that end up super cheap in certain scenarios, but expensive in others (such as cinderswallow urn depending upon if it's unveiled or not) from dropping to a lower tier.
- Added a special treatment for uniques that only consist of non-world-drops (such as unique boss drops)
- Expanded the additional protection to new/unknown uniques

## INFLUENCED TIERING OVERHAUL
- Motivation behind changes:
    - The general number of uses for shaper/elder/conqueror items has gone down and so did their demand as most meta builds run a lot more fractured+eldritch or unique items in their equipment. Still certain influenced items are still quite valuable - just are less of a chase base as they were before
    - On top of that these items are more accessable and drop in bulk at a high level from conqueror/shaper/elder maps and invitations.
    - The player is generally a bit overloaded with the number of drops
- Specific changes:
    - T1 drops:
        - Now all produce an 'exalted orb' sound (T2)
    - T2 drops: 
        - No longer produces the 'exalted orb' sound, but instead play the unique sound. These are generally good items that MAY sell, but no longer a near garantueed money maker as it was leagues before
        - Changed the T2 common useful influenced bases section to require ILVL 84 instead of ILVL 86
        - Changed the T2 common useful influenced bases section to T1+T2 basetypes from the general rare section. In layman's terms: the filter will highlight best crafting bases, such as vaal regalias, two-stone rings and eternal burgonets as T2 drops, if they're ILVL 85 and are influenced.
            - This rule is disabled on uber-strict
            - Uber-strict will only use economy based information to determine if an item is a T2 drop
            - T2 drops from economy tiering will still be shown on uber-strict
        - Reduced the threshhold for T2 drops

## CLUSTER JEWEL TIERING OVERHAUL
- Vastly improved cluster jewel tiering and done a lot of cleanup in the economy updater.
- On top of a general cleanup and improvements. fixed a bug that caused previously expensive cluster jewels to 'stick around' in the tierlist. It will now detect a lot less false positives.
- With the problem above fixed, reduced the threshhold for expensive cluster jewels.

----------------------------------
# **VERSION 8.9.1** - Economy improvements
----------------------------------

## SHORT OVERVIEW

Overall I'm quite happy with the performance of the filter. The general filtering and strictness adjustments feel quite good to me. 

This update mostly focuses on the economy side of things, integrating the new divination cards and giving treatment to all the new uniques.

On top of that I've added an algorithm to improve the handling of new uniques at the start of the league, which should help with situations like the new uber-sirus flask.

## TIERING CHANGES
- Integrated all of the new unique items into the economy tiering
- Integrated all of the new divination cards into the economy tiering
- Improved handling for Fracturing Orbs and shards.
- Introduced a much more sophisticated special algorithm that will prevent expensive new unknown uniques to be handled incorrectly. The algorithm will treat previously unknown uniques on an already known unique basetype as bossdrops until further checking. In practice the economy updater will know how to handle items like the uber-sirus flask better in the future

## MINOR CHANGES

- Fixed a bug where stacked portal and stacked wisdom scrolls while leveling had their highlights swapped.

----------------------------------
# **VERSION 8.9.0a** - Forbidden Sanctum, Ruthless Version, Tiering and Leveling improvements
----------------------------------

## SHORT OVERVIEW

Improved the tiering of some good divination cards for early league.

## STRICTNESS CHANGES

- Moved some divination cards to the early league tier

----------------------------------
# **VERSION 8.9.0** - Forbidden Sanctum, Ruthless Version, Tiering and Leveling improvements
----------------------------------

## SHORT OVERVIEW

This update implements necessary Forbidden Sanctum logic, a ruthless version of the filter, tiering improvements and leveling improvements. It also features a whole bunch of other changes big and small and a plethora of improvements to FilterBlade!

We've put a lot of work into this patch and hope you're just as excited for the upcoming league!

[We also made visual Summary of the most important changes!](https://imgur.com/a/RBtVsqr)

## FORBIDDEN SANCTUM
- Added a new section for the highlight of sanctified and normal relics. As of now all relics are shown on all strictness.
- Introduced Fracturing orbs and shards into the filter

## RUTHLESS FILTER
- We've added a ruthless-specific filter to FilterBlade. Behind the scenes, it's technically my 'semi-strict regular' filter with around ~1000 changes to finetune everything to the ruthless playstyle. As of now it's only available on FilterBlade and does not support styles and strictnesses as it changes too much for those to work correctly. Depending on the popularity of ruthless we might change the acquisition method, structure or even remake the filter in the future. As ruthless is more targetted at experienced players the user is fully expected to make their own adjustments to the filter on filterblade.
- When the Ruthless filter is selected, every 'hide' rule is automatically converted into a 'minimal' rule and the ruthless-filter is exported in the right format.
- We'll likely allow converting normal filters into ruthless format on FilterBlade in the future. For now this is disabled as using my regular filter on Ruthless will likely result in a bad experience (and we havn't finished the UI yet).

## TIERING IMPROVEMENTS
- Reworked the algorithm for divination card tiering. It has a much stronger bias against cards marked with internal "poordrop" and "lateleaguevalueloss" aspects. The result of this is that dozens of cards (such as 'the web', 'the oppulent'...) will be tiered lower than before. This only affects cards that were previously in T4.
- The compass item has been 'anchored' to the chaos tier. I'm not sure why it was rising in price (pricefixers?), since you can buy it from Kirac, but no more of that within the filter.
- Reviewed uniques and divination cards with the new and rebalanced unique in mind
- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.
- Added a new section for corrupted jewels. It uses the old appearance.
- The normal jewel section uses the multibase appearance now!

## CURRENCY STRICTNESS CHANGES
- The strictness of currency tiering has been rebalanced on the lower end. This has been done to compensate for the lost of the 'necromancer' quality currency convertion effect and to make the filter more consistent.
- The following changes specifically apply to 'supplies-tier currency' in the endgame (NOT leveling!): wisdoms, portals, armourer, transmutes, augments, whetstones
    - Stacksizes for supplies have been adjusted: small stacks are 3-5, medium stacks are 6-10, large stacks are 10+ items.
    - Regular: all shown
    - Semi-Strict: all stacks shown. Single portals, wisdoms, armourers hidden.
    - Strict: all singles hidden, all small stacks hidden.
    - Very-Strict: all singles hidden, medium portal/wisdom stacks hidden. small armourers/whetstones hidden. At this strictness level most players will and are expected to use thier large transmutes/blacksmith whetstones supplies to convert to scrolls if needed.
    - Uber-Strict: all non-large stacks are hidden
    - Uber-Plus-Strict: all supplies are hidden.

## LEVELING ADJUSTMETNS
- Standardized a lot of fontsizes during leveling. The goal is to clearly prioritize important drops, while keeping the screen clean. The General philosophy behind this rework: 
    - FontSize 45 items are outstanding pickups such as rare boots, rare jewellery, utility flasks, 4links
    - FontSize 40 are useful pickups, such as 3links early on, random rares, life flasks etc
    - FontSize 35 are other things, such as 3links later on, potential crafting pickups, vendor magic items etc.
- Flask, currency and other items are still highlighted in the old way
- Early level normal body armours (without 3+ sockets) are now shown again from level 2-9 during campaign. They're still hidden on strict+. The motivation behind this change is to not force racing-like optimizations (slower movementspeed with body equipped) to new players who start with semi-strict, which is now the default on filterblade.
- Added a new section to highlight magic items between zone level 1 and 4 in a larger font
- Thrusting one hand swords added to default item progression (fix, previously only shown normal swords)
- Added a dedicated section for highlighting stacks (3+) of wisdoms, portals, armourer, transmutes, augments, whetstones during leveling.
- Added a dedicated section for highlighting jewels during leveling

## FILTERBLADE CHANGES (short overview, full changelog in discord)
- Added ruthless support
- Implemented highlighting by total socket count and color (independent of links). Very useful for leveling.
- Reworked class selection UI
- Improved and sorted many UIs
- Added a ton of other polish and fixes. Check the changelog in discord for more details.

## OTHER STRICTNESS CHANGES
- ILVL84 T2 engame normal and rare crafting items (ok, it's a mouthful, something like level 84 normal vaal regalias) are no longer highlighted on strict. This does not apply on exotic bases (atlas bases, runic bases...) or items of ILVL86+
- Reviewed the flask tiering and adjusted it, now that the flask-splosion is gone
- Decreased the strictness on scarab tiering. Only uber-plus stirct now hides the lowest economy based tier of scarabs
- All non-unique 6L armours/weapons now have the same 'red' appearance, they no longer get the T1 appearance and 'shwing' sound
- Medium sized chrom recipes in the endgame are hidden on regular, instead of semi-strict
- Adjusted the strictnesses of some identified mod filtering rules. This shouldn't affect anything below uber-strict.
- The high quality gem section has been changed from 19 to 20 quality

## MINOR CHANGES
- Removed 2 unused rules for High tier exarch/eater items that were highlighting lvl 5+ items. These items don't drop naturally.
- Identified DOT jewels are now limitted and require exactly one specific dot mod.
- Improved delve mod magic item higlighting.
- Split the crafting decorator for normal/magic gear in the endgame into a jewellery and non-jewellery section

----------------------------------
# **VERSION 8.8.3** - Economy update, strictness and tiering adjustments
----------------------------------

## SHORT OVERVIEW

The major changes in image form: [https://imgur.com/a/zCGNanx](https://imgur.com/a/zCGNanx)!

Overall I'm quite happy with the current state of the filter. Most non-tiering sections seem to be operating really well. However, the devil is frequently in the detail. This update fleshes out a bunch of small scale detail interactions, polishes up the strictness, improves tierlist generation, refines fractured, identified and synthesised mod highlight and in general puts some love into all of the small details that you'd expect from a quality product.

## TIERING IMPROVEMENTS

- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.
- Improved the tiering algorithm to ignore relic items for the pricing of uniques
- Reworked the unique map tiering algorithm. It should place more maps into the T4 tier, unless it's the start of a new league
- Given ascetic and black sun crest (their unique basetypes to be precise) a more favorable treatment due to high rolled ones being very expensive.
- Awakened gems now have a much higher T1 threshhold. Context: if you find a divination card worth 50c, you're happy about the find. If you find a awakened gem worth 50c, you definitely don't want to hear the 'shwing' sound.
- Added a ton of improved handling for divination cards - such as unique sceptres/wands that are sometimes turned in on low level to create low level high quality bases for crafting.

## IDENTIFIED MOD FILTERING
- ID-Mod abyss jewels now consider T3 life to be a good core mod, not just T1 and T2 life.
- Identified +2 to all minion gems helmets are being detected
- +1/+2 minion gems are now being detected as part of the 'valuable mod combination'

## FRACTURED / SYNTHESISED ITEMS

- Adjusted the class list of extra-highlighted fractured classes. Added fractured flasks. Added fractured heist items. 
- Adjusted the basetype lists of extra-highlighted fractured items. The list now features many more evasion items.
- Adjusted thc class list of extra-highlighted synth classes

## STRICTNESS

- random 19%+ qual gems lose their highlight on uber strict (hidden on uber+ strict as before)
- the loreweave ring recipe highlight is now disabled by default and can be enabled on filterblade
- the high level agnerod staff extra highlight is now disabled by default and can be enabled on filterblade
- I'm intentionally not changing anything to the highlight/strictness of stacked blacksmith/armorer scraps and endgame flask highlight yet. These only occure during specific archnemesis fights and I hope these will change/be adressed (copium?). Plus I want you to know what happened to your last solaris touched mob.
- Increased the strictness on the 3 white socket weapon highlight.
- The lowest tier of talismans (random talismans without any noteworthy mods) are now hidden on semi-strict, instead of strict
- Stacked low tier divination cards are disabled instead of hidden on uber-strict

----------------------------------
# **VERSION 8.8.2** - Economy update
----------------------------------

## SHORT OVERVIEW

This is the first economy update for the kalandra league. We've retiered all existing items and have added the new uniques and content into the tierlists. Additionally there are some small fixes and improvements

## DETAILS

- All tierlists have been adjusted based on the current economy
    - This currently includes the following tierlists: Uniques, Divination Cards, Fragments (incl. splinters), Currency (incl. stacked currency and shards), Scarabs, Unique Maps, Fossils, Incubators, Oils, Vials, Delirium Orbs, Invitations, Influenced Items, Expensive Atlas Bases, Cluster Jewels, Replicas and Gems.
- Added new uniques to the tiering algorithm
- Moved the convoking wand from "atlas bases" to regular bases (as this was changed in 3.19)
- Glued house of mirrors and some other cards to T1, previously it was allowed to drop down to T3 (but not lower).
- Sacred lifeforce is now economy tiered

----------------------------------
# **VERSION 8.8.1** - Divine Orb Improvement
----------------------------------

## SHORT OVERVIEW

Since the current economy data was unavailable divines orb ended up in T2 instead of T1. Technically not a drama, but I've an override to prevent this from happening. willremove it later.

----------------------------------
# **VERSION 8.8.0** - Lake of Kalandra League
----------------------------------

## SHORT OVERVIEW

FilterBlade received a bunch of small and large upgrades. Most notably a much faster workflow: We made a 4 min video about it - https://www.youtube.com/watch?v=RA27aUdWQb8 . Highly recommended to watch.

## MAJOR FEATURES / SUMMARY
- Introduced all the new items added from the Mirror of Kalandra league
- Added the new ALLOY style. This is available on FilterBlade and features a unique color scheme and a metallic-alloy-inspired value tiering system.
- Reworked the filter generation in regards to how Divine/Exalted orbs are treated. At the start both orbs will be in T1. My filters used a fraction of the ex-orb price to scale the tier thresholds in all tierlists. Instead my filter will now be calculating that fraction based on the higher of the two prices (exalted or divine orb). 
- Marked all reworked and new uniques with a special tag for the filter generation. Tagged uniques are will be tiered slightly more beneficial than untagged uniques in the initial 3.19 filter. On top of that the uniques also have special tags for 'buffed', 'strongly buffed' and 'nerfed' uniques which protects these uniques to drop below/above a certain tier during the filter generation at the stat of the 3.19 league.
- Most exotic high orbs are no longer tied to their tiers. That means Exalted Orbs, Divine Orbs, Conqueror Orbs and Domination orbs etc. could now also theoratically drop into T2, if their price drops low enough. None of the aformentioned orbs is allowed to drop beyond T2 to prevent scenarios where automation potentially fails. This does not include Mirrors and Mirror Shards. These are anchored and don't care about the economic situation.
- Adjusted divination cards related to buffed uniques and exalted/divine orbs
- The filter generation algorithm now attempts to 'resolve' divination card prices. Oversimplified: It looks at the current price of the card, stacksize, rewardcount and compares it to the price of the actual reward. If there's a significant difference, it will prefere the reward price, as divination cards seem to contain a lot of faulty economy and there's way more price fixing going on as well.
- Massive changes and improvements to the FilterBlade workflow (details below)
- Reworked gem tiering. Details below.
- Reworked flask highlight. Details below.
- Added the new minion basetypes. From my current *cough* 'understanding' these are not atlas bases, but general bases you will find all around in the world.
- Disabled most of the recombinator specific rules designed for the sentinel league (since recombinators are now gone). Kept the top mod rules active, but added the uncorrupted requirements. The rules can be reenabled on filterblade.
- Reworked the identified mod filtering for jewels + abyss. The new rules can very well detect powerful DOT/Crit/Spellcrit/Minion/Damage jewels and generally good combinations. Thanks a lot to CDR for the help on this. These rules were very tough to narrow down and are among the most advanced things in the filter (as ridiculous as it may sound)

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

## FILTERBLADE - NEW WORKFLOW
- The general filterblade workflow has been completely redesigned. The new workflow is much more straight forward and faster. 
- FilterBlade now merges the concepts of 'saves' and 'filters'. Whenever you sync/download a filter it also updates your save. This means you don't have to save manually anymore, you won't accidently override the wrong save etc. It's also just much more intuitive.
- The save/load tab has been renamed to 'my filters'. It's also opened by default if you have any saves already.
- Saves now remember your 'sync target'. This makes saving by syncing a much faster and straightforward process
- All features still exist and work. We did remove the 'save' button though, as it's not really needed anymore and we don't want users to think that they should.

## FILTERBLADE - OTHER FEATURES:
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

## OTHER CHANGES:
- Added a rule to extra highlight Orbs of Binding during leveling.
- Added a new rule to highlight mininion items while leveling with a special purple highlight
- Added two new rules to highlight 3S whitesocket one handed weapons and 6S whitesocket 2handed weapons.
- Added a new section that highlights stacks of divination cards. It overrides the tiers T5/T4/T4currency and requires a stacksize of 3+ to be highlighted.
- Merged the Labyrinth offering items with the generic fragment tierlist. These items are now economy tiered. Removed the old secetions.
- Reduces the strictness on T3 fragments (uber plus strict reduces their highlight now, instead of hiding)
- The high level agnerod staff rule is now disabled by default as vinktar square is no longer interesting for the atlas.
- Move the anchored divination cards "Chaotic Disposition" "The Void" from T2 to T3.
- Added a misc rule to highlight heist quest contracts
- Completely reworked the +1 gem recipe section - thanks to "Mellontoss" and the discord community for the help! 
- Cleaned up the github repository, deleted a lot of old and outdated files, improved descriptions and readme files
- The filter now uses the enum-rarity format instead of the operator rarity format. This simplifies filterblade handling and is more precise.
- Removed and merged a lot of old rules

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

- ZoeyFloat/Haggis for their amazing contribution to the project development and support
- GGG for the awesome game with a special shoutout to Bex, Chris, Rory, Zeyra and Jatin for their assistance!
- A massive thank you to all the [PATREONS](https://www.patreon.com/Neversink), [DISCORD](https://discord.gg/mye6xhF) and [TWITCH](https://www.twitch.tv/neversink) community!
- The FilterBlade Team on discord - Abyxcos, Cdr, Mellontoss, Really Evil bunny, TarrasqueSorcerer, Thesenzei, VenomsAssassin
- The community (that includes you!) for using the filter and providing feedback and support!
