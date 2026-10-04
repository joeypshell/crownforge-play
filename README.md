# Crownforge — Army Deck Lab v0.20.0

[Play Crownforge](https://joeypshell.github.io/crownforge-play/?v=0.20.0)

Draw your army, chain your orders, and defend your crown. This short three-wave prototype tests a card-driven chess deckbuilder. Start with a King and Knight, draw five cards, and spend three command points on several plays before the enemy responds.

Piece cards command a matching soldier or recruit one in your home ranks with an immediate legal move. There are no free fighter moves. The same soldier can move repeatedly when you have the cards and energy. Four soldiers can stand beside your King. Captured soldiers disappear from the board; their cards and upgrades survive so you can rebuild. Only losing your King ends the run.

Chess capture geometry stays intact: Pawns advance into empty squares and capture diagonally, then promote on the far rank. Pawn cards command their promoted Queen for two points. Clear every enemy in each wave, including the final King and its defenders. The opening force gets one action; later forces get two, with each enemy acting at most once per phase.

After the first two waves, choose one of three random cards, relics, or one-copy upgrades. An optional random forge candidate costs four gold and must be purchased before choosing your free reward. Ordinary captures earn one gold, Kings four, and clearing each wave adds two.

Starter is the default deck. Cavalry and Promotion are test presets for comparing capture-and-draw chains with Pawn marches, sacrifices, and promotion. Every preset starts with the same King and Knight; these presets are lab examples, not permanent unlocks.

Select a card, choose Command or Recruit and the board target, then Confirm. End turn commits the enemy response. Undo works before End turn or wave clear. Redraw up to two cards once per turn. A selected card can instead pay for one quiet King retreat. Mobile has a scrollable Hand sheet and fixed action controls. Normal hides exact enemy responses; Easy reveals them with identical rules and AI.

Previous prototype opens the preserved eight-court game. This lab has no saved runs or full campaign yet. Automated rules, interaction, mobile, and 36 seeded simulation checks passed; simulations verify legal combinations, not human enjoyment or win rates.

This public repository contains exported assets. Development source is maintained separately; version.json identifies the tested source commit.

Made with Godot 4.7. See LICENSE-GODOT.txt.
