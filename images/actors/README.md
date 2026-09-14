# Actor photos for the Find Jackie Chan game

Each actor has a few JPEGs named `{id}-1.jpg`, `{id}-2.jpg`, ... — the game
picks one at random for each round, so the grid looks different every time.
The count for each actor is set in `ACTORS[].photoCount` in `jackiechan.html`.

| id            | Actor        | Chinese | photos |
|---------------|--------------|---------|--------|
| `jackie`      | Jackie Chan  | 成龙    | 3      |
| `jetli`       | Jet Li       | 李连杰  | 3      |
| `andylau`     | Andy Lau     | 刘德华  | 3      |
| `chowyunfat`  | Chow Yun-fat | 周润发  | 2      |
| `stephenchow` | Stephen Chow | 周星驰  | 3      |
| `donniyen`    | Donnie Yen   | 甄子丹  | 3      |
| `tonyleung`   | Tony Leung   | 梁朝伟  | 2      |
| `brucelee`    | Bruce Lee    | 李小龙  | 2      |

All photos are real, freely-licensed (public domain or CC) photographs
sourced from Wikimedia Commons.

Guidelines for adding more:

- Head-and-shoulders portrait, face near the top (cards crop with
  `object-position: center top`).
- Roughly square or 3:4 portrait, ~400px wide is plenty.
- Keep each file under ~100 KB so the grid loads fast.
- Bump the matching `photoCount` in `jackiechan.html` when you add one.

Any file missing here falls back to the Wikipedia thumbnail API, which is
blocked in some regions — so committing real files here is what makes the
game work everywhere.
