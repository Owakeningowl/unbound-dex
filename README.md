# Pokémon Unbound Pokédex

Live at <https://owakeningowl.github.io/unbound-dex/>.

Pokémon Null's dex front-end (the Showdown dex as adapted by Porydex and Null) with Pokémon Unbound 2.1.1.1's
data: every species and form with Unbound's stats, types and abilities, level-up / TM / tutor / egg learnsets,
evolutions, Mega Stones, moves with Unbound's power, accuracy and PP, and every wild encounter table (grass by
day and night, surfing, Rock Smash, fishing).

Data sources:
- [Skeli789/Dynamic-Pokemon-Expansion](https://github.com/Skeli789/Dynamic-Pokemon-Expansion) (Unbound branch):
  base stats, learnsets, TM / tutor compatibility, egg moves, evolutions
- [Skeli789/Complete-Fire-Red-Upgrade](https://github.com/Skeli789/Complete-Fire-Red-Upgrade): moves, abilities,
  their names and descriptions
- [ydarissep/Unbound-Pokedex](https://github.com/ydarissep/Unbound-Pokedex): wild encounter tables, merged-ability
  names (e.g. Air Lock on Rayquaza)
- National dex numbers, heights, weights and colours from pokeemerald-expansion; long move / ability / item
  descriptions from Null's dex data

The location list is ordered by the typical level met there (maps whose levels scale with your team come last).
Built by `tools/build_dex.py` in the local project.
