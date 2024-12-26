
# Ludus Cyclorum

- [Ludus Cyclorum](#ludus-cyclorum)
  - [1. Introduction](#1-introduction)
  - [2. How to Play](#2-how-to-play)
  - [3. Rules](#3-rules)
    - [Stone Symbols](#stone-symbols)
  - [4. Variation and Exploration](#4-variation-and-exploration)

## 1. Introduction

This is a print &amp; play game inspired by *chess*, *war games* and the roman *ludus latrunculorum*. I invite you to play it, express opinions and ideas, discuss it with me on [discord](https://discord.com/invite/QFY5Qe8) or even tell me this exists already. It's an abstract strategy game where both players fight with sets of pieces, including one leader each, the "Dux". Your goal is to either take the opposing Dux or all pieces under their command. Slightly different rules apply to each type of piece. All pieces of both players act before any single one may act again.

Warning: I haven't tested this game much, just had the idea wrote rules and made a board, then played two rounds with my dad.

## 2. How to Play

First you should read the rules, there aren't very many. There's no TTS version as of now. For physical play you'll need a board and pieces. The board is available in the repository: "board.pdf". Instead of printing it you can also just draw the lines on a piece of paper. I created my set of pieces by using german cents which I cleaned and then drew on with a metal marker. What to draw on your pieces is described in the rules. Using something that you can easily flip over is essential.

## 3. Rules

The current board and starting position look like this: ![image](assets/ludus-cyclorum-full-board.svg)

As you can see pieces (from now on called stones) are placed on line intersections. The arrows on the stones indicate which player they belong to. The dot in the center of each stone indicates its "phase". Next to the board lays the phase-marker. The back and front of each stone (and the phase-marker) are identical, but one side features the dot and the other instead a tilde. Around the dots you can see the "symbol" of each stone. Crosses are Dux, triangles are spears, squares are shields, eyes are swords and riders remain.

Now for the rules:
1. Determine the starting player somehow
2. Win by taking the opposing Dux or their party
3. Players go back and forth "acting" with a single stone each, then flipping it over
   1. Only stones that match the phase of the phase-marker may be used ("active" stones)
   2. If you still have active stones and your opponent doesn't continue alone until yours are all inactive too
   3. You must always act with one stone (though you can choose to idle, simply flipping one)
4. When all stones of both players are inactive immediately flip over the phase-marker (you've completed a cycle)
   1. If you just acted it is now your opponent's turn
5. The actions that may be performed with stones are the following:
   1. Move as many tiles as the stone symbol allows
   2. Attack another stone using the range specified by the attacker's symbol, removing the defender from the board (this does not move the attacker)
   3. Rush: A combined action of moving first, then attacking in the direction of movement
6. If a stone moves out of the attack range of another, active stone, that other stone may perform an attack of opportunity, becoming inactive and removing the stone that attempted to move
7. Friendly fire is allowed

### Stone Symbols

Assume that by default each symbol moves one space and attacks with a range of one. Each symbol has some special rules, listed below:

> **Sword**
>
> May attack and move (in any order) in a single action.

> **Shield**
>
> Can only be taken while inactive and becomes inactive when attempted to be taken while active.

> **Rider**
>
> Has no regular attack.
> May move up to 3 tiles, on each step not repeating the previous tile.
> Can trample (jump) over another stone (landing on an empty tile), taking it, using two tiles of movement.
> Can take with a "passing slash" on the second or third tile of movement, by moving between two positions adjacent to another stone, but only once per action.
> Trampling and passing slashes cannot be combined.

> **Spear**
>
> Attacks only exactly at a range of 2 and only straight (possibly "through" allied stones, without harming them).
> If trampled or rushed the attacker is also taken.

> **Dux**
>
> Has the "abilities" of both sword and shield and can pierce through shields.

## 4. Variation and Exploration

There are many things you can play around with and that I may explore whenever I feel like thinking about this game more, I'll simply list some here:

1. Some of the current symbol rules seem a little clunky, specifically aspects of the spear and rider.
2. As there are two different phases, maybe some rules could be different depending on the current phase.
3. There could be more or less starting stones.
4. There could be more, less and different kinds of stone symbols.
5. Players could start by placing stones down in custom formations or choose from a set of existing ones.
6. The board could have a different size, shape or orientation.
7. One could use a physical marker placed on stnoes, instead of flipping them over.
8. Stone mechanics could be further explored or existing ones turned into global rules, like stones being able to block like the shield by going inactive.
9. Tiles could have different "terrain" that affects stones placed on them, creating potential for different maps
10. In general, exploration of more war game mechanics could be interesting, like having a list of stone symbols online (probably removing specific interactions like between spear and rider), players showing up with custom armies, then dropping them in custom formations at the start
