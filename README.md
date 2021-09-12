# DecentSampler-Modo-Drums
Some GM mapped drum patches I've made using MODO drum as source and Logic`s Autosampler.
Here is the link to the patches/samples:
[Shared DecentPatches](https://www.jottacloud.com/s/2808382b0e52daa4ceca4a273a448d0a12f)

The patches typically has 7 velocity layers and 3 round robin groups
##The code looks something like the below

```
<DecentSampler pluginVersion="1">
  <groups>
    <group seqMode="random" release="2.0">
      <sample path="RefRockV7R3-B0-V24-M197.aif" rootNote="35" loNote="35"
              hiNote="35" loVel="0" hiVel="24" start="35"/>
      <sample path="RefRockV7R3-B0-V44-UCS7.aif" rootNote="35" loNote="35"
              hiNote="35" loVel="25" hiVel="44" start="259"/>
      <sample path="RefRockV7R3-B0-V62-XFCR.aif" rootNote="35" loNote="35"
              hiNote="35" loVel="45" hiVel="62" start="155" end="158898"/>
              
 // --------------------------------- 
      <sample path="RefRockV7R3-B2-V127-Q6WJ.aif" rootNote="59" loNote="59"
              hiNote="59" loVel="113" hiVel="127" start="27"/>
    </group>
  </groups>
</DecentSampler>
```
I've also implementet silencing open hi-hats:
```
      <sample path="RefRockV7R3-G#1-V24-PLP3.aif" tags="hihat" silencedByTags="hihat" silencingMode="fast" rootNote="44" loNote="44"
              hiNote="44" loVel="0" hiVel="24" start="202" end="19887"/>
      <sample path="RefRockV7R3-G#1-V44-0W4N.aif" tags="hihat" silencedByTags="hihat" silencingMode="fast" rootNote="44" loNote="44"
              hiNote="44" loVel="25" hiVel="44" start="42" end="26322"/>
```


These patches are very large and sounds very good. The best I can get on an iPad for sure. But at the moment an error occours after a while where the samples starts to loop a few times and it sounds as an echo effect.
