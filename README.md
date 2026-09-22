# Celine-emy-Circuits
<img width="640" height="480" alt="Celine-emy-Circuits" src="https://github.com/user-attachments/assets/80228fcd-2a35-45cc-848f-76ebfc74ec05" />

Schematic files drawn for use with [Céline]( https://celine-audio.github.io/CelineWebsite/ ), developed by Céline Audio ([@Celine-audio]( https://github.com/Celine-audio )).

# List of Circuits
Circuits of various guitar/bass amps and FX pedals. This list may expand over time.

 - ## Pedals & Effectors
   - Ao Drive (Boss BD-1 Blues Driver Style Op-Amp Clone)
     - High gain with discrete JFET transistors does not seem to work. They are replaced with NE5532 op-amps instead.
   - Boss DS-1 Distortion
   - Boss HM-2 Heavy Metal
   - Dallas Rangemaster Treble Booster
   - Jordan Boss Tone V1/V2/V3
   - K-AD1 Azusa Driver
   - K-MD1 Mio Driver
   - K-YD1 Yui Driver
   - MSA Steel Pedal Fuzz
   - Xotic EP Booster

 - ## Guitar and Bass Amps
   - Ampeg VH-140C (Preamp only)
     - Does not seem to work well with JRC4558's, so all op-amp models are Ideal components. 
   - Kitty Hawk Junior Series I
   - Marshall 1987x Lead Reissue w/ Jose Arredondo Style-mods
     - Based on [fusedbrain's schematic diagram @ Rig-Talk]( https://www.rig-talk.com/forum/threads/schematic-for-jose-build.201708/page-2#post-2246543 )
   - Marshall JMP 1959 Super Lead 100w, incl.
     - Mk2 version
     - CAE +SE3 Crunch and Lead mods
   - Marshall JMP 1987 Lead 50w, incl. Mk2
   - Marshall Silver Jubilee 2550 & 2555
   - Orange Rockerverb 50w
   - Orange Thunderverb 50w
   - Randall Warhead X2 (Preamp only)
     - Does not seem to work well with TL072's, so all op-amp models are Ideal components.
     - 2N5484's are substituted with 2N5457's.
   - Vox UL730
   - Vox UL7120
     - Biasing for the power tubes are dependent on whether either preamp or poweramp sections are combined or isolated:
       - _Preamp only:_ Output bias from the EL84 "floating paraphrase phase inverters" is a 100k Ohm resistor wired to -80V.
       - _Complete circuit/Poweramp only:_ Output bias from the EL84 "floating paraphrase phase inverters" is fixed - a 560 Ohm resistor wired to ground.
  
## Special Thanks
  - stratürkoise for letting me know that this project exists.
