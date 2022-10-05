---
layout: chapter
title: Lesson 7b - Performing a Harmonic Analysis
abc: true
---

Now that we understand how circle-of-fifths progressions within a key create a basic harmonic "outline", we can use that pattern to begin analyzing harmony. The framework of these progressions can be used to organize any piece of music in this tradition and allows us to ask the two fundamental questions of all harmonic analysis: 
- How are expectations created in the music?
- Which pitches are functional in creating these expectations?

Regardless of the complexity or era of a composition, if a theorist can answer these questions about a piece, they can analyze the qualities that define that style of composition. 

As we progress through the lesson below, we will begin to develop our process for analyzing a piece of tonal music. Students often think that "analyzing" a piece of music simply involves identifying and labeling each chord, but if that were the case, we should just use leadsheet symbols--they are flexible and do not require you to know anything more than pitches that are present.  Roman numeral analysis provides a way for us to create *context*, because our ultimate goal in analyzing music is *to better understand how a listener perceives the music*. While the first step is identifying the structure of the harmony, we must move beyond that in order to make ourselves better performers, educators, and composers. As you work through the examples, make a list of all the questions and decisions that you encounter. 

## A first attempt at harmonic analysis

Study the following chorale, and provide:
- a leadsheet symbol above every chord
- Roman numeral and inversion figure below every new harmony. As you go through this process, keep track of the questions that you solve as well as what makes this difficult. Start by looking at the big picture, and do not get bogged down in trying to figure out every pitch and chord at first glance. If you get stuck, keep moving and return to the difficult sections after you have a feel for the piece as a whole. You should also consider starting with leadsheet notation until you are confident of the key of the piece; you can then return to add Roman numerals once you have more context.

{% capture ex1 %}X:1
T:Brahms-inspired chorale
T:Altered from “Die Wollust in den Maien”, WoO 34 no. 11
M:4/4
L:1/4
Q:1/4=80
K:G
V:1
[G/2D][B/2G]| [dG] [eG] [dF] [cF]| [BG] [AF] [BG] [dG]| [c2E] [A2F]| [G4]|]
V:2 clef=bass
[G,/2B,][G,/2D,]| [G,B,,] [A,C,] [A,D,] [DD,]| [DG,] [DD,] [DG,] [DB,,]| [C2C,] [C2D,]| [B,4G,,]|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Conclusions

 To do this, there are three primary questions that must be answered in a harmonic analysis:
- What is the harmonic rhythm? (i.e. How often does the harmony change?)
- Which pitches are chord tones and non-chord tones?
- Which pitches, if any, are omitted but implied by the context?

### Harmonic rhythm

We will tackle the second and third questions in the example below, but before you can begin to analyze the chords within a piece, you need to figure out how often the chords change. This concept is called *harmonic rhythm*. It is different for every piece; sometimes it will be every beat as in the chorale above, but other pieces will have irregular patterns and/or many measures before new harmonies.

Determining harmonic rhythm is intuitively obvious to most musicians while listening, but can be difficult to illustrate when looking only at the music. This is often a chicken-or-the-egg question: you need to know how often the chord changes to determine which pitches to include in the chord, but you also need to look at which pitches create chords to figure out how often the chord changes. Chorales are an easy place to start, because most often, they change chords in a consistent rhythm--in this case, every beat--and this creates an easy-to-see visual cue as each chord is stacked vertically and mostly homorhythmic. For more complicated textures, studying melodic patterns and bass-lines is often enough to provide enough context for an educated guess. Bass-lines in particular will often sustain pitches and/or outline chords until the harmony changes, and this gives a clear indicator of probable harmonic rhythm. This becomes much easier as the student gains experience.

{% capture ex2 %}X:2
T:Brahms-inspired chorale
T:Altered from “Die Wollust in den Maien”, WoO 34 no. 11
M:4/4
L:1/4
Q:1/4=80
K:G
V:1
[G/2D][B/2G]| [dG] [eG] [dF] [cF]| [BG] [AF] [BG] [dG]| [c2E] [A2F]| [G4]|]
V:2 clef=bass
[G,/2B,][G,/2D,]| [G,B,,] [A,C,] [A,D,] [DD,]| [DG,] [DD,] [DG,] [DB,,]| [C2C,] [C2D,]| [B,4G,,]|]
w:I (6/4) (6) ii6/5 V (7) I V I (6) IV V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Omitted/implied chord tones

The chorale has a few incomplete chords, such as the downbeat of measure 3 and the downbeat of measure 4. If we do not have a full chord present, how do we determine the implied chord that a listener is likely to hear?

Let's examine the downbeat of measure 3. First, ask yourself what are all of the possible diatonic chords in the key of G major that contain both C and E? Those pitches would be the:
- root and third of the IV chord
- third and fifth of the ii chord
- fifth and seventh of the vii<sup>&oslash;7</sup>

With these options, we can look at which pitches are prioritized to see which of our three possibilities is most likely. We have already discussed that the root is the most likely chord tone to be doubled, and in this case the C is tripled. This strongly implies that the C is the root of the chord which would make this a IV chord. 

To double check that assumption, we can refer to the standard chord progression chart that we built in the last topic (and copied below) against the *function* of a possible IV chord in the context of chords on either side of it. We know that a pre-dominant chord would fit well between the tonic and dominant chords in this spot, because a I chord can resolve to any chord, and a IV chord moves well to a V chord.

| (*unnamed*) | (*unnamed*) | pre-dominant | dominant | tonic |
--- | --- | --- | --- | --- |
| iii | vi | ii | V | I |
| | | IV | vii<sup>o</sup> | |

By employing a knowledge of standard progressions, a theorist can look at a given harmony and decide which pitches support a harmonic progression that is *likely* to be heard by a listener, even if those tones are not present.

## Embellishments

One of the most difficult issues to tackle in harmonic analysis is determining *which pitches are functional*. 
- Which pitches define how the listener "hears" the music?
- Which pitches could be removed without changing the basic effect?
- Which pitches are added solely to provide variety?

**Analyze the following embellished first phrase of the chorale from above. Which notes are not necessary for the harmonic function? How would you describe their motion? If you are struggling to determine whether it belongs or not, try referring to your the harmonic outline that you built in the previous topic [Unit 7a]({{ site.baseurl }}/07-harmonic-functions/a1-diaprogcirclefifths.html). Does the voice-leading--i.e. how each chordal member resolves--work with the rules that you established in Unit 7a if you do not have a non-chord tone?**

{% capture ex3 %}X:3
T:Embellished version of the chorale
M:4/4
L:1/4
Q:1/4=80
K:G
V:1
[G/2D][B/2G]| [dG] [eG] [dF] [cF]| [BG] [AF] [BG] [dG]| [c2E] [A2F]| [G4]|]
V:2 clef=bass
[G,/2B,][G,/2D,]| [G,B,,] [A,C,] [A,D,] [DD,]| [DG,] [DD,] [DG,] [DB,,]| [C2C,] [C2D,]| [B,4G,,]|]
w:I (6/4) (6) ii6/5 V (7) I V I (6) IV V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Conclusion

The essential pitches of any harmony are those that if removed, would noticeably alter the way the listener hears the harmony. As you attempted to analyze this decorated melody, were you able to see and hear the basic framework from the first phrase of the basic version that you first analyzed? If so, it should have allowed you to figure out both the harmonic rhythm as well as which pitches were decorative. 

The harmonic rhythm stayed the same; one chord per quarter note, even though the voices were often filled double the amount of notes. 

From there, you must consider a number of factors to determine which notes are embellishments. 
- Which pitches are on the strong beats? 
- Are any pitches repeated? 
- Is one pitch more dissonant against the other chord tones? 
Differentiating between chord tones and non-chord tones is the key to deciding a chord's function.

## Before moving forward...

As you answered each of these questions, you began understanding how harmony *functions*. Even without much guidance, you can use your knowledge of musical fundamentals--intervals, chords, melodic lines, Roman numeral labeling, etc.--to create a sketch of the harmonic underpinnings of this chorale.

We use chorales to begin studying analysis because of the vertical nature of the writing. Every chord in this composition is aligned to where it can be easily parsed by sight, and almost every tone is functional. As you look at other musical styles, try to reduce the music down to a simpler texture--one that resembles a chorale voicing--if you cannot answer the basic questions of finding harmonic rhythm and chord tones.
