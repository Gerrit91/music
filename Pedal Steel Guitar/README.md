# Pedal Steel Theory Notebook

This document collects my personal elaborations on the Pedal Steel Guitar. Reason for writing up a notebook was because I did not find much material on the internet that centers around using the instrument in typical jazz and pop music. I find the Pedal Steel Guitar sounding particularly great in these contexts and I am mainly planning to use it for playing chord progressions. When you are looking for country licks or sophisticated lead playing, this notebook will certainly not meet your expectations. There should be enough books that already approach the instrument like this anyway.

Please note, that I am neither a bookwriter nor particularly talented as a teacher. I consider myself as a beginner on Pedal Steel Guitar and I thought that writing this down could be helpful for some other beginners, too. I assume some theoretical knowledge on jazz harmony and how chords are built though.

Feel free to raise pull requests for improvements or error correction whenever you find necessary. Enjoy playing! 😌

<!-- TOC depthfrom:2 -->

- [Harmony and Notation](#harmony-and-notation)
    - [Interval Abbreviation](#interval-abbreviation)
- [The E9 Nashville Tuning](#the-e9-nashville-tuning)
    - [Contained Chords](#contained-chords)
    - [Fretboard Notes](#fretboard-notes)
    - [Pedals and Levers](#pedals-and-levers)
        - [Pedal Configuration](#pedal-configuration)
            - [A Pedal](#a-pedal)
                - [Contained Chords](#contained-chords)
            - [B Pedal](#b-pedal)
                - [Contained Chords](#contained-chords)
            - [C Pedal](#c-pedal)
                - [Contained Chords](#contained-chords)
        - [Lever Configuration](#lever-configuration)
            - [Eb Lever](#eb-lever)
                - [Contained Chords](#contained-chords)
            - [F Lever](#f-lever)
                - [Contained Chords](#contained-chords)
            - [G Lever](#g-lever)
                - [Contained Chords](#contained-chords)
            - [Db Lever](#db-lever)
        - [Combining Pedals](#combining-pedals)
            - [A + B Pedal AB](#a--b-pedal-ab)
            - [B + C Pedal BC](#b--c-pedal-bc)
            - [A + F Lever](#a--f-lever)
            - [A + Db Lever](#a--db-lever)
            - [B + Eb Lever](#b--eb-lever)
    - [Base-Chords-by-Type Lookup Table](#base-chords-by-type-lookup-table)
    - [Example Voicings for Song Comping](#example-voicings-for-song-comping)
        - [Miles High](#miles-high)

<!-- /TOC -->
<!-- /TOC -->

## Harmony and Notation

Before getting started, a couple remarks on harmony and notation:

- The document approaches the instrument using pretty much standard [jazz harmony](https://en.wikipedia.org/wiki/Jazz_harmony).
- Whenever roman numerals appear they relate to the scale degrees of the major scale (see [Roman Numeral Analysis](https://en.wikipedia.org/wiki/Roman_numeral_analysis)).
- Sharps and flats maybe used incorrectly in respect to their harmonic purpose ([enharmonic equivalents](https://en.wikipedia.org/wiki/Enharmonic)).
- Like on guitar, chords for the Pedal Steel are often [inversions](https://en.wikipedia.org/wiki/Inversion_(music)). When a chord inversion sounds good (which can be subjective), it is treated equal to a chord in the root position.

### Interval Abbreviation

Personally, I find it useful to see chord tones in relationship to their root note. This is also true for fingerings, which will be used extensively in this notebook. For this reason, I introduce an own notation style for the string notation including the string to pluck in addition to an interval abbreviation.

Here is the table for interval abbreviations that are used, the letter `x` is written as a number representing a string on the Pedal Steel Guitar:

| Interval  | Abbreviation | In String Notation |
| :-------- | :----------: | :----------------: |
| root      |      1       |    **x** (bold)    |
| minor 2nd |      b9      |         x~         |
| major 2nd |      9       |        x\*         |
| minor 3rd |      -       |         x-         |
| major 3rd |      3       |         x+         |
| fourth    |      4       |   _x_ (italics)    |
| tritone   |   #11 / b5   |      x# / xb       |
| fifth     |      5       |         x          |
| minor 6th |      b6      |         x↓         |
| major 6th |      6       |         x↑         |
| minor 7th |      7       |         x◊         |
| major 7th |   maj7 / Δ   |         xΔ         |

So, a fingering for a I-Chord might look like: **8** 6+ 5 **4**, meaning:

 - Pluck the 8th string, which is a root note
 - Pluck the 6th string, which a major third
 - Pluck the 5th string, which is a fifth
 - Pluck the fourth strings, which is again a root note

## The E9 Nashville Tuning

E9 Nashville (or simply E9) appears to be one of the most common tunings used on Pedal Steel Guitar. This section tries to elaborate on the possibilities of this tuning for accompanying simple jazz standards.

The strings of the instrument are usually numbered from 10 to 1 (direction from the body to the instrument), where 10 is the lowest node of the tuning.

| String # | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note     |  B  |  D  |  E  | F#  | G#  |  B  |  E  | G#  | D#  | F#  |
| Function |  5  |  7  |  1  |  9  |  3  |  5  |  1  |  3  |  Δ  |  9  |

The note pitches are ascending from 10 to 3. Then, string 2 and 1 are tuned lower than string 3.

### Contained Chords

|   Chord   | Name |      String Notation       | Options | Avoid |
| :-------: | :--: | :------------------------: | ------- | ----- |
|   **I**   |  E   |   10 **8** 6+ 5 **4** 3+   | 7\* 1\* |       |
|  **I7**   |  E7  | 10 9◊ **8** 6+ 5 **4** 3+  | 7\* 1\* | 2Δ    |
|  **IΔ**   |  EΔ  | 10 **8** 6+ 5 **4** 3+ 2Δ  | 7\* 1\* | 9◊    |
| **III-7** | G#-  | 10- 7◊ **6** 5- **3** 2 1◊ |         | 9b    |

Remarks:

- 7 and Δ build up a b9 interval in the E chord, which is the reason why strumming all strings together does not sound extremely pretty

### Fretboard Notes

For the sake of completeness (I don't think it's really helpful), here are the notes on the fretboard for the first 12 frets:

|  S/F*  |  0  |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  | 11  | 12  |
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

\* S/F = String / Fret

### Pedals and Levers

Most Pedal Steels have three foot pedals, which are usually named A, B and C (from outer side of the instrument to the inside).

It's common to press two adjacent pedals with one foot at the same time.

Then, depending on the instrument, there are knee-levers, typically named RKR (right knee-lever right), RKL (right knee-lever left), etc. As being a left-handed player, I avoid using these terms, as "right" and "left" do not apply on mirrored instruments. Instead, for knee-levers, they will be named according to their effect on the base tuning, which is also quite a common thing to do.

Some players seem to also utilize "half-pressed" pedals to only raise notes by a half-step instead of a whole note (especially when the instrument has no knee-levers). For the beginning, intonation on the instrument is already challenging enough, so chords with half-pressed pedals are not included in this section. When your instrument has knee-levers there should already be enough choices for all basic chord types used in traditional jazz music.

#### Pedal Configuration

Even though pedals (and levers) can be configured to the taste of the player, I think there is a "default configuration" that players use, which is the following:

| Pedal | Position | Effect                                 |
| :---: | :------: | :------------------------------------- |
|   A   |   Out*   | Raises all B strings to C#             |
|   B   |  Middle  | Raises all G# strings to A             |
|   C   |   In*    | Raises strings 5 and 4 by a whole step |

\* Again these terms try to avoid "left" and "right" such that the description is correct for left-handed instruments as well. "Out" and "in" refer to your sitting position. The "in" direction points between your knees, "out" points away from the instrument.

The other foot that is free and that does not have any pedals to press is usually used for  operating a volume pedal. Volume pedals are extremely handy on Pedal Steel Guitars as they can be used to mute strings during chord transitions. This can significantly tidy up the sound and does not require sophisticated muting techniques with the picking hand.

##### A Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | C#  | D   | E   | F#  | G#  | C#  | E   | G#  | D#  | F#  |
| Bend Direction | 👆  |     |     |     |     | 👆  |     |     |     |     |


This pedal is very useful for building wide minor chords with options for add9 and add11 chords. Only string 9 needs to be avoided, which can even be mitigated in combination with the Db lever.

###### Contained Chords

| Chord   | Name | String Notation        | Options       | Avoid |
| ------- | ---- | ---------------------- | ------------- | ----- |
| **VI-** | C#-  | **10** 8- 6 **5** 4- 3 | _7_, 2\*, _1_ | 9b    |

##### B Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | E   | F#  | A   | B   | E   | A   | D#  | F#  |
| Bend Direction |     |     |     |     | 👆  |     |     | 👆  |     |     |

Predominantly, this pedal creates a sus4 sound. It's also very useful when being played with an adjacent pedal.

###### Contained Chords

| Chord      | Name   | String Notation             | Options  | Avoid |
| ---------- | ------ | --------------------------- | -------- | ----- |
| **I7sus4** | E7sus4 | 10 9◊ **8** _6_ 5 **4** _3_ | 7\*, 1\* | 2Δ    |

##### C Pedal

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | E   | F#  | G#  | C#  | F#  | G#  | D#  | F#  |
| Bend Direction |     |     |     |     |     | 👆  | 👆  |     |     |     |

Usually seems to be used in combination with the B Pedal to play the IV chord of a progression (with a "country-sounding" 6th on the top, see [B + C Pedal](#b--c-pedal-bc)). Instead of the C Pedal, the A Pedal can also be used for the IV chord though, avoiding the 6th on top, see [A + B Pedal AB](#a--b-pedal-ab).

###### Contained Chords

| Chord  | Name | String Notation          | Options      | Avoid |
| ------ | ---- | ------------------------ | ------------ | ----- |
| **I6** | E6   | 10  **8** 6+ 5↑ **4** 3+ | 9◊, 7\*, 1\* | 2Δ    |

#### Lever Configuration

My instrument has five knee-levers, but many instruments don't have the fifth lever and also there seems to be no common "default configuration" for it. Due to this reason, I omit the fifth lever chords in this section and keep them for later.

Here comes the lever configuration:

| Lever |     Position      | Effect                                     |
| :---: | :---------------: | ------------------------------------------ |
|  Eb   | Over pedals*, in  | Lowers all E strings (root) by a half-step |
|   F   | Over pedals*, out | Raises all E strings (root) by a half-step |
|   G   | Over volume*, in  | Raises all F# strings by a half-step       |
|  Db   | Over volume*, out | Lowers D string and D# string to Db        |
|  Bb   | Over pedals*, up  | Lowers B strings to Bb                     |

\* Still, I avoid the terms "left" and "right" in order to keep consistency for mirrored instruments. So, in addition to "in" and "out" from the previous section, I use the pedal position as a reference to describe the location of the lever on the instrument.

##### Eb Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | Eb  | F#  | G#  | B   | Eb  | G#  | D#  | F#  |
| Bend Direction |     |     | 👇  |     |     |     | 👇  |     |     |     |

Extends the notes for the III--Chord from the base tuning, but since the G# is pretty high on the top, the predominant sound of the entire string set is the V-Chord with an added 6th.

###### Contained Chords

| Chord     | Name | String Notation                  | Options | Avoid |
| --------- | ---- | -------------------------------- | ------- | ----- |
| **V6**    | B6   | **10**  8+ 7 6↑ **5** 4+ 3↑ 2+ 1 |         | 9-    |
| **III-7** | G#-  | 10- 8 7◊ **6** 5- 4 **3** 2 1◊   |         | 9b    |

##### F Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | B   | D   | F   | F#  | G#  | B   | F   | G#  | D#  | F#  |
| Bend Direction |     |     | 👆  |     |     |     | 👆  |     |     |     |

This lever adds some spice and allows playing some very useful chords for jazz comping. However, there are some notes to avoid when trying to clearly outline the chord's function, too.

###### Contained Chords

| Chord       | Name    | String Notation             | Options | Avoid    |
| ----------- | ------- | --------------------------- | ------- | -------- |
| **VII⁰**    | D0 / B0 | 10↑ **9** 8- 6b 5↑ 4- 3b    |         | 7+ 2~ 1+ |
| **bII-7b5** | F-7b5   | 10b **8** 6- 5b **4** 3- 2◊ |         | 9↑ 7~ 1~ |

##### G Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  |  D  |  E  |  G  | G#  |  B  |  E  |  G  | D#  | F#  |
| Bend Direction |     |     |     | 👆  |     |     |     | 👆  |     |     |

The lever allows the base tuning to be altered to a minor chord with an optional 7th in the bass. Another interesting option for jazz is the -Δ chord.

###### Contained Chords

| Chord  | Name | String Notation        | Options   | Avoid |
| ------ | ---- | ---------------------- | --------- | ----- |
| **I-** | E-   | 10 **8** 7- 5 **4** 3- | 9◊ 2Δ 1\* | 6+    |

##### Db Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  | Db  |  E  | F#  | G#  |  B  |  E  | G#  | Db  | F#  |
| Bend Direction |     | 👇  |     |     |     |     |     |     | 👇  |     |

This lever alone does not provide completely new chords but adds the 6th to the I-Chord. It's noteworthy that with this lever the usual avoid notes of the base tuning are altered, such that the entire string set has no big dissonances anymore.

#### Combining Pedals

Combining pedals now opens up a lot of further possibilities. Even when limiting yourself to using the pedals in combination with just to two knee-levers, there are already a huge amount of possibilities for chords without even moving the steel bar around.

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

Remarks:

- Provides the IV6 chord (A6, 8 **6** 5 4)

##### A + F Lever

| String #       | 10  | 9   | 8   | 7   | 6   | 5   | 4   | 3   | 2   | 1   |
| :------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Note           | C#  | D   | F   | F#  | G#  | C#  | F   | G#  | D#  | F#  |
| Bend Direction | 👆  |     | 👆  |     |     | 👆  | 👆  |     |     |     |

Remarks:

- Provides the VI chord (C#, **10** 8 6 5), option for sus4 on 7
  - This is nice because we can alter the VI- from the A pedal press to major

##### A + Db Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           | C#  | Db  |  E  | F#  | G#  | C#  |  E  | G#  | Db  | F#  |
| Bend Direction | 👆 | 👇 |     |     |     | 👆 |     |     | 👇 |     |

Remarks:

- This doubles up bass note on the instrument, which is cool because often you need to worry a lot not to hit 10 and 9 and the same time, now you can just strum the strings and it will sound alright!

##### B + Eb Lever

| String #       | 10  |  9  |  8  |  7  |  6  |  5  |  4  |  3  |  2  |  1  |
| :------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Note           |  B  |  D  | Eb  | F#  |  A  |  B  | Eb  |  A  | D#  | F#  |
| Bend Direction |     |     | 👇  |     | 👆  |     | 👇  | 👆  |     |     |

- Provides the V chord (B7, **10** 8 7 6)

### Base-Chords-by-Type Lookup Table

A beautiful trait of Pedal Steel Guitars as compared to a simple Lap Steel Guitars is that a player has many more choices to build complex chord progressions for melody accompaniment. On Lap Steel Guitar, playing complex chord progressions requires a lot of movements (does not always sound so good), slants (holding the steel bar at an angle) or it is even impossible without individual necks using more individual tunings.

For this section we only look at chords that contain the root notes of a chord. Of course, choices are highly increasing when leaving out root notes. However, when using the root note in the chord, the chords sound far more obvious, which is useful when being practicing alone. Leaving out roots can be beautiful when playing in a band context where the bass player already outlines the root notes of the song. I consider chords without root notes being an advanced chapter.

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
