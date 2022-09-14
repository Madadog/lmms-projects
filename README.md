# LMMS Projects
Just a couple [LMMS](https://github.com/LMMS/lmms) projects I made.

Note:
* Some projects require Nightly LMMS (1.3.0-alpha) to load completely
* Some projects are unfinished

Here's some quick sample projects that work on a fresh LMMS install (no external samples or soundfonts required):
* [tecchnoV2imprived.mmpz](/projects/unorganised/tecchnoV2imprived.mmpz)
* [wondrouspoppingcorn.mmpz](/projects/snippets/wonderouspoppingcorn.mmpz)
* [sidechainingexists-001-V2.mmpz](/projects/unorganised/sidechainingexists-001-V2.mmpz)
* [rhapsony.mmpz](/projects/unorganised/rhapsony.mmpz)

##### Table of Contents  
[Project Structure](#project-structure)

[Soundfonts and Samples](#soundfonts-and-samples)

[Drums](#drums)

[TODO](#todo)

[License](#license)

# Project Structure
* [snippets](/projects/snippets/) is where I dump any new projects that don't fit into other categories.
* [games](/projects/games/), [dreams](/projects/dreams/), [fivehundred](/projects/fivehundred/) and [twistending](/projects/twistending/) are all for game music.
* [covers](/projects/covers/) contains extra fun projects.
* [unorganised](/projects/unorganised) is where everything else went (mostly stuff from before 2021).

# Soundfonts and Samples
While some projects will work out of the box (such as [`whee-riff-man.mmpz`](/projects/unorganised/whee-riff-man.mmpz)), some other projects will require you to download some of these soundfonts and put them in your `lmms/samples/soundfonts/` folder:

Soundfonts (From most important to least)|Info||
|---|---|---|
[SGM V2.01](https://archive.org/details/SGM-V2.01)|Used all over the place.|
[Earthbound Soundfont](http://www.williamkage.com/snes_soundfonts/earthbound_soundfont.zip)|Used all over the place, sporadically.|
[PC51d](https://archive.org/download/free-soundfonts-sf2-2019-04/PC51d.sf2)|Used by 10 projects?|
[GeneralUser GS](https://archive.org/download/free-soundfonts-sf2-2019-04/GeneralUser%20GS%20v1.471.sf2)|Used by like 1 project, but still more important than the soundfonts below.|
[Chrono Trigger Soundfont](https://musical-artifacts.com/artifacts/194/ctsf2.zip)|Used by like ~5 projects|
[Ultimate Megadrive Soundfont](https://musical-artifacts.com/artifacts/24/The_Ultimate_Megadrive_Soundfont.zip)|Used by like ~3 projects|
[THInst](https://musical-artifacts.com/artifacts/1327/THCollection.zip)|1 or 2 projects???|
[Yet Another Earthbound Soundfont](https://musical-artifacts.com/artifacts/665/Earthbound_NEW.sf2)|Yes, this is different from the other soundfont. Learn from my mistakes: Manage your samples.|
Possibly a couple more I forgot|World Wide Web|

## Drums
The drumkits must be extracted and placed under `lmms/samples/--/drumkits`
Sample Source|Note||
---|---|---
[99kits](http://slackermedia.info/sprints/multimediaSprint_v2/99_hydrogenDrumkits.tar) ([alternate source](https://musical-artifacts.com/artifacts?q=Klaatu))|More [info](https://data.musical-artifacts.com/99kits/) about the origin and licenses of this kit.|
Any other missing samples|Try looking on [youtube](youtube.com).|

Also there are some Carla instances. They don't work for me either.

I don't think there are any Vestige instances / plugins, but if there are, just replace them with the default TripleOscillator. Enjoy the clipping.

# TODO
* Upload renders
* Add Ardour projects? (Blocking on Very Large File Size)
    * Use Ardour's archive feature??? 
        * Pros: Soundfonts are bundled.
        * Cons: Soundfonts are bundled. ~200mb per Ardour project. Does Github have a storage limit?
* Add missing LMMS projects

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.