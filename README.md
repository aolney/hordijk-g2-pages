# hordijk-g2-pages

This repo archives a website created by Rob Hordijk ([1958-2022](https://musictech.com/news/industry/rob-hordijk-dutch-creator-of-the-benjolin-blippoo-box-dies-aged-64-synth-modular/)) and converts the website html to PDF.

The html archived here and the process below can be followed for converting the website to other formats using [pandoc](https://pandoc.org/).


## Process

Saved embedded frames w/o navigation manually from:

https://web.archive.org/web/20220630033545/https://rhordijk.home.xs4all.nl/G2Pages/index.htm

Converted to pdf with:

pandoc Introduction.html 'Basic principles of sound synthesis.html' 'Patchsheets and schematics.html' 'Introduction to the G2 system.html'  SignalTypes.htm  Signallevels.htm  Switches.htm  Mixing.html  EventsAndLogicSignals.htm 'Sound sources.html' 'Feedforward and feedback.html'  Filters.html 'Resonant filters.html' 'Noise, randomness and chaos.html' 'Dynamic processing of signal levels.html' 'Waveshaping and distortion.html' 'Harmonic distortion.html' 'Frequency modulation synthesis.html' 'Capturing and looping audio.html' 'Creating evolving patterns.html' -o hordijk-g2.pdf -t html --metadata=title:"Hordijk G2 Pages" -V papersize:letter
