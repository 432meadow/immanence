# infinite carillon

a process-music bell instrument that runs in the browser and never ends.

**play it: https://432meadow.github.io/infinite-carillon/**

one html file. every sound is synthesized as it plays — modal bell physics
(tubular chimes with the church-bell partial set, half-damped handbells),
a formant choir, strings, a bass reed — through a generated convolution hall.
nothing is sampled, nothing repeats exactly.

the music is built from steve reich's processes, wearing bells:

- **bloom** performs rhythmic construction by hand — the cell gains and loses
  its notes in build order
- **canon offset** slides the second bell choir through its phase
  relationships (piano phase, between two handbell choirs)
- the **choir** sings only the resultant — the melody the interlock already
  implies, never stated by a lead
- **[ ∞ drift ]** lets the instrument wander on its own: blooming, recession,
  and — rarely — a cadence with the piece's one d♯

no dependencies, no build, no server. open `index.html` or serve it from
anywhere static.
