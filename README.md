# Oath Dice Roller

This project is a simple web app that implements dice rolling for the board game Oath. The app is contained in a single static HTML file, using Vue for reactivity.

Oath's campaign system is complex, and its fiddliness is not helped by the limited set of dice that ship with the game, despite them not being technically component-limited. It might be a sign that you're off the rails if you need more than what's in the box, but sometimes things just get out of hand. This project is a simple implementation of a dice roller for Oath's campaigns that should be flexible enough to support any modifiers made to the campaign action that affect dice rolls.

## Usage

The app is split into three main sections:

1. _Defender:_ Set the defender's participating warbands and dice pool. The _re-roll defence dice_ button populates a set of outcomes. These can also be adjusted or set manually.
2. _Attacker:_ Set the attacker's participating warbands and whether they're willing to sacrifice for victory. The _re-roll attack dice_ button populates a set of outcomes. These can also be adjusted or set manually.
3. _Outcome:_ Shows the total defence and attack roll, along with any warbands that the attacker is sacrificing.
