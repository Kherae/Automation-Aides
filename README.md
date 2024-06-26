# Automation Aides
Mod derived from Steambound Reloaded and Vesselbound's ideas
Credits:
*TP for making steambound reloaded, which this mod is based on.
*cratesmith, for vesselbound, another source of ideas.
*thegamemaster1234 (Lucca) for some shiny code contributions (round robin, even split, and moving in multiples)
*mousefrost for new filter options
*hubnester for massively boosting terminal performance. Terminal limit is now around 13k items instead of just 1k.
*sayter for router UI graphical update

change log:
---
1.9.6.1
*liquid lib serialization fix
---
1.9.6
*implemented caching system in liquidlib and transferutil scripts.
*transferutil now enforces item stack caps in throwItemsAt function.
---
1.9.5
*removed repeating from ITDs.
*removed looping from repeaters
*added warning alarm and sprite color state to repeaters
*extended some tooltips
---
1.9.4
*correct output filtration logic in case of output list consisting solely of values outside a destination container's range
---
1.9.3
*correcting a typo and adjusting a string's location for localization
---
1.9.2
*Added help mode button
---
1.9
*routers now have 2 new filter options
*object descriptions updated
*quarry ranges updated
*old money router finally removed fully
---
1.8.11
*router UI update by sayter
---
1.84
*fixed a race condition issue
--
1.82
*added throttle control as anti-lag
--
1.81
*added point sensor unlocked from bridge
--
1.8
*added item sensor and item dropper, unlocked from silicon board and iron bar
--
1.77
*fix pump code
--
1.76
*fix capacity sensors
---
1.75
*Terminals got a much needed boost.
---
1.72
*money router deprecated
*currency token added
---
1.71
*Terminal fix
*changelog format update
---
1.7
*script refactoring for performance purposes. pumps nerfed. colonny deed link.
---
1.6
*recipes all adjusted. now unlocked by picking up silicon boards and iron bars. unhandled item token now available.
---
1.5.1:
*router hotfix
---
1.5:
*recoded even split and slot split to be more precise
---
1.4.2:
*Giant spiked nerfbat for balance reasons: ITDs, MTDs and grabbers now require teleporter cores.
---
1.4.1:
*fixed an ancient routing bug I missed, that involves not having an item in the ITD's first slot
*tentative workaroundish fix for terminals acting up. Refresh if it loses sight
---
1.4:
*fixed bridges not properly clearing their lists (big sorry. ugh)
*iron and titanium quarries and pumps now available.
*overall nerfs to effectiveness and range.
---
1.3:
*even split and round robin methods added to ITDs. and moving by stack. try putting 2 of a filter item in, it'll only attempt to move in multiples of 2!
*money router. routes currencies
*'unhandled' special token for items that the router doesn't understand
*categories are now part of a (patchable) config file.
*capacity sensors! tells you whether a container has some slots filled, and whether it has all of them filled.
*storage bridge v2, which has built in capacity sensors