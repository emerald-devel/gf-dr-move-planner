# GFL DR Hole 2 Move Planner

## Why?

Planning without a planner is stupid. Planning with a planner will make you slightly less stupid. Won't fix EN syndrome, though.

## How to Install

Just download the thing and open the index.html file in your browser. No internet required. No fancy installation tools. Just browser. Or use [this online version](https://emerald-devel.github.io/gfl-ranking-move-planner/index.html). Whatever floats your boat.
## How to Use

- Left-click a node to change its faction ownership.
- Ctrl + left-click a node to mark it as being affected by an EMP.
- Right-click a node to mark it as being occupied by a mob. One click gives it a normal mob (small dot) and a second click gives it a deathstack (large dot).
- Ctrl + right-click a node to mark it as being occupied by an ally. One click gives it an NPC (small dot) and a second click gives it a deployed echelon (large dot).
- The `Turn: X` button allows you to select the current turn you're on. Setting this currently does nothing except serve as a nice visual indicator because unlike the PL version, the DR version cannot reasonably predict enemy movement. Left-clicking will add 1 to the turn and right-clicking will remove 1 (don't worry, it wraps around either way).
- Importing and exporting of the map state can be done via standard copy and paste shortcuts. Simply use Ctrl+C to copy the map state and Ctrl+V to restore from a map state currently stored in your clipboard.
- Tried to experiment with some changes and don't like them? Forgot to save the map state beforehand? Ctrl+Z is a thing. Screwed up by hitting Ctrl+Z out of habit? Ctrl+Y can reverse that, too. Remember to save your map state next time, you fucking brainlet.
- Want a clickable link to a map state? Just add `?state={your state here}` (without the curly braces!) to the end of the sim tool's URL and enjoy having fewer keys to press.

## Disclaimers

- This tool will not prevent EN syndrome.
- This tool will not cure EN syndrome, either.
- Enemy movement prediction is not available when RNG enemy movement is involved. Get over it.
- This tool will be updated to be usable with current EN ranking maps.
- If you need an older version, then look through the old releases.
- If you need this tool updated for a new event that hasn't yet run on EN, then write your own fucking code.

## Other

Want to help improve this? Write some code and make a pull request. If it's a valuable update, I'll probably approve it. Just try to keep the no-internet thing working.
