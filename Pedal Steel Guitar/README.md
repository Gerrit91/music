# Pedal Steel Theory Notebook

This document collects my personal elaborations on the Pedal Steel Guitar. Reason for writing up a notebook was because I did not find much material on the internet that centers around using the instrument in typical jazz and pop music. I find the Pedal Steel Guitar sounding particularly great in these contexts and I am mainly planning to use it for playing chord progressions. When you are looking for country licks or something alike, this notebook will certainly not meet your expectations. There should be enough books that already approach the instrument like this anyway.

Please note, that I am neither a bookwriter nor particularly talented as a teacher. I consider myself as a beginner on Pedal Steel Guitar and I thought that writing this down could be helpful for some other beginners, too. Feel free to raise pull requests for improvements or error correction whenever you find necessary. Enjoy playing! 😌

<!-- TOC depthfrom:2 -->

- [Harmony and Notation](#harmony-and-notation)
- [The E9 Nashville Tuning](#the-e9-nashville-tuning)
    - [Pedals and Levers](#pedals-and-levers)
        - [Pedal Configuration](#pedal-configuration)
            - [A Pedal](#a-pedal)
            - [B Pedal](#b-pedal)
            - [C Pedal](#c-pedal)
        - [Lever Configuration](#lever-configuration)
            - [Eb Lever](#eb-lever)
            - [F Lever](#f-lever)
            - [G Lever](#g-lever)
            - [Db Lever](#db-lever)
            - [Bb Lever](#bb-lever)
        - [Combining Pedals](#combining-pedals)
            - [A + B Pedal AB](#a--b-pedal-ab)
            - [B + C Pedal BC](#b--c-pedal-bc)
            - [B + Eb Lever](#b--eb-lever)
            - [TODO](#todo)
    - [Summary: Base-Chords-by-Type Lookup Table](#summary-base-chords-by-type-lookup-table)
    - [Example Voicings for Song Comping](#example-voicings-for-song-comping)
        - [Miles High](#miles-high)

<!-- /TOC -->

## Harmony and Notation

Before getting started, a couple remarks on harmony and notation:

- The document approaches the instrument using pretty much standard [jazz harmony](https://en.wikipedia.org/wiki/Jazz_harmony). 
- Whenever roman numerals appear they relate to the scale degrees of the major scale (see [Roman Numeral Analysis](https://en.wikipedia.org/wiki/Roman_numeral_analysis)).
- Sharps and flats maybe used incorrectly in respect to their harmonic purpose ([enharmonic equivalents](https://en.wikipedia.org/wiki/Enharmonic)).
- Like on guitar, chords for the Pedal Steel are often [inversions](https://en.wikipedia.org/wiki/Inversion_(music)). When a chord inversion sounds good, it is treated equal to a chord in the root position.
- A **bold** number is often used to indicate a chord's root note.

## The E9 Nashville Tuning

E9 Nashville (or simply E9) appears to be one of the most common tunings used on Pedal Steel Guitar. This section tries to elaborate on the possibilities of this tuning for accompanying simple jazz standards.

The strings of the instrument are usually numbered from 1 to 10, where 10 is the lowest node of the tuning.

| String # | 10  |  9  |  8   |  7  |  6  |  5  |  4   |  3  |  2  |  1  |
| :------- | :-: | :-: | :--: | :-: | :-: | :-: | :--: | :-: | :-: | :-: |
| Note     |  B  |  D  |  E   | F#  | G#  |  B  |  E   | G#  | D#  | F#  |
| Function | 5th | 7th | root | 9th | 3rd | 5th | root | 3rd |  Δ  | 9th |

Remarks:

- Provides the I7 and IΔ chord (9 **8** 6 5 and **8** 6 5 2)
- 7 and Δ build up a b9 interval, which is the reason why strumming all strings together does not sound extremely pretty
- There is also a a nice-sounding III- (G#-, **6** 5 **3** 2) hidden on the higher strings

For the sake of completeness (I don't think it's really helpful), here are the notes on the fretboard for the first 12 frets:

|  S/F   |  0  |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  | 11  | 12  |
| :----: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| **1**  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |
| **2**  | D#  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |
| **3**  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |  G  | G#  |
| **4**  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |
| **5**  |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |
| **6**  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |  G  | G#  |
| **7**  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |
| **8**  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  | D#  |  E  |
| **9**  |  D  | D#  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |  C  | C#  |  D  |
| **10** |  B  |  C  | C#  |  D  | D#  |  E  |  F  | F#  |  G  | G#  |  A  | Bb  |  B  |     

S/F = String / Fret

### Pedals and Levers

Most Pedal Steels have three foot pedals, which are usually named A, B and C (from outer side of the instrument to the inside). 

It's common to press two adjacent pedals with one foot at the same time. 

Then, depending on the instrument, there are knee-levers, typically named RKR (right knee-lever right), RKL (right knee-lever left), etc. As being a left-handed player, I avoid using these terms, as "right" and "left" do not apply on mirrored instruments. Instead, for knee-levers, they will be named according to their effect on the base tuning, which is also quite a common thing to do.

Some players seem to also utilize "half-pressed" pedals to only raise notes by a half-step instead of a whole note (especially when the instrument has no knee-levers). For the beginning, intonation on the instrument is already challenging enough, so chords with half-pressed pedals are not included in this section. When your instrument has knee-levers there should already be enough choices for all basic chord types used in traditional jazz music.

#### Pedal Configuration

Even though pedals (and levers) can be configured to the taste of the player, I think there is a "default configuration" that players use, which is the following:

| Pedal | Effect                                 |
| :---: | :------------------------------------- |
|   A   | Raises all B strings to C#             |
|   B   | Raises all G# strings to A             |
|   C   | Raises strings 5 and 4 by a whole step |

##### A Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | C#  | D   | E   | F#  | G#  | C#  | E   | G#  | D#  | F#  |
| Bend Direction | 👆  |     |     |     |     | 👆  |     |     |     |     |

Remarks:

- Provides the VI- chord (C#-, 8 6 **5** 4)

##### B Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | E   | F#  | A   | B   | E   | A   | D#  | F#  |
| Bend Direction |     |     |     |     | 👆  |     |     | 👆  |     |     |

Remarks:

- Provides the Isus4 chord (Esus4, **8** 6 5 **4**)
- Very useful when being played with an adjacent pedal

##### C Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | E   | F#  | G#  | C#  | F#  | G#  | D#  | F#  |
| Bend Direction |     |     |     |     |     | 👆  | 👆  |     |     |     |

Remarks:

- Provides the I6 chord (E6, 10 **8** 6 5)
- Usually seems to be used in combination with the B Pedal to play the IV chord of a progression (with a "country-sounding" 6th on the top, see [B + C Pedal](#b--c-pedal-bc))
  - Using the A Pedal can also be used for the IV chord instead of the B pedal, avoiding the 6th on top, see [A + B Pedal AB](#a--b-pedal-ab)

#### Lever Configuration

My instrument has five knee-levers, but I will try not to include many chords using the fifth lever as many instruments don't have one and also there are seems to be no usual "default configuration". Here comes the lever configuration:

| Lever | Effect                                     |
| :---: | ------------------------------------------ |
|  Eb   | Lowers all E strings (root) by a half-step |
|   F   | Raises all E strings (root) by a half-step |
|   G   | Raises all F# strings by a half-step       |
|  Db   | Lowers D string and D# string to Db        |
|  Bb   | Lowers B strings to Bb                     |

##### Eb Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | Eb  | F#  | G#  | B   | Eb  | G#  | D#  | F#  |
| Bend Direction |     |     | 👇  |     |     |     | 👇  |     |     |     |

Remarks:

- Provides the III- Chord, lower than the one in the base tuning (G#-, 8 **6** 5 **4**)

##### F Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | F   | F#  | G#  | B   | F   | G#  | D#  | F#  |
| Bend Direction |     |     | 👆  |     |     |     | 👆  |     |     |     |

Remarks:

- Provides the VII⁰ chord (D0, **9** 8 6 5)
- Provides the bII-7b5 chord (F-7b5, **8** 6 5 2)

##### G Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  |  D  |  E  |  G  | G#  |  B  |  E  |  G  | D#  | F#  |
| Bend Direction |     |     |     | 👆 |     |     |     | 👆 |     |     |

Remarks: TODO

##### Db Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  | Db  |  E  |  G  | G#  |  B  |  E  |  G  | Db  | F#  |
| Bend Direction |     | 👇  |     |     |     |     |     |     | 👇  |     |

Remarks: TODO

##### Bb Lever

TODO

#### Combining Pedals

Even when limiting yourself to using the pedals in combination with just a single knee-lever, there are already a huge amount of possibilities for chords without even moving the steel bar around.

Example calculation: There are 6 ways to play the foot pedals (no pedals, A, B, C, AB and AC), from which each of these ways can be combined with either the Eb- or the F-lever, which makes 18 combinations in total. This does not include your second knee, which would again increase possibilities.

Due to this high amount of possibilities, the main objective for the beginning will be to identify those combinations that provide good sounding chord shapes that cover enough material to accompany a song or a jazz standard.

##### A + B Pedal (AB)

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | C#  |  D  |  E  | F#  |  A  | C#  |  E  |  A  | D#  | F#  |
| Bend Direction | 👆  |     |     |     | 👆  | 👆  |     | 👆  |     |     |

Remarks:

- Provides the IV chord (A, 8 **6** 5 4)
- Provides the II-7 chord (F#-7, **7** 6 5 4)

##### B + C Pedal (BC)

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  |  D  |  E  | F#  |  A  | C#  | F#  |  A  | D#  | F#  |
| Bend Direction |     |     |     |     | 👆  | 👆  | 👆  | 👆  |     |     |

- Provides the IV6 chord (A6, 8 **6** 5 4)

##### B + Eb Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  |  D  | Eb  | F#  |  A  |  B  | Eb  |  A  | D#  | F#  |
| Bend Direction |     |     | 👇  |     | 👆  |     | 👇  | 👆  |     |     |

- Provides the V chord (B7, **10** 8 7 6)

##### TODO

### Summary: Base-Chords-by-Type Lookup Table

A beautiful trait of Pedal Steel Guitars as compared to a simple Lap Steel Guitars is that a player has many more choices to build complex chord progressions for melody accompaniment. On Lap Steel Guitar, playing complex chord progressions requires a lot of movements (does not always sound so good), slants (holding the steel bar at an angle) or it is even impossible without individual necks using more individual tunings.

For this section we only look at chords that contain the root notes of a chord. Of course, choices are highly increasing when leaving out root notes. However, when using the root note in the chord, the chords sound far more obvious, which is useful when being practicing alone. Leaving out roots can be  beautiful when playing in a band context where the bass player already outlines the root notes of the song. I consider chords without root notes being an advanced chapter.

The following table summarizes available chord shapes for different kind of base chords that we already found:

|  Chord Type   | Abbr. | Pedals  |   Strings    |  Options  |
| :-----------: | :---: | :-----: | :----------: | :-------: |
|    Major 7    |   Δ   |         | **8** 6 5 2  | 9th (7,1) |
|               |       |   AB    | **9** 7 6 5  | 9th (8,4) |
|  Dominant 7   |   7   |         | 9 **8** 6 5  |           |
|               |       |    B    | **10** 3 2 1 |           |
|               |       | B + Eb  | **10** 8 7 6 |           |
|     Minor     |   -   |         | **10** 9 7 5 |           |
|               |       |    A    | 8 6 **5** 4  |           |
|    Minor 7    |  -7   |         | **6** 5 3 2  |           |
|               |       |    B    | **10** 9 7 6 |           |
|               |       |   AB    | **7** 6 5 4  |           |
|               |       |   Eb    | 8 7 **6** 5  |           |
|    Minor 6    |  -6   |         | **10** 9 7 6 |           |
|               |       |   AB    | **7** 6 5 2  |           |
|               |       | AB + Eb | **7** 6 5 4  |           |
| Half-dimished | -7b5  |    F    | **8** 6 5 2  |           |
|               |       |  B + F  | **10** 9 8 6 |           |
|               |       | AB + Eb | **8** 7 6 5  |           |

### Example Voicings for Song Comping

In this section, we'll use the chords that we already came up with in order to play first song accompaniments. The best way to move some of the theory into muscle memory is practicing songs. 

Of course, this section contains only the chord changes of with a possible voicing. Feel free to exchange chords to your taste, learn the melodies or sing the lyrics by hearing the original records.

#### 500 Miles High

|             |     E-9      |     G-6      |     BbΔ     |    B-7b5    |      E7      |
| :---------: | :----------: | :----------: | :---------: | :---------: | :----------: |
|  **Fret**   |     III      |     VIII     |    VIII     |     VI      |      V       |
| **Pedals**  |      A       |              |     AB      |      F      |    B + Eb    |
| **Strings** | **10** 8 6 5 | **10** 9 7 5 | **9** 7 6 5 | **8** 6 5 2 | **10** 8 7 6 |

|             |     A-      |    F#-7b5    |     F-      |    C-11     |     B7      |
| :---------: | :---------: | :----------: | :---------: | :---------: | :---------: |
|  **Fret**   |    VIII     |     VII      |     IV      |     IV      |     VII     |
| **Pedals**  |      A      |    B + F     |      A      |     Eb      |             |
| **Strings** | 8 6 **5** 4 | **10** 9 8 6 | 8 6 **5** 4 | 8 7 **6** 5 | 9 **8** 6 5 |
