# Actor photos for the Find Jackie Chan game

Drop a JPEG here for each actor, named exactly by id:

| File              | Actor        | Chinese |
|-------------------|--------------|---------|
| `jackie.jpg`      | Jackie Chan  | 成龙    |
| `jetli.jpg`       | Jet Li       | 李连杰  |
| `andylau.jpg`     | Andy Lau     | 刘德华  |
| `chowyunfat.jpg`  | Chow Yun-fat | 周润发  |
| `stephenchow.jpg` | Stephen Chow | 周星驰  |
| `donniyen.jpg`    | Donnie Yen   | 甄子丹  |
| `tonyleung.jpg`   | Tony Leung   | 梁朝伟  |
| `brucelee.jpg`    | Bruce Lee    | 李小龙  |

Guidelines:

- Head-and-shoulders portrait, face near the top (cards crop with
  `object-position: center top`).
- Roughly square or 3:4 portrait, ~400px wide is plenty.
- Keep each file under ~200 KB so the grid loads fast.

Any file missing here falls back to the Wikipedia thumbnail API, which is
blocked in some regions — so committing real files here is what makes the
game work everywhere.
