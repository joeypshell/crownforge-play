# Crownforge — moving crowns v0.17

[Play Crownforge](https://joeypshell.github.io/crownforge-play/?v=0.17.0)

Start with **your King and one Knight**. Defend your King and capture the enemy King across three encounters. The enemy King gets **two quiet one-square steps per encounter**, using its army's shared action. Its remaining steps appear on the board and in Details. Captures do not spend steps, and it can still capture adjacent pieces after both steps are used. Each encounter restores two steps. Capturing it immediately wins even if defenders or future waves remain.

Each side shares one basic move per turn. Extra commands come from upgrades and consumables. Additional fighters appear as random reward or paid reinforcement cards, competing with equipment and army relics. Choose one free card from three after each of the first two wins; an optional paid market permits one separate purchase. Knight recruits are common, Bishops less likely from the second visit, and Rooks are reserved for later expansion. Maximum army: King and two fighters. Recruitment does not add another basic move.

Captures are permanent. Losing your King **or your last fighter** ends the run. If you have two fighters, losing one lets you continue, but its equipment and kill progress are gone. Each ordinary capture earns 1 gold, enemy King capture earns 4, and the visible Hold Formation objective adds 2 if your starting escorts survive. Equipment and relics persist only within the run.

Enemy movement follows chess geometry; Pawns move forward, capture diagonally, and can promote. Defenders prioritize their King and avoid immediately giving away pieces when safe alternatives exist. This is a heuristic and can be outplayed by upgrades and extra commands. No enemy Knights appear in this short trial.

On mobile, tap a piece and a destination, then **Confirm**. Swipe vertically through reward cards; dragging cancels purchase taps. Use **Details** for rules and **Menu** to restart. Desktop supports click moves and hover forecasts. **End Phase** explicitly commits the shown response, and **Undo** works until commitment or encounter clear.

Start with one Hold Draught to skip your required move once without protection. Markets sometimes stock another for 3 gold. Major movement grafts and Second Command stay rare and expensive from shop four, outside this trial. The separate Combo Lab demonstrates late build potential.

Prototype limits: three encounters, no saved runs, no audio, procedural art. This public repository contains exported assets; development source is maintained separately. Published `version.json` identifies the tested source commit. Desktop, touch, rules, random progression, and complete earned-progression runs are tested.

Made with Godot 4.7. See `LICENSE-GODOT.txt`.
