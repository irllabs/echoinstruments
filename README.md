# echojam 

Hardware and Software modules for a family of children's musical toys.

High-level overview:

- '01_echo-wheel': hand-held live-sampler, turn-wheel-to-record-and-playback 
- '02_echo-air': two-handed record (microphone, switch in one hand) and play (speaker and gesture sensors in the other) instrument
- '03_echo-keys': BlueTooth keyboard mouse/keyboard sampler
- '04_echo-touch' Sound Microscopy; clip in objects to hear their sounds
- '05_echo-vroom': Toy-car based sample-playback car sound-effect maker
- 'aLib-pd': external repository, used as a submodule in the the instruments that require PureData
- 'sounds': a few sound samples used for development

Installation and usage instructions vary by instrument.

# Echo Wheel: '01_echo-wheel'

## Instructions
- clone this repository
- enter the cloned repo and update submodules
```
git submodule init
git submodule update
```
- install the PdParty app on iOS
- use the PdParty's built-in WebDav server to transfer 1) the contents of the
