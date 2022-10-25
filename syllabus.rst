========
Syllabus
========

Class: Digital Synthesis Techniques

Term: Summer 2023

Instructor: Fede Camara Halac

----

04.04.23  `week1 <week1>`_ - Pure Data Basics
    Intro to the class. Installing pd. Configuring Pd. Making and saving a patch. The 5 objects in pd: object, message, number, symbol, comment.
    The sinusoid.
    Order of execution. Hot and Cold inlets.
    Simple math exercises.
    Pd objects:  ``unpack``, ``trigger``, ``+``, ``-``, ``*``, ``/``, ``print``

----

11.04.23 `week2 <week2>`_ - The Digital Signal
    The sample. Sample rate. Nyquist. Aliasing. 
    Differences between audio and control signals.
    Pd objects: ``osc~``, ``dac~``,  ``adc~``

----

18.04.23 `week3 <week3>`_ - Frequency and Amplitude
    Frequency and amplitude control.
    Pitch-frequency relation: MIDI / Herz (Hz)
    Dynamics-amplitude relation: Decibels (dB) / RMS amplitude
    The famous "click" sound: signal discontinuities.
    Pd objects: ``line~``, ``line``, ``mtof``, ``ftom``, ``dbtorms``, ``rmstodb``

----

25.04.23 `week4 <week4>`_ - Wavetable Synthesis
    classic waveshapes: sawtooth,  cosine, triangle, square
    Reading from / writing to arrays
    Pd objects: ``tabosc4~``, ``phasor~``, ``clip~``, ``abs~``, ``wrap~``, ``array``

----

02.05.23 `week5 <week5>`_ - Sequencing and Envelopes
    How to make a counter.
    How to make a sequencer.
    ADSR envelopes
    Subpatches and abstractions
    Pd objects: ``metro``, ``sel``, ``float``, ``bng``, ``tgl``, ``sliders``, ``del``

----

09.05.23 `week6 <week6>`_ - Filters and Sustractive Synthesis
    Different configurations: series, parallel, combined
    Substractive synthesis basics: VCF
    *Preparing for midterm*
    Pd objects: ``hp~``, ``lop~``, ``bp~``, ``noise~``, ``vcf~``

----

16.05.23 `week7 <week7>`_ - Interfacing with MIDI
    *Preparing for midterm*
    B.Y.O.C. (bring your own controller if you have one)
    Connecting and using a MIDI controller/keyboard
    Voice management and polyphony
    Pd objects: ``send``, ``receive``, ``notein``, ``noteout``, ``makenote``, ``clone``, ``poly``

----

23.05.23 `week8 <week8>`_- Class midterm presentations
    Midterm: make a sustractive synthesizer

----

30.05.23 `week9 <week9>`_ - Granular Synthesis
    Loading wav files
    Reading wav files
    Writing wav files
    Basic granular synthesis
    Pd objects: ``soundfiler``, ``tabread4~``, ``tabplay~``

----

06.06.23  `week10 <week10>`_ - More Synthesis Techniques
    Classic synthesis spectra: Amplitud modulation. Frecuency modulation (FM synthesis). Phase modulation. Ring modulation
    Waveshaping. Chebychev polynomials
    Pd objects: ``cos~``

----

13.06.23 `week11 <week11>`_ - Delay Networks
    Recirculating Delay Networks. Variable delays.
    Algoritmo Karplus-Strong. Pitch shifting
    Echo and Reverb
    Pd objects: ``rev3~``, ``delwrite~``, ``delread~``, ``delread4~``

----

20.06.23 `week12 <week12>`_ - Signal Analysis
    Basic Fourier Transform concepts. Signal Analysis.
    Spectrum. Partials. Amplitude analysis.
    Pd objects: ``env~``, ``sigmund~``, ``bonk~``, ``rifft~``, ``rfft~``

----

27.06.23 `week13 <week13>`_ - Guest presentation
    TBD

----

04.07.23 `week14 <week14>`_ - Noises and space
    Randomness. Probability. Walks and Markov Chains.
    Stereo panning. Equal-amplitude panning. Point-source localization.
    Quadraphonic panning. Multichannel signals.
    Pd objects: ``noise~``, ``mod``, ``random``, ``moses``

----

11.07.23 `week15 <week15>`_ - Final projects presentation
    Final project: **design and make a sonic experience using Pd and some techniques shown in this seminar**

    This is our last meeting of the semester, so let's have some vegan gluten-free pizza and enjoy each other's sonic explorations!

----
