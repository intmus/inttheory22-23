---
layout: chapter
title: Lesson 10c - The Circle-of-Fifths Progression in Four-part Harmony
abc: true
---

## Developing Progressions Based on Voice-leading

In the previous topic, we showed that by studying the voice-leading of a simple V (or V<sup>7</sup>) to I progression, you can propose rules that *do not* rely on scale degrees, and yet explain the voice-leading between the two chords. Specifically:
- For chords that have roots separated by a P5:
    - The *seventh* of the first chord resolves to the *third* of the second chord.
    - the *third* of the first chord resolves to the *root* of the second chord.
    - If both chords are in root position, the bass voice moves from the *root* of the first chord to the *root* of the next chord.

This is the beginning of a *circle-of-fifths progression*: a progression in which each chord root follows the circle of fifths. Using these new voice-leading rules in combination with a few simple voicing guidelines, you should be able to create a simple four-part harmony in a circle-of-fifths progression. 

## Brief introduction to voicing a four-part progression

Voice-leading rules govern the horizontal axis of music by shaping the melodies within each voice. Before we can combine multiple voices, though, we need to have a basic framework to keep our four voices sounding together. I have listed four simple rules below, but we will explore these in more detail in [Unit 10a]({{ site.baseurl }}/10-part-writing/a1-voiceleadingerrors.html).

A basic four-part texture has four voices: the soprano (highest), alto (second highest), tenor (third highest), and bass (lowest). The soprano and alto voices are best notated in treble clef, and the the tenor and bass voices are written in the bass clef. 

- Range
    - Use the treble and bass staves as your guide. 
        - Your soprano should sit between the bottom line of the treble clef staff to a ledger line above the treble clef staff.
        - The alto voice can go as low two ledger lines below the treble clef staff and up to the top of the treble clef.
        - The tenor voice will typically range from the middle of the bass clef staff to three ledger lines above the bass clef staff.
        - The bass voice will range from the top of the bass clef staff to a ledger line below the bass clef staff.
- Spacing
    - Your upper three voices should never have more than an octave between adjacent voices. The soprano and tenor *can* be more than an octave apart though.
    - Your bass can be as more than an octave from the tenor. 
- Doubling
    - If you need to double a pitch, you can double (or even triple!) the root of most chords, and you should generally avoid doubling the chordal third and seventh. You can omit the chordal fifth if necessary, but the other pitches cannot be omitted entirely. 
- Voice-crossing
     - In your early attempts at part-writing, do not allow your voices to cross.

## Voicing a four-part progression

Let us return to the progressions from the last topic. We can now mix our voicing guidelines with our derived voice-leading rules to create a variety of progressions. 

There are two likely voicings for creating this next chord in the progression:

{% capture ex7 %}X:7
T:Two possible voicings for a ii chord
M:4/4
L:1/2
Q:1/4=100
K:C
V:1
[Fd]| [BG]| [c2G2]|| [FA]| [BG]| [c2G2]|]
V:2 clef=bass
[D,A,]| [G,D]| [C,2E2]|| [D,D]| [G,D]| [C,2E2]|]
w:C:ii V I ii V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

Some will prefer the sound of the first voicing, probably because they find the melodic shape in the soprano more interesting. Unfortunately, this voicing creates multiple issues. Not only are the parts more difficult to sing, particularly for the tenor voice, but the parallel perfect 5ths between the tenor and bass voices means that the tenor voice will meld into the bass voice and lose its independence. This doesn't sound too odd in a short excerpt like this, but in a longer passage, having parallel perfect 5ths will change the texture for brief moments in a noticeable way.

The second progression has less melodic variety, but it provides the smoothest, easiest voice-leading for each part with no voice-leading errors. If you add two more chords to the progression by following the circle-of-fifths progression we are creating, you should be able to add vi and then iii without much issue by following the pattern.

From this, we can demonstrate the process by which voice-leading creates one of the most fundamental progressions of all diatonic harmony, the circle-of-fifths progression.
  
{% capture ex8 %}X:8
T:A standard circle-of-fifths progression
M:4/4
L:1
K:C
V:1
[EG]| [EA]| [FA]| [BG]| [cG]|]
V:2 clef=bass
[E,B,]| [A,,C]| [D,D]| [G,,D]| [C,E]|]
w:C:iii vi ii V I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}