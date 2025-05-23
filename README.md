# Magic Roll
A handmade, alternative keyboard layout that uses multiple repeat and magic keys for a more comfortable and optimal typing experience.
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q 𝕊 @ ,  k m f w v
         ★  ␣ ☆

𝕊 = Symbol Layer
@ = Repeat
★ = Left Magic
☆ = Right Magic
J, H, X, Q, B, G, K, and Z double as magic keys
```
## Table of Contents:
- [Glossary](glossary.md)
- [Stats](#stats)
- [Design](#design)
  - [Thumb Keys](#thumb-keys)
  - [Left Half](#left-half)
  - [Right Half](#right-half)
  - [Tools Used](#tools-used) 
- [Magic Functions](#magic-functions)
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

### <ins>Design:

Using [Hyperroll](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit?tab=t.0#heading=h.an6umzmpc3dj "Hyperroll Keyboard Layout") as a starting point, I experimented with pretty much everything except for `HIEA` + `YOU`. My goal was to have minimal outrolls, redirects, and inner column use, within reason. I went through about two dozen [iterations](layout_design_progression.md "Layout Design Progression") before I had something I was happy with, then added repeat and magic to improve it further.

#### *Thumb Keys:*
Each thumb has a magic key that's used to eliminate most SFBs and make certain patterns more comfortable. The outputs have been kept strictly 1:1 to keep them more like normal keys and less like macros. Not only does this make using them simpler, they won't get you banned from typing websites either.

In general, if the previous key was on the same hand, the output will be the key above or below it. *E.g. `E★` → `EO`. `O★` → `OE`*

If the previous key was on the opposite hand, the output will be something a little less useful like fixing the same (or different) SFB, or an awkward pattern. *E.g. `L★` → `LS`. `Q☆` → `QU`*. `☆ → Space` SFBs can also be avoided this way.

#### *Left Half:*
The `YI` `OE` `UA` vowel block is used, with `H` on the pinky in order to mimimize outrolls and redirects. I chose to not have any common consonants on this side for the same reason. This also helps to keep one-handed strings low.

Magic `X` and `J` complete the pinky column. They turn most consonant-hand outrolls into alternates, and since a vowel almost always comes after, they become inrolls. These letters basically never pair with the other consonants so they're perfect for this job. *E.g. `BX` → `BR` `SJ` → `SW`*

Magic `Q` completes the ring column. It doesn't do much besides fix a few SFBs and uncomfortable patterns.

Punctuation is almost entirely on the inner index column except for `?`. I needed to make room for the repeat key so it got pushed to the outer pinky column, with the rest of the symbols being put on another layer.

Repeat was put on the index since I didn't have a free thumb key for it, wasn't willing to give up magic on either side, and just don't find thumb → finger rolls to be that comfortable. Thankfully, this placement doesn't really cause any problems. Even though it *does* introduce a few new SFBs, they can be fixed with magic or alt-fingering. Additionally, this key has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon. `HT` becomes a roll.
- `Q@` → `QU`. `QQ` is even more uncommon. `U` is two rows above `Q`, making it a little uncomfortable to type normally.
- `Backspace` after repeats and in all other situations. This brings up the index's usage and gets backspace off the pinky.

#### *Right Half:*
The right half was arranged for as many inrolls and comfortable patterns as possible, while accounting for finger strength, and not overloading the pinky. SFBs were mostly ignored since I planned to fix them later with magic.



The `LSF` and `CRW` columns are a little funky, but with nearly all of the consonants on this side, my options were pretty limited. You could swap `L` and `C` for a marginal improvement but then you'd lose the `CL` inroll and make `NCL` (e.g. include) a redirect.

b d l c p 
g t s r n z
k m f w v

wip

#### Downsides:
- `DTMBGK` has 20% usage
- pnv has 10% usage. fairly high
- right hand has to move more
- magic makes the learning curve steeper
- sfs is high

wip

### <ins>Tools Used:
- The [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o "Keyboard Layouts Google Doc") for design knowledge
- The [Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") analyzer for drag and drop letter swaps and their resulting stats
- The [Cyanophage](https://cyanophage.github.io "Cyanophage Analyzer") analyzer for more stats
- [MonkeyType's](https://monkeytype.com "MonkeyType") word filter for specific bigram, trigram, etc. frequencies
- [AutoHotkey](https://www.autohotkey.com "AutoHotkey's Website") to handle repeat and magic functions, since I couldn't be bothered to implement them with [QMK](https://docs.qmk.fm/features/repeat_key "QMK Repeat/Magic Documentation")

---

### <ins>Magic Functions:
```
★:
  ★ → Shift
  ☆★ → ␣
  .★ → ." 
  ,★ → ,"
  ?★ → ?"
  !★ → !"
  "★ → "A
  A★ → AU
  B★ → BT
  E★ → EO
  H★ → H?
  I★ → IQ
  J★ → JH
  K★ → KG
  L★ → LS
  M★ → MP
  N★ → NP
  O★ → OE
  P★ → PV
  Q★ → QI
  R★ → RP
  S★ → SZ
  T★ → TX
  U★ → UA
  V★ → VP
  W★ → WL
  X★ → XI
  Y★ → YI 

☆:
  ★☆ → U
  .☆ → ..
  A☆ → A.
  C☆ → CC
  D☆ → DM
  E☆ → EY
  F☆ → FL
  G☆ → GM
  H☆ → HH
  I☆ → IY
  J☆ → JO
  L☆ → LS
  M☆ → MP
  N☆ → NV
  O☆ → OX
  P☆ → PN
  Q☆ → QU
  R☆ → RC
  S☆ → SL
  T☆ → TR
  U☆ → U,
  W☆ → WL
  X☆ → XH

J:
  KJ → KN
  LJ → LR
  RJ → RV
  SJ → SW
  TJ → TD
  WJ → WN

H:
  FH → FR

X:
  ☆X → ☆L
  @X → @A
  BX → BR
  CX → CR
  DX → DR
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

Q:
  @Q → @U
  BQ → BM
  LQ → LF
  RQ → RZ

Z:
  DZ → DT
  FZ → FS
  GZ → GT
  LZ → LW
  MZ → MT
  RZ → RW
  SZ → SF
B:
  CB → CK

G:
  CG → CH
  SG → SC
```
