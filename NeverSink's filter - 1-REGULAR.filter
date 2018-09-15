#===============================================================================================================
# NeverSink's Indepth Loot Filter - for Path of Exile
#===============================================================================================================
# VERSION:		6.33
# TYPE:			1-REGULAR
# STYLE:		NORMAL
# AUTHOR:		NeverSink
# BUILDNOTES:	Filter improved with NeverSink's Filterpolish tool (v0.5)
#
#------------------------------------
# LINKS TO LATEST VERSION / REPOSITORY / FILTER EDITOR:
#------------------------------------
#
# EDIT/CUSTOMIZE FILTER ON: 	http://www.FilterBlade.xyz
# GET THE LATEST VERSION ON: 	http://www.FilterBlade.xyz or https://github.com/NeverSinkDev/NeverSink-Filter
# DETAILED EXPLANATIONS: 		https://goo.gl/oQn4EN
#
#------------------------------------
# LINKS TO LATEST VERSION / REPOSITORY / FILTER EDITOR:
#------------------------------------
#
# SUPPORT ME ON PATREON: 		https://www.patreon.com/Neversink
# SUPPORT THE FILTERBLADE TEAM: http://www.filterblade.xyz/About
#
#------------------------------------
# INSTALLATION / UPDATE :
#------------------------------------
#
# 0) It's recommended to check for updates once a month or at least before new leagues, to receive economy finetuning and new features!
# 1) Paste this file into the following folder: %userprofile%/Documents/My Games/Path of Exile
# 2) INGAME: Escape -> Options -> UI -> Scroll down -> Select the filter from the Dropdown box
#
#------------------------------------
# CONTACT - if you want to get notifications about updates or just get in touch:
#------------------------------------
# PLEASE READ THE FAQ ON https://goo.gl/oQn4EN BEFORE ASKING QUESTIONS
#
# TWITTER: @NeverSinkGaming
# REDDIT:  NeverSinkDev
# GITHUB:  NeverSinkDev
# EMAIL :  NeverSinkGaming-at-gmail.com

#===============================================================================================================
#[WELCOME] TABLE OF CONTENTS + QUICKJUMP TABLE
#===============================================================================================================
#
# [[0100]] OVERRIDE AREA 1 - Override ALL rules here
# [[0200]] 6 LINKS
# [[0300]] SHAPER ITEMS
#   [0301] Exception Handling - Rings, Amulets, Belts
#   [0302] Shaper Item Layers - T1
#   [0303] Shaper Item Layers - T2
#   [0304] Shaper Item Layers - T3
# [[0400]] ELDER ITEMS
#   [0401] Exception Handling - Rings, Amulets, Belts
#   [0402] Elder Item Layers - T1
#   [0403] Elder Item Layers - T2
#   [0404] Elder Item Layers - T3
# [[0500]] Explicit Mod filtering
#   [0501] League-Specific Magic Items
#   [0502] Magic Mod Permutations
#   [0503] Rare Item Permutations
# [[0600]] Explicit Mod filtering - EXPERIMENTAL
#   [0601] Rare Item Permutations
#   [0602] Weapons-Physical (Key: IPD)
#   [0603] The Suffix Abomination
#   [0604] Casters
# [[0700]] Recipes, Magic and Normal items (endgame!)
#   [0701] Overqualitied Items
#   [0702] 5-Linked items
#   [0703] 6-Socket Items
#   [0704] Exclusive bases: Stygian Vise
#   [0705] Abyss Jewels (Rare and Magic)
#   [0706] Exclusive bases: Top Value
#   [0707] Exclusive bases: Trinkets
#   [0708] Exclusive bases: Others
#   [0709] Corrupted Amulets
#   [0710] Chancing items
#   [0711] FLASKS (Endgame rules)
#   [0712] Add your own crafting rules here
#   [0713] 86+ Endgame crafting rules
#   [0714] 83/84+ Endgame crafting rules
#   [0715] 60+ Crafting rules for 60++ trinkets
#   [0716] Remaining crafting rules - add your own bases here!
#   [0717] Chisel recipe items
#   [0718] Fishing Rod
#   [0719] SRS Crude Bow
#   [0720] Chromatic recipe items ("RGB Recipe")
#   [0721] Endgame-start 4-links
#   [0722] Animate Weapon script - deactivated by default
#   [0723] W-soc offhand weapons
#   [0724] Sacrificial Garb
# [[0800]] HIDE LAYER 1 - MAGIC AND NORMAL ITEMS
# [[0900]] Currency - PART 1 - Common currency
# [[1000]] OVERRIDE AREA 2 - Override the default rare rulesets here
# [[1100]] RARE ITEMS - TRINKETS (ENDGAME)
#   [1101] Rare trinkets 86+
#   [1102] Rare trinkets 84+
#   [1103] Breach Rings
#   [1104] Rare trinkets "remaining"
# [[1200]] RARE ITEMS - WEAPONS AND ARMORS (ENDGAME)
#   [1201] Rare crafting bases 86+
#   [1202] Rare crafting bases 83+
#   [1203] T1 rare items
#   [1204] T2 rare items
#   [1205] Other Conditions
#   [1206] 1H Daggers
#   [1207] 1H Claws
#   [1208] 1H Wands
#   [1209] 1H Foils
#   [1210] 1H Swords
#   [1211] 1H Maces
#   [1212] 1H Axes
#   [1213] 1H Sceptres
#   [1214] 2H Staves
#   [1215] 2H Swords, Axes, Maces
#   [1216] 2H Bows
#   [1217] AR: Gloves, Boots, Helmets
#   [1218] AR: Body Armors
#   [1219] OH: Shields
#   [1220] OH: Quivers
# [[1300]] HIDE LAYER 2 - RARE ITEMS (65+ ONLY FOR NON-REGULAR VERSIONS)
# [[1400]] OVERRIDE AREA 3 - Override Map, Gem and Flask drops here
# [[1500]] Gems
#   [1501] Special Gems
#   [1502] Top Gems
#   [1503] Quality Gems
#   [1504] Leveled Gems
#   [1505] Other gems
# [[1600]] UTILITY FLASKS (Levelling Rules)
# [[1700]] HIDE LAYER 3: Random Endgame Flasks
# [[1800]] Maps, fragments and labyrinth items
#   [1801] Unique Maps
#   [1802] Labyrinth items, Offerings
#   [1803] Shaped Maps
#   [1804] Top tier maps (T15-16)
#   [1805] High tier maps(T11-14)
#   [1806] Mid tier maps (T6-10)
#   [1807] Low tier maps (T1-T5)
#   [1808] Map fragments
# [[1900]] Currency - PART 2 - Rare currency
#   [1901] Regular Rare Currency
#   [1902] Harbinger Currency
#   [1903] Incursion Currency
#   [1904] Delve Currency - Resonators
#   [1905] Delve Currency - Fossil
#   [1906] Bestiary Currency
#   [1907] Top Currency
#   [1908] Essence Tier List
#   [1909] Perandus
#   [1910] Breach
#   [1911] Others
# [[2000]] Currency - PART 3 - Divination cards (yes the strange sorting is intended)
#   [2001] Exceptions to prevent ident. mistakes
#   [2002] T1 - Top tier cards
#   [2003] T2 - Great cards
#   [2004] T3 - Decent cards
#   [2005] Special - Special Currency Cards
#   [2006] T5 - Format trash tier cards... before
#   [2007] T4 - ...showing the remaining cards
# [[2100]] Currency - PART 4 - remaining items
# [[2200]] Leaguestones - Tierlists
# [[2300]] Uniques!
#   [2301] Exceptions
#   [2302] Harbinger - Pieces
#   [2303] Tier 1 uniques
#   [2304] Tier 2 uniques
#   [2305] Multi-Unique bases.
#   [2306] Special Unique Searches
#   [2307] Prophecy-Material Uniques
#   [2308] Random Uniques
# [[2400]] Quest Items and Shaper Orbs
# [[2500]] OVERRIDE AREA 4 - Insert your custom Leveling adjustments here
# [[2600]] Leveling - Flasks
#   [2601] Hide outdated flasks
#   [2602] Hybrid flasks (normal)
#   [2603] Life Flasks - Normal (Kudos to Antnee)
#   [2604] Mana Flasks - Magic (Kudos to Antnee)
#   [2605] Show remaining flasks
# [[2700]] Leveling - Merged Rules
# [[2800]] Leveling - RGB Recipes
# [[2900]] Leveling - RARES
#   [2901] Leveling rares - specific items
#   [2902] Leveling rares - Progression
#   [2903] Leveling rares - remaining rules
# [[3000]] Leveling - Useful items
#   [3001] Linked gear - 4links
#   [3002] Linked gear - Caster Weapon Configuration
#   [3003] Linked gear - 3links
#   [3004] Extra Highlight: Boots
#   [3005] Optional Recipes
#   [3006] Act 1
#   [3007] Act 2+3
#   [3008] Act 4+5+6
#   [3009] Jewellery - Regular Highlight
#   [3010] Quivers - Progression
#   [3011] Magic Gear
#   [3012] 20% quality items for those strange people who want them
# [[3100]] Leveling - normal and magic item progression
#   [3101] Progression - Part 1 1-30
#   [3102] Progression - Part 2 30-40
#   [3103] Progression - Part 4 40-65
#   [3104] Normal items - First 12 levels - exceptions
#   [3105] Magic items - general highlight
# [[3200]] HIDE LAYER 5 - Remaining Items
# [[3300]] CATCHALL - if you see pink items - send me a mail please - should never happen
# [[3400]] Special thanks to!

#===============================================================================================================
# [[0100]] OVERRIDE AREA 1 - Override ALL rules here
#===============================================================================================================

#===============================================================================================================
# [[0200]] 6 LINKS
#===============================================================================================================

Show #
	LinkedSockets 6
	Rarity <= Rare
	Class "Body Armour"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show #
	LinkedSockets 6
	Rarity <= Rare
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Red Diamond
	PlayEffect Red

#===============================================================================================================
# [[0300]] SHAPER ITEMS
#===============================================================================================================

#------------------------------------
#   [0301] Exception Handling - Rings, Amulets, Belts
#------------------------------------

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 84
	Rarity <= Rare
	BaseType "Coral Amulet" "Paua Amulet" "Gold Amulet" "Gold Ring" "Paua Ring" "Iron Ring" "Amethyst Ring" "Unset Ring" "Moonstone Ring" "Studded Belt" "Cloth Belt" "Chain Belt"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0302] Shaper Item Layers - T1
#------------------------------------

# Level-Independent Expensive finds

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	Rarity <= Rare
	BaseType "Opal Ring" "Steel Ring" "Stygian Vise" "Crystal Belt" "Vanguard Belt" "Blue Pearl Amulet" "Marble Amulet"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

# Level-Dependent Expensive finds (82)

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 82
	Rarity <= Rare
	Class "Amulets"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 85
	Rarity <= Rare
	Class "Quivers" "Rings" "Belts"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 82
	Rarity <= Rare
	BaseType "Bone Helmet" "Two-Stone Ring" "Diamond Ring" "Two-Toned Boots" "Kris" "Void Sceptre" "Opal Sceptre" "Sambar Sceptre" "Gripped Gloves" "Fingerless Silk Gloves" "Spiked Gloves"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

# Level-Dependent Expensive finds (84)

Show # $Rare->Shaper->T1 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 85
	Rarity <= Rare
	BaseType "Sorcerer Gloves" "Lion Pelt" "Hubris Circlet" "Royal Burgonet" "Eternal Burgonet" "Vaal Regalia" "Astral Plate" "Colossal Tower Shield" "Pinnacle Tower Shield" "Mirrored Spiked Shield" "Archon Kite Shield" "Crusader Buckler" "Eclipse Staff" "Harbinger Bow" "Vaal Axe" "Runic Hatchet" "Jewelled Foil" "Spiraled Foil" "Exquisite Blade" "Titan Greaves" "Assassin's Garb" "Harmonic Spirit Shield" "Titanium Spirit Shield"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

#------------------------------------
#   [0303] Shaper Item Layers - T2
#------------------------------------

Show # $Rare->Shaper->T2 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 80
	Rarity <= Rare
	Class "Daggers" "Sceptres" "Quivers"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

Show # $Rare->Shaper->T2 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 86
	Rarity <= Rare
	Class "Gloves" "Boots" "Helmets"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

Show # $Rare->Shaper->T2 $x->ShaperElder
	ShaperItem True
	ItemLevel >= 83
	DropLevel >= 62
	Rarity <= Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords" "Bows" "One Hand Swords" "One Hand Maces" "One Hand Axes" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

Show # $Rare->Shaper->T2 $x->ShaperElder
	ShaperItem True
	Rarity <= Rare
	Class "Amulets" "Rings" "Belts"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 25 235 25 255         # BORDERCOLOR:	 Shaper Elder Ring
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

#------------------------------------
#   [0304] Shaper Item Layers - T3
#------------------------------------

Show # $Rare->Shaper->T3 $x->ShaperElder
	ShaperItem True
	Rarity <= Rare
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 50 130 165        # BACKGROUND:	 Shaper T3

#===============================================================================================================
# [[0400]] ELDER ITEMS
#===============================================================================================================

#------------------------------------
#   [0401] Exception Handling - Rings, Amulets, Belts
#------------------------------------

Show # $Rare->Elder->T1 $x->ShaperElder
	ElderItem True
	ItemLevel >= 84
	Rarity <= Rare
	BaseType "Coral Amulet" "Paua Amulet" "Gold Amulet" "Gold Ring" "Paua Ring" "Iron Ring" "Amethyst Ring" "Unset Ring" "Moonstone Ring" "Studded Belt" "Cloth Belt" "Chain Belt"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0402] Elder Item Layers - T1
#------------------------------------

# Level-Independent Expensive finds

Show # $Rare->Elder->T1 $x->ShaperElder
	ElderItem True
	Rarity <= Rare
	BaseType "Opal Ring" "Steel Ring" "Stygian Vise" "Crystal Belt" "Vanguard Belt" "Blue Pearl Amulet" "Marble Amulet"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

# Level-Dependent Expensive finds (80)

Show # $Rare->Elder->T1 $x->ShaperElder
	ElderItem True
	ItemLevel >= 85
	Rarity <= Rare
	Class "Belts" "Rings" "Amulets"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

Show # $Rare->Elder->T1 $x->ShaperElder
	ElderItem True
	ItemLevel >= 82
	Rarity <= Rare
	BaseType "Bone Helmet" "Two-Stone Ring" "Diamond Ring" "Two-Toned Boots" "Gripped Gloves" "Fingerless Silk Gloves" "Spiked Gloves"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Red

# Level-Dependent Expensive finds (84)

Show # $Rare->Elder->T1 $x->ShaperElder
	ElderItem True
	ItemLevel >= 85
	Rarity <= Rare
	BaseType "Glorious Plate" "Colossal Tower Shield" "Pinnacle Tower Shield" "Crusader Buckler" "Eclipse Staff" "Vaal Axe" "Jewelled Foil" "Assassin's Garb" "Coronal Maul" "Ambusher" "Lion Pelt" "Hubris Circlet" "Royal Burgonet" "Eternal Burgonet" "Astral Plate" "Titan Gauntlets" "Sorcerer Gloves" "Slink Gloves" "Harmonic Spirit Shield" "Titanium Spirit Shield"
	SetFontSize 45
	SetTextColor 50 130 165 255          # TEXTCOLOR:	 ShaperElder
	SetBorderColor 50 130 165 255        # BORDERCOLOR:	 Shaper T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Red Diamond
	PlayEffect Red

#------------------------------------
#   [0403] Elder Item Layers - T2
#------------------------------------

Show # $Rare->Elder->T2 $x->ShaperElder
	ElderItem True
	Rarity <= Rare
	Class "Amulets" "Rings" "Belts"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 25 235 25 255         # BORDERCOLOR:	 Shaper Elder Ring
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

Show # $Rare->Elder->T2 $x->ShaperElder
	ElderItem True
	ItemLevel >= 86
	Rarity <= Rare
	Class "Gloves" "Boots" "Helmets"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

Show # $Rare->Elder->T2 $x->ShaperElder
	ElderItem True
	ItemLevel >= 83
	DropLevel >= 62
	Rarity <= Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords" "Bows" "One Hand Swords" "One Hand Maces" "One Hand Axes" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 20 110 220        # BACKGROUND:	 ShaperElder T2
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

#------------------------------------
#   [0404] Elder Item Layers - T3
#------------------------------------

Show # $Rare->Elder->T3 $x->ShaperElder
	ElderItem True
	Rarity <= Rare
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 50 130 165        # BACKGROUND:	 Shaper T3

#===============================================================================================================
# [[0500]] Explicit Mod filtering
#===============================================================================================================

#------------------------------------
#   [0501] League-Specific Magic Items
#------------------------------------

Show # Delve Mod Items
	Identified True
	HasExplicitMod "of Crafting" "of Spellcraft" "of Weaponcraft" "of the Underground" "Subterranean"
	SetFontSize 45
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Stupid Beast Mod Items
	Identified True
	HasExplicitMod "of Farrul" "of Craiceann" "of Fenumus" "of Saqawal"
	SetFontSize 45
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Incursion Mod Items
	Identified True
	Rarity Rare
	HasExplicitMod "Tacati" "Citaqualotl" "Matatl" "Topotante" "Xopec" "Guatelitzi" "Puhuarte"
	SetFontSize 45
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Incursion Mod Items
	Identified True
	Rarity Magic
	HasExplicitMod "Tacati" "Citaqualotl" "Matatl" "Topotante" "Xopec" "Guatelitzi" "Puhuarte"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Warband Mod Items
	Identified True
	HasExplicitMod "Brinerot" "Mutewind" "Redblade" "Betrayer's" "Deceiver's" "Turncoat's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0502] Magic Mod Permutations
#------------------------------------

Show # Noteworthy phys rolls
	Corrupted False
	Identified True
	DropLevel > 55
	Rarity Magic
	HasExplicitMod "Merciless"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy phys rolls 2
	Corrupted False
	Identified True
	DropLevel > 55
	Rarity Magic
	Class "Dagger" "Wand" "One Hand" "Claw" "Bow"
	HasExplicitMod "Flaring" "Tempered" "Dictator's" "Emperor's" "Electrocuting" "Cremating" "Entombing" "Malicious" "Tyrannical" "Merciless"
	HasExplicitMod "of Rending" "of Incision" "of Penetrating" "of Destruction" "of Ferocity" "of Celebration"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy caster rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Dagger" "Sceptre"
	HasExplicitMod "Runic" "Xoph's" "Esh's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy dual magic rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Dagger" "Sceptre" "Wand"
	HasExplicitMod "Runic" "Glyphic" "Lich's" "Cremating" "Electrocuting" "Entombing" "Runic" "Xoph's" "Esh's" "Tul's"
	HasExplicitMod "of Destruction" "of Celebration" "of Finesse" "of Sortilege" "of Unmaking" "of Ruin" "of Ashes" "of Glaciation" "of Arcing"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Summonner +3 helmets (?)
	Corrupted False
	Identified True
	DropLevel > 55
	Rarity Magic
	HasExplicitMod "Necromancer's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy boots rolls
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Magic
	Class "Boots"
	HasExplicitMod "Hellion's" "Cheetah's" "Seething" "Unassailable"
	HasExplicitMod "of the Lightning" "of Ephij" "of Tzteosh" "of the Magma" "of the Ice" "of Haast"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy armor rolls
	Corrupted False
	Identified True
	DropLevel > 60
	Rarity Magic
	Class "Body Armour"
	HasExplicitMod "Prime" "Resplendent" "Unfaltering" "Unassailable"
	HasExplicitMod "of the Lightning" "of Ephij" "of Tzteosh" "of the Magma" "of the Ice" "of Haast"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy glove rolls
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Magic
	Class "Gloves"
	HasExplicitMod "Athlete's" "Seething" "Unassailable"
	HasExplicitMod "of the Lightning" "of Ephij" "of Tzteosh" "of the Magma" "of the Ice" "of Haast" "of Grandmastery" "of Lioneye" "of the Assassin"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy shield rolls
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Magic
	Class "Shield"
	HasExplicitMod "Vigorous" "Xoph's" "Runic" "Esh's" "Unfaltering" "Incandescent" "Tul's"
	HasExplicitMod "of Ephij" "of Tzteosh" "of Haast" "of Expertise" "of the Span" "of Unmaking"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy quiver rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Quiver"
	BaseType "Penetrating Arrow Quiver" "Spike-Point Arrow Quiver" "Broadhead Arrow Quiver"
	HasExplicitMod "Overpowering" "Devastating" "Fecund"
	HasExplicitMod "of Ease" "of Rending" "of Destruction"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy helmets rolls
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Magic
	Class "Helmets"
	HasExplicitMod "Fecund" "Blazing" "Unassailable"
	HasExplicitMod "of the Lightning" "of Ephij" "of Tzteosh" "of the Magma" "of the Ice" "of Haast" "of Lioneye"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy amulet rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Amulet"
	HasExplicitMod "Athlete's" "Virile" "Dazzling" "Flaring" "Cremating" "Entombing" "Electrocuting" "Unassailable" "Wizard's" "Devastating"
	HasExplicitMod "of the Gods" "of the Wind" "of the Genius" "of Talent" "of Skill" "of the Assassin" "of Tzteosh" "of Haast" "of Ephij" "of the Rainbow" "of Immolation" "of Floe" "of Discharge" "of Nirvana" "of Destruction" "of Incision" "of the Multiverse" "of Expertise"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy ring rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Rings"
	HasExplicitMod "Flawless" "Electrocuting" "Overpowering" "Virile" "Rotund" "Resplendent" "Annealed" "Cremating" "Entombing"
	HasExplicitMod "of the Gods" "of the Wind" "of the Genius" "of the Comet" "of Talent" "of Skill" "of the Assassin" "of Tzteosh" "of Haast" "of Ephij" "of the Rainbow" "of Flames" "of Rime" "of Voltage"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # Noteworthy ring rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Jewel"
	HasExplicitMod "Vivid" "Shimmering"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base

Show # Noteworthy ring rolls
	Corrupted False
	Identified True
	Rarity Magic
	Class "Belts"
	HasExplicitMod "Fecund" "Dazzling" "Devastating" "Overpowering" "Enveloped"
	HasExplicitMod "of the Gods" "of the Godslayer" "of Tzteosh" "of Haast" "of Ephij" "of Overflowing" "of Sipping" "of Savouring"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0503] Rare Item Permutations
#------------------------------------

Show
	Corrupted False
	Identified True
	Class "Bow" "Staves"
	HasExplicitMod "Sharpshooter's" "Anarchist's" "Lava Caller's" "Tempest King's" "Winterbringer's"
	HasExplicitMod "Paragon's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

#===============================================================================================================
# [[0600]] Explicit Mod filtering - EXPERIMENTAL
#===============================================================================================================

#------------------------------------
#   [0601] Rare Item Permutations
#------------------------------------

Show # Phys DPS 3-Stat Combos (Bows/Wands)
	Identified True
	DropLevel > 50
	Rarity Rare
	Class "Bows" "Wands"
	HasExplicitMod "Merciless" "Tyrannical" "Cruel" "Bloodthirsty"
	HasExplicitMod "Flaring" "Tempered" "Razor-sharp" "Annealed"
	HasExplicitMod "of Renown" "of Mastery" "of Ease"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # Phys DPS 2-Stat Combos (Bows/Wands)
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Rare
	Class "Bows" "Wands"
	HasExplicitMod "Merciless" "Tyrannical"
	HasExplicitMod "of Renown"	"of Incision"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0602] Weapons-Physical (Key: IPD)
#------------------------------------

Show # Phys DPS 3-Stat Combos
	Identified True
	DropLevel > 50
	Rarity Rare
	HasExplicitMod "Merciless" "Tyrannical" "Cruel" "Bloodthirsty"
	HasExplicitMod "Flaring" "Tempered" "Razor-sharp" "Annealed"
	HasExplicitMod "Dictator's" "Emperor's" "Conqueror's" "Champion's" "of Celebration" "of Infamy" "of Fame" "of Acclaim" "of Renown" "of Incision" "of Penetrating" "of Destruction" "of the Assassin"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # Phys DPS 2-Stat Combos
	Identified True
	DropLevel > 50
	Rarity Rare
	HasExplicitMod "Merciless" "Tyrannical" "Cruel"
	HasExplicitMod "Flaring" "Tempered" "Razor-sharp" "Dictator's" "Emperor's" "Conqueror's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # Phys DPS 2-Stat Combos
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Rare
	HasExplicitMod "Merciless" "Tyrannical"
	HasExplicitMod "of Celebration" "of Infamy"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0603] The Suffix Abomination
#------------------------------------

Show
	Corrupted False
	Identified True
	DropLevel > 50
	Rarity Rare
	Class "Wands" "Daggers" "One Hand Swords" "Thrusting One Hand Swords" "Claws" "Bows"
	HasExplicitMod "of Incision" "of Penetrating"
	HasExplicitMod "of Destruction" "of Ferocity" "of Fury"
	HasExplicitMod "of Celebration" "of Infamy"
	HasExplicitMod "Merciless" "Tyrannical" "Cruel" "Bloodthirsty" "Flaring" "Tempered" "Razor-sharp" "Annealed" "Dictator's" "Emperor's" "Conqueror's" "Champion's" "Entombing" "Polar" "Glaciated" "Frozen" "Cremating" "Blasting" "Incinerating" "Scorching" "Electrocuting" "Discharging" "Shocking" "Arcing"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0604] Casters
#------------------------------------

Show
	Corrupted False
	Identified True
	Rarity Rare
	Class "Sceptres" "Daggers"
	HasExplicitMod "of Celebration" "of Infamy" "of Fame"
	HasExplicitMod "of Unmaking" "of Ruin" "of Calamity" "of Finesse" "of Sortilege" "of Prestidigitation" "of Glaciation" "of Floe" "of Ashes" "of Immolation" "of Arcing" "of Discharge"
	HasExplicitMod "Runic" "Glyphic" "Xoph's" "Pyroclastic" "Esh's" "Ionising" "Tul's" "Cryomancer's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show
	Corrupted False
	Identified True
	Rarity Rare
	Class "Sceptres" "Daggers" "Wands"
	HasExplicitMod "Runic" "Glyphic" "Xoph's" "Pyroclastic"
	HasExplicitMod "of Ashes" "of Immolation" "of Conflagrating" "of Combusting" "Cremating" "Lich's" "Archmage's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show
	Corrupted False
	Identified True
	Rarity Rare
	Class "Sceptres" "Daggers" "Wands"
	HasExplicitMod "Runic" "Glyphic" "Esh's" "Ionising"
	HasExplicitMod "of Arcing" "of Discharge" "Electrocuting" "Lich's" "Archmage's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show
	Corrupted False
	Identified True
	Rarity Rare
	Class "Sceptres" "Daggers" "Wands"
	HasExplicitMod "Runic" "Glyphic" "Tul's" "Cryomancer's"
	HasExplicitMod "of Glaciation" "of Floe" "Entombing" "Lich's" "Archmage's"
	SetFontSize 45
	SetTextColor 0 240 190 240           # TEXTCOLOR:	 Special
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

#===============================================================================================================
# [[0700]] Recipes, Magic and Normal items (endgame!)
#===============================================================================================================

#------------------------------------
#   [0701] Overqualitied Items
#------------------------------------

Show
	Corrupted False
	Quality >= 25
	ItemLevel >= 75
	DropLevel >= 50
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

#------------------------------------
#   [0702] 5-Linked items
#------------------------------------
# Very useful at the start of the league. Otherwise often trash. Still, highlight material.
# There’s a lot of exceptions we can introduce here, such as 6S, high value bases, but this
# Is a rare occurrence, so we won’t be doing it for performance reasons.

Show # $recipe->6S $linked->5L %D5
	LinkedSockets 5
	Sockets 6
	Rarity <= Rare
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 100 100 100 255   # BACKGROUND:	 Recipe T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # $linked->5L %D4
	LinkedSockets 5
	ItemLevel >= 65
	Rarity < Unique
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $linked->5L $lvl %D5
	LinkedSockets 5
	ItemLevel < 65
	Rarity < Unique
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

#------------------------------------
#   [0703] 6-Socket Items
#------------------------------------
# Can be sold for 7 jeweller orbs. We also highlight the ilvl83/84 ones that are OK for crafting.
# Chances are high that people will want to buy those.

Show # $EGC->86 $recipe->6S %TB-6S-Rare-Armors %D5
	Sockets 6
	ItemLevel >= 86
	Rarity <= Rare
	BaseType "Assassin's Garb" "Glorious Plate" "Astral Plate" "Vaal Regalia" "Zodiac Leather"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus
	SetBackgroundColor 100 100 100 255   # BACKGROUND:	 Recipe T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $EGC->85 $recipe->6S %TB-6S-Rare-Weapons %D5
	Sockets 6
	ItemLevel >= 85
	Rarity <= Rare
	BaseType "Harbinger Bow" "Vaal Axe" "Coronal Maul" "Exquisite Blade"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus
	SetBackgroundColor 100 100 100 255   # BACKGROUND:	 Recipe T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $recipe->6S %D5
	Sockets 6
	Rarity <= Rare
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 100 100 100 255   # BACKGROUND:	 Recipe T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

#------------------------------------
#   [0704] Exclusive bases: Stygian Vise
#------------------------------------

Show # $rare $x->Abyss->Stygian $EGC->86 %TB-Vise
	ItemLevel >= 86
	Rarity <= Rare
	BaseType "Stygian Vise"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 255 125 0 255     # BACKGROUND:	 SpecialBase T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # $Rare->Regal $Rare->tiny $x->Abyss->Stygian %TB-Vise
	ItemLevel >= 75
	Rarity <= Rare
	BaseType "Stygian Vise"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue	Temp

Show # $Rare->tiny $x->Abyss->Stygian %TB-Vise %H5
	Rarity <= Rare
	BaseType "Stygian Vise"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue	Temp

#------------------------------------
#   [0705] Abyss Jewels (Rare and Magic)
#------------------------------------

Show # $EGC->82 $x->Abyss->Jewel $Jewels->Rare
	ItemLevel >= 82
	Rarity = Rare
	Class "Abyss Jewel"
	SetFontSize 45
	SetTextColor 255 255 0 255           # TEXTCOLOR:	 Jewel Text
	SetBorderColor 220 0 0 240           # BORDERCOLOR:	 Aspect High Potential
	SetBackgroundColor 120 120 0 225     # BACKGROUND:	 Rare Jewel
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # $EGC->82 $x->Abyss->Jewel $Jewels->Magic
	ItemLevel >= 82
	Rarity <= Magic
	Class "Abyss Jewel"
	SetFontSize 45
	SetTextColor 0 100 255               # TEXTCOLOR:	 Jewel Magic
	SetBorderColor 220 0 0 240           # BORDERCOLOR:	 Aspect High Potential
	SetBackgroundColor 0 20 40 255       # BACKGROUND:	 Jewel Magic
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Blue Diamond
	PlayEffect Blue

Show # $x->Abyss->Jewel $Jewels->Rare
	Rarity = Rare
	Class "Abyss Jewel"
	SetFontSize 45
	SetTextColor 255 255 0 255           # TEXTCOLOR:	 Jewel Text
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus
	SetBackgroundColor 120 120 0 225     # BACKGROUND:	 Rare Jewel
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue	Temp

Show # $x->Abyss->Jewel $Jewels->Magic %H4
	Rarity <= Magic
	Class "Abyss Jewel"
	SetFontSize 45
	SetTextColor 0 100 255               # TEXTCOLOR:	 Jewel Magic
	SetBorderColor 0 75 250              # BORDERCOLOR:	 Magic Jewel
	SetBackgroundColor 0 20 40 255       # BACKGROUND:	 Jewel Magic

Show # $Jewels->Rare %TC-Rare-Jewels
	Rarity Rare
	Class Jewel
	SetFontSize 45
	SetTextColor 255 255 0 255           # TEXTCOLOR:	 Jewel Text
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus
	SetBackgroundColor 120 120 0 225     # BACKGROUND:	 Rare Jewel
	MinimapIcon 2 Blue Diamond

#------------------------------------
#   [0706] Exclusive bases: Top Value
#------------------------------------
# These bases are valuable crafting due to their rarity and strong implicit.

Show # $x->Atlas->T1 $EGC->86 %TB-Top-Atlas-Bases
	ItemLevel >= 86
	Rarity <= Rare
	BaseType "Steel Ring" "Opal Ring"
	SetFontSize 45
	SetTextColor 255 125 0 255           # TEXTCOLOR:	 Atlas Base
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Diamond
	PlayEffect Blue

Show # $x->Atlas->T1 %TB-Top-Atlas-Bases
	Rarity <= Rare
	BaseType "Steel Ring" "Opal Ring"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 255 125 0 255     # BACKGROUND:	 SpecialBase T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Yellow

#------------------------------------
#   [0707] Exclusive bases: Trinkets
#------------------------------------
# These bases are valuable crafting due to their rarity and strong implicit.

Show # $x->Atlas->T2 %TB-Atlas-Bases
	ItemLevel >= 86
	Rarity < Rare
	BaseType "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Crystal Belt"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 255 125 0 255     # BACKGROUND:	 SpecialBase T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Diamond
	PlayEffect Blue

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases
	ItemLevel >= 84
	Rarity = Rare
	BaseType "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Crystal Belt"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 255 125 0 255     # BACKGROUND:	 SpecialBase T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Diamond
	PlayEffect Blue

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases %D5
	ItemLevel >= 75
	Rarity = Rare
	BaseType "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Crystal Belt"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Diamond
	PlayEffect White Temp

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases %D5
	Rarity = Rare
	BaseType "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Crystal Belt"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Diamond
	PlayEffect White Temp

Show # $x->Atlas->T2 %TB-Atlas-Bases
	Rarity <= Magic
	BaseType "Blue Pearl Amulet" "Marble Amulet" "Vanguard Belt" "Crystal Belt"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base

Show # $x->Talismans %TB-Talisman
	Rarity < Unique
	Class Amulets
	BaseType "Talisman"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [0708] Exclusive bases: Others
#------------------------------------
# These bases are valuable crafting due to their rarity and strong implicit.

Show # $x->Atlas->T2 %TB-Atlas-Bases
	ItemLevel >= 86
	Rarity < Rare
	BaseType "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetFontSize 45
	SetTextColor 255 125 0 255           # TEXTCOLOR:	 Atlas Base
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases %D5
	ItemLevel >= 84
	Rarity = Rare
	BaseType "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetFontSize 45
	SetTextColor 255 125 0 255           # TEXTCOLOR:	 Atlas Base
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	MinimapIcon 2 Blue Diamond
	PlayEffect Blue Temp

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases %D4
	ItemLevel >= 75
	Rarity = Rare
	BaseType "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetFontSize 45
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $x->Atlas->T2 $Rare->Tiny %TB-Atlas-Bases %D4
	Rarity = Rare
	BaseType "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $x->Atlas->T2 %TB-Atlas-Bases %D2
	Rarity <= Magic
	BaseType "Bone Helmet" "Two-Toned Boots" "Spiked Gloves" "Gripped Gloves" "Fingerless Silk Gloves"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base

#------------------------------------
#   [0709] Corrupted Amulets
#------------------------------------
# Corrupted amulets for rare lab shrines (to turn them rare)

# Show # $outdated $normal $corr %TC-Corrupted-Bases
#	Corrupted True
#	Class Amulet Belt
#	Rarity = Normal
#	SetFontSize 36
#	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Crafting: T0

#------------------------------------
#   [0710] Chancing items
#------------------------------------
# You can add your own items here. The items in this section have a dropsound

# LEGACY UNIQUES: THESE UNIQUES CAN ONLY BE CHANCED IN THE CORRECT ZANA-LEAGUE MODS
# Agate Amulet - ANARCHY ONLY - can be chance to voll's in anarchy maps
# Leather belt - NEMESIS only - can be chanced into a headhunter belt!

# EXAMPLE OF NON LEGACY UNIQUES:
# Prophecy wand - Void Battery
# Judgement Staff - Hegemony's/Pledge of Hands

# TO ADD AN ITEM ATTACH IT'S NAME TO THE BASAETYPE'S IN ONE OF THE 2 ENTRIES BELOW.
# Example, to add Agate amulet:
# BaseType "Sorcerer Boots"

#Show # $Chancing B-T1-Chancing %D4
#	BaseType "Glorious Plate" "Close Helmet" "Occultist's Vestment"
#	Rarity Normal
#	SetFontSize 38
#	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
#	SetBorderColor 0 210 0 210           # BORDERCOLOR:	 T1 Chancing
#	PlayAlertSound 7 300                 # DROPSOUND:	 T1 chancing items
#	Corrupted False

Show # $Chancing %TB-T2-Chancing %D3
	Corrupted False
	Rarity Normal
	BaseType "Leather Belt"
	SetFontSize 36
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 0 150 0 150           # BORDERCOLOR:	 T2 Chancing

Show # $Chancing %TB-T2-Chancing %D2
	Corrupted False
	Rarity Normal
	BaseType "Sadist Garb" "Glorious Plate" "Gold Amulet" "Sapphire Flask" "Imperial Bow"
	SetFontSize 36
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 0 150 0 150           # BORDERCOLOR:	 T2 Chancing

#------------------------------------
#   [0711] FLASKS (Endgame rules)
#------------------------------------

Show # $Recipes->Glassblower->20% %D3
	Quality = 20
	ItemLevel > 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 40
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # $Recipes->Glassblower->15% %D1
	Quality >= 15
	ItemLevel > 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # $Recipes->Glassblower %D1
	Quality >= 1
	ItemLevel > 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # $Flasks->Life %D1
	ItemLevel <= 74
	ItemLevel >= 66
	Rarity <= Magic
	Class "Life Flasks"
	BaseType "Divine" "Eternal"
	SetFontSize 36
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask

Show # $Flasks->Mana %D1
	ItemLevel <= 74
	ItemLevel >= 66
	Rarity <= Magic
	Class "Mana Flasks"
	BaseType "Divine" "Eternal"
	SetFontSize 36
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask

Show # $Flasks->Utility %D2
	ItemLevel > 65
	Rarity <= Magic
	Class "Utility Flasks"
	SetFontSize 36
	SetBorderColor 50 200 125            # BORDERCOLOR:	 Flask
	SetBackgroundColor 25 100 75         # BACKGROUND:	 Flasks

#------------------------------------
#   [0712] Add your own crafting rules here
#------------------------------------
# Please use ItemLevel >= 65if you DON'T want your rules to affect Leveling progression.
# Example: To highlight all white "Vaal Claw" and "Gemini Claw" in the endgame, uncomment the following section (remove the '#')

# Show #
# BaseType "Gemini Claw" "Vaal Claw"
# ItemLevel >= 65
# Rarity = Normal
# SetBorderColor 0 255 255 255
# SetFontSize 40

#------------------------------------
#   [0713] 86+ Endgame crafting rules
#------------------------------------

Show # $EGC->86->T1 %D5
	ItemLevel >= 86
	Rarity < Rare
	BaseType "Onyx Amulet" "Diamond Ring" "Two-Stone Ring" "Unset Ring" "Eternal Burgonet" "Lion Pelt" "Colossal Tower Shield"
	SetFontSize 45
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # $EGC->86->T2 %D4
	ItemLevel >= 86
	Rarity < Rare
	BaseType "Titan Gauntlets" "Slink Gloves" "Royal Burgonet" "Titan Greaves" "Slink Boots" "Hubris Circlet" "Ruby Ring" "Sapphire Ring" "Topaz Ring" "Prismatic" "Gold Ring" "Citrine Amulet" "Turquoise Amulet" "Agate Amulet" "Coral Ring" "Moonstone Ring" "Leather Belt" "Heavy Belt" "Amber Amulet" "Jade Amulet" "Lapis Amulet" "Rustic Sash" "Vaal Axe" "Coronal Maul" "Exquisite Blade" "Fleshripper" "Harbinger Bow" "Gemini Claw" "Ambusher" "Siege Axe" "Harpy Rapier" "Demon Dagger" "Skean" "Spiraled Foil" "Jewelled Foil" "Profane Wand" "Sambar Sceptre" "Void Sceptre" "Imbued Wand" "Pinnacle Tower Shield" "Kris" "Prismatic" "Astral Plate" "Assassin's Garb" "Saintly Chainmail" "Harmonic Spirit Shield" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Sorcerer Boots" "Sorcerer Gloves" "Vaal Regalia"
	SetFontSize 40
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0714] 83/84+ Endgame crafting rules
#------------------------------------
# These entries are non-exclusive bases that are popular for crafting

Show # $EGC->84->T1 %TB-T1-Crafting %D4
	ItemLevel >= 84
	Rarity < Rare
	BaseType "Onyx Amulet" "Diamond Ring" "Two-Stone" "Eternal Burgonet"
	SetFontSize 40
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus

Show # $EGC->84->T2 %TB-T2-Crafting %D3
	ItemLevel >= 84
	Rarity < Rare
	BaseType "Titan Gauntlets" "Slink Gloves" "Royal Burgonet" "Lion Pelt" "Titan Greaves" "Slink Boots" "Hubris Circlet"
	SetFontSize 40
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus

Show # $EGC->84->T3 %TB-T2-Trinket-Bases %D2
	ItemLevel >= 84
	Rarity < Rare
	Class Rings Amulet Belts
	BaseType "Ruby" "Sapphire" "Topaz" "Prismatic" "Unset" "Gold" "Citrine" "Turquoise" "Agate" "Coral Ring" "Moonstone" "Leather" "Heavy Belt" "Amber" "Jade" "Lapis" "Rustic Sash"
	SetBorderColor 200 200 0 190         # BORDERCOLOR:	 Aspect: 83plus T2
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # $EGC->83->T3 %TB-T2-Crafting-83 %D2
	ItemLevel >= 83
	Rarity < Rare
	BaseType "Vaal Axe" "Coronal Maul" "Exquisite Blade" "Fleshripper" "Harbinger Bow" "Gemini Claw" "Ambusher" "Siege Axe" "Harpy Rapier" "Demon Dagger" "Skean" "Spiraled Foil" "Jewelled Foil"
	SetBorderColor 200 200 0 190         # BORDERCOLOR:	 Aspect: 83plus T2
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # $EGC->84->T3 %TB-T2-Crafting-84 %D2
	ItemLevel >= 84
	Rarity < Rare
	BaseType "Profane Wand" "Sambar Sceptre" "Void Sceptre" "Imbued Wand" "Pinnacle Tower Shield" "Kris" "Prismatic" "Astral Plate" "Assassin's Garb"
	SetBorderColor 200 200 0 190         # BORDERCOLOR:	 Aspect: 83plus T2
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # $EGC->84->T4 %TB-T2-Crafting-84-ES %D1
	ItemLevel >= 84
	Rarity < Rare
	BaseType "Saintly Chainmail" "Harmonic Spirit Shield" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Sorcerer Boots" "Sorcerer Gloves" "Vaal Regalia"
	SetBorderColor 200 200 0 190         # BORDERCOLOR:	 Aspect: 83plus T2
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0715] 60+ Crafting rules for 60++ trinkets
#------------------------------------
# This section handles the crafting bases for the entry level endgame

Show # $Jewels->Magic %H2
	Rarity <= Magic
	Class Jewel
	SetFontSize 40
	SetTextColor 0 100 255               # TEXTCOLOR:	 Jewel Magic
	SetBorderColor 0 75 250              # BORDERCOLOR:	 Magic Jewel
	SetBackgroundColor 0 20 40 255       # BACKGROUND:	 Jewel Magic

Show # $Craft->75 %TB-T1-Trinket-Bases %D1
	ItemLevel >= 75
	Rarity Normal
	Class Rings Amulet Belts
	BaseType "Onyx" "Two-Stone" "Diamond" "Prismatic"
	SetFontSize 36
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#Show # $Craft->75 $mid %TB-T2-Trinket-Bases %D0
#	ItemLevel >= 75
#	Rarity Normal
#	Class Rings Amulet Belts
#	BaseType "Ruby" "Sapphire" "Topaz" "Gold" "Citrine" "Turquoise" "Agate" "Coral Ring" "Moonstone" "Leather" "Heavy Belt" "Amber" "Jade" "Lapis" "Rustic Sash"
#	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
#	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#Show # $Craft->65 $low %TB-T1-Trinket-Bases %D0
#	ItemLevel >= 65
#	ItemLevel <= 74
#	Rarity Normal
#	Class Rings Amulet Belts
#	BaseType "Onyx" "Two-Stone" "Diamond" "Prismatic"
#	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
#	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#Show # $Craft->65 $mid %TB-T2-Trinket-Bases %D0
#	ItemLevel >= 65
#	ItemLevel <= 74
#	Rarity Normal
#	Class Rings Amulet Belts
#	BaseType "Ruby" "Sapphire" "Topaz" "Gold" "Citrine" "Turquoise" "Agate" "Coral Ring" "Moonstone" "Leather" "Heavy Belt" "Amber" "Jade" "Lapis" "Rustic Sash" "Chain Belt"
#	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
#	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#Show # $Craft->65 $low %D0
#	ItemLevel >= 65
#	Rarity Magic
#	Class Rings Amulets Belts
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
#	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0716] Remaining crafting rules - add your own bases here!
#------------------------------------
# This section handles additional crafting bases.

#Show # %TB-Individual-And-SSF-Craft-Bases
#	BaseType "Hubris Circlet" "Vaal Regalia" "Harbinger Bow"
#	Rarity < Rare
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight

#------------------------------------
#   [0717] Chisel recipe items
#------------------------------------
# Chisel Recipe: You can sell a 20% hammer + random map for 1 chisel

Show # %TB-Gavels %D2 $Recipe->Chisel->20
	Quality = 20
	Rarity < Unique
	BaseType "Gavel" "Rock Breaker" "Stone Hammer"
	SetFontSize 36
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %TB-Gavels %D1 $Recipe->Chisel->15
	Corrupted False
	Quality > 17
	Rarity Magic
	BaseType "Gavel" "Rock Breaker" "Stone Hammer"
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %TB-Gavels %D1 $Recipe->Chisel->15
	Corrupted False
	Quality > 14
	Rarity Normal
	BaseType "Gavel" "Rock Breaker" "Stone Hammer"
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %TB-Gavels %D1 $Recipe->Chisel
	Corrupted False
	Quality > 11
	Rarity Magic
	BaseType "Gavel" "Rock Breaker" "Stone Hammer"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %TB-Gavels %D1 $Recipe->Chisel
	Corrupted False
	Rarity Normal
	BaseType "Gavel" "Rock Breaker" "Stone Hammer"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

#------------------------------------
#   [0718] Fishing Rod
#------------------------------------

# Give a man a fish and he won't be hungry for a day, teach a man to fish and GGG will ban you for disclosing fishing secrets.

Show # $x->Fish %TC-Secret
	Class "Fishing Rod"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

#------------------------------------
#   [0719] SRS Crude Bow
#------------------------------------
# Crude bows are a meta weapon for SRS summoners, so we'll highlight them no matter the rarity post level 49

Show # $x->SrsBow $crafting %TB-Low-BaseType-Crafting %D3
	ItemLevel >= 50
	Rarity <= Rare
	BaseType "Crude Bow"
	SetFontSize 40
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0720] Chromatic recipe items ("RGB Recipe")
#------------------------------------
# These items have a RGB link and sell for a chromatic orb each.

Show # %H2 $Recipe->RGB->Small
	Width <= 2
	Height <= 2
	ItemLevel >= 65
	Rarity < Rare
	SocketGroup RGB
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %H2 $Recipe->RGB->Small
	Width <= 1
	Height <= 3
	ItemLevel >= 65
	Rarity < Rare
	SocketGroup RGB
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %H1 $Recipe->RGB->Large
	Width >= 2
	Height >= 4
	ItemLevel >= 65
	Rarity < Rare
	SocketGroup RGB
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %H1 $Recipe->RGB
	ItemLevel >= 65
	Rarity < Rare
	SocketGroup RGB
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

#------------------------------------
#   [0721] Endgame-start 4-links
#------------------------------------

#Show # %D0 $Crafting->Low $Links->4
#	LinkedSockets >= 4
#	ItemLevel < 72
#	DropLevel >= 65
#	Rarity < Rare
#	Class "Boots" "Gloves" "Body Armour" "Helmets"
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
#	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0722] Animate Weapon script - deactivated by default
#------------------------------------
# UNCOMMENT THIS SCRIPT TO MAKE IT WORK (remove the # in front of the next 7 lines)

#Show # $x->AW
#	Class "One Hand" "Two Hand" "Staves" "Daggers" "Thrusting" "Sceptres" "Claws"
#	Rarity Normal
#	SetBackgroundColor 0 0 0 255
#	SetTextColor 150 0 0 255
#	SetBorderColor 150 0 0 255
#	SetFontSize 20

#Show # $x->AW ranged
#	Class "Bows" "Wands"
#	Rarity Normal
#	SetBackgroundColor 0 0 0 255
#	SetTextColor 150 0 0 255
#	SetBorderColor 150 0 0 255
#	SetFontSize 20

#Show # $x->AW identified
#	Class "One Hand" "Two Hand" "Staves" "Daggers" "Thrusting" "Sceptres" "Claws"
#	Rarity Magic
#	SetBackgroundColor 0 0 0 255
#	SetTextColor 150 0 0 255
#	SetBorderColor 150 0 0 255
#	SetFontSize 20
#	Identified True

#Show # $x->AW identified, ranged
#	Class "Bows" "Wands"
#	Rarity Magic
#	SetBackgroundColor 0 0 0 255
#	SetTextColor 150 0 0 255
#	SetBorderColor 150 0 0 255
#	SetFontSize 20
#	Identified True

#------------------------------------
#   [0723] W-soc offhand weapons
#------------------------------------
# Useful for gem Leveling.

Show # $x->WhiteSoc %D5 %TC-Offslot-Gem-Leveling
	Sockets >= 3
	Rarity <= Rare
	Class Wands Daggers One Hand Shields Thrusting Sceptre Claws
	SocketGroup WWW
	SetFontSize 40
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base

Show # $x->WhiteSoc %D1 %TC-Offslot-Gem-Leveling
	Sockets >= 3
	Rarity < Rare
	Class Wands Daggers One Hand Shields Thrusting Sceptre Claws
	SocketGroup W
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [0724] Sacrificial Garb
#------------------------------------
# Generally not useful, but very specific drop-location, some people still might want to see it

Show # $x->SacGarn %TB-Special-AlwaysShow-Bases %D4
	Rarity <= Rare
	BaseType "Sacrificial Garb"
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#===============================================================================================================
# [[0800]] HIDE LAYER 1 - MAGIC AND NORMAL ITEMS
#===============================================================================================================

Hide # Minimize junk instead of hiding (if "Show") %TC-Junkable
	ItemLevel >= 65
	Rarity < Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 18
	SetBorderColor 0 0 0 100             # BORDERCOLOR:	 Neutral T4
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

#===============================================================================================================
# [[0900]] Currency - PART 1 - Common currency
#===============================================================================================================
# We'll keep this section up here to boost the performance.

Show # $Currency->Low->T1 %H5 %TB-Currency-SilverCoin
	Class Currency
	BaseType "Silver Coin"
	SetFontSize 45
	SetTextColor 45 50 130 255           # TEXTCOLOR:	 Silver Coin
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 210 178 135 255   # BACKGROUND:	 Currency T5

Show # $Currency->Low->T1 %H4 %TB-Currency-T4
	Class Currency
	BaseType "Orb of Chance" "Orb of Alteration" "Chromatic Orb" "Jeweller's Orb" "Glassblower's Bauble"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 200             # BORDERCOLOR:	 Neutral T2
	SetBackgroundColor 210 178 135 255   # BACKGROUND:	 Currency T5

Show # $Currency->Low->T2 %H4 %TB-Currency-T5
	Class Currency
	BaseType "Orb of Transmutation" "Blacksmith's Whetstone" "Alchemy Shard"
	SetFontSize 45
	SetTextColor 170 158 130             # TEXTCOLOR:	 Currency Cosmetic
	SetBorderColor 190 178 135 180       # BORDERCOLOR:	 Transmutation
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # $Currency->Scroll->Portal %RF1 %H3 %TB-Currency-T7
	Class Currency
	BaseType "Portal Scroll"
	SetFontSize 40
	SetTextColor 170 158 130 220         # TEXTCOLOR:	 Currency Cosmetic 2
	SetBorderColor 30 50 100 255         # BORDERCOLOR:	 Portal
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # $Currency->Low->T3 %H2 %TB-Currency-T6
	Class Currency
	BaseType "Armourer's Scrap" "Orb of Augmentation" "Transmutation Shard" "Alteration Shard"
	SetFontSize 40
	SetTextColor 170 158 130 220         # TEXTCOLOR:	 Currency Cosmetic 2
	SetBorderColor 75 75 75 255          # BORDERCOLOR:	 Currency Augment
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # $Currency->Scroll->Wisdoms
	Class Currency
	BaseType "Scroll of Wisdom"
	StackSize > 1
	SetFontSize 45
	SetTextColor 170 158 130 220         # TEXTCOLOR:	 Currency Cosmetic 2
	SetBorderColor 100 50 30 255         # BORDERCOLOR:	 Wisdom
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # $Currency->Scroll->Wisdom %RF1 %H2 %TB-Currency-T8
	Class Currency
	BaseType "Scroll of Wisdom"
	SetFontSize 40
	SetTextColor 170 158 130 220         # TEXTCOLOR:	 Currency Cosmetic 2
	SetBorderColor 100 50 30 255         # BORDERCOLOR:	 Wisdom
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#===============================================================================================================
# [[1000]] OVERRIDE AREA 2 - Override the default rare rulesets here
#===============================================================================================================

# Example: This section displays 20% quality rares (between lvl 60 and 74), it's disabled by default, remove
# The #'s in front of the next lines to enable it and show the items with a Cyan border.

# Show #
# Rarity Rare
# Quality = 20
# Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
# ItemLevel >= 60
# SetFontSize 42
# SetBorderColor 0 255 255 255         # BORDERCOLOR:	 Crafting: T1
# SetBackgroundColor 0 0 0 255

#===============================================================================================================
# [[1100]] RARE ITEMS - TRINKETS (ENDGAME)
#===============================================================================================================

#------------------------------------
#   [1101] Rare trinkets 86+
#------------------------------------

Show # $Rare->Crafting $EGC->86 %D5 %TB-T1-Crafting
	ItemLevel >= 86
	Rarity Rare
	BaseType "Onyx Amulet" "Diamond Ring" "Two-Stone Ring"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

Show # $Rare->Crafting $EGC->86 %D4 %TB-T1-Crafting
	ItemLevel >= 86
	Rarity Rare
	BaseType "Ruby Ring" "Sapphire Ring" "Topaz Ring" "Prismatic" "Unset Ring" "Gold Ring" "Citrine Amulet" "Turquoise Amulet" "Agate Amulet" "Coral Ring" "Moonstone Ring" "Leather Belt" "Heavy Belt" "Amber Amulet" "Jade Amulet" "Lapis Amulet" "Rustic Sash"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

#------------------------------------
#   [1102] Rare trinkets 84+
#------------------------------------

Show # $Rare->Crafting $EGC->86 %D5 %TB-T1-Crafting
	ItemLevel >= 84
	Rarity Rare
	BaseType "Onyx Amulet" "Diamond Ring" "Two-Stone Ring"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 255 0 255         # BORDERCOLOR:	 Aspect: High Ring T2
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

Show # $Rare->Crafting $EGC->86 %D4 %TB-T1-Crafting
	ItemLevel >= 84
	Rarity Rare
	BaseType "Ruby Ring" "Sapphire Ring" "Topaz Ring" "Prismatic" "Unset Ring" "Gold Ring" "Citrine Amulet" "Turquoise Amulet" "Agate Amulet" "Coral Ring" "Moonstone Ring" "Leather Belt" "Heavy Belt" "Amber Amulet" "Jade Amulet" "Lapis Amulet" "Rustic Sash"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 255 0 255         # BORDERCOLOR:	 Aspect: High Ring T2
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

#------------------------------------
#   [1103] Breach Rings
#------------------------------------

Show # $Rare->Regal $x->Breach->Ring %H3
	ItemLevel >= 75
	Rarity <= Rare
	Class Rings
	BaseType "Breach"
	SetFontSize 36
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 130 25 255 255        # BORDERCOLOR:	 Breach
	SetBackgroundColor 65 20 80          # BACKGROUND:	 Breach

Show # $x->Breach->Ring %H3
	Rarity <= Rare
	Class Rings
	BaseType "Breach"
	SetFontSize 36
	SetBorderColor 130 25 255 255        # BORDERCOLOR:	 Breach
	SetBackgroundColor 65 20 80          # BACKGROUND:	 Breach

#------------------------------------
#   [1104] Rare trinkets "remaining"
#------------------------------------

Show # $Rare->T2 $Rare->Tiny %TB-Rare-Trinkets-T2 %H4
	ItemLevel >= 75
	Rarity Rare
	Class Rings Amulets Belts
	BaseType "Iron Ring" "Paua Ring" "Moonstone Ring" "Amethyst Ring" "Chain Belt" "Cloth Belt" "Studded Belt" "Coral Amulet" "Paua Amulet"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 160 200 50 255    # BACKGROUND:	 Trinket T2

Show # $Rare->T2 $Rare->Tiny %TB-Rare-Trinkets-T2 %H4
	ItemLevel >= 65
	Rarity Rare
	Class Rings Amulets Belts
	BaseType "Iron Ring" "Paua Ring" "Moonstone Ring" "Amethyst Ring" "Chain Belt" "Cloth Belt" "Studded Belt" "Coral Amulet" "Paua Amulet"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 160 200 50 255    # BACKGROUND:	 Trinket T2

Show # $Rare->T1 $Rare->Tiny %TC-Rare-Trinkets %D5
	ItemLevel >= 75
	Rarity Rare
	Class Rings Amulets Belts
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

Show # $Rare->T1 $Rare->Tiny %TC-Rare-Trinkets %D5
	ItemLevel >= 65
	Rarity Rare
	Class Rings Amulets Belts
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1

#===============================================================================================================
# [[1200]] RARE ITEMS - WEAPONS AND ARMORS (ENDGAME)
#===============================================================================================================

#------------------------------------
#   [1201] Rare crafting bases 86+
#------------------------------------

Show # $Rare->Crafting $EGC->86 %D5 %TB-T1-Crafting
	ItemLevel >= 86
	Rarity Rare
	BaseType "Eternal Burgonet" "Lion Pelt" "Colossal Tower Shield"
	SetFontSize 45
	SetTextColor 255 125 0               # TEXTCOLOR:	 Rare 86
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->Crafting $EGC->86 %D4 %TB-T1-Crafting
	ItemLevel >= 86
	Rarity Rare
	BaseType "Titan Gauntlets" "Slink Gloves" "Royal Burgonet" "Titan Greaves" "Slink Boots" "Hubris Circlet" "Vaal Axe" "Coronal Maul" "Exquisite Blade" "Fleshripper" "Harbinger Bow" "Gemini Claw" "Ambusher" "Siege Axe" "Harpy Rapier" "Demon Dagger" "Skean" "Spiraled Foil" "Jewelled Foil" "Profane Wand" "Sambar Sceptre" "Void Sceptre" "Imbued Wand" "Pinnacle Tower Shield" "Kris" "Prismatic" "Astral Plate" "Assassin's Garb" "Saintly Chainmail" "Harmonic Spirit Shield" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Sorcerer Boots" "Sorcerer Gloves" "Vaal Regalia"
	SetFontSize 45
	SetTextColor 255 125 0               # TEXTCOLOR:	 Rare 86
	SetBorderColor 255 125 0 255         # BORDERCOLOR:	 Aspect High Base
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

#------------------------------------
#   [1202] Rare crafting bases 83+
#------------------------------------

Show # $Rare->Crafting $EGC->84 %D4 %TB-T1-Crafting
	ItemLevel >= 84
	Rarity Rare
	BaseType "Titan Gauntlets" "Slink Gloves" "Royal Burgonet" "Lion Pelt" "Titan Greaves" "Slink Boots" "Hubris Circlet" "Eternal Burgonet"
	SetFontSize 45
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 220 220 0 255         # BORDERCOLOR:	 Aspect: 84
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->Crafting $EGC->84 %D1 %TB-T2-Crafting-84-ES
	ItemLevel >= 84
	Rarity Rare
	BaseType "Saintly Chainmail" "Harmonic Spirit Shield" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Sorcerer Boots" "Sorcerer Gloves" "Vaal Regalia"
	SetFontSize 40
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 220 220 0 255         # BORDERCOLOR:	 Aspect: 84
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->Crafting $EGC->84 %D2 %TB-T2-Crafting-84-Rest
	ItemLevel >= 84
	Rarity Rare
	BaseType "Profane Wand" "Sambar Sceptre" "Void Sceptre" "Imbued Wand" "Pinnacle Tower Shield" "Kris" "Prismatic" "Astral Plate" "Assassin's Garb"
	SetFontSize 40
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 220 220 0 255         # BORDERCOLOR:	 Aspect: 84
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->Crafting $EGC->83 %D2 %TB-T2-Crafting-83
	ItemLevel >= 83
	Rarity Rare
	BaseType "Vaal Axe" "Coronal Maul" "Exquisite Blade" "Fleshripper" "Harbinger Bow" "Gemini Claw" "Ambusher" "Siege Axe" "Demon Dagger" "Skean" "Spiraled Foil" "Jewelled Foil" "Imperial Claw"
	SetFontSize 40
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 220 220 0 255         # BORDERCOLOR:	 Aspect: 84
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

#------------------------------------
#   [1203] T1 rare items
#------------------------------------

Show # $Rare->T1 $Rare->Small %D4 %TB-RARE-T1-WepSmall %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Imperial Claw" "Gemini Claw" "Imbued Wand" "Platinum Kris" "Jewelled Foil" "Spiraled Foil" "Corsair Sword"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Imperial Claw" "Gemini Claw" "Imbued Wand" "Platinum Kris" "Jewelled Foil" "Spiraled Foil" "Corsair Sword"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->T1 $Rare->Small  %D4 %TB-RARE-T1-ArmSmall %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Titan Gauntlets" "Lion Pelt" "Slink Boots" "Titan Greaves" "Royal Burgonet" "Slink Gloves" "Hubris Circlet" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Crusader Buckler" "Eternal Burgonet" "Goliath Greaves" "Vaal Gauntlets"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Titan Gauntlets" "Lion Pelt" "Slink Boots" "Titan Greaves" "Royal Burgonet" "Slink Gloves" "Hubris Circlet" "Fossilised Spirit Shield" "Titanium Spirit Shield" "Crusader Buckler" "Eternal Burgonet" "Goliath Greaves" "Vaal Gauntlets"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->T1 %D4 %TB-RARE-T1-Wep %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Siege Axe" "Opal Sceptre" "Void Sceptre"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Siege Axe" "Opal Sceptre" "Void Sceptre"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # $Rare->T1 %D4 %TB-RARE-T1-Arm %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Astral Plate" "Archon Kite Shield"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Astral Plate" "Archon Kite Shield"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

#------------------------------------
#   [1204] T2 rare items
#------------------------------------

Show # $Rare->T2 $Rare->Small %D3 %TB-RARE-T2-WepSmall %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Terror Claw" "Eye Gouger" "Tornado Wand" "Opal Wand" "Kris" "Vaal Rapier" "Fancy Foil" "Dragoon Sword" "Profane Wand" "Skean" "Ambusher"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Terror Claw" "Eye Gouger" "Tornado Wand" "Opal Wand" "Kris" "Vaal Rapier" "Fancy Foil" "Dragoon Sword" "Profane Wand" "Skean" "Ambusher"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # $Rare->T2 %D3 %TB-RARE-T2-WepBig %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Vaal Axe" "Harbinger Bow"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Vaal Axe" "Harbinger Bow"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # $Rare->T2 %D3 %TB-RARE-T2-Wep %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Vaal Sceptre" "Eternal Sword" "Behemoth Mace" "Vaal Hatchet" "Runic Hatchet" "Sambar Sceptre"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Vaal Sceptre" "Eternal Sword" "Behemoth Mace" "Vaal Hatchet" "Runic Hatchet" "Sambar Sceptre"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # $Rare->T2 $Rare->Small %D3 %TB-RARE-T2-ArmSmall %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Crusader Boots" "Nightmare Bascinet" "Murder Boots" "Dragonscale Boots" "Vaal Greaves" "Stealth Boots" "Murder Mitts" "Dragonscale Gauntlets" "Crusader Gloves" "Praetor Crown" "Deicide Mask" "Sinner Tricorne" "Arcanist Slippers" "Arcanist Gloves" "Mind Cage" "Sorcerer Boots" "Sorcerer Gloves" "Harmonic Spirit Shield" "Supreme Spiked Shield" "Shagreen Boots" "Imperial Buckler" "Ancient Greaves" "Ancient Gauntlets" "Ezomyte Burgonet" "Vaal Spirit Shield"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Crusader Boots" "Nightmare Bascinet" "Murder Boots" "Dragonscale Boots" "Vaal Greaves" "Stealth Boots" "Murder Mitts" "Dragonscale Gauntlets" "Crusader Gloves" "Praetor Crown" "Deicide Mask" "Sinner Tricorne" "Arcanist Slippers" "Arcanist Gloves" "Mind Cage" "Sorcerer Boots" "Sorcerer Gloves" "Harmonic Spirit Shield" "Supreme Spiked Shield" "Shagreen Boots" "Imperial Buckler" "Ancient Greaves" "Ancient Gauntlets" "Ezomyte Burgonet" "Vaal Spirit Shield"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # $Rare->T2 %D3 %TB-RARE-T2-Arm %UP
	ItemLevel >= 75
	Rarity Rare
	BaseType "Glorious Plate" "Spike-Point Arrow Quiver" "Vaal Regalia" "Elegant Round Shield" "Pinnacle Tower Shield" "Assassin's Garb" "Broadhead Arrow Quiver" "Mosaic Kite Shield" "Colossal Tower Shield" "Cardinal Round Shield"
	SetFontSize 40
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show
	ItemLevel >= 65
	Rarity Rare
	BaseType "Glorious Plate" "Spike-Point Arrow Quiver" "Vaal Regalia" "Elegant Round Shield" "Pinnacle Tower Shield" "Assassin's Garb" "Broadhead Arrow Quiver" "Mosaic Kite Shield" "Colossal Tower Shield" "Cardinal Round Shield"
	SetFontSize 40
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

#------------------------------------
#   [1205] Other Conditions
#------------------------------------

Show # %D3 %UP $Recipe->RGB->Small
	Width <= 2
	Height <= 2
	ItemLevel >= 75
	Rarity = Rare
	SocketGroup RGB
	SetFontSize 36
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show
	Width <= 2
	Height <= 2
	ItemLevel >= 65
	Rarity = Rare
	SocketGroup RGB
	SetFontSize 36
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D3 %UP $Recipe->RGB->Small
	Width <= 1
	Height <= 3
	ItemLevel >= 75
	Rarity = Rare
	SocketGroup RGB
	SetFontSize 36
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show
	Width <= 1
	Height <= 3
	ItemLevel >= 65
	Rarity = Rare
	SocketGroup RGB
	SetFontSize 36
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D1 %UP $Recipe->RGB->Large
	ItemLevel >= 75
	Rarity = Rare
	SocketGroup RGB
	SetTextColor 255 190 0 255           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show
	ItemLevel >= 65
	Rarity = Rare
	SocketGroup RGB
	SetTextColor 255 255 119 255         # TEXTCOLOR:	 T2 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

#------------------------------------
#   [1206] 1H Daggers
#------------------------------------

Show # $Rare->T3->Daggers $Rare->Small %D2 %TD-Rare-Good-Daggers %UP
	ItemLevel >= 75
	DropLevel >= 56
	Rarity Rare
	Class Daggers
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 56
	Rarity Rare
	Class Daggers
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Daggers $Rare->Small %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class Daggers
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class Daggers
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1207] 1H Claws
#------------------------------------

Show # $Rare->T3->Claws $Rare->Small %D2 %TD-Rare-Good-Claws %UP
	ItemLevel >= 75
	DropLevel >= 55
	Rarity Rare
	Class Claws
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 55
	Rarity Rare
	Class Claws
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Claws $Rare->Small %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class Claws
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class Claws
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1208] 1H Wands
#------------------------------------

Show # $Rare->T3->Wands $Rare->Small %D2 %TD-Rare-Good-Wands %UP
	ItemLevel >= 75
	DropLevel >= 59
	Rarity Rare
	Class Wands
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 59
	Rarity Rare
	Class Wands
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Wands $Rare->Small %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class Wands
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class Wands
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1209] 1H Foils
#------------------------------------

Show # $Rare->T3->Foils $Rare->Small %D2 %TD-Rare-Good-Swords %UP
	Height = 4
	ItemLevel >= 75
	DropLevel >= 58
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	Height = 4
	ItemLevel >= 65
	DropLevel >= 58
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Foils $Rare->Small %D1 %UP
	Height = 4
	ItemLevel >= 75
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	Height = 4
	ItemLevel >= 65
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1210] 1H Swords
#------------------------------------

Show # $Rare->T3->1hSwords %D2 %TD-Rare-Good-Swords %UP
	Height < 4
	ItemLevel >= 75
	DropLevel >= 56
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	Height < 4
	ItemLevel >= 65
	DropLevel >= 56
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->1hSwords %D1 %UP
	Height < 4
	ItemLevel >= 75
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	Height < 4
	ItemLevel >= 65
	Rarity Rare
	Class "One Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1211] 1H Maces
#------------------------------------

Show # $Rare->T3->1hMaces %D2 %TD-Rare-Good-Maces %UP
	ItemLevel >= 75
	DropLevel >= 62
	Rarity Rare
	Class "One Hand Maces"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 62
	Rarity Rare
	Class "One Hand Maces"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->1hMaces %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "One Hand Maces"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "One Hand Maces"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1212] 1H Axes
#------------------------------------

Show # $Rare->T3->1hAxes %D2 %TD-Rare-Good-Axes %UP
	ItemLevel >= 75
	DropLevel >= 57
	Rarity Rare
	Class "One Hand Axes"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 57
	Rarity Rare
	Class "One Hand Axes"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->1hAxes %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "One Hand Axes"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "One Hand Axes"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1213] 1H Sceptres
#------------------------------------

Show # $Rare->T3->Sceptres %D2 %TD-Rare-Good-Sceptres %UP
	ItemLevel >= 75
	DropLevel >= 55
	Rarity Rare
	Class "Sceptres"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 55
	Rarity Rare
	Class "Sceptres"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Sceptres %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Sceptres"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Sceptres"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1214] 2H Staves
#------------------------------------

Show # $Rare->T3->Staves %D2 %TD-Rare-Good-Staves %UP
	ItemLevel >= 75
	DropLevel >= 68
	Rarity Rare
	Class "Staves"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 68
	Rarity Rare
	Class "Staves"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Staves %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Staves"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Staves"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1215] 2H Swords, Axes, Maces
#------------------------------------

Show # $Rare->T3->2H %D2 %TD-Rare-Good-2H-Axes-Maces-Swords %UP
	ItemLevel >= 75
	DropLevel >= 63
	Rarity Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 63
	Rarity Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->2H %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Two Hand Maces" "Two Hand Axes" "Two Hand Swords"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1216] 2H Bows
#------------------------------------

Show # $Rare->T3->Bows %D2 %TD-Rare-Good-Bows %UP
	ItemLevel >= 75
	DropLevel >= 57
	Rarity Rare
	Class "Bows"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 57
	Rarity Rare
	Class "Bows"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Bows %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Bows"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Bows"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1217] AR: Gloves, Boots, Helmets
#------------------------------------

#Show # $Rare->T3->ArmorSmall $Rare->Small %D2 %UP
#	LinkedSockets = 4
#	ItemLevel >= 65
#	SetTextColor 220 220 119 200
#	Class "Gloves" "Boots" "Helmets"
#	Rarity Rare
#	SetFontSize 40
#	SetBorderColor 0 140 240 219         # BORDERCOLOR:	 Rare 4L Experimental
#	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Rares - T3

Show # $Rare->T3->ArmorSmall $Rare->Small %D2 %TD-Rare-Good-SmallArmor %UP
	ItemLevel >= 75
	DropLevel >= 20
	Rarity Rare
	Class "Gloves" "Boots" "Helmets"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 20
	Rarity Rare
	Class "Gloves" "Boots" "Helmets"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->ArmorSmall $Rare->Small %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Gloves" "Boots" "Helmets"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Gloves" "Boots" "Helmets"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1218] AR: Body Armors
#------------------------------------

Show # $Rare->T3->Armor %D2 %TD-Rare-Good-Armor %UP
	ItemLevel >= 75
	DropLevel >= 55
	Rarity Rare
	Class "Body Armour"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel >= 55
	Rarity Rare
	Class "Body Armour"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Armor %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Body Armour"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Body Armour"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1219] OH: Shields
#------------------------------------

Show # $Rare->T3->Shields $Rare->Small %D2 %TD-Rare-Good-Small-Shields %UP
	Width <= 2
	Height <= 2
	ItemLevel >= 75
	DropLevel >= 58
	Rarity Rare
	Class "Shields"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	Width <= 2
	Height <= 2
	ItemLevel >= 65
	DropLevel >= 58
	Rarity Rare
	Class "Shields"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Shields $Rare->Small %D1 %UP
	Width <= 2
	Height <= 2
	ItemLevel >= 75
	Rarity Rare
	Class "Shields"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	Width <= 2
	Height <= 2
	ItemLevel >= 65
	Rarity Rare
	Class "Shields"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show # $Rare->T3->Shields %D2 %UP %TD-Rare-Good-Big-Shields
	ItemLevel >= 75
	DropLevel > 62
	Rarity Rare
	Class "Shields"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	DropLevel > 62
	Rarity Rare
	Class "Shields"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Shields %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Shields"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Shields"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#------------------------------------
#   [1220] OH: Quivers
#------------------------------------

Show # $Rare->T3->Quivers %D2 %TB-Rare-Good-Quivers %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Quivers"
	BaseType "Spike-Point Arrow Quiver" "Broadhead Arrow Quiver" "Penetrating Arrow Quiver"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Quivers"
	BaseType "Spike-Point Arrow Quiver" "Broadhead Arrow Quiver" "Penetrating Arrow Quiver"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # $Rare->T4->Quivers %D1 %UP
	ItemLevel >= 75
	Rarity Rare
	Class "Quivers"
	SetTextColor 255 190 0 220           # TEXTCOLOR:	 Rares - Level - 75+
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

Show
	ItemLevel >= 65
	Rarity Rare
	Class "Quivers"
	SetTextColor 220 220 119 220         # TEXTCOLOR:	 T3 Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 150         # BACKGROUND:	 Neutral T6

#===============================================================================================================
# [[1300]] HIDE LAYER 2 - RARE ITEMS (65+ ONLY FOR NON-REGULAR VERSIONS)
#===============================================================================================================
# Hide remaining rares

Hide # $Rare->Regal $Rare->Hidden $Rare->Small  Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	Width <= 1
	Height <= 4
	ItemLevel >= 75
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

Hide # $Rare->Hidden $Rare->Small Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	Width <= 1
	Height <= 4
	ItemLevel >= 65
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

Hide # $Rare->Regal $Rare->Hidden $Rare->Small Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	Width <= 2
	Height <= 2
	ItemLevel >= 75
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

Hide # $Rare->Hidden $Rare->Small Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	Width <= 2
	Height <= 2
	ItemLevel >= 65
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

Hide # $Rare->Regal $Rare->Hidden Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	ItemLevel >= 75
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetTextColor 255 190 0               # TEXTCOLOR:	 Rare 75+
	SetBorderColor 0 0 0 100             # BORDERCOLOR:	 Neutral T4
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

Hide # $Rare->Hidden Hide remaining rare endgame items (note: on the regular version this line never happens) %TC-Rareable-Junkable-Expanded
	ItemLevel >= 65
	Rarity = Rare
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Daggers" "Shields" "Belts" "Rings" "Amulets"
	SetFontSize 24
	SetBorderColor 0 0 0 100             # BORDERCOLOR:	 Neutral T4
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

#===============================================================================================================
# [[1400]] OVERRIDE AREA 3 - Override Map, Gem and Flask drops here
#===============================================================================================================

#===============================================================================================================
# [[1500]] Gems
#===============================================================================================================

#------------------------------------
#   [1501] Special Gems
#------------------------------------

Show # $Gem->T1->Qual %TB-Qual-Top-Gem
	Class Gems
	BaseType "Empower" "Enlighten" "Enhance"
	GemLevel >= 2
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 150 180 255        # BORDERCOLOR:	 Gem T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $Gem->T1->Qual %TB-Qual-Top-Gem
	Corrupted False
	Quality >= 15
	Class Gems
	BaseType "Empower" "Enlighten"
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 150 180 255        # BORDERCOLOR:	 Gem T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Triangle
	PlayEffect Red

Show # $Gem->T1 %TB-Top-Gem
	Class Gems
	BaseType "Portal" "Empower" "Enlighten" "Vaal Haste" "Vaal Grace" "Item Quantity" "Vaal Breach"
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 150 180 255        # BORDERCOLOR:	 Gem T1
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Yellow Triangle
	PlayEffect White

#------------------------------------
#   [1502] Top Gems
#------------------------------------

Show # $Gem->Qual->20
	Class Gems
	GemLevel >= 20
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 150 180 255        # BORDERCOLOR:	 Gem T1
	SetBackgroundColor 6 0 60            # BACKGROUND:	 20QualGem
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Triangle
	PlayEffect Yellow

Show # $Gem->Qual->20
	Quality >= 20
	Class Gems
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 150 180 255        # BORDERCOLOR:	 Gem T1
	SetBackgroundColor 6 0 60            # BACKGROUND:	 20QualGem
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 0 Yellow Triangle
	PlayEffect Yellow

#------------------------------------
#   [1503] Quality Gems
#------------------------------------

Show # $Gem->Qual->15
	Quality >= 14
	Class Gems
	SetFontSize 45
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 30 200 200 255        # BORDERCOLOR:	 Gem T2
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White Temp

Show # $Gem->Qual %D4
	Quality >= 1
	Class Gems
	SetFontSize 40
	SetBorderColor 30 150 180 150        # BORDERCOLOR:	 Gem T3

#------------------------------------
#   [1504] Leveled Gems
#------------------------------------

Show # $Gem->Level-19 %D4
	Class Gems
	GemLevel >= 18
	SetFontSize 40
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

Show # $Gem->Level-19 %D3
	Class Gems
	GemLevel >= 10
	SetFontSize 40
	SetTextColor 30 200 200 255          # TEXTCOLOR:	 Gem High
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

Show # $Gem->T2 %TB-DropOnly-Gem %D4
	Class Gems
	BaseType "Detonate Mines" "Added Chaos Damage" "Vaal" "Enhance"
	SetFontSize 40
	SetBorderColor 30 150 180 150        # BORDERCOLOR:	 Gem T3

#------------------------------------
#   [1505] Other gems
#------------------------------------

Show # $Gem %H2
	Class Gems
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

#===============================================================================================================
# [[1600]] UTILITY FLASKS (Levelling Rules)
#===============================================================================================================

Show # $lvl $flasks->utility %TB-T1-Leveling-Flask %REMS1
	Quality >= 1
	ItemLevel <= 65
	Rarity <= Magic
	BaseType "Stibnite Flask" "Quicksilver Flask" "Silver Flask" "Bismuth Flask" "Basalt Flask" "Granite Flask" "Diamond Flask" "Jade Flask" "Ruby Flask" "Sapphire Flask" "Topaz Flask"
	SetFontSize 45
	SetBorderColor 50 200 125            # BORDERCOLOR:	 Flask
	SetBackgroundColor 25 100 75         # BACKGROUND:	 Flasks
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show # $lvl $flasks->utility %TB-T1-Leveling-Flask %REMS1
	ItemLevel <= 65
	Rarity <= Magic
	BaseType "Stibnite Flask" "Quicksilver Flask" "Silver Flask" "Bismuth Flask" "Basalt Flask" "Granite Flask" "Diamond Flask" "Jade Flask" "Ruby Flask" "Sapphire Flask" "Topaz Flask"
	SetFontSize 45
	SetBorderColor 50 200 125            # BORDERCOLOR:	 Flask
	SetBackgroundColor 25 100 75         # BACKGROUND:	 Flasks
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

#===============================================================================================================
# [[1700]] HIDE LAYER 3: Random Endgame Flasks
#===============================================================================================================

Hide #
	ItemLevel >= 69
	Rarity <= Magic
	BaseType Flask
	SetFontSize 18
	SetBorderColor 0 0 0 150             # BORDERCOLOR:	 Neutral T3
	SetBackgroundColor 0 0 0 165         # BACKGROUND:	 Neutral T5

#===============================================================================================================
# [[1800]] Maps, fragments and labyrinth items
#===============================================================================================================

#------------------------------------
#   [1801] Unique Maps
#------------------------------------

Show # $uniques->T1 $maps->unique
	Rarity Unique
	Class Maps
	BaseType "Chateau Map" "Museum Map"
	SetFontSize 45
	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
	SetBorderColor 175 96 37 255         # BORDERCOLOR:	 Aspect Unique
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $uniques->T2  $maps->unique
	Rarity Unique
	Class Maps
	BaseType "Moon Temple Map" "Courtyard Map" "Temple Map" "Shore Map"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Yellow Star
	PlayEffect Yellow

Show # $uniques $maps->unique Maps:Unique
	Rarity Unique
	Class Maps
	SetFontSize 45
	SetBorderColor 175 96 37 255         # BORDERCOLOR:	 Aspect Unique
	SetBackgroundColor 53 13 13 255      # BACKGROUND:	 Unique T3
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Brown Star
	PlayEffect Brown

#------------------------------------
#   [1802] Labyrinth items, Offerings
#------------------------------------

Show # $frag->%TB-OfferingToTheGoddess
	BaseType "Offering to the Goddess"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	MinimapIcon 0 Yellow Square
	PlayEffect Yellow

Show #
	Class "Labyrinth"
	SetFontSize 45
	SetTextColor 74 230 58               # TEXTCOLOR:	 Quest
	SetBorderColor 74 230 58             # BORDERCOLOR:	 Quest Item
	MinimapIcon 1 Green Hexagon
	PlayEffect Green Temp

#------------------------------------
#   [1803] Shaped Maps
#------------------------------------

Show # $maps->elder->Top
	Class Maps
	ElderMap True
	SetFontSize 45
	SetTextColor 100 0 122 255           # TEXTCOLOR:	 High Map
	SetBorderColor 100 0 255 255         # BORDERCOLOR:	 T0 Map
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Square
	PlayEffect Red

Show # $maps->shaped->Top
	ShapedMap True
	DropLevel >= 77
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 0 Red Square
	PlayEffect Red

Show # $maps->shaped->High
	ShapedMap True
	DropLevel >= 73
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 200 200 200 255   # BACKGROUND:	 High Maps
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 0 Red Square
	PlayEffect Yellow

Show # $maps->shaped->Mid
	ShapedMap True
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	MinimapIcon 2 Yellow Square
	PlayEffect White

#------------------------------------
#   [1804] Top tier maps (T15-16)
#------------------------------------

Show # $maps->T16
	DropLevel >= 83
	Class Maps
	SetFontSize 45
	SetTextColor 100 0 122 255           # TEXTCOLOR:	 High Map
	SetBorderColor 100 0 255 255         # BORDERCOLOR:	 T0 Map
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Square
	PlayEffect Red

Show # $maps->T15
	DropLevel >= 82
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 0 Red Square
	PlayEffect Red

#------------------------------------
#   [1805] High tier maps(T11-14)
#------------------------------------

Show # $maps->T14
	DropLevel >= 81
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 200 200 200 255   # BACKGROUND:	 High Maps
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 1 Red Square
	PlayEffect Yellow

Show # $maps->T13
	DropLevel >= 80
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 200 200 200 255   # BACKGROUND:	 High Maps
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 1 Red Square
	PlayEffect Yellow

Show # $maps->T12
	DropLevel >= 79
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 200 200 200 255   # BACKGROUND:	 High Maps
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 1 Red Square
	PlayEffect Yellow

Show # $maps->T11
	DropLevel >= 78
	Class Maps
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 200 200 200 255   # BACKGROUND:	 High Maps
	PlayAlertSound 5 300                 # DROPSOUND:	 High Map Sound
	MinimapIcon 1 Red Square
	PlayEffect Yellow

#------------------------------------
#   [1806] Mid tier maps (T6-10)
#------------------------------------

Show # $maps->Vaal
	Identified True
	Class Maps
	HasExplicitMod "Vaal"
	SetFontSize 45
	SetBorderColor 0 240 190 240         # BORDERCOLOR:	 Special Base
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	MinimapIcon 2 Yellow Square
	PlayEffect White

Show # $maps->T10
	DropLevel >= 77
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	MinimapIcon 2 Yellow Square
	PlayEffect White

#------------------------------------
#  T9 - Maps
#------------------------------------

Show # $maps->T9
	ItemLevel < 84
	DropLevel >= 76
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	DisableDropSound True
	MinimapIcon 2 Yellow Square
	PlayEffect White

Show # %H4 $maps->outleveled
	DropLevel >= 76
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T8 - Maps
#------------------------------------

Show # $maps->T8
	ItemLevel < 83
	DropLevel >= 75
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	DisableDropSound True
	MinimapIcon 2 Yellow Square
	PlayEffect White

Show # %H4 $maps->outleveled
	DropLevel >= 75
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T7 - Maps
#------------------------------------

Show # $maps->T7
	ItemLevel < 82
	DropLevel >= 74
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	DisableDropSound True
	MinimapIcon 2 Yellow Square
	PlayEffect White

Show # %H4 $maps->outleveled
	DropLevel >= 74
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T6 - Maps
#------------------------------------

Show # $maps->T6
	ItemLevel < 81
	DropLevel >= 73
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	DisableDropSound True
	MinimapIcon 2 Yellow Square
	PlayEffect White

Show # %H4 $maps->outleveled
	DropLevel >= 73
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#   [1807] Low tier maps (T1-T5)
#------------------------------------

Show # $maps->T5
	ItemLevel < 80
	DropLevel >= 72
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound
	DisableDropSound True
	MinimapIcon 2 White Square
	PlayEffect White Temp

Show # %H3 $maps->outleveled
	DropLevel >= 72
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T4 - Maps
#------------------------------------

Show # $maps->T4
	ItemLevel < 79
	DropLevel >= 71
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4
	PlayAlertSound 4 150                 # DROPSOUND:	 Low Map Sound
	DisableDropSound True
	MinimapIcon 2 White Square
	PlayEffect White Temp

Show # %H3 $maps->outleveled
	DropLevel >= 71
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T3 - Maps
#------------------------------------

Show # $maps->T3
	ItemLevel < 78
	DropLevel >= 70
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4
	PlayAlertSound 4 150                 # DROPSOUND:	 Low Map Sound
	DisableDropSound True
	MinimapIcon 2 White Square
	PlayEffect White Temp

Show # %H3 $maps->outleveled
	DropLevel >= 70
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T2 - Maps
#------------------------------------

Show # $maps->T2
	ItemLevel < 77
	DropLevel = 69
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4
	PlayAlertSound 4 150                 # DROPSOUND:	 Low Map Sound
	DisableDropSound True
	MinimapIcon 2 White Square
	PlayEffect White Temp

Show # %H3 $maps->outleveled
	DropLevel = 69
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

#------------------------------------
#  T1 - Maps
#------------------------------------

Show # $maps->T1
	ItemLevel < 76
	DropLevel <= 68
	Class Maps
	SetFontSize 45
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4
	PlayAlertSound 4 150                 # DROPSOUND:	 Low Map Sound
	DisableDropSound True
	MinimapIcon 2 White Square
	PlayEffect White Temp

Show # %H3 $maps->outleveled
	DropLevel < 69
	Class Maps
	SetTextColor 150 150 150             # TEXTCOLOR:	 outleveled
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3
	DisableDropSound True

# This should never happen. If you find pink maps, you probably deleted/commented sections above
# or should update the filter. Alternatively use www.filterblade.xyz

Show # Safetyline / Missing map
	Class Maps
	SetFontSize 45
	SetTextColor 255 0 255 255           # TEXTCOLOR:	 Error
	SetBorderColor 255 0 255 255         # BORDERCOLOR:	 Error
	PlayAlertSound 4 300                 # DROPSOUND:	 Map Sound

#------------------------------------
#   [1808] Map fragments
#------------------------------------

Show # $x->Legacy->AncientRelicKey
	Class "Misc Map Items"
	BaseType "Ancient Reliquary Key" "Timeworn Reliquary Key"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $x->Legacy->AncientRelicKey
	Class "Misc Map Items"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Blue Triangle
	PlayEffect Blue

Show # $Fragments->T1 $x->Fragments->Mortal %TB-Fragments-T1
	Class "Map Fragments"
	BaseType "Mortal Hope" "Mortal Ignorance"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Triangle
	PlayEffect Red

Show # $Fragments->T2 %TB-Fragments-T2
	Class "Map Fragments"
	BaseType "Mortal" "Eber's Key" "Yriel's Key" "Inya's Key" "Volkuur's Key" "Sacrifice at Midnight" "Fragment of the Phoenix" "Fragment of the Minotaur" "Fragment of the Chimera" "Fragment of the Hydra" "Breachstone"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Yellow Triangle
	PlayEffect Yellow

Show # $Fragments->Vessel %TB-Fragments-Vessel
	Class "Map Fragments"
	BaseType "Divine Vessel"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White

Show # $Fragments
	Class "Map Fragments"
	SetFontSize 45
	SetTextColor 159 15 213 255          # TEXTCOLOR:	 Fragment
	SetBorderColor 159 15 213 255        # BORDERCOLOR:	 Map Fragment
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White

Show # $Fragments->Vessel
	Class "Pantheon Soul"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White

#===============================================================================================================
# [[1900]] Currency - PART 2 - Rare currency
#===============================================================================================================

#------------------------------------
#   [1901] Regular Rare Currency
#------------------------------------

Show # $Currency->High-T1 %TB-Currency-T1.5
	Class Currency
	BaseType "Master Cartographer's Sextant" "Journeyman Cartographer's Sextant"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 240 90 35 255     # BACKGROUND:	 Currency T2
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	DisableDropSound True
	MinimapIcon 1 Yellow Circle
	PlayEffect Yellow

Show # $Currency->High-T2 %TB-Currency-T2
	Class Currency
	BaseType "Regal Orb" "Orb of Regret" "Chaos Orb" "Gemcutter's Prism" "Stacked Deck" "Apprentice Cartographer's Sextant"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 249 150 25 255    # BACKGROUND:	 Currency T3
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	DisableDropSound True
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $Currency->High-T3 %TB-Currency-T3
	Class Currency
	BaseType "Blessed Orb" "Orb of Fusing" "Orb of Alchemy" "Cartographer's Chisel" "Engineer's Orb" "Orb of Horizons" "Orb of Binding" "Bestiary Orb" "Orb of Scouring" "Vaal Orb"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 213 159 0 255     # BACKGROUND:	 Currency T4
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	DisableDropSound True
	MinimapIcon 2 White Circle
	PlayEffect White

#------------------------------------
#   [1902] Harbinger Currency
#------------------------------------

Show # $Currency->Harbinger->T1 %TB-Currency-Harbinger-ShardsT1
	Class Currency
	BaseType "Annulment Shard" "Harbinger's Shard" "Ancient Shard" "Exalted Shard"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 40 220 255 255        # BORDERCOLOR:	 Harbinger Currency
	SetBackgroundColor 80 95 210 255     # BACKGROUND:	 Shard T1
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $Currency->Harbinger->T2 %TB-Currency-Harbinger-ShardsT2 %H4
	Class Currency
	BaseType "Horizon Shard" "Engineer's Shard" "Binding Shard" "Regal Shard" "Chaos Shard"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 135 140 100 255   # BACKGROUND:	 Shard T2

#------------------------------------
#   [1903] Incursion Currency
#------------------------------------

Show # $Currency->Incursion->Vial
	Class Currency
	BaseType "Vial of Awakening" "Vial of Sacrifice" "Vial of the Ghost"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $Currency->Incursion->Vial
	Class Currency
	BaseType "Vial of Transcendence" "Vial of Summoning" "Vial of the Ritual" "Vial of Fate" "Vial of Consequence" "Vial of Dominance"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White

#------------------------------------
#   [1904] Delve Currency - Resonators
#------------------------------------

Show # $Currency->Reso-T1 %TB-Currency-T1.5
	Class "Delve Socketable Currency"
	BaseType "Prime Alchemical Resonator" "Prime Chaotic Resonator"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 240 90 35 255     # BACKGROUND:	 Currency T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	DisableDropSound True
	MinimapIcon 0 Red Circle
	PlayEffect Red

Show # $Currency->Reso-T2 %TB-Currency-T1.5
	Class "Delve Socketable Currency"
	BaseType "Powerful Chaotic Resonator"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 249 150 25 255    # BACKGROUND:	 Currency T3
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	DisableDropSound True
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $Currency->Reso-T3
	Class "Delve Socketable Currency"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 200             # BORDERCOLOR:	 Neutral T2
	SetBackgroundColor 210 178 135 255   # BACKGROUND:	 Currency T5

#------------------------------------
#   [1905] Delve Currency - Fossil
#------------------------------------

Show # $Currency->Fossil->T1 %TB-Currency-Fossil-T1
	Class Currency
	BaseType "Faceted Fossil" "Fractured Fossil" "Hollow Fossil" "Glyphic Fossil" "Shuddering Fossil"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $Currency->Fossil->T2 %TB-Currency-Fossil-T2
	Class Currency
	BaseType "Bloodstained Fossil" "Tangled Fossil" "Gilded Fossil" "Sanctified Fossil" "Lucent Fossil"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 240 90 35 255     # BACKGROUND:	 Currency T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	DisableDropSound True
	MinimapIcon 0 Red Circle
	PlayEffect Red

Show # $Currency->Fossil->T3
	Class Currency
	BaseType "Fossil"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 249 150 25 255    # BACKGROUND:	 Currency T3
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	DisableDropSound True
	MinimapIcon 1 Yellow Circle
	PlayEffect Yellow

#------------------------------------
#   [1906] Bestiary Currency
#------------------------------------

# You shall be missed Einhar... Stupid Beast

#Show #$Currency->Net->T1
#	Class Currency
#	BaseType "Necromancy Net"
#	SetFontSize 45
#	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
#	SetBackgroundColor 213 159 0 255     # BACKGROUND:	 T3 Currency
#	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#Show #$Currency->Net->T1 %H4
#	Class Currency
#	BaseType "Thaumaturgical Net"
#	SetFontSize 45
#	SetTextColor 155 210 135 255         # TEXTCOLOR:	 Net Color
#	SetBorderColor 0 255 36 255          # BORDERCOLOR:	 Net Color 4
#	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 T6-10 maps, currency, talismans
#	DisableDropSound True

#Show #$Currency->Net->T2 %H3
#	Class Currency
#	BaseType "Strong Steel Net"
#	SetFontSize 45
#	SetTextColor 155 210 135 255         # TEXTCOLOR:	 Net Color
#	SetBorderColor 0 120 16 255          # BORDERCOLOR:	 Net Color 3
#	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 T6-10 maps, currency, talismans
#	DisableDropSound True

#Show #$Currency->Net->T3 %H2
#	Class Currency
#	BaseType "Simple Iron Net" "Reinforced Iron Net" "Strong Iron Net" "Simple Steel Net" "Reinforced Steel Net"
#	SetFontSize 40
#	SetTextColor 155 210 135 255         # TEXTCOLOR:	 Net Color
#	SetBorderColor 110 110 110 255       # BORDERCOLOR:	 Net Color 1
#	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 T6-10 maps, currency, talismans
#	DisableDropSound True

#Show #$Currency->Net->T4 %H2
#	Class Currency
#	BaseType "Simple Rope Net" "Reinforced Rope Net" "Strong Rope Net"
#	SetFontSize 40
#	SetTextColor 155 210 135 255         # TEXTCOLOR:	 Net Color
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
#	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 T6-10 maps, currency, talismans
#	DisableDropSound True

#------------------------------------
#   [1907] Top Currency
#------------------------------------

Show # $Currency->Harbinger->Top %TB-Currency-T1-higher
	Class Currency
	BaseType "Mirror of Kalandra" "Exalted Orb" "Mirror Shard" "Eternal Orb" "Albino Rhoa Feather"
	SetFontSize 45
	SetTextColor 255 0 0 255             # TEXTCOLOR:	 T0 Item
	SetBorderColor 255 0 0 255           # BORDERCOLOR:	 T0 Item
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $Currency->Harbinger->Top %TB-Currency-T1-lower
	Class Currency
	BaseType "Divine Orb" "Orb of Annulment" "Harbinger's Orb" "Ancient Orb"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 240 90 35 255     # BACKGROUND:	 Currency T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	DisableDropSound True
	MinimapIcon 0 Red Circle
	PlayEffect Red

#------------------------------------
#   [1908] Essence Tier List
#------------------------------------

Show # $Currency->Ess->T1 %TB-Essence-T1
	Class Currency
	BaseType "Shrieking Essence of" "Essence of Hysteria" "Essence of Insanity" "Essence of Horror" "Essence of Delirium" "Deafening Essence of" "Remnant of Corruption"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Yellow Circle
	PlayEffect Yellow

Show # $Currency->Ess->T2
	Class Currency
	BaseType "Screaming Essence of"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 15 180 200 255    # BACKGROUND:	 Ess T2
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $Currency->Ess->T3
	Class Currency
	BaseType "Wailing Essence of"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 30 159 200 255    # BACKGROUND:	 Ess T3
	MinimapIcon 2 White Circle
	PlayEffect White Temp

Show # $Currency->Ess->T4
	Class Currency
	BaseType "Weeping Essence of"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 30 159 200 225    # BACKGROUND:	 Ess T4
	MinimapIcon 2 White Circle
	PlayEffect White Temp

Show # $Currency->Ess->T5
	Class Currency
	BaseType "Muttering Essence of"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 30 159 200 200    # BACKGROUND:	 Ess T5

Show #$Currency->Ess->T6
	Class Currency
	BaseType "Whispering Essence of"
	SetFontSize 40
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 30 159 200 175    # BACKGROUND:	 Ess T6

#------------------------------------
#   [1909] Perandus
#------------------------------------

Show # $x->PerandusCoin $Currency->Special
	Class Currency
	BaseType "Perandus Coin"
	StackSize >= 15
	SetFontSize 45
	SetTextColor 255 178 135 255         # TEXTCOLOR:	 Perandus Coin
	SetBorderColor 255 178 135 135       # BORDERCOLOR:	 Perandus Coin
	PlayEffect White Temp

Show # $x->PerandusCoin $Currency->Special %H3
	Class Currency
	BaseType "Perandus Coin"
	StackSize < 4
	SetFontSize 36
	SetTextColor 255 178 135 255         # TEXTCOLOR:	 Perandus Coin
	SetBorderColor 255 178 135 135       # BORDERCOLOR:	 Perandus Coin

Show # $x->PerandusCoin $Currency->Special
	Class Currency
	BaseType "Perandus Coin"
	SetFontSize 40
	SetTextColor 255 178 135 255         # TEXTCOLOR:	 Perandus Coin
	SetBorderColor 255 178 135 135       # BORDERCOLOR:	 Perandus Coin

#------------------------------------
#   [1910] Breach
#------------------------------------

Show # $x->Breach->Blessing->T1
	Class Currency
	BaseType "Blessing of Chayula"
	SetFontSize 45
	SetTextColor 130 25 255 255          # TEXTCOLOR:	 Blessing
	SetBorderColor 130 25 255 255        # BORDERCOLOR:	 Breach
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $x->Breach->Blessing->T2
	Class Currency
	BaseType "Blessing of Xoph" "Blessing of Esh" "Blessing of Tul" "Blessing of Uul-Netol"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 0 Yellow Circle
	PlayEffect Yellow

Show # $x->Breach->Splinter->T1
	Class Currency
	BaseType "Splinter of Chayula"
	SetFontSize 45
	SetTextColor 255 235 235 255         # TEXTCOLOR:	 Splinter
	SetBorderColor 210 20 210 255        # BORDERCOLOR:	 Chayula
	SetBackgroundColor 65 20 80          # BACKGROUND:	 Breach
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

Show # $x->Breach->Splinter->T2 %HS5
	Class Currency
	BaseType "Splinter of Xoph" "Splinter of Esh" "Splinter of Tul" "Splinter of Uul-Netol"
	SetFontSize 45
	SetTextColor 255 235 235 255         # TEXTCOLOR:	 Splinter
	SetBorderColor 130 25 255 255        # BORDERCOLOR:	 Breach
	SetBackgroundColor 65 20 80          # BACKGROUND:	 Breach
	PlayAlertSound 2 100                 # DROPSOUND:	 Splinter Sound

#------------------------------------
#   [1911] Others
#------------------------------------

Show # $Currency->Special %TB-Currency-NonDrop1
	Class Currency
	BaseType "Unshaping Orb" "Cartographer's Seal" "Prophecy" "Imprint" "Vial of"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 159 15 213 255    # BACKGROUND:	 Special
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Circle
	PlayEffect White

#===============================================================================================================
# [[2000]] Currency - PART 3 - Divination cards (yes the strange sorting is intended)
#===============================================================================================================

#------------------------------------
#   [2001] Exceptions to prevent ident. mistakes
#------------------------------------

Show # $Div->T4 %TB-Divination-Exception
	Class "Divination"
	BaseType "The Wolf's Shadow"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 100 150 255         # BORDERCOLOR:	 Divi T4
	SetBackgroundColor 145 215 230 225   # BACKGROUND:	 Divi T4
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound

#------------------------------------
#   [2002] T1 - Top tier cards
#------------------------------------

Show # $Div->T1 %TB-Divination-T1
	Class "Divination"
	BaseType "Abandoned Wealth" "Beauty Through Death" "House of Mirrors" "Hunter's Reward" "Immortal Resolve" "Mawr Blaidd" "Polymath" "Pride Before the Fall" "Spark and the Flame" "The Artist" "The Celestial Justicar" "The Celestial Stone" "The Doctor" "The Dragon's Heart" "The Enlightened" "The Fiend" "The Hunger" "The Immortal" "The Iron Bard" "The King's Heart" "The Last One Standing" "The Master" "The Mayor" "The Queen" "The Saint's Treasure" "The Samurai's Eye" "The Spark and the Flame" "The Undaunted" "The Wind" "The Wolf" "The Wolven King's Bite" "The World Eater" "Wealth and Power"
	SetFontSize 45
	SetTextColor 0 0 255 255             # TEXTCOLOR:	 Divi T1
	SetBorderColor 0 0 255 255           # BORDERCOLOR:	 Divi T1
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

#------------------------------------
#   [2003] T2 - Great cards
#------------------------------------

Show # $Div->T2 %TB-Divination-T2
	Class "Divination"
	BaseType "Boon of the First Ones" "Bowyer's Dream" "Chaotic Disposition" "Heterochromia" "Last Hope" "Left to Fate" "Lucky Deck" "Perfection" "Saint's Treasure" "The Breach" "The Cartographer" "The Dapper Prodigy" "The Ethereal" "The Hale Heart" "The Hoarder" "The Jeweller's Boon" "The Offering" "The Polymath" "The Porcupine" "The Professor" "The Risk" "The Sephirot" "The Thaumaturgist" "The Undisputed" "The Valkyrie" "The Valley of Steel Boxes" "The Vast" "The Void" "Time-Lost Relic"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 200 200 0 255         # BORDERCOLOR:	 Aspect: 83plus
	SetBackgroundColor 100 250 250 245   # BACKGROUND:	 Divi T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Red Triangle
	PlayEffect Red

#------------------------------------
#   [2004] T3 - Decent cards
#------------------------------------

Show # $Div->T3 %TB-Divination-T3
	Class "Divination"
	BaseType "Atziri's Arsenal" "Blind Venture" "Earth Drinker" "Emperor of Purity" "Gemcutter's Promise" "Harmony of Souls" "Hope" "Hubris" "Humility" "Jack in the Box" "Lingering Remnants" "Lucky Connections" "No Traces" "Rebirth" "Scholar of the Seas" "Standoff" "The Admirer" "The Aesthete" "The Beast" "The Blazing Fire" "The Body" "The Brittle Emperor" "The Cacophony" "The Chains that Bind" "The Cursed King" "The Dark Mage" "The Darkest Dream" "The Dreamer" "The Dreamland" "The Encroaching Darkness" "The Endless Darkness" "The Fletcher" "The Formless Sea" "The Gladiator" "The Innocent" "The Inventor" "The Jester" "The Lion" "The Mercenary" "The Obscured" "The Penitent" "The Price of Protection" "The Soul" "The Standoff" "The Surveyor" "The Sword King's Salute" "The Throne" "The Trial" "The Twilight Moon" "The Warlord" "The Wilted Rose" "The Wretched" "Valley of Steel Boxes"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 255 255           # BORDERCOLOR:	 Divi T1
	SetBackgroundColor 50 220 240 235    # BACKGROUND:	 Divi T3
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 Yellow Triangle
	PlayEffect Yellow

#------------------------------------
#   [2005] Special - Special Currency Cards
#------------------------------------

Show # $Div->T4Currency %HS5 %TB-Divination-T4Currency
	Class "Divination"
	BaseType "Coveted Possession" "Emperor's Luck" "Loyalty" "The Catalyst" "The Gemcutter" "The Survivalist" "The Union" "The Wrath" "Three Faces in the Dark" "Three Voices" "Vinia's Token"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 100 150 255         # BORDERCOLOR:	 Divi T4
	SetBackgroundColor 145 215 230 225   # BACKGROUND:	 Divi T4
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White

Show # $Div->T5Currency %H4 %TB-Divination-T5Currency
	Class "Divination"
	BaseType "Rain of Chaos" "The Puzzle" "The Scholar"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 175 215 230 180   # BACKGROUND:	 Divi T5

#------------------------------------
#   [2006] T5 - Format trash tier cards... before
#------------------------------------

Show # $Div->T5 %H3 %TB-Divination-T5
	Class "Divination"
	BaseType "A Mother's Parting Gift" "Anarchy's Price" "Audacity" "Birth of the Three" "Carrion Crow" "Cartographer's Delight" "Death" "Destined to Crumble" "Doedre's Madness" "Dying Anguish" "Hermit" "King's Blade" "Lantador's Lost Love" "Light and Truth" "Metalsmith's Gift" "Might is Right" "Other Cheek" "Prosperity" "Rain of Chaos" "Rain Tempter" "Struck by Lightning" "The Army of Blood" "The Betrayal" "The Coming Storm" "The Conduit" "The Eye of the Dragon" "The Feast" "The Incantation" "The Inoculated" "The Lich" "The Lover" "The Lunaris Priestess" "The Metalsmith's Gift" "The Oath" "The Rabid Rhoa" "The Ruthless Ceinture" "The Scarred Meadow" "The Scholar" "The Sigil" "The Siren" "The Surgeon" "The Tower" "The Twins" "The Warden" "The Wolverine" "Thunderous Skies" "Volatile Power"
	SetFontSize 36
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 175 215 230 180   # BACKGROUND:	 Divi T5

#------------------------------------
#   [2007] T4 - ...showing the remaining cards
#------------------------------------

Show # $Div->T4 %HS4
	Class "Divination"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 100 150 255         # BORDERCOLOR:	 Divi T4
	SetBackgroundColor 145 215 230 225   # BACKGROUND:	 Divi T4
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 2 White Triangle
	PlayEffect White Temp

#===============================================================================================================
# [[2100]] Currency - PART 4 - remaining items
#===============================================================================================================

Show # %H2 %TB-Currency-T8
	Class Currency
	BaseType "Scroll Fragment"
	SetFontSize 28
	SetTextColor 170 158 130 165         # TEXTCOLOR:	 Currency Cosmetic 3
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

Show # %H3
	Class Currency
	SetFontSize 36
	SetTextColor 170 158 130             # TEXTCOLOR:	 Currency Cosmetic
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1

#===============================================================================================================
# [[2200]] Leaguestones - Tierlists
#===============================================================================================================

#Show # $x->Legacy->LeagueStone->T1 %TB-Leaguestone-Value
#	ItemLevel >= 67
#	Class Leaguestone
#	BaseType "Perandus" "Breach" "Nemesis" "Bloodline" "Beyond" "Onslaught" "Domination"
#	Rarity = Magic
#	SetFontSize 45
#	SetTextColor 50 0 100 255            # TEXTCOLOR:	 LeagueStone Magic
#	SetBorderColor 50 0 100 255          # BORDERCOLOR:	 LeagueStone Magic
#	SetBackgroundColor 90 240 140 255    # BACKGROUND:	 LeagueStone T1
#	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#Show # $x->Legacy->LeagueStone->T2
#	Class Leaguestone
#	Rarity >= Magic
#	SetFontSize 45
#	SetTextColor 50 0 100 255            # TEXTCOLOR:	 LeagueStone Magic
#	SetBorderColor 50 0 100 255          # BORDERCOLOR:	 LeagueStone Magic
#	SetBackgroundColor 100 220 145 255   # BACKGROUND:	 LeagueStone T2
#	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#Show #  $x->Legacy->LeagueStone->T3 %TB-Leaguestone-Value
#	ItemLevel >= 67
#	Class Leaguestone
#	BaseType "Perandus" "Breach" "Nemesis" "Bloodline" "Beyond" "Onslaught" "Domination"
#	Rarity = Normal
#	SetFontSize 45
#	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
#	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Cosmetic: Highlight good drops
#	SetBackgroundColor 100 220 145 255   # BACKGROUND:	 LeagueStone T2
#	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#Show #  $x->Legacy->LeagueStone->T4 %HS4
#	Class Leaguestone
#	Rarity = Normal
#	SetFontSize 40
#	SetTextColor 0 0 0 255               # TEXTCOLOR:	 Cosmetic: Black Text
#	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Cosmetic: Highlight good drops
#	SetBackgroundColor 70 160 100 230    # BACKGROUND:	 LeagueStone T3
#	PlayAlertSound 2 300                 # DROPSOUND:	 Value Drop: Currency, fragments

#===============================================================================================================
# [[2300]] Uniques!
#===============================================================================================================

#------------------------------------
#   [2301] Exceptions
#------------------------------------

Show # $uniques->T2
	Rarity Unique
	BaseType "Simple Robe"
	SocketGroup WWWWWW
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

Show # $uniques->T1
	LinkedSockets 6
	Rarity Unique
	SetFontSize 45
	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
	SetBorderColor 175 96 37 255         # BORDERCOLOR:	 Aspect Unique
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

#------------------------------------
#   [2302] Harbinger - Pieces
#------------------------------------

Show # $uniques->Harbinger
	Class Piece
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Cosmetic White
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 37 105 175 255    # BACKGROUND:	 Harbinger Piece
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Blue Star
	PlayEffect Blue

#------------------------------------
#   [2303] Tier 1 uniques
#------------------------------------

Show # $uniques->T1 %TB-Uniques-T1
	Rarity Unique
	BaseType "Ambush Mitts" "Callous Mask" "Clutching Talisman" "Crusader Boots" "Ezomyte Tower Shield" "Glorious Plate" "Grand Mana Flask" "Greatwolf Talisman" "Harlequin Mask" "Legion Gloves" "Occultist's Vestment" "Prismatic Jewel" "Prophecy Wand" "Rawhide Boots" "Rawhide Tower Shield" "Riveted Gloves" "Rotfeather Talisman" "Royal Axe" "Ruby Flask" "Sanctified Life Flask" "Sanctified Mana Flask" "Sapphire Flask" "Wereclaw Talisman"
	SetFontSize 45
	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
	SetBorderColor 175 96 37 255         # BORDERCOLOR:	 Aspect Unique
	SetBackgroundColor 255 255 255 255   # BACKGROUND:	 T0 Drop
	PlayAlertSound 6 300                 # DROPSOUND:	 T0 Drop
	MinimapIcon 0 Red Star
	PlayEffect Red

#------------------------------------
#   [2304] Tier 2 uniques
#------------------------------------

Show # $uniques->T2 %TB-Uniques-T2
	Rarity Unique
	BaseType "Arcanist Gloves" "Arcanist Slippers" "Assassin's Boots" "Bismuth Flask" "Black Maw Talisman" "Blood Raiment" "Carnal Boots" "Carnal Sceptre" "Citadel Bow" "Cutlass" "Destiny Leather" "Gemstone Sword" "Gladiator Plate" "Hydrascale Boots" "Hydrascale Gauntlets" "Imperial Maul" "Magistrate Crown" "Nightmare Mace" "Nubuck Boots" "Ritual Sceptre" "Royal Burgonet" "Sacrificial Garb" "Savant's Robe" "Siege Axe" "Silken Hood" "Thorium Spirit Shield" "Topaz Flask" "Vaal Mask" "Vaal Spirit Shield" "Void Axe"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Yellow Star
	PlayEffect Yellow

Show # $uniques->T2
	LinkedSockets = 5
	Rarity Unique
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Yellow Star
	PlayEffect Yellow

#------------------------------------
#   [2305] Multi-Unique bases.
#------------------------------------
# These bases have multiple uniques. One of the uniques, is a high value one
# While others are cheap. We give them a high quality display, while making a normal unique
# Sound to prevent false excitement.

Show # $uniques->MultiBase %TB-Uniques-T2-MultiBase-League
	Rarity Unique
	BaseType "Amber Amulet" "Exquisite Leather" "Lapis Amulet" "Leather Belt" "Onyx Amulet" "Titan Greaves" "Topaz Ring"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Blue Star
	PlayEffect Blue

Show # $uniques->MultiBase %TB-Uniques-T2-MultiBase-Special
	Rarity Unique
	BaseType "Carved Wand" "Citrine Amulet" "Ebony Tower Shield" "Full Wyrmscale" "Goathide Boots" "Gold Amulet" "Gold Ring" "Granite Flask" "Hubris Circlet" "Imperial Bow" "Imperial Staff" "Murder Boots" "Paua Ring" "Sadist Garb" "Sorcerer Boots" "Stibnite Flask" "Terror Claw" "Tornado Wand" "Two-Stone Ring" "Unset Ring" "Vaal Sceptre"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 175 96 37 255     # BACKGROUND:	 Unique T2
	PlayAlertSound 1 300                 # DROPSOUND:	 T1 Dropsound
	MinimapIcon 0 Blue Star
	PlayEffect Blue

#------------------------------------
#   [2306] Special Unique Searches
#------------------------------------

#Show
#	ItemLevel >= 85
#	Class "Rings"
#	Rarity Unique
#	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
#	SetBorderColor 255 0 0
#	SetBackgroundColor 53 13 13 255      # BACKGROUND:	 Unique T3
#	PlayAlertSound 3 300                 # DROPSOUND:	 Unique

#Show
#	Class "Rings"
#	Rarity Unique
#	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
#	SetBorderColor 255 0 0
#	SetBackgroundColor 53 13 13 255      # BACKGROUND:	 Unique T3
#	PlayAlertSound 3 300                 # DROPSOUND:	 Unique

#------------------------------------
#   [2307] Prophecy-Material Uniques
#------------------------------------

Show # $uniques->Prophecy %TB-Uniques-Fated
	Rarity Unique
	BaseType "Coral Amulet" "Coral Ring" "Crude Bow" "Death Bow" "Fire Arrow Quiver" "Gavel" "Gilded Sallet" "Gnarled Branch" "Goathide Gloves" "Golden Buckler" "Iron Hat" "Iron Ring" "Iron Staff" "Jade Amulet" "Jade Hatchet" "Jagged Maul" "Long Bow" "Ornate Sword" "Painted Buckler" "Plank Kite Shield" "Plate Vest" "Reaver Sword" "Reinforced Greaves" "Royal Bow" "Royal Staff" "Scholar Boots" "Serrated Arrow Quiver" "Sledgehammer" "Spiraled Wand" "Studded Belt" "Velvet Gloves" "Velvet Slippers" "Vine Circlet" "War Buckler" "Wild Leather" "Woodsplitter"
	SetFontSize 45
	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
	SetBorderColor 100 37 255 200        # BORDERCOLOR:	 Prophecy Unique
	SetBackgroundColor 31 9 46 255       # BACKGROUND:	 Prophecy
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Brown Star
	PlayEffect Brown

#------------------------------------
#   [2308] Random Uniques
#------------------------------------

Show # $uniques T3
	Rarity Unique
	SetFontSize 45
	SetTextColor 175 96 37 255           # TEXTCOLOR:	 Unique
	SetBorderColor 175 96 37 255         # BORDERCOLOR:	 Aspect Unique
	SetBackgroundColor 53 13 13 255      # BACKGROUND:	 Unique T3
	PlayAlertSound 3 300                 # DROPSOUND:	 Unique
	MinimapIcon 2 Brown Star
	PlayEffect Brown

#===============================================================================================================
# [[2400]] Quest Items and Shaper Orbs
#===============================================================================================================

Show # $quest
	Class "Incursion Item"
	SetFontSize 45
	SetTextColor 74 230 58 255           # TEXTCOLOR:	 Quest
	SetBorderColor 74 230 58             # BORDERCOLOR:	 Quest Item
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 1 Green Hexagon
	PlayEffect Green

Show # $quest
	Class Quest
	BaseType "Shaper's Orb" "Elder's Orb"
	SetFontSize 45
	SetBorderColor 74 230 58             # BORDERCOLOR:	 Quest Item
	PlayAlertSound 2 300                 # DROPSOUND:	 Currency Sound
	MinimapIcon 1 Green Hexagon
	PlayEffect Green Temp

Show # $quest
	Class Quest
	SetFontSize 45
	SetBorderColor 74 230 58             # BORDERCOLOR:	 Quest Item
	MinimapIcon 1 Green Hexagon
	PlayEffect Green Temp

#===============================================================================================================
# [[2500]] OVERRIDE AREA 4 - Insert your custom Leveling adjustments here
#===============================================================================================================

#===============================================================================================================
# [[2600]] Leveling - Flasks
#===============================================================================================================

#------------------------------------
#   [2601] Hide outdated flasks
#------------------------------------

Hide # lvl
	Quality = 0
	ItemLevel >= 35
	Class "Life Flask" "Mana Flask"
	BaseType Small Medium Large Greater Grand
	SetFontSize 20
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

Hide # lvl
	Quality = 0
	ItemLevel >= 53
	Class "Life Flask" "Mana Flask"
	BaseType Giant Colossal Sacred
	SetFontSize 20
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

Hide # lvl
	Quality = 0
	ItemLevel >= 67
	Class "Life Flask" "Mana Flask"
	BaseType Hallowed Sanctified Divine Eternal
	SetFontSize 20
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

#------------------------------------
#   [2602] Hybrid flasks (normal)
#------------------------------------

Show # %D4
	ItemLevel <= 15
	Class "Hybrid Flask"
	BaseType "Small"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D4
	ItemLevel <= 25
	Class "Hybrid Flask"
	BaseType "Medium"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D4
	ItemLevel <= 35
	Class "Hybrid Flask"
	BaseType "Large"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D4
	ItemLevel <= 45
	Class "Hybrid Flask"
	BaseType "Colossal"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D4
	ItemLevel <= 55
	Class "Hybrid Flask"
	BaseType "Sacred"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D4
	ItemLevel <= 67
	Class "Hybrid Flask"
	BaseType "Hallowed"
	SetFontSize 40
	SetBorderColor 100 0 100             # BORDERCOLOR:	 Hybrid
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [2603] Life Flasks - Normal (Kudos to Antnee)
#------------------------------------

Show # %D5
	ItemLevel <= 5
	Class "Life Flasks"
	BaseType "Small"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 9
	ItemLevel >= 3
	Class "Life Flasks"
	BaseType "Medium"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 13
	ItemLevel >= 5
	Class "Life Flasks"
	BaseType "Large"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 19
	ItemLevel >= 12
	Class "Life Flasks"
	BaseType "Greater"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 24
	ItemLevel >= 18
	Class "Life Flasks"
	BaseType "Grand"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 30
	ItemLevel >= 24
	Class "Life Flasks"
	BaseType "Giant"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 37
	ItemLevel >= 30
	Class "Life Flasks"
	BaseType "Colossal"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 42
	ItemLevel >= 36
	Class "Life Flasks"
	BaseType "Sacred"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 48
	ItemLevel >= 42
	Class "Life Flasks"
	BaseType "Hallowed"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 55
	ItemLevel >= 48
	Class "Life Flasks"
	BaseType "Sanctified"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 67
	ItemLevel >= 60
	Class "Life Flasks"
	BaseType "Divine"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 70
	ItemLevel >= 65
	Class "Life Flasks"
	BaseType "Eternal"
	SetFontSize 40
	SetBorderColor 120 0 0               # BORDERCOLOR:	 Aspect Life Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [2604] Mana Flasks - Magic (Kudos to Antnee)
#------------------------------------

Show # %D5
	ItemLevel <= 5
	Class "Mana Flasks"
	BaseType "Small"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 8
	ItemLevel >= 3
	Class "Mana Flasks"
	BaseType "Medium"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 12
	ItemLevel >= 5
	Class "Mana Flasks"
	BaseType "Large"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 18
	ItemLevel >= 12
	Class "Mana Flasks"
	BaseType "Greater"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 24
	ItemLevel >= 18
	Class "Mana Flasks"
	BaseType "Grand"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 30
	ItemLevel >= 24
	Class "Mana Flasks"
	BaseType "Giant"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 37
	ItemLevel >= 30
	Class "Mana Flasks"
	BaseType "Colossal"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 42
	ItemLevel >= 36
	Class "Mana Flasks"
	BaseType "Sacred"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 48
	ItemLevel >= 42
	Class "Mana Flasks"
	BaseType "Hallowed"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 55
	ItemLevel >= 48
	Class "Mana Flasks"
	BaseType "Sanctified"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 67
	ItemLevel >= 60
	Class "Mana Flasks"
	BaseType "Divine"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D5
	ItemLevel <= 70
	ItemLevel >= 65
	Class "Mana Flasks"
	BaseType "Eternal"
	SetFontSize 40
	SetBorderColor 0 0 120               # BORDERCOLOR:	 Aspect: Mana Flask
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [2605] Show remaining flasks
#------------------------------------

Show # %D4
	Quality = 20
	ItemLevel <= 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 40
	SetBorderColor 255 255 255 255       # BORDERCOLOR:	 T1 highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D3
	Quality >= 15
	ItemLevel <= 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 40
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D2
	Quality > 1
	ItemLevel <= 65
	Rarity <= Magic
	BaseType "Flask"
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D3
	ItemLevel <= 65
	Rarity <= Magic
	Class "Utility Flasks"
	SetFontSize 36
	SetBorderColor 50 200 125            # BORDERCOLOR:	 Flask
	SetBackgroundColor 25 100 75         # BACKGROUND:	 Flasks

Show # %D1
	Rarity <= Magic
	BaseType Flask
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

#===============================================================================================================
# [[2700]] Leveling - Merged Rules
#===============================================================================================================

Show # %REMS1 %D5 %RVR
	LinkedSockets = 4
	Rarity = Normal
	Class "Gloves" "Boots" "Helmets" "Body Armour"
	SocketGroup RGB
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show
	LinkedSockets = 4
	Rarity = Magic
	Class "Gloves" "Boots" "Helmets" "Body Armour"
	SocketGroup RGB
	SetFontSize 45
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show # %REMS1 %D5
	LinkedSockets = 4
	Rarity Rare
	Class "Gloves" "Boots" "Helmets" "Body Armour"
	SocketGroup RGB
	SetFontSize 45
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

#===============================================================================================================
# [[2800]] Leveling - RGB Recipes
#===============================================================================================================

Show # %D3
	Width <= 2
	Height <= 2
	SocketGroup RGB
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D3
	Width <= 1
	Height <= 3
	SocketGroup RGB
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D2
	Width >= 2
	Height >= 4
	SocketGroup RGB
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

Show # %D2
	Height <= 3
	SocketGroup RGB
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipe T2

#===============================================================================================================
# [[2900]] Leveling - RARES
#===============================================================================================================

#------------------------------------
#   [2901] Leveling rares - specific items
#------------------------------------

Show # %REMS1 %D4
	LinkedSockets >= 4
	Rarity Rare
	SetFontSize 45
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show # %REMS1 %D4
	Rarity Rare
	Class "Rings" "Amulets" "Belts"
	SetFontSize 45
	SetTextColor 0 0 0 255               # TEXTCOLOR:	 High Special Base
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 170 225 70 255    # BACKGROUND:	 Trinket T1
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show # %D4
	ItemLevel < 30
	Rarity Rare
	Class "Boots"
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # %D4
	Height = 2
	Rarity Rare
	Class "Boots" "Helmets" "Gloves" "Shields"
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 75 30 255       # BACKGROUND:	 Rare T1

Show # %D4
	Rarity Rare
	Class "Sceptres" "Daggers" "Wands"
	SetFontSize 40
	SetBorderColor 0 0 0 255             # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

#------------------------------------
#   [2902] Leveling rares - Progression
#------------------------------------

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel <= 12
	Rarity Rare
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel <= 12
	Rarity Rare
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel <= 12
	Rarity Rare
	SetFontSize 45
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 15
	DropLevel > 5
	Rarity Rare
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 15
	DropLevel > 5
	Rarity Rare
	SetFontSize 45
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 15
	DropLevel > 5
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 20
	DropLevel > 10
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 20
	DropLevel > 10
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 20
	DropLevel > 10
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 25
	DropLevel > 15
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 25
	DropLevel > 15
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 25
	DropLevel > 15
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 30
	DropLevel > 20
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 30
	DropLevel > 20
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 30
	DropLevel > 20
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 35
	DropLevel > 25
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D4
	Width <= 1
	Height <= 3
	ItemLevel < 35
	DropLevel > 25
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 35
	DropLevel > 25
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 40
	DropLevel > 30
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 40
	DropLevel > 30
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 40
	DropLevel > 30
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 45
	DropLevel > 35
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 45
	DropLevel > 35
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D4
	ItemLevel < 45
	DropLevel > 35
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 50
	DropLevel > 40
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 50
	DropLevel > 40
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 50
	DropLevel > 40
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 55
	DropLevel > 45
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 55
	DropLevel > 45
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 55
	DropLevel > 45
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	ItemLevel < 60
	DropLevel > 50
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	ItemLevel < 60
	DropLevel > 50
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	ItemLevel < 60
	DropLevel > 50
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D3
	Width <= 2
	Height <= 2
	DropLevel > 55
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	Width <= 1
	Height <= 3
	DropLevel > 55
	Rarity Rare
	SetFontSize 36
	SetBorderColor 150 150 150           # BORDERCOLOR:	 Neutral T1
	SetBackgroundColor 0 50 0 255        # BACKGROUND:	 Rare T2

Show # %D3
	DropLevel > 55
	Rarity Rare
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [2903] Leveling rares - remaining rules
#------------------------------------

Show # %D2
	Width <= 1
	Height <= 3
	Rarity Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # %D2
	Width <= 2
	Height <= 2
	Rarity Rare
	SetBorderColor 120 120 120           # BORDERCOLOR:	 Rares: small
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

Show # %D2
	Rarity Rare
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 219         # BACKGROUND:	 Neutral T4

#===============================================================================================================
# [[3000]] Leveling - Useful items
#===============================================================================================================

#------------------------------------
#   [3001] Linked gear - 4links
#------------------------------------

Show # %D3 %RVR %REMS1
	LinkedSockets >= 4
	Rarity = Normal
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

Show
	LinkedSockets >= 4
	Rarity = Magic
	SetFontSize 45
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 0 140 240 255         # BORDERCOLOR:	 Leveling Strong Highlight
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2
	PlayAlertSound 12 300                # DROPSOUND:	 Underrated Leveling Sound

#------------------------------------
#   [3002] Linked gear - Caster Weapon Configuration
#------------------------------------

Show # %D1 %RVR
	LinkedSockets = 3
	ItemLevel <= 25
	Rarity = Normal
	Class "Sceptres" "Wands" "Daggers"
	SocketGroup BB
	SetFontSize 40
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show
	LinkedSockets = 3
	ItemLevel <= 25
	Rarity = Magic
	Class "Sceptres" "Wands" "Daggers"
	SocketGroup BB
	SetFontSize 40
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [3003] Linked gear - 3links
#------------------------------------

Show # %D2 %RVR
	LinkedSockets >= 3
	ItemLevel <= 25
	Rarity = Normal
	Class "Gloves" "Boots" "Helmets" "Shields" "Body Armour"
	SetFontSize 36
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show
	LinkedSockets >= 3
	ItemLevel <= 25
	Rarity = Magic
	Class "Gloves" "Boots" "Helmets" "Shields" "Body Armour"
	SetFontSize 36
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D2 %RVR
	LinkedSockets >= 3
	ItemLevel <= 12
	Rarity = Normal
	SetFontSize 40
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show
	LinkedSockets >= 3
	ItemLevel <= 12
	Rarity = Magic
	SetFontSize 40
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3Link
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#Show # %D1
#	LinkedSockets >= 3
#	ItemLevel <= 36
#	Class "Gloves" "Boots" "Helmets" "Shields" "Body Armour"
#	Rarity <= Magic
#	SetFontSize 36
#	SetBorderColor 0 120 120 255         # BORDERCOLOR:	 3-links
#	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 T6-10 maps, currency, talismans

#------------------------------------
#   [3004] Extra Highlight: Boots
#------------------------------------

Show # %D2
	ItemLevel <= 12
	Rarity = Magic
	Class "Boots"
	SetFontSize 45
	SetTextColor 25 95 235 255           # TEXTCOLOR:	 Leveling Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D2
	ItemLevel <= 24
	Rarity = Magic
	Class "Boots"
	SetFontSize 36
	SetTextColor 25 95 235 255           # TEXTCOLOR:	 Leveling Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling

#------------------------------------
#   [3005] Optional Recipes
#------------------------------------

#Show #summoner recipe shield
#	BaseType "Bone Spirit Shield"
#	ItemLevel < 40
#	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Leveling: strong highlight

#------------------------------------
#   [3006] Act 1
#------------------------------------
# Early on we focus on flat wins
# Iron Rings, Leather Belts and Corals help the leveling progression a lot
# We also want to highlight all elemental resist rings for the +1 Recipe

Show # %TB-Leveling-Trinkets-Phys %D3 %RVR
	ItemLevel <= 12
	Rarity = Normal
	BaseType "Iron Ring" "Rustic Sash"
	SetFontSize 45
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show
	ItemLevel <= 12
	Rarity = Magic
	BaseType "Iron Ring" "Rustic Sash"
	SetFontSize 45
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %TB-Leveling-Trinkets-Life %D3 %RVR
	ItemLevel <= 16
	Rarity = Normal
	BaseType "Coral Ring" "Leather Belt" "Sapphire Ring" "Ruby Ring" "Topaz Ring"
	SetFontSize 40
	SetTextColor 255 255 255 255         # TEXTCOLOR:	 Normal Items: Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show
	ItemLevel <= 16
	Rarity = Magic
	BaseType "Coral Ring" "Leather Belt" "Sapphire Ring" "Ruby Ring" "Topaz Ring"
	SetFontSize 40
	SetTextColor 25 95 235 255           # TEXTCOLOR: Magic Items: Strong Highlight
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

Show # %D2
	ItemLevel <= 12
	Rarity <= Magic
	Class "Rings" "Amulets" "Belts"
	SetFontSize 40
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

# Racers have found that a healthy mix of EV/AR gear can help facetank brutus easy - even on lower levels

Show # %D3
	ItemLevel <= 12
	Rarity = Magic
	Class "Sceptres" "Wands" "Daggers"
	SetFontSize 40
	SetTextColor 25 95 235 255           # TEXTCOLOR:	 Leveling Strong Highlight
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [3007] Act 2+3
#------------------------------------
# Act 2 and 3 hosts several high lightning damage sources. We highlight topaz rings to help us out.

Show # %TB-Leveling-Trinkets-Life %D2
	ItemLevel <= 32
	Rarity <= Magic
	BaseType "Topaz Ring" "Two-Stone Ring" "Rustic Sash"
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [3008] Act 4+5+6
#------------------------------------
# Act 4-6 have a highly varying damage composition
# However several of the strongest elemental attacks are fire-typed

Show # %TB-Leveling-Trinkets-Life %D3
	ItemLevel <= 50
	ItemLevel >= 32
	Rarity <= Magic
	BaseType "Ruby Ring" "Two-Stone Ring"
	SetBorderColor 100 100 100 255       # BORDERCOLOR:	 Aspect Small Leveling
	SetBackgroundColor 0 0 0 255         # BACKGROUND:	 Neutral T2

#------------------------------------
#   [3009] Jewellery - Regular Highlight
#------------------------------------

# Worthwhile rings + Onyx - focus on resists for quick enchanting.

Show # %D2
	ItemLevel <= 40
	Rarity <= Magic
	BaseType "Topaz Ring" "Ruby Ring" "Topaz Ring" "Two-Stone Ring" "Coral Ring" "Onyx Amulet"
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling

# Worthwhile belts

Show # %TB-Leveling-Trinkets-Life %D2
	ItemLevel <= 26
	Rarity <= Magic
	BaseType "Leather Belt" "Rustic Sash" "Heavy Belt"
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

# Worthwhile amulets - only stat amulets to help with stats

Show # %D2
	ItemLevel <= 26
	Rarity <= Magic
	BaseType "Amber Amulet" "Jade Amulet" "Lapis Amulet" "Turquoise Amulet" "Citrine Amulet" "Onyx Amulet" "Agate Amulet"
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3010] Quivers - Progression
#------------------------------------

# Quivers - early gear acquisition

Show # %D2
	ItemLevel <= 8
	Rarity <= Magic
	BaseType "Serrated Arrow Quiver" "Two-Point Arrow Quiver"
	SetFontSize 36
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

# Quivers - possible upgrades

Show # %D1
	ItemLevel <= 24
	Rarity <= Magic
	BaseType "Serrated Arrow Quiver" "Two-Point Arrow Quiver"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

# Quivers - first appearance of broadhead arrow quivers

Show # %D2
	ItemLevel < 35
	Rarity <= Magic
	BaseType "Broadhead Arrow Quiver"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %D1
	ItemLevel <= 48
	Rarity <= Magic
	BaseType "Broadhead Arrow Quiver" "Penetrating Arrow Quiver" "Spike-Point Arrow Quiver"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3011] Magic Gear
#------------------------------------

Show # %D2
	ItemLevel <= 32
	Rarity Magic
	Class Rings Amulets Belts
	SetFontSize 36
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3012] 20% quality items for those strange people who want them
#------------------------------------

#Show # quality, lvl, nonmf
#	Quality = 20
#	Class "Body Armour" "Helmets" "Gloves" "Boots" "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers" "Shields"
#	Rarity <= Magic
#	ItemLevel <= 60
#	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Cosmetic: Neutral Highlight
#	SetBackgroundColor 75 75 75 255      # BACKGROUND:	 Recipes

#===============================================================================================================
# [[3100]] Leveling - normal and magic item progression
#===============================================================================================================

#------------------------------------
#   [3101] Progression - Part 1 1-30
#------------------------------------

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 9
	DropLevel >= 5
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 11
	DropLevel >= 8
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 14
	DropLevel >= 11
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 16
	DropLevel >= 13
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 18
	DropLevel >= 16
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 20
	DropLevel >= 18
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 22
	DropLevel >= 20
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 24
	DropLevel >= 22
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 26
	DropLevel >= 24
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 28
	DropLevel >= 26
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 30
	DropLevel >= 28
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3102] Progression - Part 2 30-40
#------------------------------------

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 32
	DropLevel >= 30
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 34
	DropLevel >= 32
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 36
	DropLevel >= 34
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 40
	DropLevel >= 38
	Rarity <= Magic
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3103] Progression - Part 4 40-65
#------------------------------------

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 42
	DropLevel >= 40
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 44
	DropLevel >= 42
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 46
	DropLevel >= 44
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 48
	DropLevel >= 46
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 50
	DropLevel >= 48
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 52
	DropLevel >= 50
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 54
	DropLevel >= 52
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 56
	DropLevel >= 54
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 58
	DropLevel >= 56
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 60
	DropLevel >= 58
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 62
	DropLevel >= 60
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 64
	DropLevel >= 62
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %TC-LVL-Weapons %D1
	ItemLevel <= 66
	DropLevel >= 64
	Rarity = Normal
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Daggers"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

#------------------------------------
#   [3104] Normal items - First 12 levels - exceptions
#------------------------------------

Show # %H1
	ItemLevel <= 4
	Rarity Normal
	Class "Body Armours"
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %D2
	Width <= 1
	Height <= 4
	ItemLevel <= 4
	Rarity Normal
	SetFontSize 36
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling

Show # %D2
	Width <= 2
	Height <= 2
	ItemLevel <= 4
	Rarity Normal
	SetFontSize 36
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling

Show # %D2
	ItemLevel <= 4
	Rarity Normal
	SetTextColor 200 200 200 210         # TEXTCOLOR:	 Neutral Priority
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5

#------------------------------------
#   [3105] Magic items - general highlight
#------------------------------------

# Highlight small magic items until level 24 for Trans-Selling

# Until level 12 - show all blue items, no matter what

Show # %D2
	ItemLevel <= 16
	Rarity Magic
	SetFontSize 36
	SetBorderColor 50 50 50              # BORDERCOLOR:	 Aspect Decent Leveling

Show # %D2
	Width <= 1
	Height <= 4
	ItemLevel <= 36
	Rarity Magic
	SetTextColor 136 136 255 185         # TEXTCOLOR:	 Magic Vendor Items
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

Show # %D2
	Width <= 2
	Height <= 2
	ItemLevel <= 36
	Rarity Magic
	SetTextColor 136 136 255 185         # TEXTCOLOR:	 Magic Vendor Items
	SetBorderColor 0 0 0                 # BORDERCOLOR:	 Neutral T1.5
	SetBackgroundColor 0 0 0 185         # BACKGROUND:	 Neutral T3

# Later on keep them shown, but really small

#===============================================================================================================
# [[3200]] HIDE LAYER 5 - Remaining Items
#===============================================================================================================

Hide # Minimize junk instead of hiding (if "Show") %TC-Junkable
	Class "Two Hand" "Bows" "One Hand" "Wand" "Sceptre" "Staves" "Claws" "Body Armour" "Gloves" "Boots" "Helmets" "Quivers" "Flask" "Daggers" "Shields" "Belts" "Rings" "Amulets" "Jewel"
	SetFontSize 18
	SetBorderColor 0 0 0 150             # BORDERCOLOR:	 Neutral T3
	SetBackgroundColor 0 0 0 75          # BACKGROUND:	 Hidden

#===============================================================================================================
# [[3300]] CATCHALL - if you see pink items - send me a mail please - should never happen
#===============================================================================================================

Show # SafetyLine!
	SetFontSize 45
	SetTextColor 255 0 255 255           # TEXTCOLOR:	 Error
	SetBorderColor 255 0 255 255         # BORDERCOLOR:	 Error

#===============================================================================================================
# [[3400]] Special thanks to!
#===============================================================================================================
# PATREON:
# Special Thanks to the Patreon Supporters:
# 00cosgrovep, Divinezensei, Ryndaar, DePace, dimon222, Phegan,
#
# COMMUNITY:
# Special thanks to the supporters, stream-viewers and my guild :)
# Everyone who provided feedback on my thread/github and on reddit.
#
# GRINDING GEAR GAMES:
# Bex - Awesome. Also compiled information for smooth updating during league starts!
# Jonathan - Thank you for going into the detail on the filter algorithm. Also for the filter algorithm!
# Chris - The man.
#
# FRIENDS:
# Haggis & Tobnac - I'd need to a document to list all the things they've assisted with. Also members of the "Filterblade" project!
# C4pture - Good friend, helped out a lot and is nice enough to only annoy me 75% of the time. He has a straaange cat.
# MrPing - Helped out a ton with testing recently.
# Victoria - <3
#
# SUGGESTIONS / HELP:
# Antnee - adapted some of his ideas. Also helped with feedback. He also has a nice lootfilter himself, check it out.
# Ghudda - I took his script as a template. It made learning the syntax even easier.
# Malchron - consulted me on some complicated topics
# ZiggyD - tested the filter during the 2.0 beta
# Helmannn - tested the filter during the Ascendancy Alpha!
# StarRune - Found several flaws and improvement possibilities. Thanks!
# Also thanks to http://bschug.github.io/poedit/poedit.html - I used this site to test my setup
#
# Script by NeverSink

