# The Wizard's Tower

A fantasy puzzle game for the family (aimed at ~10-year-olds, in English).
Each run is three trials picked at random from seven puzzle types, avoiding the ones used in the previous run
(remembered in the browser's localStorage).

| Trial | Puzzle |
|---|---|
| Potion Cellar | water-sort (boards are checked solvable) |
| Rune Lock | Lights Out (always solvable; Hint button) |
| Riddle Gate | 3 riddles from a pool of 22, answered with letter stones (Hint, keyboard typing); recently seen riddles are skipped |
| Shifting Stones | 8-puzzle slide (scrambled by legal moves, so always solvable) |
| Memory Mirrors | find 6 matching pairs |
| Crystal Choir | Simon-style: repeat a growing 5-note sequence |
| Mana Pipes | rotate pipes to carry magic from the star to the diamond |

Single self-contained file: `index.html` (no dependencies, works offline, touch-friendly).
