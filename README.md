# Crownforge

[Play Crownforge 0.6](https://joeypshell.github.io/crownforge-play/?v=0.6.0)

A chess roguelike about building powerful pieces through random upgrade offers.

Version 0.6 starts you with **one shared command per phase**. There is no health: enemies capture with legal chess moves, and losing your crowned protagonist ends the run. A captured companion is permanently lost.

Spend commands, inspect the live enemy forecast, and choose **End phase** when ready. Enemies wait even after your last command. **Undo (Z)** is available until you commit; **Space** ends the phase. Hover destinations to preview captures, effects, and danger.

Earn additional commands through Rhythm, Momentum, movement-only Footwork, or companion-only Handoff. Reserve Order supplies one manually activated full command per encounter. All sources share a two-bonus-per-phase limit.

**Second Command** permanently adds a shared action each phase. It is a rare find from shop four, costs 18 gold, occupies two of the protagonist's four slots, and has an independent 8% chance per eligible market roll. Movement grafts remain limited to one per piece. Powerful chess grafts are also rare and late; Pawn Graft is a common 3-gold foundation.

Six encounters feature slower reinforcement waves, pawn promotion races, and late hybrid enemies. Waves advance by enemy phases, never commands spent. Newly arriving and promoted enemies receive no immediate extra attack. Three random market offers, one purchase, and a limited paid reroll keep each build uncertain. Recruitment is optional, supports at most two pieces, and adds no commands.

Combo Lab demonstrates a fully upgraded queen: jump D2 -> E4, then slide E4 -> H7 after the chain removes the guards.

Prototype: desktop mouse controls, procedural artwork, no audio, and no saved runs. Difficulty and progression are still being playtested. This public repository contains exported game files; source development is maintained separately.

Made with Godot 4.7. See `LICENSE-GODOT.txt`.
