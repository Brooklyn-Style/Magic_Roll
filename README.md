# Magic Roll
Magic Roll is a handmade keyboard layout that minimizes outrolls and eliminates almost all SFBs through it's clever use of repeat and magic keys.

If you're not already familiar with alt layout terminology, check out the [glossary](glossary.md).
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q _ @ ,  k m f w v
         ★  ␣ ☆

_ = Free Key (I have a layer key here)
@ = Repeat
★/☆ = Magic

J, H, X, Y, Q, B, G, M, F, C, P and Z are magic keys as well.
```
You can try the layout [here](https://keyboard-layout-try-out.pages.dev/?l0r0=q+w+e+r+t++y+u+i+o+p&l0r1=a+s+d+f+g++h+j+k+l+%3B+%27&l0r2=z+x+c+v+b++n+m+%2C+.+%2F&l1r0=j+y+o+u+%27++k+d+l+c+p&l1r1=h+i+e+a+.++g+t+s+r+n+z&l1r2=x+q+++++%2C++b+m+f+w+v&z=z). Just scroll down and click "convert words", then "type words".
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
★:          ☆:           B:           G:           J:           P:           Q:           X:
--------     --------     --------     --------     --------     --------     --------     --------
★ → Shift   --------     CB → CK      CG → CH       MJ → MM     BP → BV       @Q → @U     @X → @A
☆★ → ␣     ★☆ → U      SB → SW      PG → PH       RJ → RV     DP → DV       BQ → BM     BX → BL
.★ → ."     .☆ → ..      --------     SG → SC      SJ → SS                   LQ → LF     CX → CR
,★ → ,"     --------                  TG → TC       TJ → TG                   WQ → WB     DX → DW
?★ → ?"     --------     C:           --------      WJ → WN                   XQ → XR     FX → FF
!★ → !"     --------     --------                                                         GX → GL
@★ → @"     --------     SC → SF      M:            K:                                    KX → KT
"★ → "A     --------     --------     --------      --------                              LX → LV
(★ → (A     --------                  FM → FL       MK → MB                               MX → MB
A★ → AU     A☆ → A.      F:          --------                                             PX → PR 
B★ → BT     --------     -------                                                          RX → RP
--------    C☆ → CC      VF → VL      H:                                                  SX → SP 
D★ → DS     D☆ → DM      WF → WL     --------                                             TX → TW
E★ → EO     E☆ → EY                  BH → BR                                              WX → WR 
--------    F☆ → FL           	      DH → DR                                              --------
G★ → GS     G☆ → GM                  FH → FR													
H★ → H?     H☆ → HH                  GH → GR                                              Y:
I★ → IQ     I☆ → IY          	      KH → KN                                              --------
--------    J☆ → JO                   LH → LL                                             JY → JI
K★ → KG     --------                  MH → MP                                             --------
L★ → LS     L☆ → LS                  RH → RR                                                     
M★ → MP     M☆ → MP                                                                       Z:
N★ → NP     N☆ → NV                                                                       --------
O★ → OE     O☆ → OX                                                                       DZ → DT
P★ → PV     P☆ → PN                                                                       GZ → GT
Q★ → QI     Q☆ → QU                                                                       LZ → LW
R★ → RC     R☆ → RC                                                                       MZ → MT
--------    S☆ → SL                                                                        RZ → RW
--------    T☆ → TR                                                                        TZ → TM
U★ → UA     U☆ → U,                                                                   
V★ → VP     V☆ → VV                                                                   
X★ → XI     X☆ → XH                                                                   
Y★ → YI                                                                        
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
**[KeySolve](https://luminespire.github.io/keysolve-web/ "Keysolve"):**
![keysolve](images/keysolve.jpg)

</details>

---

## Design:
#### <ins>*Thumbs:*
Each thumb has a magic key that's used to turn SFBs into inrolls and make certain patterns more comfortable. The outputs are 1:1 to keep it simple and ensure that you won't get banned from typing websites.

In general, if the previous key was on the same hand, the output will be the key above or below it. *E.g. `E★` → `EO` `O★` → `OE`*

If the previous key was on the opposite hand, the output will fix an awkward pattern, uncommon SFB, or even the same SFB if it's at the end of a word. *E.g. `Q☆` → `QU` `L★` → `LS`*. `☆ → Space` SFBs can be avoided this way.

#### <ins>*Left Half:*
The pinky `H` + `IEA`/`YOU` setup is used for it's insane 83:1 inroll ratio. `J`, `X`, and `Q` then complete the pinky and ring columns, with punctuation being placed on the inner index for low SFBs. 

`X` almost never comes after a consonant so it turns consonant-hand outrolls into alternates. They then become inrolls when a vowel follows. *E.g. `BX` → `BR` (+ `AEIOU`)*

`H` does the same thing, just to a lesser extent since it *does* pair with most of the other consonants.

`Repeat` was put on the index since I didn't have a free thumb key and wasn't willing to give up magic for it. This placement doesn't really cause any problems though, as the new SFBs are pretty infequent and can be fixed with magic or alt-fingering. 

Additionally, this key has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll.
- `Q@` → `QU`. `QQ` doesn't appear in any word and since `U` is two rows above `Q`, it becomes more comfortable to type like this.
- `Backspace` after repeats or if more than 400ms has passed since the last keypress. This gets backspace off the pinky and brings up the index's usage a bit.

#### <ins>*Right Half:*
Nearly all of the consonants have been placed on this side to minimize outrolls, redirects, and one-handed strings, with the top row being favored to keep scissors low. Magic is then used to mitigate the uncomfortable row jumps like `WL` and `DW`.

`N` is similar to `H` in that it usually comes before a consonant so it's been placed on the pinky. The rest of the letters aren't nearly as unidirectional but even so, they've been arranged for inrolls.

The `BGK` inner index column puts `NG` on the home row and `BL` on the same row. It also achieves the lowest "word effort" on the Cyanophage analyzer compared to other arrangements. Even though this placement *does* lose some inrolls, it's better than putting it on the pinky with `P` and `N`.

`D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable. `M` pairs nicely with the other index letters in terms of SFBs once `MB`/`BM` gets fixed with magic.

The `LSF` and `CRW` columns are a little questionable but there weren't many other options. You could swap `L` and `C` for marginally better stats, but then you'd lose the `CL` and `RLD` inrolls, and make `NCL` a redirect, which might not be worth it.

The `PNV` column, while good if it was on any other finger, isn't great on the pinky. The SFBs are low but it's usage is relatively high. The SFSs are also quite bothersome so swapping `P` with `K` or `B` could be a potential solution.

## Tools Used:
- The [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o "Keyboard Layouts Google Doc") for design knowledge
- The [Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") analyzer for drag and drop letter swaps and their resulting stats
- [Cyanophage's](https://cyanophage.github.io "Cyanophage Analyzer") analyzer for more stats
- [MonkeyType's](https://monkeytype.com "MonkeyType") word filter for specific bigram and trigram frequencies
- [Merriam-Webster's](https://www.merriam-webster.com/wordfinder "Merriam-Webster Word Finder") word finder to do the same thing but with a few more filters.
- [AutoHotkey](https://www.autohotkey.com "AutoHotkey's Website") to handle repeat and magic functions, since I couldn't be bothered to implement them with [QMK](https://docs.qmk.fm/features/repeat_key "QMK Repeat/Magic Documentation")
---
### Typing Test:
![typing test](images/typing%20test.jpg)
