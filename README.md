# Magic Roll
A handmade keyboard layout that uses repeat and a dozen magic keys to increase inrolls for a more comfortable typing experience.
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q _ @ ,  k m f w v
         ★  ␣ ☆

_ = Free Key (I have a layer key here)
@ = Repeat
★/☆ = Magic

J, H, X, Y, Q, B, G, M, F, P and Z are magic keys as well.
```
## Table of Contents:
- [Glossary](glossary.md)
- [Magic Functions](#magic-functions)
- [Stats](#stats)
- [Design](#design)
  - [Left Half](#left-half)
  - [Right Half](#right-half)
  - [Thumbs](#thumbs)
- [Tools Used](#tools-used)
---

<details>
  <summary><h2>Magic Functions:</h2></summary>

```
★:          ☆:           B:          G:          J:          P:          Q:          X:
--------     --------     --------    --------    --------    --------    --------    --------
★ → Shift   --------     CB → CK     CG → CH     SJ → SS     BP → BV     @Q → @U     ☆X → ☆L
☆★ → ␣     ★☆ → U      SB → SW     SG → SC     WJ → WN     DP → DV     BQ → BM     @X → @A
.★ → ."     .☆ → ..      --------    --------    --------                LQ → LF     BX → BR
,★ → ,"     --------                                                     WQ → WB      CX → CR
?★ → ?"     --------     F:          H:          M:                      XQ → XR      DX → DW
!★ → !"     --------     --------    --------    --------                             FX → FL
@★ → @"     --------     WF → WL     BH → BL     FM → FL                              GX → GR
"★ → "A     --------                 DH → DR                                          KX → KT
(★ → (A     --------                 FH → FR                                          LX → LV
A★ → AU     A☆ → A.                  KH → KN                                          MX → MB
B★ → BT     --------                 LH → LL                                          PX → PR
--------    C☆ → CC                  MH → MP                                          RX → RP
--------    D☆ → DM                                                                   SX → SP
E★ → EO     E☆ → EY                                                                   TX → TW
--------    F☆ → FL                                                                    WX → WR
--------    G☆ → GM                                                                   --------
H★ → H?     H☆ → HH
I★ → IQ     I☆ → IY                                                                   Y:
--------    J☆ → JO                                                                   --------
K★ → KG     --------                                                                  JY → JI
L★ → LS     L☆ → LS                                                                   --------
M★ → MP     M☆ → MP
N★ → NP     N☆ → NV                                                                   Z:
O★ → OE     O☆ → OX                                                                   --------
P★ → PV     P☆ → PN                                                                   DZ → DT
Q★ → QI     Q☆ → IQU                                                                  FZ → FS
R★ → RC     R☆ → RC                                                                   GZ → GT
--------    S☆ → SL                                                                    LZ → LW
--------    T☆ → TR                                                                    MZ → MT
U★ → UA     U☆ → U,                                                                   RZ → RW
V★ → VP     V☆ → VV                                                                   SZ → SF
X★ → XI     X☆ → XH                                                                   TZ → TD
Y★ → YI     --------                                                                   --------
```
</details>

---
<details>
  <summary><h2>Stats:</h2></summary>
Without repeat or magic unless specified.

**[Layout Playground](https://oxey.dev/playground/index.html "Layout Playground"):**
![without repeat](images/without%20repeat.jpg)
**[Layout Playground](https://oxey.dev/playground/index.html "Layout Playground")** (With Repeat):
![repeat](images/repeat.jpg)
**[Cyanophage](https://cyanophage.github.io/playground.html?layout=jyou%27bdlcp-hiea.gtsrnzxq%5C%3D%2Ckmfwv%2F%3B&mode=ergo&lan=english "View on Cyanophage"):**
![cyanophage](images/cyanophage.jpg)
**[KeySolve](https://drowningnewt.github.io/keysolve-web "Keysolve"):**
![keysolve](images/keysolve.jpg)

</details>

---
### Typing Test:
![typing test](images/typing%20test.jpg)

## Design:
Inspired by layouts like [Hieamtsrn](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit?tab=t.0#heading=h.ojttb28dodph "Hieamtsrn") and [Hands Down Neu](https://sites.google.com/alanreiser.com/handsdown/home/hands-down-neu "Hands Down Neu"), Magic Roll puts all of the common consonants on one side to minimize outrolls, then uses magic to increase inrolls and avoid SFBs.

#### <ins>*Left Half:*
As is standard for these kinds of layouts, the pinky `H` + vowels setup is used since it has an 83:1 inroll ratio. Rare letters then fill the rest of this side, with punctuation being placed on the inner column for low SFBs. 

`X` almost never comes after a consonant so consonant-hand outrolls can be turned into alternates. They then become inrolls when a vowel follows. *E.g. `BX` → `BR` (+ `AEIOU`)*

`H` does the same thing, just to a lesser degree, as it *does* pair with a majority of the consonants.

`Repeat` was put on the index, as opposed to the thumb sicne I didn't have a free key for it and wasn't willing to give up magic. This placement doesn't really cause any problems though, as the new SFBs are pretty infequent and can be fixed with magic or alt-fingering. 

This key also has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll instead.
- `Q@` → `QU`. `QQ` is even more uncommon and since `U` is two rows above `Q`, it becomes more comfortable to type. (I prefer to just use the right magic thumb key for this though).
- `Backspace` after repeats or if more than 400ms has passed since the last keypress. This gets backspace off the pinky and brings up the index's usage.

#### <ins>*Right Half:*
The right half was arranged around the `TSRN` home keys, as these are the most [frequently](https://norvig.com/mayzner.html#:~:text=electrocardiographic%0Ainstitutionalization%09%09%20uncharacteristically-,Letter%20Counts,-Enough%20of%20words "Norvig Letter Frequency Chart") used consonants. 

- `T` is the most used so it goes on the index.
- `S` and `R` go on the middle and ring to make `ST` and `RS` inrolls.
- `N` pairs with every letter so putting it on the pinky makes every letter that follows an inroll.

The `BGK` inner index column was set up like this put `NG` on the home row and `BL` on the same row. It also achieves the lowest "word effort" stat on the Cyanophage analyzer compared to the other possible arrangements. 

Having `D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable. `M` pairs nicely with the rest of the index letters in terms of SFBs, except for `B`, but that gets fixed with magic.

The `LSF` and `CRW` columns are a little questionable but with nearly all of the consonants on this side, there weren't many other options. Thankfully, magic saves the day again. You could swap `L` and `C` though for marginally better stats, but then you'd lose the `CL` and `RLD` inrolls, and make `NCL` a redirect, which might not be worth it.

The `PNV` column, while good if it was on any other finger, isn't great on the pinky. The SFBs are low but it's usage is relatively high. The SFSs are also quite bothersome so swapping `P` with `K` or `B` could be a potential solution.

#### <ins>*Thumbs:*
Each thumb has a magic key that's used to eliminate most SFBs and make certain patterns more comfortable. The outputs are 1:1 to make them more like normal keys and less like macros. This makes using them simpler and ensures you won't get banned from typing websites either.

In general, if the previous key was on the same hand, the output will be the key above or below it. *E.g. `E★` → `EO` `O★` → `OE`*

If the previous key was on the opposite hand, the output will be something a little less useful like fixing the same (or different) SFB, or an awkward pattern. *E.g. `L★` → `LS` `Q☆` → `QU`*. `☆ → Space` SFBs can be avoided this way.

## Tools Used:
- The [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o "Keyboard Layouts Google Doc") for design knowledge
- The [Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") analyzer for drag and drop letter swaps and their resulting stats
- The [Cyanophage](https://cyanophage.github.io "Cyanophage Analyzer") analyzer for more stats
- [MonkeyType's](https://monkeytype.com "MonkeyType") word filter for specific bigram and trigram frequencies
- [AutoHotkey](https://www.autohotkey.com "AutoHotkey's Website") to handle repeat and magic functions, since I couldn't be bothered to implement them with [QMK](https://docs.qmk.fm/features/repeat_key "QMK Repeat/Magic Documentation")
