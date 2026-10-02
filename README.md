# Crownforge

Public browser build of Crownforge, a chess-inspired roguelike about stacking abilities on powerful pieces.

## Play

[Play Crownforge](https://joeypshell.github.io/crownforge-play/)

Click to select a piece and move. Hover destinations to preview captures and effects. Space ends your phase. The Combo Lab demonstrates the complete queen build.

Version 0.5: each piece can carry only one movement graft. Common Pawn Graft costs 3 gold and adds modest forward movement and diagonal captures. Royal Step costs 8 and unlocks after encounter three. Rook, Bishop, and Knight Grafts cost 16/14/14, cannot appear before the market after encounter four, and share an 8% chance per eligible market roll to occupy one offer. A new graft must explicitly replace the old one.

Stop enemy pawns before they reach rank 1 and promote to queens. Gold warnings and move previews reveal promotion danger. Newly promoted queens announce their attacks for the next phase, giving you time to respond. Pawn Graft preserves your piece's base identity and does not grant promotion.

Enemies move and attack with their normal chess geometry. Pawns attack only forward diagonals; rooks, bishops, queens, and knights follow their own shapes. Blocking an announced sliding route cancels its move. Later waves introduce marked Pawn + Rook, Bishop + Knight, Rook + Knight, and Queen + Knight stacks that combine only those movement and attack patterns.

Six encounters feature announced reinforcement waves and a final boss. Start with a plain knight and build through three random market offers, one upgrade purchase per visit, and one paid reroll. Fourteen upgrades support movement, splashes, chains, defense, and extra actions. Recruit one optional companion; both pieces share two actions per phase.

This is an early playable prototype with placeholder vector art, no audio, and no saved runs. Difficulty and upgrade pacing remain open to playtesting.

This repository contains the exported game for hosting. Source development is maintained separately.

Made with Godot 4.7. See `LICENSE-GODOT.txt` for the engine license.
