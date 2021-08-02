# QwickSteps - Learn the Qwickly keyboard layout in 4 easy steps

Easier to learn than Minimak, faster than Dvorak, and your shortcuts stay put.

Read the blog [How Qwickly came to be](https://blog.keithkim.org/opensource/making-the-qwickest-keyboard-layout).

### Installer for all macOS/OS X versions
- QwickSteps [QwickSteps.dmg](https://github.com/qwickly-org/QwickSteps/releases/download/v1.0/QwickSteps.dmg)

Created using [Ukelele software](https://software.sil.org/ukelele).

### Installers for Windows (64-bit)
- QwickStep1 [QwickStep1_amd64.msi](https://github.com/qwickly-org/QwickStep/releases/download/v1.0/QwickStep1_amd64.msi)
- QwickStep2 [QwickStep2_amd64.msi](https://github.com/qwickly-org/QwickStep/releases/download/v1.0/QwickStep2_amd64.msi)
- QwickStep3 [QwickStep3_amd64.msi](https://github.com/qwickly-org/QwickStep/releases/download/v1.0/QwickStep3_amd64.msi)
- QwickStep4 [QwickStep4_amd64.msi](https://github.com/qwickly-org/QwickStep/releases/download/v1.0/QwickStep4_amd64.msi)

Created using Microsoft Keyboard Layout Creator v1.4.

### Installers for Linux
- in development (stay tuned)


## QwickStep 1

Let's get the 8 most [frequently occurring letters](https://en.wikipedia.org/wiki/Letter_frequency) in home finger positions. `A` and `S` are already there.

Swap frequently occurring letters: `E`, `T`, `N`, `I`, `O`, `P`<br/>
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
The keys `ASET GH NIOP` uses the same fingers' muscle-memory from QWERTY, only staying much more frequently on the home row.<br/>
With this layout, you may often miss `DF JKL` but that's okay since the letter you want is immediately next to the miss it's quick to correct.<br/>
We are mostly learning the home row. Move on to **QwickStep 2** as soon as you can handle it (sometime before getting fully comfortable).

## QwickStep 2

Let's put that `R` on the home row where it belongs. Shift the `O` right, bumping `P` that shifts `F` left to where `R` was.
```
 Q   W  (D) (F) <P>  Y   U  (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) <R> [O]  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

The home row is now looking really good, and other keys are moving to their final places so we don't have to relearn much as we go.
Switch to **QwickStep 3** as soon as you can handle it, or sooner to test out the waters.

## QwickStep 3

Now we want to lock down the place of the vowel `U`. Shift `D` right, bumping `F` to where `U` was.
```
 Q   W  <U> [D] <P>  Y  <F> (K) (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) <R> [O]  '   enter

   Z   X   C   V   B   (J)  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

Now we've got most of the keys in their final places or close-by.
Don't get too comfortable, switch to **QwickStep 4** as soon as you can.

## QwickStep 4

Now we're tweaking the remaining few unsmooth letter placements. Swap `Y` with `K` and `B` with `J`.
```
 Q   W  <U> [D] <P> [K] <F> [Y] (L) (;)  [   ]   \

  A   S  (E) (T)  G   H  (N) (I) <R> [O]  '   enter

   Z   X   C   V  <J>  <B>  M   ,   .   /

Legend
    same as QWERTY
( ) same finger as QWERTY
[ ] same hand as QWERTY
< > other hand than QWERTY
```

This is already a really good layout that's better than many that are harder to learn.
Trivia: this ends up being a more optimized version of the **NIRO** layout (rotates B-K-J keys).
In fact this was the original version of **Qwickly** and we could call this the *final* version of **QwickStep**.

### WPM per letter on day 6

There's some evidence that reusing muscle-memory for home row keys works.<br/>
Notice which letters are more/less quickly typed than others.

![wpm per letter](https://github.com/qwickly-org/QwickSteps/blob/master/wpm-letters-day-6.png)

### WPM progress day 2 to 6

Day 1 started at ~15 wpm after about an hour of practice.

![wpm progress days 2 through 6](https://github.com/qwickly-org/QwickSteps/blob/master/wpm-days-2-6.png)

### Benchmarks

Using https://stevep99.github.io/keyboard-layout-analyzer

<pre><code>
              Colemak  QwickStep4  Niro     S.Dvorak

   <b>Alice</b>       67.31     <b>68.27</b>*    67.55     63.59
   Common      <b>74.50</b>*    71.75     70.75     64.48
   S.A.T.      <b>71.38</b>*    70.01     68.19     60.79
   <b>Magna</b>       69.29     <b>69.86</b>*    68.85     63.99
   <b>1984</b>        69.30     <b>70.53</b>*    69.08     65.19
   <b>Tarzan</b>      69.73     <b>70.34</b>*    69.45     64.73
   <b>Jungle</b>      65.57     66.09     <b>66.44</b>*    61.71
   Difficult   <b>67.30</b>*    66.18     65.28     61.31
   Medical     <b>72.08</b>*    69.34     67.34     58.77
   <b>Quotes</b>      56.54     <b>57.68</b>*    57.40     48.43
   <b>Tao</b>         61.44     <b>61.46</b>*    60.34     57.78
   Bigrams     <b>77.43</b>*    76.23     75.39     70.88
   <b>Cost</b>        <b>60.69</b>*    60.06     59.84     52.09
   <b>Contract</b>    <b>60.17</b>*    54.67     54.61     49.24
   <b>Binary</b>      <b>61.05</b>*    59.70     59.05     55.12
   Lorem       57.89     <b>59.72</b>*    59.18     50.96
   Game        43.99     <b>45.11</b>*    44.82     41.64
</code></pre>
**bold name** = prose (English sentences)
**bold score*** = best score

**QwickStep4** got tops on 6 of the 10 English prose samples,<br/>
**Colemak** taking the 3 (Cost/Contract/Binary) Academics, and **Niro** taking The Jungle Book.

#### QwickStep4
![QwickStep4 keyboard layout](https://github.com/qwickly-org/QwickStep/blob/master/QwickStep4.png)
