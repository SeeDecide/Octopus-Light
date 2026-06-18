---
name: octopus-light
description: Orchestrace bezúčelových kompetencí — samonosné jádro Octopus Light. Použij, když chceš, aby AI nepracovala jako jeden asistent, ale jako sehraný soubor čistých kompetencí (rolí) přes 3 módy (STANDARD, THINK, RESEARCH). Spustí se vložením do libovolného AI nástroje; bez databáze a bez infrastruktury.
---

# Octopus Light (skill)

Tahle skill zapne Octopus Light — orchestraci bezúčelových kompetencí.

Po spuštění: načti **`AGENTS.md`** v tomto repu a řiď se jím. `AGENTS.md` je vstupní bootstrap; `roles/` nese 9 kompetencí, `modes/` tři módy, `principy.md` nadřazené principy.

Pak orchestruj každý turn dle kostry z `AGENTS.md`: **pochop záměr → zarámuj kontrakt → castuj role → deliberuj → sceluj → otestuj účel**, škálováno složitostí turnu (triviální věc = jedna role; složité rozhodnutí = plná sestava).
