# Magic Roll
<img src="https://github.com/Brooklyn-Style/Magic_Roll/blob/main/images/magic%20roll.jpg" width="70%">

Magic Roll is a handmade keyboard layout that minimizes outrolls and eliminates SFBs through it's clever use of repeat and magic keys.

If you're not already familiar with alt layout terminology, check out the [glossary](glossary.md).
```
  j y o u '  b d l c p 
? h i e a .  g t s r n z
  x q _ @ ,  k m f w v
         \   ␣ /

_ = Free Key (I have a layer key here)
@ = Repeat
\ = Left Magic
/ = Right Magic

Half of the alphas are magic keys as well.
```
You can try the base layout [here](https://keyboard-layout-try-out.pages.dev/?l0r0=q+w+e+r+t++y+u+i+o+p&l0r1=a+s+d+f+g++h+j+k+l+%3B+%27&l0r2=z+x+c+v+b++n+m+%2C+.+%2F&l1r0=j+y+o+u+%27++k+d+l+c+p&l1r1=h+i+e+a+.++g+t+s+r+n+z&l1r2=x+q+++++%2C++b+m+f+w+v&z=z). Just scroll down and click "convert words", then "type words".
## Table of Contents
- [Glossary](glossary.md)
- [Stats](#stats)
- [Design](#design)
  - [Left Half](#left-half)
  - [Right Half](#right-half)
  - [Magic](#magic)
    - [Thumbs](#thumbs)
    - [Alphas](#alphas)
- [Magic Charts](#magic-charts)
- [Tools Used](#tools-used)
---
<details>
  <summary><h2>Stats</h2></summary>
Without repeat or magic unless specified.

[Layout Playground](https://oxey.dev/playground/index.html "Layout Playground"):
![without repeat](images/without%20repeat.jpg)
[Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") (With Repeat):
![repeat](images/repeat.jpg)
Manual analysis of magic's affect on outrolls: https://docs.google.com/spreadsheets/d/15rUa7rHMag776j3FILCoby1qDpYqKLfsa13CaCaucxs
<img src="https://github.com/Brooklyn-Style/Magic_Roll/blob/main/images/magic%20inrolls.jpg" width="40%">

[Cyanophage](https://cyanophage.github.io/playground.html?layout=jyou%27bdlcp-hiea.gtsrnzxq%5C%3D%2Ckmfwv%2F%3B&mode=ergo&lan=english "View on Cyanophage"):
![cyanophage](images/cyanophage.jpg)
[KeySolve](https://luminespire.github.io/keysolve-web/ "Keysolve"):
![keysolve](images/keysolve.jpg)

</details>

---

## Design
### *<ins>Left Half*
The pinky `H` + `IEA`/`YOU` setup is used for it's insane 83:1 inroll ratio. `J`, `X`, and `Q` then complete the pinky and ring columns, with punctuation being placed on the inner index for low SFBs. 

`Repeat` was put on the index since I didn't have a free thumb key and wasn't willing to give up magic for it. This placement doesn't really cause any problems though, as the new SFBs are pretty infequent and can be fixed with magic or alt-fingering. 

This key also has some exceptions:
- `_E@` → `EX`. `EX` is more common than `EE` at the beginning of words. `E@` will function as expected otherwise.
- `H@` → `HT`. `HH` is extremely uncommon so this makes `HT` a roll.
- `I@` → `I'`. `II` basically never starts a word so this eliminates the stretch to the inner column.
- `Q@` → `QU`. `QQ` doesn't appear in any word and since `U` is two rows above `Q`, it becomes more comfortable to type this way.
- `Backspace` after being used or if more than 400ms have passed since the last keypress. This gets backspace off the pinky and brings up the index's usage a little bit.

### *<ins>Right Half*
Nearly all of the consonants have been placed on this side to minimize outrolls, redirects, and one-handed strings, with the top row being favored to keep scissors low. This unfortunately results in more movement but I haven't had a problem with it.

`N` is similar to `H` in that it usually comes before a consonant so it's been placed on the pinky. The rest of the letters aren't nearly as unidirectional but even so, they've been arranged for inrolls as well.

The `BGK` inner index column puts `NG` on the home row and `BL` on the same row. It also achieves the lowest "word effort" on Cyanophage's analyzer compared to other arrangements. `B`'s placement *does* lose some inrolls, but it's better than putting it on the pinky with `P` and `N`.

`D` on the top row makes it + `B`, `G`, and `K` easily alt-fingerable.

`M` pairs nicely with the other index letters once `MB`/`BM` gets fixed with magic.

The `LSF` and `CRW` columns are a little questionable but there weren't many other options. You could swap `L` and `C` for marginally better stats, but then you'd lose the `CL` and `RLD` inrolls, and make `NCL` a redirect, which might not be worth it.

The `PNV` column, while good if it was on any other finger, isn't great on the pinky. The SFBs are low but it's usage is relatively high. The SFSs are also quite bothersome so swapping `P` with `K` or `B` could be a potential solution.

## Magic
The output of each magic key is limited to just one character to retain the feel of normal typing and ensure that you won't get banned from typing websites. They're context dependent though so they won't always output the same character even if the last key pressed was the same. *E.g. `A\` → `AU`* while *`WA\` → `WAY`*. 

They can also be chained together to further increase typing comfort. *E.g. `FH` → `FR`* and then *`U\` → `UI`* for the word "fruit".

### *<ins>Thumbs*
In general, if the previous key was on the same hand, the output will be the key above or below it to avoid SFBs. *E.g. `E\` → `EO`. `O\` → `OE`*.

If the previous key was on the opposite hand, the output will fix an awkward pattern, uncommon SFB, or even the same SFB as the other thumb if it's at the end of a word. *E.g. `Q/` → `QU`. `K\` → `KG`. `L\` → `LS`*. `Magic` → `Space` SFBs can be avoided this way. 

### *<ins>Alphas*
Inspired [Hands Down](https://sites.google.com/alanreiser.com/handsdown/home/hands-down-neu "Hands Down Neu")'s adaptive keys, half of the alphas have magic functions to eliminate scissors, increase same-row rolls, and reduce outrolls. They've been set up to be as intuitive as possible and cause the fewest amount of conflicts, with a short timeout so that the original bigram can still be typed.

*E.g. `WF` → `WL`*. `W` and `L` are two rows apart so by using `F` in place of `L`, it can be typed on the same row with the same fingers. 

*`BX` → `BL`*. `X` almost never comes after a consonant so it can turn consonant-hand outrolls into alternates. They then become inrolls when a vowel follows.

Check out the charts below to see every magic function.

---
<details>
  <summary><h2>Magic Charts</h2></summary>

```
\:          /:           B:           G:           J:           P:           Q:           X:
--------    --------     --------     --------     --------     --------     --------     --------
\ → Shift   --------     CB → CK      CG → CH      MJ → MM      BP → BV      @Q → @U      @X → @A
/\ → ␣      \/ → U      SB → SW      PG → PH      RJ → RV       DP → DV      BQ → BM      BX → BL
.\ → ."     ./ → ..      --------     SG → SC      SJ → SS                   LQ → LF      CX → CR
,\ → ,"     --------                  TG → TC      TJ → TG                   WQ → WB      DX → DW
?\ → ?"     --------     C:           --------     WJ → WN                   XQ → XR      FX → FL
!\ → !"     --------     --------                  --------                               GX → GL
@\ → @"     --------     SC → SF      M:                                                  KX → KT
"\ → "A     --------     --------     --------     K:                                     LX → LV
(\ → (A     --------                  FM → FL      --------                               MX → MB
A\ → AU     A/ → A.      D:           --------     MK → MB                                PX → PH
B\ → BT     --------     --------                                                         RX → RP
--------    C/ → CC      CD → CK      H:                                                  SX → SP
D\ → DS     D/ → DM      --------     --------                                            TX → TW
E\ → EO     E/ → EY                   BH → BR                                             WX → WR
--------    F/ → FF      F:     	  DH → DR                                             --------
G\ → GS     G/ → GM      -------      FH → FR                                              
H\ → H?     H/ → HH      VF → VL      GH → GR                                             Y:
I\ → IQ     I/ → IY      WF → WL      KH → KN                                             --------
--------    J/ → JO                   LH → LS                                             JY → JI 
K\ → KG     --------                  MH → MP                                             --------
L\ → LS     L/ → LS                   PH → PR                                                    
M\ → MP     M/ → MP                   RH → RR                                             Z:
N\ → NP     N/ → NV                                                                       --------
O\ → OE     O/ → OX                                                                       DZ → DT
P\ → PV     P/ → PN                                                                       GZ → GT
Q\ → QI     Q/ → QU                                                                       LZ → LW
R\ → RC     R/ → RC                                                                       MZ → MT
--------    S/ → SL                                                                       RZ → RW
--------    T/ → TR                                                                       TZ → TM
U\ → UA     U/ → U,                                                                              
V\ → VP     V/ → VV                                                                              
--------    W/ → WC
X\ → XI     X/ → XH
Y\ → YI     --------                                                                   
```
Magic Sequences:

"-" denotes a prefix or suffix. "_" denotes a space or no prior key. If other magic functions are used for the input sequence, they're written as their non-magic equivalent (E.g. `CB` instead of `CK`). For the sake of simplicity, only the input and the magic key's output are written. A use case is also provided.
```
H:                         @:                      \:                      /:
----------------------     -------------------     -------------------     ----------------------
-ab → l   | able           _e → x   | explain      -cb → s  | blocks       -/es → s  | accessory
-cal → l  | basically      _i → '   | I'd          -nt → s  | tent         -eces → s | necessary
-ial → l  | especially     -ide → r | consider     aga → i  | again        -ld → n   | shouldn't
-ib → l   | impossible     -ve → n  | even         avo → i  | avoid        -ial → l  | especially
-mal → l  | normally       inte → r | interest     ba → y   | bay          -mal → l  | normally
-mk → l   | humble         mone → y | money        bo → x   | box          -nal → l  | finally
-nal → l  | origanally     neke → r | never        e@ → a   | example      an → n    | anniversary
ac/es → s | accessory      obe → y  | obey         fhu → i  | fruit        ap → p    | apple
af → t    | after          the → y  | they         fi@ → e  | fixed        do\s → n  | doesn't
al → s    | also           weve → r | however      ja → y   | jay          fun → n   | funny
ans → w   | answer         fi → x   | fix          ka → y   | kay          hal → l   | hall
ap/ → l   | apple          mi → x   | mix          ma → y   | may          hit → t   | hitting
bet → w   | between        si → x   | six          mi@ → e  | mixed        jam → m   | jamming
cir/ → l  | circle         -------------------     ra → y   | ray          let → t   | letter
colum → n | column                                 sq@ → a  | square       lit → t   | litter
com → m   | comment        F:                      the@ → ' | they'd       other → w | otherwise
cur → v   | curve          -------------------     wa → y   | way          pos → s   | possible
doub → l  | double         fe@ → l  | feel         ya → y   | yay          put → t   | putting
fun → n   | funny          fo → l   | follow       yda → y  | everyday
gent → l  | gentle         -------------------     yea → h  | yeah
gham → m  | grammar                                you → '  | you're
gon → n   | gonna          M:
gxos → s  | glossary       -------------------
iang → l  | triangle       cxow → d | crowd 
lit/ → l  | little         -------------------   
m/ → l    | simple        
mem → b   | member         X:   
num → b   | number         -------------------   
phob → l  | problem        -m/ → r  | improve  
pos → s   | possible       -sg → r  | screen  
pub → l   | public        
real → l  | really        
sgis → s  | scissor    
sym → b   | symbol
wan → n   | wanna
```
</details>

## Tools Used
- The [Keyboard Layouts Google Doc](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o "Keyboard Layouts Google Doc") for design knowledge
- The [Layout Playground](https://oxey.dev/playground/index.html "Layout Playground") analyzer for drag and drop letter swaps and their resulting stats
- [Cyanophage's](https://cyanophage.github.io "Cyanophage Analyzer") analyzer for more stats
- [MonkeyType's](https://monkeytype.com "MonkeyType") word filter for specific bigram and trigram frequencies
- [Merriam-Webster's](https://www.merriam-webster.com/wordfinder "Merriam-Webster Word Finder") word finder to do the same thing but with a few more filters
- [AutoHotkey](https://www.autohotkey.com "AutoHotkey's Website") to handle the repeat and magic functions since I couldn't be bothered to implement them with [QMK](https://docs.qmk.fm/features/repeat_key "QMK Repeat/Magic Documentation")
---
## Typing Test
![typing test](images/typing%20test.jpg)
