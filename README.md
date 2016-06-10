# Eve's Stellaris Mod Merge
This repo contains a combined superset of stellaris mods which the author wanted to use but which do overlapping things, and thus had compatibility or support issues with at least one other mod contained within.  

All of the hard work is courtesy of the authors of the respective mods and not my own.  These mods are contained within:

```
* (Advanced Fleet Operations)[http://steamcommunity.com/sharedfiles/filedetails/?id=686641980]: modified to add Rangefinder modules to new ships
* (Better Empire Names)[http://steamcommunity.com/sharedfiles/filedetails/?id=684475224]: adding new governments to the name lists
* (Enhanced Terraforming)[http://steamcommunity.com/sharedfiles/filedetails/?id=683262202]: merged with other 
* (Ethics, Government, Policies)[http://steamcommunity.com/sharedfiles/filedetails/?id=688581447]: merging of governments
* (Galactic Governance)[http://steamcommunity.com/sharedfiles/filedetails/?id=687892748]: merging of goverments, ethics
* (Larger Homeworld)[http://steamcommunity.com/sharedfiles/filedetails/?id=686173963]: merged changes with other planet-modifying mods
* (Make Space(Governments) Great Again)[http://steamcommunity.com/sharedfiles/filedetails/?id=693897659]: merging of governments
* (More Edicts: Protocols and Doctrines)[http://steamcommunity.com/sharedfiles/filedetails/?id=686166072]: merging of edicts
* (More Events)[http://steamcommunity.com/sharedfiles/filedetails/?id=690089574]: merging events with other mods that added them
* (More Planet Types)[http://steamcommunity.com/sharedfiles/filedetails/?id=694585917]: merging of planet type information
* (New Ship Classes & More)[http://steamcommunity.com/sharedfiles/filedetails/?id=683230077]: modified to add Rangerfinder modules to new ships
* (Rangefinder)[http://steamcommunity.com/sharedfiles/filedetails/?id=684750984]: added new modules to other mods that added ships
* (Stone's Politics Expansion)[http://steamcommunity.com/sharedfiles/filedetails/?id=690755908]: merging of governments, edicts, etc
* (The Belt)[http://steamcommunity.com/sharedfiles/filedetails/?id=694492075]: merging of planet type information
```

##Changes##

* Ships: The mods that added new ship types worked quite nicely with one another.  However, the new ship types needed to have the Rangefinder modules added to them.

* Planets: A few mods made dramatic changes to the files that modified planet generation, starting planets, etc.  Some added numerous new planet types entirely.  These changes were some of the more complicated, and in many cases involved deciding which mods changes to give precedence to.  Much of the remaining work was just a matter of adding new planet types to the lists for what planets blockers could appear on, etc.

* Governments: Most of the government mods just added new ones, but Ethics, Government, Policies changed existing ones as well.  Many events have different rates of occurance or different text chains depending on your government or ethics, so the different mods added their own governments to those and had conflicting changes that had to be merged.

* Edicts: These were relatively simple, and the additions and changes just needed to be merged together.

* Events: For the most part this consisted of just merging additions together, or adding new governments/etc into events so that they could occur for new types.

##Installation##

Drop the directory and the .mod file into %UserProfile%\Documents\Paradox Interactive\Stellaris\mod