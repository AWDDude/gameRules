# Liar's Dice Rules

## Overview

Liar's Dice is a bluffing and deduction dice game for 2 or more players. Each player has a set of dice hidden under a cup. Players take turns making increasingly bold claims about the total dice on the table, and opponents must decide whether to believe or challenge. The last player with dice remaining wins.

## Players

2-6 players (best with 4-5 players)

## Equipment

- 5 standard six-sided dice per player
- 1 opaque cup per player (to hide dice)

## Objective

Be the last player with dice remaining by outbluffing opponents and accurately reading their claims.

## Setup

1. Each player starts with 5 dice and a cup
2. All players simultaneously roll their dice and keep them hidden under their cup
3. Each player may look at their own dice but must keep them hidden from others
4. Choose a starting player (first round is random; subsequent rounds start with the player who lost the previous challenge)

## Gameplay

### Making a Bid

On your turn, you must either **raise the bid** or **challenge** the previous bid.

A bid consists of a **quantity** and a **face value** — for example, "three 4s" means you are claiming there are at least three dice showing 4 among all dice on the table (including your own).

### Raising the Bid

To raise, you must increase the bid in one of two ways:

- **Increase the quantity** with any face value (e.g., "three 4s" → "four 2s")
- **Keep the same quantity but increase the face value** (e.g., "three 4s" → "three 5s")

Play proceeds clockwise. Each player must raise or challenge — you cannot pass.

### Challenging (Calling "Liar")

Instead of raising, you may challenge the previous player's bid by calling "Liar!" (or "I doubt it," etc.). When a challenge is made:

1. **All players lift their cups** and reveal their dice
2. **Count the total** number of dice showing the bid's face value across all players
3. **Determine the outcome**:
   - If the actual count is **equal to or greater than** the bid → the **challenger loses** (the bid was valid)
   - If the actual count is **less than** the bid → the **bidder loses** (the bid was a lie)

The loser removes one die from the game permanently.

### Starting a New Round

After a challenge:

1. The loser starts the next round
2. All players re-roll their remaining dice and hide them
3. A new round of bidding begins with no prior bid

### Elimination

When a player loses all their dice, they are eliminated. Play continues until only one player remains.

## Wildcards (1s are Wild)

In the standard version, **dice showing 1 count as every face value**. This effectively increases the count for any bid.

**Example**: The dice on the table are 1, 1, 3, 4, 5, 6, 3, 2, 4, 3. If someone bids "five 3s," the actual count of 3s is 3 (actual 3s) + 2 (wild 1s) = 5. The bid is valid.

### Bidding 1s

Because 1s are wild, they are harder to bid and follow special rules:

- **Bidding 1s requires only half the quantity** (rounded up) compared to other face values. For example, if the current bid is "six 3s," a bid of 1s only needs to be "three 1s" or higher.
- **Switching from 1s back to another face value** requires doubling the quantity plus one. For example, "three 1s" requires at least "seven 2s" (or higher face) to raise with a non-wild value.

### No-Wilds Variant

Some groups play without wild 1s — each die only counts for its actual face value. This simplifies bidding rules and makes the game more predictable.

## Scoring

There is no point-based scoring. The game is purely elimination-based — lose a challenge, lose a die. Lose all dice, you're out.

## Winning

The last player with one or more dice remaining wins the game.

## Strategy Tips

1. **Use your own dice as a baseline** — if you have two 5s, there are likely more on the table
2. **Calculate expected counts** — with N total dice on the table, expect roughly N/3 of any face value (N/6 natural + N/6 wild 1s)
3. **Bid conservatively early** — small raises give you information from others' reactions
4. **Watch for hesitation** — players who pause before raising may be bluffing
5. **Bluff strategically** — occasional bold bids keep opponents guessing and discourage challenges
6. **Challenge when the math doesn't work** — if a bid exceeds half the total dice on the table, it's statistically unlikely
7. **Adjust for player count** — with fewer players remaining, bids should be lower
8. **Track eliminated dice** — as dice leave the game, maximum possible counts drop

## Common Variations

### Palifico (Spot On)

A player reduced to one die triggers a **Palifico round**:
- 1s are **not wild** for that round only
- Bids can only increase in quantity, not face value (unless changing the face value entirely)
- Normal rules resume next round

### Exact Call

Any player may call **"Exact"** (or "Spot On") instead of raising or challenging:
- If the actual count **exactly matches** the current bid, the caller gains a lost die back (up to 5)
- If the count does not match exactly, the caller loses a die
- High risk, high reward

### Open Hand

When a player is reduced to one die, they roll it openly (visible to all). Other players' dice remain hidden.

## Terminology

- **Bid**: A claim about the minimum number of dice showing a specific face value across all players
- **Challenge**: Calling another player's bid a lie, triggering a reveal
- **Wild**: Dice showing 1, which count as any face value (in standard rules)
- **Palifico**: A special round triggered when a player is reduced to one die
- **Spot On / Exact**: A call that the current bid is precisely correct

## Example Hand Walkthrough

### Setup

3 players (Alice, Bob, Carol), each with 5 dice (15 total dice on the table).

### Roll

- Alice looks at her dice: 1, 3, 3, 5, 6
- Bob looks at his dice: 2, 2, 4, 4, 6
- Carol looks at her dice: 1, 3, 5, 5, 6

### Bidding

- **Alice** opens: "Three 3s" (she has two 3s and a wild 1 — she knows of three already)
- **Bob** raises: "Four 5s" (a guess — he has no 5s but is bluffing to shift the face value)
- **Carol** raises: "Five 5s" (she has two 5s and a wild 1 — she believes there are likely more)
- **Alice** raises: "Five 6s" (same quantity, higher face value)
- **Bob** thinks this is too high and calls **"Liar!"**

### Reveal

All players reveal their dice. Count the 6s (including wild 1s):
- Alice: 6, 1 (wild) → 2
- Bob: 6 → 1
- Carol: 6, 1 (wild) → 2

Total 6s: **5**. Alice's bid of "five 6s" is exactly correct.

### Result

Bob loses because the bid was valid (5 ≥ 5). Bob removes one die and now plays with 4. Bob starts the next round.
