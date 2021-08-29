---
layout: chapter
title: Lesson 2a - Diatonic Scales
abc: true
---

"Organized sound" is a common way to define music in its simplest form, and we can use this definition as a launching point for discussing pitch collections and scales. If we accept that music is "organized sound", then the methods used to organize it will define all aspects of the composition. 

## Tonal music

For this course, the majority of music that we'll study will be *tonal* music, meaning music that is organized around a central pitch called the *tonic*.

When we build a tonality around a tonic pitch, every pitch in the tonality can be found by measuring the distance, or *interval*, between it and the tonic. It is these intervallic relationships that differentiate one pitch collection from another, and we can categorize each pitch collection by studying their commonalities and differences. 

In Unit 1, we discussed moveable-do solfege as a way for us to look at the relationships between a group of pitches that are organized around a central pitch. In doing so, we created a *scale*, even though we did not define it as such. Whenever you group any number of pitches, you create a *collection*. However, when you order a collection by the frequency of each pitch--or more simply stated, arranging pitches from high to low--you create a scale. So a scale is *a collection of pitches that are organized in an ascending or descending form*, and consequently create a fixed intervallic pattern. A scale can encompass any tuning system or style of composition.

Certain scales are at the core of all common practice harmony, and as a music student, you are likely already familiar with these: *major, minor, modal, pentatonic, and chromatic*. Below, we discuss the diatonic scales (i.e. major and minor) and Topic 2b details the others. We will explore even more types of scales in Unit 22.

### Diatonic music

For the majority of this course, we will be discussing *diatonic* music, which is a subset of tonal music. The term *diatonic* can have a variety of meanings depending on context, but for this course, we will be using this term to refer to music that:
- is built around a tonic pitch
- includes all seven pitch names (i.e. letters)
- creates harmonic tension and release using tonic and dominant harmonies (more on this in Unit 6)

Put simply, our musical hierarchy is:

- *Music* - organized sound
    - *Tonal music* - music organized around a central pitch
        - *Diatonic music* - tonal music that uses all seven letter names only once and follows a specific order of intervals
            - *Diatonic scale* - a ascending (or descending) ordering of all seven pitches in a diatonic pitch collection, contained within one octave

## Goals for this topic:

As you listen through all of the examples below, you should:
- describe the pattern that determines the pitches in the *major* scale and all forms of *minor* scales regardless of starting pitch
    - You can think of this question as how to describe the scale without using note names or solfege.
- figure out why *natural, melodic,* and *harmonic* minors are named as they are
- memorize the names for each scale degree (i.e. tonic) as well as the corresponding numeral notation
    - how the names for each scale degree are derived (e.g. How are dominant and subdominant scale degrees related?)
- incorporate the Latin spelling for every solfege

### Important notes

The following examples demonstrate how the tune of *Happy Birthday* would be written if only using the notes from a particular scale. In most examples, scale degrees are numbered below each pitch as well as solfege using movable "do". Additionally, scale degrees are named above the pitches for the examples in major and melodic minor. When determining your pitch collections, pay particular attention to the differences of the sixth and seventh scale degrees.

### Major

(Because ABC notation does not support scale degrees, I have placed a `^` in front of each scale degree. In normal scale degree notation, the `^` would appear *above* the numeral for each scale degree, not before it.)

{% capture ex1 %}X: 1
%%staffsep 100%
T:Happy Birthday in G major
M:3/4
L:1/4
Q:1/4=90
K:G
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do ti sol sol la sol re do sol sol
d "mediant"B G| F E "subdominant"c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol mi do ti la fa fa mi do re do{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Minor scales

There are three forms of the minor scale, and each has a specific role. As you listen to these three melodies, only one of them will sound as if it has no surprising pitches. Once you have found the example that doesn't have a "surprise moment, consider the name of the mode. Does it give you some insight into why it sounds best playing this melody?

### Natural minor

{% capture ex2 %}X:2
%%staffsep 75%
T:Happy Birthday in G natural minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do te sol sol le sol re do sol sol
d B G| F E c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do te le fa fa me do re do{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

### Harmonic minor

{% capture ex3 %}X:3
%%staffsep 75%
T:Happy Birthday in E harmonic minor
T:using the relative minor to G major
M:3/4
L:1/4
Q:1/4=90
K:G
B,/2>B,/2| C B, E| ^D2 B,/2>B,/2| C B, F| E2 B,/2>B,/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
B G E| ^D C A/2>A/2| G E F| E2|]
w:^5 ^3 ^1 ^#7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do ti le fa fa me do re do{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

### Melodic minor

When first determining your basic rules for melodic minor, you may want to choose to ignore 'le' in measure 6. That pitch serves a harmonic goal as part of a *cadence*, rather than a melodic function.

{% capture ex4 %}X:4
%%staffsep 100%
T:Happy Birthday in G melodic minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
"dominant"D/2>D/2| "submediant"E D "tonic"G| "leading tone"^F2 D/2>D/2| E D "supertonic"A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d "mediant"B G| "subtonic"F HE "subdominant"c/2>c/2| B G A/4D/4"raised submediant"=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

### Conclusions

### Intervallic patterns

In diatonic music, each scale has seven pitches. All seven letters can be used once, and no letter can be used more than once. This creates a series of 2nds that create our scale.

Major scales have an intervallic pattern of:

*(W = whole-step, H = half-step, A = augmented 2nd)*

W - W - H - W - W - W - H

Natural minor scales have an intervallic pattern of:

W - H - W - W - H - W - W

Harmonic minor scales have an intervallic pattern of:

W - H - W - W - H - A - H

Melodic minor scales have both an ascending and descending form. The intervallic pattern for descending melodic minor is identical to a descending natural minor scale. (The necessity of this seemingly redundant pattern is discussed below under "Why we *need* three minor scales".) The intervallic pattern for 4ascending melodic minor is:

W - H - W - W - W - W - H

### Labeling scale degrees

When discussing scales, it is helpful to have a method that refers to pitches without referencing a specific key. For example, the first "Happy Birthday" example on the previous page is written in G major, but there are eleven other tonics around which we could structure that melody's intervallic structure. In order to reference the interval pattern rather than the actual pitches, we use *scale degrees*. 

One common way to communicate pitches of the scale is to use scale degree numbers. We denote these by placing a caret `^` above the scale degree number. For example, the pitch that is a fifth above the tonic would be called fifth scale degree and would be written as `^5`, although the caret would be above the numeral, not to the side.

A second common way to describe scale degrees is to use *solfege syllables*. In this system, each scale degree is assigned a single-syllable Latin word, and this can be helpful when sight-singing. The chart below shows all seven base solfege syllables and how each can be altered for raised and lowered pitches. If a solfege symbol is marked as "N/A", this alteration is non-functional in tonal harmony.

Scale degree | Solfege syllable | Raised | Lowered
 --- | --- | --- | ---
 ^1 | do | di | N/A
 ^2 | re | ri | ra
 ^3 | mi | N/A | me
 ^4 | fa | fi | N/A
 ^5 | sol | si | se
 ^6 | la | li | le
 ^7 | ti | N/A | te

A final method for labeling scale degrees is to use the names of the functions of each pitch as it relates to tonic. These names evolved over centuries of theory treatises from scholars such as Rameau, Riemann, Secther, Schoenberg, and Schenker. We will not use these names often in this course, but knowing them can help understand harmonic function when that concept is introduced.

They are:
1. Tonic 
2. Supertonic
3. Mediant
4. Subdominant
5. Dominant
6. Submediant
7. Leading-tone/Subtonic

Notice the relationship between any term and its counterpart as denoted by the prefix `sub`. The dominant is a fifth above the tonic; the subdominant is a fifth below the tonic. The mediant is a third above the tonic; the submediant is a third below the tonic. 

The supertonic is a 2nd above the tonic, but because of the importance and function of the leading-tone, its scale degree name changes to reflect the difference between a major 2nd below the tonic versus the minor 2nd below the tonic. If the 2nd below the tonic is a whole-step, we call it the subtonic. If the 2nd below the tonic is a half-step, we call it the leading tone. This is true in both major and minor.

### Tonal centers and modes

We consider a key to be defined by its tonic, so if two scales share a tonic, they are considered to be the same key but different *modes* of each other. For example, G major and G minor are the same key, but different modes. This is confusing for many students, because they have always associated their concept of a key with its key signature.

### Why we need three minor scales

Most intermediate music students learn various forms of the minor scale, but they do not often give much thought as to why. 

Natural minor is the most obvious. It uses all of the naturally occurring notes from the key signature.

We will discuss the role of harmonic minor more when we begin analyzing chords, but as the name implies, it is a form of minor that emphasizes the most common scale degrees from a harmonic standpoint.

The "Happy Birthday" examples above are perfect for exploring the importance of melodic minor. By keeping the interval sizes from "Happy Birthday" but changing the pitches to fit the various forms of minor, you can hear three similar but distinct versions of "Happy Birthday". When a student first listens to the natural minor version, they often feel that the first `te` does not work with the rest of the tune, and in the harmonic minor version, the augmented 2nd that occurs between `ti` and `le` is jarring. On the other hand, the melodic minor version sounds entirely correct (although some may not like the darker tone of a traditionally "happy" song.)

This easily highlights the role of melodic minor -- to create melodies in minor. By having both an ascending and descending version, we can resolve the sixth and seventh scale degrees upward and downward by relying on the tendency of those scale degrees. `Te` and `le` both have a strong downward pull and almost always resolve downward. `Ti` and `la` both have a strong upward pull and tend to resolve upward. These are general rules and are occasionally broken, but I encourage you to play with the example below to hear how "strange" the piece becomes if you do not allow the sixth and seventh scale degrees to account for their resolutions. (Try putting `la` in for every sixth scale degree for the most obviously jarring version.)

{% capture ex8 %}X:8
%%staffsep 100%
T:Happy Birthday in G melodic minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| ^F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d B G| F HE c/2>c/2| B G A/4D/4=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}