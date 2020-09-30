---
layout: chapter
title: 9a Lesson - Non-chord Tones, Part 1
abc: true
---

<!--FIX THIS. Moved from what used to be end of 7b. Needs to be incorporated to fit the continuity. -->

## Chord tones versus non-chord tones (NCTs)

<!-- This sub-section used to be in a different unit. This needs editing to combine it.-->

Even though the Old Hundreth Psalm has no non-chord tones, it is important for us to discuss them in this context, because understanding the question of "Which pitches are functional?" means determining which pitches belong to the chord (chord tones) and which pitches are decoration for these chord tones.

Much like determining the harmonic rhythm, finding NCTs can be difficult because it requires working through all possible combinations of the pitches within a given harmony and then choosing the most likely combination. Even if you know that the harmony includes only two beats, if there are many pitches within those two beats, it can be difficult to sort through all the possible combinations. Fortunately, the same strategies that work for determining the harmonic rhythm work just as well for determining NCTs. Looking at melodic patterns and bass-lines is a great start, but it is also helpful to be aware of whether a note occurs in a strong or weak position. It is unusual for the functional tones to occur only on offbeats, as the ear is drawn to pitches when they occur on the beat. 

Even for one experienced in finding patterns within the music, this still sometimes requires trial-and-error. For beginning students, they should try copying the pitches to another staff (or lightly next to the chord if there is room,) and begin rearranging the pitches to see what triads and seventh chords are even possible. Usually this is enough to limit the possibilities to one or two chords. When it is not, they should refer to their harmonic flowchart to see if there is some context that could provide a probable chord.

### Notating non-chord tones

To notate non-chord tones, you should place parentheses around the note head of each non-chord tone. You must also label the NCT with its abbreviation. Currently, we only have three possible NCTs:
- pt (passing tone)
- nt (neighbor tone)
- sus (suspension)

The students had an excellent question regarding non-chord tones.
- If there is a V chord with a chordal seventh in a moving line, should that be considered a V<sup>7</sup>?
    - The most common answer is yes, but make sure that it functions as a chordal seventh. If it resolves down by step to the third of the following chord, it is best to include this as a functional chordal 7th. If it resolves another way (e.g. up by step), it might be a melodic passing tone and is therefore not functional.

Regardless of whether you include the pitch as functional, the NCTs must always match the Roman numeral. In this scenario, if you choose to include the chordal seventh in your harmony, you only need to write the proper Roman numeral and inversion figure. If, however, you decide that the chordal seventh is just a passing tone, you must label it as a non-chord tone and write only `V` for the Roman numeral.

## Embellishing Tones in Cadential Motion

**The next example contains the same harmonies from the first example, but it has an additional pitch in each measure.**
- Are the new intervals consonant or dissonant?
  - For each new pitch, do you feel it strengthens or weakens the cadence?
- Which, if any, of these "new" notes belong to the chords that you assigned in the previous example? 
  - From this, you can label what you consider to be *chord tones* and *non-chord tones*--chord tones are pitches that belong to the harmony, and non-chord tones do not.
- What do intervals of the non-chord tones have in common? 
- Finally, how would you describe the types of motion between the chord tones and non-chord tones?

{% capture ex2 %}X:2
T:Chord skips and passing/neighbor non-chord tones
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
Bc|| F/2D/2E|| d/2f/2e|| Bc|| Bc|| G/2A/2G|]
V:2 clef=bass
"M3"G,/2"M6"D,/2"P8"C,|| "m7"G,/2"P5"G,/2"M3"C,|| "P5"G,/2"m7"G,/2"M3"C,|| "+4"F,/2"M6"D,/2"m6"E,|| "P8"B,/2"M2"A,/2"P4"G,|| "M2"F,/2"M3"F,/2"m3"E,|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Conclusion

As we first begin to study non-chord tones, the most important thing to remember is what the name "non-chord tone" emphasizes. **NCTs must not belong to the chord.** The first four measures added decorations that were simply part of the V or V<sup>7</sup> chords that were already implied. Of note, you will likely hear the added `F` in measures 3 and 4 as changing the harmony from V to V<sup>7</sup>, meaning that the embellishment was still part of the harmony. 

In measure 5 however, the A on beat 2 is certainly not part of the implied V or V7 harmonies. An embellishment that does not belong to the harmony is called a *non-chord tone* (NCT), and there a variety of NCTs that can be classified by how they are approached and left. The measure 5 NCT is called a *passing tone*, because it has a passing motion, so we can define a passing tone as a non-chord tone that is *approached by step* and *left by step in the same direction*. 

The final measure also clearly contains a non-chord tone, because the `A` can not be incorporated into a V or V<sup>7</sup> chord. This is an example of a *neighbor tone*--a non-chord tone that is *approached by step* and *left by step in the opposite direction*.

A final reminder: always make sure that the pitch is not actually a chord tone! This is one of the most common mistakes for beginning analysts.

## Suspensions

**The suspension is another type of non-chord tone. Each of the measures in the next example are grouped in pairs to demonstrate how suspensions are formed. The first measure is a simple two-voice harmony from the examples above, but the next measure adds a suspension to that framework.**
- How would you define a suspension? What are the three parts of any suspension? 
- How do we determine the labels (i.e. numbers after the word *sus*)?

{% capture ex3 %}X:3
T:Suspensions
M:4/4
L:1/2
Q:1/4=80
K:C
V:1
FE| F-"sus4-3"F/2E/2|| dc|| d-"sus9-8"d/2c/2|| GE|| GE|]
V:2 clef=bass
G,C,| G,C,|| G,C,| G,C,|| D,C,|| D,-"sus2-3"D,/2C,/2|]{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Conclusion

After looking at the examples for suspensions, it may seem that a *suspension* is a pitch that is tied over from the previous chord. This is on the right track, but defining a suspension requires considerably more information. 

With this in mind, a suspension must have all three of the following qualities to be considered a suspension:
- It must start as a *chord tone* in the previous chord and then remain unchanged into the new chord.
- It must create a *non-chord tone* at the beginning of the new chord.
- It must then resolve down by step to a chord tone of the new chord.

Of note, it is a common misconception among students that a suspension is only present if you see a *tied* note. This is not true; the tone can be re-articulated.

These three rules directly relate to the terminology that we use to describe the three basic components of a suspension:
- *Preparation* - A chord tone that occurs as part of a chord before the suspension.
- *Suspension* - A non-chord tone that occurs at the moment that all other voices change to the new chord. This tone must be carried over from the previous chord, but it can be re-articulated.
- *Resolution* - The non-chord tone then resolves downward by step to a chord tone.

There are many common mistakes when creating or analyzing suspensions:
- There must be two chords. You cannot have a suspension with only one chord.
- It must resolve downward. If it resolves upward, it is a different kind of non-chord tone.
- It must resolve by step.

#### Labeling suspensions

Once you have familiarized yourself with these three concepts, review the examples above to ensure that you understand the form of a suspension. While doing this, you will notice that each of the suspensions is labeled with a pair of numbers in addition to the word *sus*.

Because suspensions can take many forms, we apply intervallic labels. When the suspension is in an upper voice, we always label the intervals of the suspension and its resolution against the *bass* meaning that the intervals will move from large to small (e.g. 4-3, 7-6, 9-8, etc.). When a suspended note is in the bass voice, however, we label the intervals against the most dissonant interval which means that the intervals will move from small to large (e.g. 2-3). This is because suspensions always resolve *down* by step. When you measure a downward resolution in an upper voice against a lower voice, the intervals get smaller as the upper voice moves *closer* to the bass. When you measure a downward resolution against a higher voice, the intervals get larger as the bass moves *away* from the upper voice.

Of note, because we use the most dissonant voice to label suspensions in the bass, you will use the "2-3" label in the vast majority of this type of suspension. These intervals will be present for suspensions resolving to either the root or chordal third as long as the chord is complete. You are unlikely to encounter a suspension above a chordal fifth in the bass because of the usage rules of second inversion chords, and a suspension above the chordal seventh would just be the root of the chord--meaning that it is not a non-chord tone.

The most common suspensions are the 4-3, 7-6, 9-8 (2-1), and 2-3 suspensions, but others can and do occur regularly. 
