# Gungi
Hello players! Welcome to Gungi. A board game from Hunter x Hunter.

The rules for this version of Gungi were originally detailed in
[this tumblr post](https://mmmmalo.tumblr.com/post/74510568781/rules-of-gungi).
This version does its best to use these rules as much as possible. Any 
discrepancies will be highlighted below.

Gungi takes place on a 9 by 9 square board. There are two players. By default
they are Black and White. Black goes first, and then the two players take turns.

Pieces that are on the board are called **active** pieces, while captured pieces
are taken from the board and added to your **hand**. 

Horizontal rows are to as **rank**. Vertical columns are **files**.

## Initial arrangement
The first three ranks on your side of the board are your territory.
At the beginning of the game, after the players have picked their colors,
the **initial arrangement** begins. Gungi does not have predefined starting
positions the same way chess does. Players take turns placing pieces wherever
they please within their territory. Every single piece must be placed on the
board during the **initial arrangement**. It should be noted that there also
must be a *Pawn* in every **file** at the end of **initial arrangement**.

## Towers
Pieces can be stacked on top of each other in Gungi; any position on the board 
with such an arrangement is called a **tower**. A **tower** can have up to three 
layers, called **tiers**. While it is safest to build on your own pieces, it is
also possible to land on your opponent’s pieces and share a tower 
with your opponent.

Within a **tower**, two pieces of the same type and team cannot coexist. 
It is not against the rules to occupy the **tower** of an enemy that contains 
a piece of the same type.

Only pieces on the top-most **tier** of a **tower** are able to move. Any 
piece(s) below are rendered immobile until the piece(s) above them have 
been removed.

## Attacks
There are two types of attacks: **mobile** and **immobile**.

In a **mobile strike**, you attack an enemy piece within your piece’s range, 
occupy its position, and add the enemy piece to your **hand**. When attacking 
another **tower** with a **mobile strike**, you can only attack the top-most 
**tier**, no matter how high your own **tower** may be. This means that when 
you attack a **tower**, you replace the top-most **tier**. This is turn exposes
the attacker to the threat of an **immobile strike**.

An **immobile strike** lets you attack the piece above or below your piece in 
a **tower** and add it to your **hand**. If the piece was on top, you simply 
capture it. If the piece was below, the pieces above it descend to a lower 
**tier**. You cannot attack a piece that is two **tiers** above or below your 
piece.

## Drops
When you capture a **Front** piece, the accompanying **Back** piece is added 
to your **hand**, and vice-versa. The pieces in your **hand** can be played 
anew as a member your team. Doing this is called a **drop**. Like any other 
move or attack, a **drop** takes up one turn.

You can **drop** a piece from your **hand** onto any empty space on the board. 
You cannot capture a piece with a **drop**. Aside from a few exceptions, 
you cannot **drop** directly on top of another piece. 
**Drops** can be used to achieve **checkmate**, with some exceptions.

## Checkmate
The ultimate goal of Gungi is to capture the *Commander*. This piece shares the 
functionality of the King in chess, but was likely renamed for political reasons 
within the Hunter x Hunter universe.

If a *Commander* is in range of a **mobile** or **immobile strike** from the 
enemy such that it could be captured on the next turn, it is said to be in 
**check**. A *Commander* cannot move into **check**. To avoid defeat, a 
*Commander* in **check** must either run away, block the attack of the piece(s) 
that threaten it, or eliminate the piece(s) that threaten it. 
Failure to do any of these results in **checkmate**. Whoever puts their opponent
in **checkmate** wins.

---

## Pieces
There are a total of 46 pieces on the board at the start of the game, 
23 for each side. As mentioned before, each of these pieces has a **Front** 
and **Back** side with different abilities. The pairings and amount of each 
pair per team are as follows:

| **Front** | **Back** | amount |
| ---   | ---  |    ---:|
| *Commander* | N/A | 1 |
| *Captain* | *Pistol* | 2 |
| *Samurai* | *Pike* | 2 |
| *Spy* | *Clandestinite* | 3 |
| *Catapult* | *Lance* | 1 |
| *Fortress* | *Lance* | 1 |
| *Hidden Dragon* | *Dragon King* | 1 |
| *Prodigy* | *Phoenix* | 1 |
| *Bow* | *Arrow* | 2 |
| *Pawn* | *Bronze* | 7 |
| *Pawn* | *Silver* | 1 |
| *Pawn* | *Gold* | 1 |

Traditionally each piece has a Chinese character that labels them. This version
of Gungi uses icons. They all also have a range of movement that can be altered 
by moving to a different **tier** in their own **tower**. Any piece that is on 
top of an enemy piece has the same set of moves as *Gold*, no matter what. Some 
also have more nuanced special abilities. We’ll start to cover those here.

### Front
#### Commander
![Commander move set](https://66.media.tumblr.com/9768f6cc235edc8314a30c8de745e6b2/tumblr_inline_p7hqjaXd2S1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       .....
.XXX.       .XXX.       .XXX.
.XCX.       .XCX.       .XCX.
.XXX.       .XXX.       .XXX.
.....       .....       .....
```
- Moves to any adjacent space, including diagonally, regardless of **tier**. Similar 
  to a King in chess.
- Cannot move into **check**.
- When in **check**, cannot move to a space occupied by your own pieces.
- A **tower** cannot be built on top of a *Commander*.
- Cannot receive **Mobile Range Expansion Effect**.
- Cannot be added to **hand**.

#### Captain
![Captain move set](https://66.media.tumblr.com/a08c904f109051398311460d9a2cc4e0/tumblr_inline_p7hqjahj751r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       X...X
.XXX.       .XXX.       .X.X.
..C..       ..C..       X.C.X
.X.X.       .XXX.       .X.X.
.....       .....       .....
```
- Has the **1-3 Tier Exchange Effect**.

#### Samurai
![Samurai move set](https://66.media.tumblr.com/c73034abb3949478ef1e0e4c25b17418/tumblr_inline_p7hqjbw7Oc1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       ..X..       ..X..
.XXX.       .X.X.       .X.X.
.XSX.       .XSX.       .XSX.
.....       .....       .....
.....       ..X..       ..X..
```
- Has the **Substitution Effect**.

#### Spy
![Spy move set](https://66.media.tumblr.com/b642d012f60fa299583b12318d7feb32/tumblr_inline_p7hqjbgSdV1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.X.X.       .X.X.       .X.X.
.....       .X.X.       .X.X.
..S..       ..S..       ..S..
.....       .....       .....
.....       .....       .....
```
- Able to jump over other pieces.
- Has the **Forced Recovery Effect**.
- Has the ability **Land-Link**.

#### Catapult
![Catapult move set](https://66.media.tumblr.com/d136ac94c9c8b0c4b4f5a87b425e3b47/tumblr_inline_p7hqjbMDmM1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       .....
.....       .....       .....
..C..       ..C..       ..C..
.....       .....       .....
.....       .....       .....
```
- Completely **immobile**. Can’t do **mobile strikes** at all.
- Imparts the **Mobile Range Expansion Effect**.
- Has the ability **Land-Link**.
- Cannot be added to your **hand**.

#### Fortress
![Fortress move set](https://66.media.tumblr.com/dbafe60efc5a53ea7429c3e67bbcf2ae/tumblr_inline_p7hqjbrCHs1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       .....
.....       .....       .....
..F..       ..F..       ..F..
.....       .....       .....
.....       .....       .....
```
- Completely **immobile**. Can’t do **mobile strikes** at all.
- Cannot do **immobile strikes** either.
- Imparts the **Mobile Range Expansion Effect**.
- Has the ability **Land-Link**.
- Cannot be added to your **hand**.

#### Hidden Dragon
![Hidden Dragon move set](https://66.media.tumblr.com/2f9aec2815a4ed1fc754b0c0ecc4cb39/tumblr_inline_p7hqjcIDTV1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
..!..       .....       .....
..!..       .X.X.       .X.X.
!!H!!       ..H..       ..H..
..!..       .X.X.       .X.X.
..!..       .....       .....
```
- Moves like a Rook in chess does on **tier** 1.
- Does not experience the **Mobile Range Expansion Effect**.

#### Prodigy
![Prodigy move set](https://66.media.tumblr.com/6f55a450dcdecf872e29fd850b5e0941/tumblr_inline_p7hqjcB9vH1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
!...!       .....       .....
.!.!.       ..X..       ..X..
..P..       .XPX.       .XPX.
.!.!.       ..X..       ..X..
!...!       .....       .....
```
- Moves like a Bishop in chess does on **tier** 1.
- Does not experience the **Mobile Range Expansion Effect**.

#### Bow
![Bow move set](https://66.media.tumblr.com/87483c212ff1624da51a9ea41c864b3f/tumblr_inline_p7hqjc1Vxt1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
..X..       X...X       X...X
.....       ..X..       .....
X.B.X       ..B..       X.B.X
.....       ..X..       .....
.....       .....       ..X..
```
- Able to jump over other pieces.

#### Pawn
![Pawn move set](https://66.media.tumblr.com/6fd00d45c17c8218e154303f8ea46ed0/tumblr_inline_p7hqjdazuI1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       .....
..X..       ..X..       .X.X.
..P..       X.P.X       X.P.X
.....       .....       .....
.....       .....       .....
```
- **Double-Pawn Drop** is **foul play**.
- **Pawn Drop Checkmate** is **foul play**.
- Has the **Forced Recovery Effect**.
- Following the **Initial Arrangement**, there must be a *Pawn* in every **file**.

### Back
#### Pistol 
![Pistol move set](https://66.media.tumblr.com/f9a460af098f21df4778a823fdeaedbd/tumblr_inline_p7hqjeDqrm1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.....       .....       .....
.X.X.       ..X..       ..X..
..P..       .XPX.       .XPX.
.X.X.       ..X..       ..X..
.....       .....       .....
```
- No special abilities

#### Pike 
![Pike move set](https://64.media.tumblr.com/01d759b9aa0ccafb523bcc24baaafda5/tumblr_inline_p7hqjesz191r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
..X..       .....       .....
..X..       .X.X.       .X.X.
.XPX.       ..P..       ..P..
..X..       .X.X.       .X.X.
.....       .....       .....
```
- No special abilities

#### Clandestinite 
![Clandestinite move set](https://64.media.tumblr.com/8948dde3cd15a334b932e8303342b4bf/tumblr_inline_p7hqjeDrcS1r9k30q_500.png)
```
Tier 1:     Tier 2:     Tier 3:
.X.X.       .X.X.       .X.X.
.....       .X.X.       .X.X.
..C..       ..C..       ..C..
..X..       ..X..       ..X..
.....       .....       XX.XX
```

- Able to jump over other pieces.
- Has the ability **Land-Link**.

#### Lance 
#### Dragon King
#### Phoenix
#### Arrow
#### Bronze
#### Silver 
#### Gold