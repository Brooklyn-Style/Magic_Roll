# Magic Roll
A handmade keyboard layout that uses a dozen magic keys and repeat to increase inrolls for a more comfortable typing experience.
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q _ @ ,  k m f w v
         ★  ␣ ☆

_ = Free Key (I have a layer key here)
@ = Repeat
★/☆ = Magic

J, H, X, Y, Q, B, G, M, F, P and Z are magic keys as well. A list of every function will be included at the bottom 
```
## Table of Contents:
- [Glossary](glossary.md)
- [Stats](#stats)
- [Design](#design)
  - [Left Half](#left-half)
  - [Right Half](#right-half)
  - [Thumbs](#thumbs)
- [Magic Functions](#magic-functions)
- [Tools Used](#tools-used)
---
<details>
  <summary><h2>Magic Functions:</h2></summary>
  
```
★:          ☆:
★ → Shift   ★☆ → U
☆★ → ␣     .☆ → ..
.★ → ."     A☆ → A.
,★ → ,"     C☆ → CC
?★ → ?"     D☆ → DM
!★ → !"     E☆ → EY
@★ → @"     F☆ → FL
"★ → "A     G☆ → GM
(★ → (A     H☆ → HH
A★ → AU     I☆ → IY
B★ → BT     J☆ → JO
E★ → EO     L☆ → LS
H★ → H?     M☆ → MP
I★ → IQ     N☆ → NV
K★ → KG     O☆ → OX
L★ → LS     P☆ → PN
M★ → MP     Q☆ → QU
N★ → NP     R☆ → RC
O★ → OE     S☆ → SL
P★ → PV     T☆ → TR
Q★ → QI     U☆ → U,
R★ → RC     V☆ → VV
U★ → UA     X☆ → XH
V★ → VP	
Y★ → YI	
X★ → XI		

B:
 CB → CK
 SB → SW

F:
 WF → WL

G:
 CG → CH
 SG → SC

H:
 BH → BL
 DH → DR
 FH → FR
 KH → KN
 LH → LL
 MH → MP
 
J:
 SJ → SS
 WJ → WN

M:
 FM → FL 

P:
 BP → BV
 DP → DV

Q:
 @Q → @U
 BQ → BM
  BQ★ → BMI
 LQ → LF
 WQ → WB
 XQ → XR

X:
 ☆X → ☆L
 @X → @A
 BX → BR
 CX → CR
 DX → DW
 FX → FL
 GX → GR
 KX → KT
 LX → LV
 MX → MB
 PX → PR
 RX → RP
 SX → SP
 TX → TW
 WX → WR

Y:
 JY → JI 

Z:
 DZ → DT
 FZ → FS
 GZ → GT
 LZ → LW
 MZ → MT
 RZ → RW
 SZ → SF
 TZ → TD
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
**Typing Test:**
![typing test](images/typing%20test.jpg)

## Design:

#### <ins>*Left Half:*
The pinky `H` + `IEA`/`YOU` setup is used since it's the best at minimizing outrolls. No common consonants have been placed on this side either for the same reason, and to keep one-handed strings low.

`X` almost never comes after a consonant so with magic it can be used to turn consonant-hand outrolls into alternates. They then become inrolls when a vowel follows. *E.g. `BX` → `BR` (+ `AEIOU`)*

`H` does the same thing, just with less letters, as it pairs with most of the other consonants.

`Repeat` was put on the index since I didn't have a free thumb key for it and wasn't willing to give up magic on either side. This placement doesn't really cause any problems though, as the new SFBs can be fixed with magic or alt-fingering. 

This key has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll instead.
- `Q@` → `QU`. `QQ` is even more uncommon and since `U` is two rows above `Q`, it becomes more comfortable to type this way. (I prefer to just use the right magic thumb key for this though).
- `Backspace` after repeats or if more than 400ms has passed since the last keypress. This gets backspace off the pinky and brings up the index's usage.

#### <ins>*Right Half:*
The right half was arranged around the `TSRN` home keys, as these are the most [frequently](https://norvig.com/mayzner.html#:~:text=electrocardiographic%0Ainstitutionalization%09%09%20uncharacteristically-,Letter%20Counts,-Enough%20of%20words "Norvig Letter Frequency Chart") used consonants:

- `T` is the most used so it goes on the index.
- `S` and `R` go on the middle and ring to make `ST` and `RS` inrolls.
- `N` pairs with every letter so putting it on the pinky makes every letter that follows an inroll.

The `BGK` inner index column was set up like this put `NG` on the home row and `BL` on the same row. `D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable. `M` pairs nicely with the rest of the index letters, except `B`, but that gets fixed with magic. It's also the most common letter on the bottom row so it's been placed on the index.

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
