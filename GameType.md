| Friendly Name         | Type Name       | Database Name | ID            |
| -------------         | -------------   | ------------- | ------------- |
| Quakecraft            | QUAKECRAFT      | Quake         | 2             |
| The Walls             | WALLS           | Walls         | 3             |
| Paintball Warfare     | PAINTBALL       | Paintball     | 4             |
| Blitz Survival Games  | SURVIVAL_GAMES  | HungerGames   | 5             |
| The TNT Games         | TNTGAMES        | TNTGames      | 6             |
| VampireZ              | VAMPIREZ        | VampireZ      | 7             |
| Mega Walls            | WALLS3          | Walls3        | 13            |
| Arcade Games          | ARCADE          | Arcade        | 14            |
| Arena Brawl           | ARENA           | Arena         | 17            |
| UHC Champions         | UHC             | UHC           | 20            |
| Cops and Crims        | MCGO            | MCGO          | 21            |

### Storage
Games store their respective stats and data in a Player's `stats` collection. The game's specific data is held within a JSON object named after it's `Database Name` (seen above.)

### Notes
* Chances are the IDs will not ever be used/needed in the API or API clients.
* Friendly names are what is displayed to the user when referencing the name.
* Type names are used when the API references a specific GameType.
