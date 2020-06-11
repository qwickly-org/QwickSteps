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

Let's get the 8 most frequently occurring letters in home finger positions. `A` and `S` are already there.

Swap frequently occuring letters: `E`, `T`, `N`, `I`, `O`, `P`<br/>
with letters above or below them: `D`, `F`, `J`, `K`, `L`, `;`

*(`R` occurs more than `P` but we'll get this in the next step.)*
```
 Q   W  (D)  R  (F)  Y   U  (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) (P)  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
```

## Qwickly II

The next frequently occurring letters `D`, `H`, and `L` are already in close positions.

Reduce finger travel for other frequently occuring letters: `R`, `U`<br/>
rotate-swap with letters: `D`, `P` *(We move `D` for `U` because it works out better in the end.)*
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

This is near the efficiency of Dvorak or Asset layouts when compared on https://stevep99.github.io/keyboard-layout-analyzer test inputs.

Taking this design to its logical conclusion we can add a few more tweaks.

## Qwickly

`K` occurs less than `L`/`P`/`Y`. The ordering `L`/`P`/`Y` minimizes same-finger [bigrams](https://blogs.sas.com/content/iml/2014/09/26/bigrams.html).<br/>
`J` occurs less than `B`.

Final tweak rotate-swap letters: `K`/`L`<- , ->`P`/`Y`<br/>
and swap letters: `J`<->`B`
```
 Q   W  <U> [D] (F) [K] [L] [P] [Y] (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) <R>  '   enter

   Z   X   C   V  <J>  <B>  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```
*(This is the layout I am using (with possible punctuation tweaks for coding.)*

## Qwickly (Niro)

Alternative to **Qwickly** instead rotate-swap letters: `K`/`P`/`Y`<br/>
and swap letters: `J`<->`B` and `R`<->`O`<br/>
This layout is often a touch faster than Quickly but have to learn new `O` finger/position.

*(Personally, I feel moving `O` goes against the spirit of 'easy to learn' for a smallish gain. Added because people will ask.)*
```
 Q   W  <U> [D] (F) [K] [P] [Y] (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) <R> [O]  '   enter

   Z   X   C   V  <J>  <B>  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

Benchmarks
```
              Colemak  Qwickly  S.Dvorak  Minimak-12  Asset

    Alice      66.61    67.13^    63.71     62.45     64.29
    Common     73.94^   72.62     66.82     65.58     66.53
    S.A.T.     73.11^   71.36     64.26     63.21     65.52
    Magna      68.09    68.64^    65.08     62.41     64.27
    1984       67.47    67.80^    65.25     62.04     64.44
    Tarzan     68.38    68.70^    65.43     62.07     64.22
    Jungle     63.98    64.71^    61.22     57.55     61.24
    Difficult  67.97    68.14^    63.82     60.34     61.63
    Medical    72.76^   69.55     61.49     60.74     58.50
    Quotes     54.50^   53.66     46.74     49.92     51.61
    Tao        61.61^   60.25     58.68     56.35     58.37
    Bigrams    72.68^   72.26     68.24     69.10     70.18
    Cost       58.11    58.60^    50.78     52.93     54.84
    Contract   57.38^   54.39     47.38     49.73     52.70
    Binary     59.05^   57.67     54.23     51.51     52.70
    Lorem      57.06    57.32^    51.61     48.29     54.55
    Game       38.86    40.10^    35.35     34.56     36.04
```
^ fastest

Colemak looks like a winner but not clearly so--Qwickly goes head-to-head with it.<jd/>
Simplified Dvorak is head-to-head with Asset. Minimak-12 is last.

My goal was to make something easier to learn than the existing layouts with key changes to stay closeby so I wouldn't have much trouble relearning shortcuts.
