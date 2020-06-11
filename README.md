# Qwickly - The 'quick to learn/type' Keyboard Layout

Easier to learn than Minimak, faster than Dvorak, and your shortcuts (mostly) stay put.

### Installer for all macOS/OS X versions
- Qwickly (includes I and II) [Qwickly.dmg](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly.dmg)

Created using [Ukelele software](https://software.sil.org/ukelele).

### Installers for Windows (64-bit)
- Qwickly [Qwickly_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly_amd64.msi)
- Qwickly I [Qwickly1_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly1_amd64.msi)
- Qwickly II [Qwickly2_amd64.msi](https://github.com/qwickly-org/Qwickly/releases/download/v1.0/Qwickly2_amd64.msi)

Created using Microsoft Keyboard Layout Creator v1.4.

### Installers for Linux
- in development (stay tuned)


## Qwickly I

Let's get the 8 most [frequently occurring letters](https://en.wikipedia.org/wiki/Letter_frequency) in home finger positions. `A` and `S` are already there.

Swap frequently occuring letters: `E`, `T`, `N`, `I`, `O`, `P`<br/>
with letters above or below them: `D`, `F`, `J`, `K`, `L`, `;`

*(`R` occurs more than `P` but we'll get it in the next step.)*
```
 Q   W  (D)  R  (F)  Y   U  (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) (O) (P)  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
```
The keys `ASET GH NIOP` uses the same finger muscle-memory from QWERTY, just not moving fingers off the home-row.<br/>
With this layout, you will often miss `DF JKL` but that's okay since the letter you want is just above/below the miss.<br/>
We are mostly learning the home row. Switch to **Qwickly II** as soon as you can handle it.

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

This is near the efficiency of Dvorak or Asset layouts.<br/>
Here we're trying to learn the new `U`, `D` and `R` positions.<br/>
`K`/`I` and `L`/`O` bigrams will be awkward as it's same fingers like QWERTY but 'upside-down'.<br/>
Switch to **Qwickly** as soon as you can handle it. You can even try going directly from **Qwickly I** to **Qwickly**.

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
Note to `vi`/`vim` users: `J` is below `K` and `H` left of `L`.

Benchmarks on https://stevep99.github.io/keyboard-layout-analyzer
```
              Colemak  Qwickly   S.Dvorak   Asset   Minimak-12

   Alice       66.61    67.13^    63.71     64.29     62.45
   Common      73.94^   72.62     66.82     66.53     65.58
   S.A.T.      73.11^   71.36     64.26     65.52     63.21
   Magna       68.09    68.64^    65.08     64.27     62.41
   1984        67.47    67.80^    65.25     64.44     62.04
   Tarzan      68.38    68.70^    65.43     64.22     62.07
   Jungle      63.98    64.71^    61.22     61.24     57.55
   Difficult   67.97    68.14^    63.82     61.63     60.34
   Medical     72.76^   69.55     61.49     58.50     60.74
   Quotes      54.50^   53.66     46.74     51.61     49.92
   Tao         61.61^   60.25     58.68     58.37     56.35
   Bigrams     72.68^   72.26     68.24     70.18     69.10
   Cost        58.11    58.60^    50.78     54.84     52.93
   Contract    57.38^   54.39     47.38     52.70     49.73
   Binary      59.05^   57.67     54.23     52.70     51.51
   Lorem       57.06    57.32^    51.61     54.55     48.29
   Game        38.86    40.10^    35.35     36.04     34.56
```
^ fastest

Colemak looks like a winner but not clearly so--Qwickly goes head-to-head with it.<br/>
Simplified Dvorak is head-to-head with Asset. Minimak-12 is last.

My goal was to make something easier to learn than the existing layouts with key changes to stay closeby so I wouldn't have much trouble relearning shortcuts.
