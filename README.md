# Magic Roll
A handmade, alternative keyboard layout that uses a repeat key and multiple magic keys for a more comfortable and optimal typing experience.
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q _ @ ,  k m f w v
         ★  ␣ ☆

_ = Free Key (I have a layer key here)
@ = Repeat
★ = Left Magic
☆ = Right Magic
J, H, X, Y, Q, B, G, M, F, P and Z have magic functions
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
Using [Hyperroll](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit?tab=t.0#heading=h.an6umzmpc3dj "Hyperroll Keyboard Layout") as a starting point, I experimented with everything except for `H` and the vowels. I was still new to alt layouts at the time so I didn't know exactly what I wanted besides inrolls, comfort, and a layout that would make me stop searching for something better. I figured out early on that I disliked the `PNB` pinky, consonant-hand outrolls, and the `LD` LSB. I also wasn't a fan of `G` or `J`'s placements either, as `NG` is fairly common, and `GL` and `JO` are uncomfortable two row jumps. I ended up going through about two dozen [iterations](layout_design_progression.md "Layout Design Progression") before I had something I was happy with, then added repeat and magic to improve the layout further.

#### *Thumb Keys:*
Each thumb has a magic key that's used to eliminate most SFBs and make certain patterns more comfortable. The outputs have been kept 1:1 to make them more like normal keys and less like macros. This makes using them simpler and ensures you won't get banned from typing websites either.

In general, if the previous key was on the same hand, the output will be the key above or below it. *E.g. `E★` → `EO` `O★` → `OE`*

If the previous key was on the opposite hand, the output will be something a little less useful like fixing the same (or different) SFB, or an awkward pattern. *E.g. `L★` → `LS` `Q☆` → `QU`*. `☆ → Space` SFBs can be avoided this way.

#### *Left Half:*
The pinky `H` + `IEA`/`YOU`setup is the best for inrolls, as `H` rarely comes after a vowel. No common consonants have been placed on this side either to keep outrolls and one-handed strings low. Additionally, `J`, `H`, `X`, and `Q` increase inrolls and take care of a couple SFBs.

<details>
  <summary>Consonant → Vowel Roll Direction Chart:</summary>
  
![Roll Direction Chart](images/Roll%20Direction%20Chart.jpg "Roll Direction Chart")

Source: [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o/edit?tab=t.2yb5bwiy1wa8#heading=h.b3afrbm4ggth "Keyboard Layouts Google Doc")
</details>

`X` and `J` almost never pair with the other consonants so consonant-hand outrolls can be turned into alternates. They then become inrolls when a vowel follows. *E.g. `BX` → `BR` (+ `AEIOU`). `SJ` → `SW` (+ `AEIOU`)*

`H` is used the same way, but to get inrolls on the home row instead. Only a handful of letters are used though, as `H` pairs with more of the consonants. *E.g. `DH` → `DR`. `FH` → `FR`*

`Q` fixes a few SFBs and uncomfortable patterns. *E.g. `BQ` → `BM`. `WQ` → `WB`*

Punctuation is almost entirely on the inner index column except for `?`. I needed to make room for the repeat key so it got pushed to the outer pinky column, with the rest of the symbols being put on another layer.

`Repeat` was put on the index since I didn't have a free thumb key for it and wasn't willing to give up magic on either side. This placement doesn't really cause any problems though, as the new SFBs can be fixed with magic or alt-fingering. 

This key has a few exceptions:
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll instead.
- `Q@` → `QU`. `QQ` is even more uncommon and since `U` is two rows above `Q`, it becomes more comfortable to type this way. (I prefer to just use the right magic thumb key for this though).
- `Backspace` after repeats or if more than 400ms has passed since the last keypress. This gets backspace off the pinky and brings up the index's usage.

#### *Right Half:*
The right half was arranged around the `TSRN` home keys, as these are the most [frequently](https://norvig.com/mayzner.html#:~:text=electrocardiographic%0Ainstitutionalization%09%09%20uncharacteristically-,Letter%20Counts,-Enough%20of%20words "Norvig Letter Frequency Chart") used consonants:

- `T` is the most used so it goes on the index.
- `S` and `R` go on the middle and ring to make `ST` and `RS` inrolls.
- `N` pairs with every letter so putting it on the pinky makes every letter that follows an inroll as well.

<details>
  <summary>Consonant → Consonant Roll Direction Chart:</summary>
  
![Roll Direction Chart2](images/Roll%20Direction%20Chart2.jpg "Roll Direction Chart")

Source: [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o/edit?tab=t.2yb5bwiy1wa8#heading=h.wg1f0t5cod2o "Keyboard Layouts Google Doc")
</details>

The `BGK` inner index column was set up like this put `NG` on the home row and `BL` on the same row. `D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable. `M` on the bottom row makes `SM` a nice roll and pairs nicely with the rest of the index letters, except `B`, which gets fixed with magic. It's also the most common letter on the bottom row so it should be on the index.

The `LSF` and `CRW` columns are a little questionable but with nearly all of the consonants on this side, there weren't many other options. Thankfully, magic makes them viable. You could swap `L` and `C` for marginally better stats but then you'd lose the `CL` and `RLD` inrolls, and make `NCL` a redirect which wouldn't be worth it.

The `PNV` column, while good if it was on any other finger, isn't great on the pinky. The SFBs are low but it's usage is relatively high. The SFSs are quite bothersome as well but swapping `P` with `K` or `B` could be a potential solution.

Aside from all of the movement that this hand has to do, the pinky and SFSs in general are this layout's biggest downsides

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
 @★ → @" - @ = repeat
 "★ → "A
 (★ → (A 
 A★ → AU
 B★ → BT
 E★ → EO
 H★ → H?
 I★ → IQ
  I★☆ → IQU
 K★ → KG
 L★ → LS
 M★ → MP
 N★ → NP
 O★ → OE
 P★ → PV
 Q★ → QI
 R★ → RC
 U★ → UA
 V★ → VP
 Y★ → YI 
 X★ → XI

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
 L☆ → LV
 M☆ → MP
 N☆ → NV
 O☆ → OX
 P☆ → PN
 Q☆ → QU
 R☆ → RC
 S☆ → SL
 T☆ → TR
 U☆ → U,
 V☆ → VV
 X☆ → XH

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
 CJ → CC
 FJ → FF
 GJ → GG
 LJ → LL
 MJ → MM
 PJ → PP
 RJ → RR
 SJ → SS
 TJ → TT
 WJ → WN
 ZJ → ZZ

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
 LX → LS
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
```
