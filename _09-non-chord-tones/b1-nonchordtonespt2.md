---
layout: chapter
title: 9b Lesson - Non-chord Tones, Part 2
abc: true
---

*NOTE: The full descriptions below of each type of non-chord tone are from the online textbook, [Open Music Theory](http://www.openmusictheory.net), although each has been edited to suit this textbook's terminology and purpose. If you have not had a chance to check out Open Music Theory in the Further Reading sections from the previous units, please take the time to do so. It is an excellent resource!*

## Non-chord tone recap

Understanding non-chord tones is critical for increasing the accuracy and speed of your tonal analysis. When looking at pieces of music, specifically those that have complicated textures, you will often face difficult decisions about which tones are functional to the harmonic progression and which tones are embellishing those functional tones. If you know the shapes that chord tones and their embellishments form, you can separate chord tones from embellishments by simply looking for common patterns.

**We will use the same simple progression that we used in the previous topic as a template for demonstrating non-chord tones. If you do not still have this analyzed, you may wish to do so again before proceeding.**

{% capture ex1 %}X:1
T:A simple phrase
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## More non-chord tones

Compare the examples below to the original progression to determine what has changed knowing that any added pitches will be the NCTs of that type. As you do this, use the the three characteristics discussed in the previous topic--preparation, NCT, and resolution--to create a definition for each NCT. Once you have a working definition, see if the other other descriptors (e.g. upper/lower, ascending/descending, chromatic/diatonic, on-chord/off-chord, or accented/non-accented) can be applied to each NCT.

### Neighbor Groups (NG) - also called "double neighbor tones"

**How does the neighbor group relate to a neighbor tone?**

{% capture ex4 %}X:4
T:With added neighbor groups
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| [C/2F/2]"ng"[C/4G2/4][C/4E/4]H[CF]|]
V:2 clef=bass
[F,C]| [B,,D] "ng"[C/4C,/4][D/4C,/4][C/4C,/4][B,/4C,/4]| [CF,] [D,B,]| [B,,/2G,/2]"ng"[B,,/4F,/4][B,,/4A,/4] [G,C,]| H[A,2F,,2]|]
w:F:I ii6 V7 _ _ _ I IV6 ii6 _ _ V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

#### Conclusions

![](/images/embellishingTones/doubleNeighbor.png)

Like neighbor tones, a *neighbor group*, also known as a double neighbor figure, begins and ends on the *same* stable tone. Between those two instances of the stable tone are two embellishing tones — one a step above and the other a step below the stable tone being embellished. Though individually we may consider each of the two embellishing tones to be incomplete neighbor tones, working together in the double-neighbor figure, they balance each other and create a contiguous whole, with the overall stability of a complete neighbor. A double neighbor figure is typically unaccented and off-chord, although it could be both accented and on-chord.

### Appoggiaturas (APP)

**In the same way that suspensions and retardations are often grouped together, appoggiaturas and escape tones are as well. The following two examples include NCT appoggiaturas and escape tones as well as appoggiaturas *figures* and escape tone *figures*. Use the example below to answer the following:**
- What is the definition for both of these non-chord tones?
- What do they have in common and why are they grouped together?
- What major difference does the term "figure" imply when used in referencing non-chord tones? Do you think that "figure" could be applied to any of the previous NCTs that we have studied?

{% capture ex5 %}X:5
T:With added appoggiaturas
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [D/2G/2]"app"[D/2c/2] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[CF,]| [B,,D] [C/2C,/2]"app fig"[C/2G,/2]| [CF,] "app"[D,/2A,/2][D,/2B,/2]| [B,,G,/2][G,C,]| H[A,2F,,2]|]
w:F:I _ ii6 V7 _ I IV6 _ ii6 V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

### Escape tones (ET)

{% capture ex6 %}X:6
T:With added escape tones
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [E/2B/2]"et fig"[E/2c/2]| [F/2A/2]"et"[F/2B/2] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,/2B,/2]"et"[D,/2C/2]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:F:I ii6 V7 I IV6 _ ii6 V I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

#### Conclusions

![][appoggiatura]

An appoggiatura is a kind of incomplete neighbor tone that is *approached by leap, and followed by step in the opposite direction*.

![][escape]

An escape tone, or *echappée*, is *approached by stepwise motion and left by leap in the opposite direction*.

The term "figure" can be used when discussing non-chord tones to imply that the melody follows the *shape* of a particular non-chord tone, but all pitches are actually chord tones. This is very useful in describing melodic shapes. (e.g. A melody can be described as having a passing tone figure if the melody has a stepwise movement continuously in one direction, even if every note belongs to a chord.)

### Anticipations (ANT)

{% capture ex7 %}X:7
T:With added anticipations
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [E/2B/2]"ant"[E/2A/2]| [FA] [FD]| [DD] [C/2E/2]"ant"[C/2F/2]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,/2B,/2]"ant"[D,/2G,/2]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:F:I ii6 V7 I IV6 _ ii6 V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

#### Conclusions

![][anticipation]

An anticipation is essentially an otherwise stable tone that comes too early. An anticipation is a non-chord tone that will occur immediately before a change of harmony, and it will be followed on that change of harmony by the same note, now a chord tone of the new harmony. Therefore, it is approached by stepwise motion and left by static motion. The static motion between the NCT and its resolution means that you may consider this related to both suspensions and retardations, although unlike suspensions and retardations, this is an unaccented, off-chord NCT with static motion occurring *after* the NCT rather than before. It is typically found at the ends of phrases and larger formal units.

#### Syncopation versus anticipations

![](/images/embellishingTones/syncopatedNote.png)

Some theorists classify syncopated rhythmic figures as separate from anticipations, but this is more a discussion of re-articulation. For those that classify these differently, [syncopation](http://openmusictheory.com/syncopation.html) occurs when a rhythmic pattern that typically occurs on strong beats or strong parts of the beat occurs instead on weak beats or weak parts of the beat. Like the anticipation, the syncopated note is an early arrival — it tends to belong to the chord on the following beat. Unlike the anticipation, the syncopation is tied into a note in that chord and is not rearticulated. Rather than anticipating a note in the chord that follows, a syncopation is simply a disjointed and repeated arrival of the chord itself. Of course, you should consider context when making this decision as this difference is subtle, but if there is a pattern of syncopated rhythms in a passage, you could be more likely to label syncopation for the passage as a whole, rather than many anticpations.

### Pedals (PED)

**Pedals, often referred to as pedal points, most often occur in the bass voice but can occur in any voice. They can be difficult to spot if the texture is broken into arpeggiated chords, so it may be necessary to reduce a complicated texture down to block chords to more easily find the pedals.**

{% capture ex8 %}X:8
T:With an added pedal point
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| [CF][DF]| H[C2F2]|]
V:2 clef=bass
[F,C]| [F,B,] "ped"[F,C]| [CF,] [D,B,]| [B,,G,] [G,C,]| [A,F,,] "ped fig"[B,F,,]| H[A,2F,,2]|]
w:F:I ii6 V7 I IV6 ii6 V I IV6/4 I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}

#### Conclusions

Pedals are *approached by static motion and left by static motion*; essentially, this is just a pitch that refuses to leave regardless of whether it belongs to the chord. Pedals are one of the most interesting non-chord tones because they have a dual nature--they create some of the strongest dissonances in tonal harmony, but their repetitive nature provides a sort of strange stability. As a pedal continues, it will often alternate between acting as a chord tone and non-chord tone, so it can be helpful to label the chord tones as "pedal figures" to show the continuation of the pedal.

## A less common non-chord tone

### Incomplete Neighbor Tone (INT)

It is uncommon, but you will occasionally encounter an unaccented non-chord tone that is approached by leap and left in the *same* direction; resembling an appoggiatura but not resolving in the opposite direction. For this course, we will label these as *incomplete neighbor tones*, although some theorists use this term to refer to appoggiaturas and escape tones as well. Broadly speaking, you should not resort to an incomplete neighbor tone NCT unless you have exhausted all other options, because it is far more likely for this shape is part of a chordal skip rather than an NCT.


[INT]: {{ site.baseurl }}/images/embellishingTones/INT.png
[appoggiatura]: {{ site.baseurl }}/images/embellishingTones/appoggiatura.png
[escape]: {{ site.baseurl }}/images/embellishingTones/escapeTone.png
[anticipation]: {{ site.baseurl }}/images/embellishingTones/anticipation.png
[syncopation]: {{ site.baseurl }}/images/embellishingTones/syncopatedNote.png