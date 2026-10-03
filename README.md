# Crownforge

[Play Crownforge 0.10](https://joeypshell.github.io/crownforge-play/?v=0.10.0)

A chess roguelike about building powerful pieces through random upgrade offers.

Version 0.10 adds a responsive phone/tablet interface. Tap a piece and a destination, review the forecast, then press **Confirm**. Use **Type** to compare alternatives, **Details** for rules and abilities, and **Menu** for restart and speed. Portrait and landscape layouts adapt to the screen; the upgrade shop scrolls vertically. Rotation preserves the run and shop choices while canceling an unconfirmed move. Desktop mouse controls remain available.

The enemy army has **one shared move or capture per phase**. One selected enemy acts while the others hold their positions. The forecast identifies that response and updates as you play. Kings hold their ground: they cannot retreat or take quiet moves, but can capture adjacent attackers using the army's one action.

The opening king starts on E7 with pawn defenders on C6 and G6. Remove defenders or find a safe route around them; a pawn reinforces after phase three. A legal direct king capture ends the encounter even with enemies alive or waves pending. Gold escort diamonds confer no immunity. Take an early opening to win, or risk further captures for gold.

Every friendly piece has **one required move per round**. Each friendly owns its basic move; completely blocked pieces may pass. Captures, including pawn captures, stay optional. There is no health: losing your crowned protagonist ends the run. A captured companion is permanently lost.

Move each piece, inspect the live enemy forecast, and choose **End phase** when ready. Extra moves are optional and expire at commitment. Enemies wait even after your last command. **Undo (Z)** is available until you commit; **Space** ends the phase once all required moves are fulfilled. Hover destinations to preview captures, effects, and danger. Idle defenders' potential capture coverage is distinct from the one selected enemy action.

Start with one **Hold Draught**. It lets one unmoved friendly skip its required move once, without protection or combat effects. Carry up to two. Markets have a 35% chance to stock one for 3 gold, separate from the upgrade purchase; rerolls do not change potion stock. Draughts persist but never refill automatically. Undo restores a used draught before commitment.

Earn additional commands through Rhythm, Momentum, movement-only Footwork, or companion-only Handoff. Reserve Order supplies one manually activated full command per encounter. All sources share a two-bonus-per-phase limit.

**Second Command** permanently adds a shared action each phase. It is a rare find from shop four, costs 18 gold, occupies two of the protagonist's four slots, and has an independent 8% chance per eligible market roll. Movement grafts remain limited to one per piece. Powerful chess grafts are also rare and late; Pawn Graft is a common 3-gold foundation.

Six encounters feature slower reinforcement waves, pawn promotion races, and late hybrid enemies. Waves advance by enemy phases, never commands spent. Newly arriving and promoted enemies receive no immediate extra attack. Three random market offers, one purchase, and a limited paid reroll keep each build uncertain. Optional recruits appear from shop three, support at most two pieces, and bring their own required move.

Combo Lab demonstrates a fully upgraded queen: jump D2 -> E4, then slide E4 -> H7 to capture the king. Clearing every escort is optional whenever a legal route opens.

Prototype: desktop mouse controls, procedural artwork, no audio, and no saved runs. Difficulty and progression are still being playtested. This public repository contains exported game files; source development is maintained separately.

Made with Godot 4.7. See `LICENSE-GODOT.txt`.
