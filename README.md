# Qwickly - The 'quick to learn/type' Keyboard Layout

Easier to learn than Minimak, faster than Dvorak, and your shortcuts (mostly) stay put.

### Installer for all macOS/OS X versions
- Qwickly with I, II, and Qwickly (Niro) [Qwickly.dmg](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly.dmg)

Created using [Ukelele software](https://software.sil.org/ukelele).

### Installers for Windows (64-bit)
- Qwickly [Qwickly_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly_amd64.msi)
- Qwickly I [Qwickly1_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly1_amd64.msi)
- Qwickly II [Qwickly2_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly2_amd64.msi)
- Qwickly (Niro) [QwicklyN_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/QwicklyN_amd64.msi)

Created using Microsoft Keyboard Layout Creator v1.4.

### Installers for Linux
- in development (stay tuned)


## Qwickly I

Swap frequently occuring letters: `E`, `T`, `N`, `I`, `O`, `P`<br/>
with letters above or below them: `D`, `F`, `J`, `K`, `L`, `;`
```
 Q   W  (D)  R  (F)  Y   U  (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) (P)  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
```

## Qwickly II

Reduced finger travel for other frequently occuring letters: `R`, `U`<br/>
rotate-swap with letters: `D`, `P`
```
 Q   W  <U> [D] (F)  Y  [P] (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

You can just stop right here as huge gains have been made over QWERTY.
In fact this is at the level of Dvorak or Asset layouts (give and take) when compared on https://stevep99.github.io/keyboard-layout-analyzer test inputs.

Taking this design to its logical conclusion we can add a few tweaks more, if you so choose.

## Qwickly

Final tweak rotate-swap letters: `K`->`Y`->`P`<br/>
and swap letters: `J`<->`B`
```
 Q   W  <U> [D] (F) [K] (Y) [P] (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V  {J}  {B}  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
{ } either same-finger/other-hand as QWERTY (depending on your typing style)
< > other hand than QWERTY
```

## Qwickly (Niro)

Alternative to **Qwickly** also swap letters: `R`<->`O` <br/>
This layout is often a bit faster than Quickly but have to learn new `O` finger/position.
```
 Q   W  <U> [D] (F) [K] (Y) [P] (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) <R> [O]  '   enter

   Z   X   C   V  {J}  {B}  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
{ } either same-finger/other-hand as QWERTY (depending on your typing style)
< > other hand than QWERTY
```

Benchmarks
```
              Colemak  Qwickly  S.Dvorak  Minimak-12  Asset

    Alice      66.61    64.76     63.71     62.45     64.29
    Common     73.94    68.21     66.82     65.58     66.53
    S.A.T.     73.11    66.47     64.26     63.21     65.52
    Magna      68.09    65.34     65.08     62.41     64.27
    1984       67.47    65.65     65.25     62.04     64.44
    Tarzan     68.38    65.69     65.43     62.07     64.22
    Jungle     63.98    61.37     61.22     57.55     61.24
    Difficult  67.97    61.24     63.82     60.34     61.63
    Medical    72.76    61.63     61.49     60.74     58.50
    Quotes     54.50    52.87     46.74     49.92     51.61
    Tao        61.61    59.50     58.68     56.35     58.37
    Bigrams    72.68    70.70     68.24     69.10     70.18
    Cost       58.11    55.06     50.78     52.93     54.84
    Contract   57.38    52.85     47.38     49.73     52.70
    Binary     59.05    52.23     54.23     51.51     52.70
    Lorem      57.06    53.30     51.61     48.29     54.55
    Game       38.86    36.85     35.35     34.56     36.04
```

Clearly Colemak stands out as expected. Looks like Qwickly edges out Asset.<jd/>
Simplified Dvorak is head-to-head with Asset. Minimak-12 is last.

My goal was to make something easier to learn than the existing layouts with key changes to stay closeby so I wouldn't have much trouble relearning shortcuts.
