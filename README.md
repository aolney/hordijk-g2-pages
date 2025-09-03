# hordijk-g2-pages

This repo archives one of Rob Hordijk's websites and converts the html to PDF.


## Process

Saved embedded frames w/o navigation manually from:

https://web.archive.org/web/20220630033545/https://rhordijk.home.xs4all.nl/G2Pages/index.htm

Converted to pdf with:

pandoc Introduction.html 'Basic principles of sound synthesis.html' 'Patchsheets and schematics.html' 'Introduction to the G2 system.html'  SignalTypes.htm  Signallevels.htm  Switches.htm  Mixing.html  EventsAndLogicSignals.htm 'Sound sources.html' 'Feedforward and feedback.html'  Filters.html 'Resonant filters.html' 'Noise, randomness and chaos.html' 'Dynamic processing of signal levels.html' 'Waveshaping and distortion.html' 'Harmonic distortion.html' 'Frequency modulation synthesis.html' 'Capturing and looping audio.html' 'Creating evolving patterns.html' -o hordijk-g2.pdf -t html --metadata=title:"Hordijk G2 Pages" -V papersize:letter
