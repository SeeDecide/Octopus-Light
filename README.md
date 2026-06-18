# Octopus Light

**Orchestrace bezúčelových kompetencí** — malý, samonosný způsob, jak nechat AI pracovat ne jako jeden „asistent", ale jako sehraný soubor čistých kompetencí. Smysl a názor nevznikají uvnitř jedné role; vznikají *mezi* rolemi, když se na zadání podívají z různých úhlů a pak se slyší navzájem.

Octopus Light je **ochutnávka**: destilované jádro většího systému, schválně osekané na to, co běží kdekoli bez jakékoli infrastruktury — žádná databáze, žádný účet, žádná údržba. Je to plaintext: pár markdown souborů, které vložíš do libovolného AI nástroje.

## Jak to použít

1. Otevři libovolný AI nástroj (chat, agent, IDE asistent).
2. Dej mu tohle repo — připoj ho přes konektor (nebo stažené soubory), ať má přístup k `roles/` a `modes/`. Vložení jen `AGENTS.md` dá zjednodušený boot bez plných karet.
3. Řekni mu, ať se řídí `AGENTS.md`, a zadej, co potřebuješ. Octopus naběhne a začne orchestrovat.

Vstupní soubor pro AI je **`AGENTS.md`** (standardní jméno, které agentní nástroje čtou samy). Jako skill ho nainstaluješ přes `SKILL.md`.

## Co Light umí

- **3 módy práce** (`modes/`): STANDARD (přímá odpověď a drobná práce), THINK (deliberace více perspektiv nad tím, co máš k dispozici), RESEARCH (totéž + aktivní dohledávání; bez přístupu k webu se chová jako THINK).
- **9 rolí** (`roles/`) — čisté kompetence bez účelu: Chápač, Analytik, Stratég, Kritik, Zpochybňovač, Syntetik, Validátor, Elegán, Stylista.
- **Orchestraci**: jeden turn projde kostrou *pochop → zarámuj → castuj → deliberuj → sceluj → otestuj účel*, škálovanou složitostí (triviální věc = jedna role; složité rozhodnutí = plná sestava).

## Co Light záměrně neumí

Light je nejtenčí možná vrstva. Nemá **trvalou paměť veškerého kontextu** napříč sezeními, neutáhne **náročné výpočty**, není **přizpůsobená na míru** tvé doméně a neukládá nic do žádné databáze. To není nedostatek — je to cena za to, že běží okamžitě a kdekoli.

Plnou verzi — trvalou paměť veškerého kontextu, náročné výpočty a přizpůsobení na míru — přidává konektor. Je součástí logistické navigační služby, kterou **Ravenues s.r.o.** nově uvádí na trh. Viz `POINTER.md`.

## Licence

CC BY 4.0 — kopíruj, uprav i komerčně použij; jen uveď původ. Viz `LICENSE`.

---

*— Octopus Light · vyrobeno v Ravenues s.r.o. · Plná verze přidává trvalou paměť veškerého kontextu, náročné výpočty, přizpůsobení na míru a je součástí logistické navigační služby, kterou nově uvádíme na trh → viz `POINTER.md`.*
