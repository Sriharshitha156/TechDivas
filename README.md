# TechDivas
Android Workshop Project: Video Gaming


1. Problem Statement

Most action or magic-based games rely on fixed buttons and repeated patterns of attack. This makes the gameplay predictable, less skill-based, and not very unique.
Our game solves this problem by allowing players to draw gestures (shapes) to cast spells, making the gameplay more natural, creative, and completely skill-based.
Additionally:
Traditional games often force players into fixed character stories → we allow players to choose or create their own character story.
Most games use god characters directly, which may create conflict → we use god-inspired powers without showing gods themselves.
Many multiplayer games match players with strangers → we allow the player to select their own opponents, giving more control and safety.

2. Idea Description

Wizard’s Circle is a multiplayer magical combat game where players draw rune-shapes with their fingers (or mouse) to cast spells.
Our updated idea also includes:
Powers in the game are inspired by mythological gods (like lightning, fire, storm, creation, destruction), but no god appears directly to avoid religious issues.
Each character has no fixed story — instead, players can create their own background.
The game lets players choose whom they want to fight, avoiding unwanted matchups.
In team mode, if a teammate is in danger, you can instantly teleport to their location to help.
Players can watch other players’ fights live as a spectator.
If a player goes inactive, AI automatically takes control so their team isn't at a disadvantage.
If one team is far behind, the game can give balancing points to keep competition fair and fun.

3. Theme & Genre

Theme:
Magical, fantasy-based world filled with glowing spells, ancient runes, and mystical arenas.

Genre:
Action
Multiplayer Arena Combat
Fantasy
Skill-based gesture system
Casual + Competitive PvP

4. Base Features

A. Non-Negotiables (Must Be Included)
These features are required for the game to function properly.

1. Rune Drawing Spell System
Players draw shapes (Triangle, Circle, Square, Zig-Zag, Spiral, Caret ^).
Each shape becomes a spell.
For example:
Triangle → Fire Burst (explosion)
Circle → Trap Ring (enemy cannot move)
Zig-Zag → Lightning Bolt
Explained simply: You draw a shape → It becomes magic.

2.  Wizard Classes with Passive Abilities
Wizards have built-in abilities that are always active.
Examples:
Frostel → When she hits someone, they slow down.
Umbrix → Can teleport farther than others.
This gives variety and strategy.

3. Core Gameplay Loop
The repeated cycle that makes the game playable:
Player enters arena
Moves around
Draws gestures to cast spells
Survives hazards
Arena shrinks
Last player standing wins
In simple words: Enter → Fight → Survive → Win.

4. One Functional Arena (Arcane Circle)
This is the main fighting area.
It slowly becomes smaller, forcing players closer so the match finishes.

5. Basic Movement & Health System
Players must be able to:
Walk
Take damage
Lose health
Die when health becomes zero
Without this, the game cannot function.

B. Good-to-Have Features

These make the game better, but the game can still run without them.
Extra arenas with special mechanics
Spell combinations (multiple shapes in a sequence)
Character skins
Sound effects
Simple matchmaking
Practice mode with AI
Reflection-based arena effects

C. Not Implementing (Future Scope)

Ranked 2v2 competitive mode
Magic guild system
Story/campaign mode
Seasonal battle pass
Advanced rune system

5. Custom Features 

God-inspired powers but no gods shown
Prevents cultural or religious conflict.
Still allows powerful, myth-inspired magic.
Player can choose their own character story
Gives freedom and personal connection.
Game uses gesture controls only
No button-pressing moves.
Every action feels magical.
Choose your own opponents
Players have control over who they fight.
Safer for younger players.
Team Support Teleport
If your teammate is losing, you can directly teleport to them to help.
Live Spectator Mode
Players can watch ongoing battles.
AI Autoplay if Player is Inactive
Prevents unfair disadvantage in team matches.
Dynamic Balance System
If one team is too strong, the losing team gets small bonus points.
Keeps games fun and reduces frustration.

6. Tech Stack (Tools Used)

Frontend (Game visuals & mechanics):
