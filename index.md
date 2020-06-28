With Groove Modeler you can create grooves with consistent rhythmic feel in programmed music, for the time being in music created with [Sonic Pi](https://github.com/samaaron/sonic-pi). This is done by manipulating parameters relevant to the creation of groove like how laid back an instrument is or how much it swings.

Just download and install [Sonic Pi](https://github.com/samaaron/sonic-pi) (it's free!), grab some code from the [Groove Modeler GitHub page](https://github.com/fritzfeger/groove-modeler), paste into Sonic Pi, hit run and enjoy.

* [The Theory of Groove][The Theory of Groove]
* [Modeling Groove With Sonic Pi][Modeling Groove With Sonic Pi]

## The Theory of Groove

There is a lot of mystery around the pheonomenon of groove, see e.g. the [Wikipedia page on groove](https://en.wikipedia.org/wiki/Groove_(music)). No matter how culturally coined, dependent from learning the perception of groove, or how important vor communication and participation, it seems clear that it is caused completely un-esoteric pyhsical properties of rhythmic sounds. There is also some, though not much, great quantitative research, e.g. [lucerne groove research library](https://www.grooveresearch.ch/index.php?browse) on groove. 

For the Groove Modeling project, it is crucial to identify the variables which determine how a drum pattern or a whole piece of music is perceived rhytmically, which feel it "has", i.e. which sensation it evokes.

What follows is a hypothesis about important variables - please raise an issue on [this website's GitHub source page](https://github.com/fritzfeger/groove-modeler-website) if you think something is wrong or missing!

### Timing

1. swing - how soft or hard, i.e. how much is the first of two eigth or sixteenth notes is prolonged (and the following one shortened)?
1. laid back - how much behind the beat (or ahead of the beat!) does an instrument play?
1. tightness/looseness - how much does the timing vary, from machine-like precision to a "drunk" feel? Question: would "drunk" feel be best captured by randomness, or is there a system behind loose timing of able players which makes it distinguishable from plain bad timing of beginners / weaker players?
1. togetherness/apartness - how much do these three rhythmic variables differ between the different instruments?
1. articulation (1/2) - how short or long are notes played? When exactly does a note end?

### Dynamics

1. velocity - how much harder, how much softer some notes are played than others? How does this articulation (2/) relate to something like intensity?
1. loudness - how much louder, how much lower some notes or whole voices are amplified than others? How does the mix influence rhythmic feel?

## Modeling Groove With Sonic Pi

At this place a documentation about [Groove Modeler](https://github.com/fritzfeger/groove-modeler) is about to happen...
