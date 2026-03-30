# About Wanderer

Wanderer is an old text-based game originally written by Steven Shipway in C on a Sun/3-160.

## Gameplay

In the following description, the character used for each item is shown as it appears in full-screen mode (press `#`). This is also the character used in the screen files that define each level.

You are a spider (`@`) who must gather all the treasure (`*`) in a level and then reach the exit (`X`), all before the allotted number of moves expire. The game is played over many levels, each becoming available as you finish the prior one. When you complete a level you receive a password that lets you jump directly to that level in a future session.

### Items

| Character | Item | Description |
|-----------|------|-------------|
| `*` | Treasure | Collect for 10 points. Must collect all to exit. |
| `X` | Exit | Go here once all treasure is collected. Worth 250 points. |
| `:` | Passable earth | Dig through it, clearing it away. Worth 1 point each. |
| `#` | Solid rock | Cannot be blown up. |
| `=` or `\_` | Destructible rock | Can be blown up. |
| `T` | Teleport | Takes you to a new location (`A` in screen files). Optional, but worth a 50 point bonus. |
| `O` | Boulder | Falls down. A falling boulder kills you. Can be pushed sideways (but not in groups). |
| `<` | Left arrow | Shoots left. Triggers if you come near. Kills you if it hits you. Can be pushed up or down (but not in vertical groups). |
| `>` | Right arrow | Shoots right. Same behavior as left arrow. |
| `!` | Landmine | Kills you on contact. |
| `S` | Baby Monster | Travels along surfaces. Must be captured in a cage — the cage becomes a diamond you must then collect before you can exit. Worth 50 points when captured. |
| `+` | Baby Monster Cage | Captures Baby Monsters on contact and turns into treasure. |
| `/` or `\` | Slope | Boulders, arrows, and balloons slide off these. |
| `C` | Time Capsule | Worth 5 points and grants 250 extra moves. |
| `M` | Big Monster | Chases and kills you. Kill it by hitting it with an arrow or dropping a boulder on it (worth 100 points). |
| `B` | Bomb | Explodes and destroys the surrounding area if hit by a boulder or arrow. Fatal if you are in the blast radius. |
| `~` | Thingy | Can be pushed around and stays where placed. Boulders and arrows do not slip around it. |
| ` ` or `-` | Open space | Move freely. |
| `\|` | Wall | |

## Commands

| Key | Action |
|-----|--------|
| Arrow keys or `hjkl` | Move (left, down, up, right) |
| `#` | Toggle full-screen mode |
| `~` | Jump to level (using password) |
| `S` | Save game |
| `R` | Restore game |
| `?` | Help |
| `!` | Show map |
| `@` | Center map |
| `q` | Quit |
| `x` | Exit |
