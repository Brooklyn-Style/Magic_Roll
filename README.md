# Magic Roll
A handmade, alternative keyboard layout that uses repeat and a dozen magic keys to increase inrolls for a more comfortable typing experience.
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
  - [Thumbs](#thumbs)
  - [Left Half](#left-half)
  - [Right Half](#right-half)
- [Tools Used](#tools-used)
---

<details>
  <summary><h2>Magic Functions:</h2></summary>

```
★:          ☆:           B:          G:          J:          P:          Q:          X:
--------     --------     --------    --------    --------    --------    --------    --------
★ → Shift   --------     CB → CK     CG → CH     MJ → MM     BP → BV     @Q → @U     ☆X → ☆L
☆★ → ␣     ★☆ → U      SB → SW     SG → SC     SJ → SS     DP → DV     BQ → BM     @X → @A
.★ → ."     .☆ → ..      --------    --------    WJ → WN                LQ → LF      BX → BR
,★ → ,"     --------                             --------                WQ → WB      CX → CR
?★ → ?"     --------     F:          H:                                  XQ → XR      DX → DW
!★ → !"     --------     --------    --------    M:                                   FX → FL
@★ → @"     --------     WF → WL     BH → BL     --------                             GX → GR
"★ → "A     --------     VF → VL     DH → DR     FM → FL                              KX → KT
(★ → (A     --------                 FH → FR                                          LX → LV
A★ → AU     A☆ → A.                 KH → KN                                          MX → MB
B★ → BT     --------                 LH → LL                                          PX → PR
--------    C☆ → CC                  MH → MP                                          RX → RP
--------    D☆ → DM                  RH → RR                                          SX → SP
E★ → EO     E☆ → EY                                                                  TX → TW
--------    F☆ → FL                                                                   WX → WR
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
Q★ → QI     Q☆ → QU                                                                   FZ → FS
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
#### <ins>*Thumbs:*
Each thumb has a magic key that's used to eliminate most SFBs and make certain patterns more comfortable. The outputs are 1:1 to make them more like normal keys and less like macros. This makes using them simpler and ensures that you won't get banned from typing websites either.

In general, if the previous key was on the same hand, the output will be the key above or below it. *E.g. `E★` → `EO` `O★` → `OE`*

If the previous key was on the opposite hand, the output will fix an awkward pattern, uncommon SFB, or even the same SFB if it's at the end of a word. *E.g. `Q☆` → `QU` `L★` → `LS`*. `☆ → Space` SFBs can be avoided this way.

#### <ins>*Left Half:*
The pinky `H` + `IEA`/`YOU` setup is used for it's insane 83:1 inroll ratio. `J`, `X`, and `Q` then complete the pinky and ring columns, with punctuation being placed on the inner index for low SFBs. 

`X` almost never comes after a consonant so it turns consonant-hand outrolls into alternates. They then become inrolls when a vowel follows. *E.g. `BX` → `BR` (+ `AEIOU`)*

`H` does the same thing, just to a lesser degree since it *does* pair with most of the other consonants.

`Repeat` was put on the index since I didn't have a free thumb key and wasn't willing to give up magic. This placement doesn't really cause any problems though, as the new SFBs are pretty infequent and can be fixed with magic or alt-fingering. 

Additionally, this key has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll instead.
- `Q@` → `QU`. `QQ` doesn't occur at all and since `U` is two rows above `Q`, it becomes more comfortable to type.
- `Backspace` after repeats or if more than 400ms has passed since the last keypress. This gets backspace off the pinky and brings up the index's usage.

#### <ins>*Right Half:*
Almost all of the consonants have been placed on this side to minimize one-handed strings and outrolls, with the top row being preferred to keep scissors low. Magic is then used to mitigate the remaining uncomfortable 2U row jumps.

`N` is similar to `H` in that it usually comes before a consonant so it goes on the pinky. The rest of the letters aren't nearly as unidirectional but even so, they've been arranged for inrolls.

The `BGK` inner index column puts `NG` on the home row and `BL` on the same row. It also achieves the lowest "word effort" on the Cyanophage analyzer compared to other arrangements. Even though this placement *does* lose some inrolls, it's better than overloading the pinky like some other layouts do.

`D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable. `M` pairs nicely with the other index letters in terms of SFBs once `MB`/`BM` gets fixed with magic.

The `LSF` and `CRW` columns are a little questionable but with all the consonants on this side, there weren't many other options. You could swap `L` and `C` though for marginally better stats, but then you'd lose the `CL` and `RLD` inrolls, and make `NCL` a redirect, which might not be worth it.

The `PNV` column, while good if it was on any other finger, isn't great on the pinky. The SFBs are low but it's usage is relatively high. The SFSs are also quite bothersome so swapping `P` with `K` or `B` could be a potential solution.

## Tools Used:
- The [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o "Keyboard Layouts Google Doc") for design knowledge
- The [Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") analyzer for drag and drop letter swaps and their resulting stats
- The [Cyanophage](https://cyanophage.github.io "Cyanophage Analyzer") analyzer for more stats
- [MonkeyType's](https://monkeytype.com "MonkeyType") word filter for specific bigram and trigram frequencies
- [AutoHotkey](https://www.autohotkey.com "AutoHotkey's Website") to handle repeat and magic functions, since I couldn't be bothered to implement them with [QMK](https://docs.qmk.fm/features/repeat_key "QMK Repeat/Magic Documentation")
