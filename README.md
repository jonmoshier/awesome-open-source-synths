# Awesome Open Source Synthesizers

An awesome list of open source synthesizer projects.

## Contents

- [Modular](#modular)
  - [Audio source (things that can generate frequencies above 20Hz)](#audio-source)
  - [Audio processing (filter, amplifier, ring modulator, frequency shifter, waveshaper, distortion)](#audio-processing)
  - [Modulation source (LFOs, EGs, gates, triggers, random voltages, offset generators)](#modulation-source)
  - [Modulation processing (logic functions, sample and hold, slew limiter, comparator, inverter, quantizer)](#modulation-processing)
  - [Routing (mixer, switch, mult)](#routing)
  - [Audio effects (delays, DSP, phaser, pitchshifter)](#audio-effects)
  - [Other/utility (oscilloscope, lights, MIDI-to-CV, etc)](#otherutility)
  - [Full Voice](#full-voice)
- [Standalone](#standalone)


## Modular

### Audio Source
  - Eurorack

    - Oscillator
      - [Braids](https://github.com/pichenettes/eurorack/tree/master/braids) : Macro-oscillator ([Mutable Instruments - Braids](https://mutable-instruments.net/modules/braids/))
      - [Edges](https://github.com/pichenettes/eurorack/tree/master/edges) : Quad chiptune digital oscillator ([Mutable Instruments - Edges](https://mutable-instruments.net/modules/edges/))
      - [Rings](https://github.com/pichenettes/eurorack/tree/master/rings) : Resonator ([Mutable Instruments - Rings](https://mutable-instruments.net/modules/rings/))

### Audio Processing

- Eurorack

  - Filter
    - [Jove](https://github.com/minisystem/JOVE) : Roland Jupiter 6 inspired multimode filter in 14HP Eurorack format ([System80 - Jove](http://system80.net/product/jove/))
    - [Ripples](https://github.com/pichenettes/eurorack/tree/master/ripples/hardware_design) : Liquid 2-pole BP, 2-pole LP and 4-pole LP filter ([Mutable Instruments - Ripples](https://mutable-instruments.net/modules/ripples/))
    - [Shelves](https://github.com/pichenettes/eurorack/tree/master/shelves/hardware_design) : Eq filter ([Mutable Instruments - Shelves](https://mutable-instruments.net/modules/shelves/))
    - [Streams](https://github.com/pichenettes/eurorack/tree/master/streams) : Dual dynamics gate ([Mutable Instruments - Streams](https://mutable-instruments.net/modules/streams/))
  - Waveshaper
    - [Warps](https://github.com/pichenettes/eurorack/tree/master/warps) : Meta-modulator ([Mutable Instruments - Warps](https://mutable-instruments.net/modules/warps/))
  - Amplifier
      - [Mikrophonie](https://github.com/TomWhitwell/Mikrophonie) : 4hp contact mic pre-amp module ([Music Thing Modular - Mikrophonie](http://www.musicthing.co.uk/pages/mikrophonie.html))
      - [Ears](https://github.com/pichenettes/eurorack/tree/master/ears/hardware_design) : Contact Microphone ([Mutable Instruments - Ears](https://mutable-instruments.net/modules/ears/))
  - VCA
    - [Veils](https://github.com/pichenettes/eurorack/tree/master/veils/hardware_design) : Quad VCA ([Mutable Instruments - Veils](https://mutable-instruments.net/modules/veils/))

### Modulation Source

- Eurorack
  - LFO
    - [Swirls](https://github.com/ElectricMist/Swirls) : Tides in an 8hp footprint
    - [Tides](https://github.com/pichenettes/eurorack/tree/master/tides) : Tidal modulator ([Mutable Instruments - Tides](https://mutable-instruments.net/modules/tides/))
    - [Wobbler](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production) : Advanced LFO ([TINRS - Wobbler](http://www2.thisisnotrocketscience.nl/eurorack/wobbler/))

  - Sequencer
    - [Tuesday](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production) : Procedural Sequencer ([TINRS - Tuesday](http://www2.thisisnotrocketscience.nl/eurorack/tuesday/))

    - [Turing Machine Mk2](https://github.com/TomWhitwell/TuringMachine) : Random Looping Sequencer ([Music Thing Modular - Turing Machine Mk2](http://musicthing.co.uk/pages/turing.html))
    - [Turing Machine Mk2 expander - Volts](https://github.com/TomWhitwell/Volts) : Expander for the Turing Machine Mk2 [(Music Thing Modular - Volts Expander](http://musicthing.co.uk/pages/volts.html)
    - [Turing Machine Mk2 expander - Pulses](https://github.com/TomWhitwell/Turing-Pulse-Expander) : Expander for the Turing Machine Mk2 ([Music Thing Modular - Pulses Expander](http://musicthing.co.uk/pages/pulses.html))
    - [Turing Macine Mk2 expander - Voltages](https://github.com/TomWhitwell/Voltages-Expander) : Expander for the Turing Machine Mk2 ([Music Thing Modular - Voltages](http://musicthing.co.uk/pages/voltages.html))

    - [Turing Machine Mk2](https://github.com/TomWhitwell/TuringMachine) : Random Looping Sequencer ([Music Thing Modular - Turing Machine Mk2](http://www.musicthing.co.uk/pages/turing.html))
    - [Turing Machine Mk2 expander - Volts](https://github.com/TomWhitwell/Volts) : Expander for the Turing Machine Mk2 [(Music Thing Modular - Volts Expander](http://www.musicthing.co.uk/pages/volts.html)
    - [Turing Machine Mk2 expander - Pulses](https://github.com/TomWhitwell/Turing-Pulse-Expander) : Expander for the Turing Machine Mk2 ([Music Thing Modular - Pulses Expander](http://www.musicthing.co.uk/pages/pulses.html))
    - [Turing Macine Mk2 expander - Voltages](https://github.com/TomWhitwell/Voltages-Expander) : Expander for the Turing Machine Mk2 ([Music Thing Modular - Voltages](http://www.musicthing.co.uk/pages/voltages.html))
    - [Grids](https://github.com/pichenettes/eurorack/tree/master/grids) : Topographic drum sequencer ([Mutable Instruments - Grids](https://mutable-instruments.net/modules/grids/))

  - Envelope Generator / ADSR
    - [Edgecutter](https://github.com/ThisIsNotRocketScience/Eurorack-Modules/tree/master/Production) : Visual envelope ([TINRS - Edgecutter](http://www2.thisisnotrocketscience.nl/eurorack/edgecutter/))
    - [Peaks](https://github.com/pichenettes/eurorack/tree/master/peaks) : Envelope/LFO/tap LFO/Drum generator ([Mutable Instruments - Peaks](https://mutable-instruments.net/modules/peaks/))
    - [Tides](https://github.com/pichenettes/eurorack/tree/master/tides) : ([Mutable Instruments - Tides](https://mutable-instruments.net/modules/tides/))

### Modulation Processing
- Eurorack

  - Logic Functions
    - [Branches](https://github.com/pichenettes/eurorack/tree/master/branches) : Dual Bernoulli Gate ([Mutable Instruments - Branches](https://mutable-instruments.net/modules/branches/))
  - Inverter
    - [Blinds](https://github.com/pichenettes/eurorack/tree/master/blinds) : Quad VC-polarizer ([Mutable Instruments - Blinds](https://mutable-instruments.net/modules/blinds/))
  - Sample and Hold
    - [Kinks](https://github.com/pichenettes/eurorack/tree/master/kinks/hardware_design) : S&H, rectifier, analog logic, noise ([Mutable Instruments - Kinks](https://mutable-instruments.net/modules/kinks/))

### Routing
- Eurorack

  - Mixer
    - [Tripple Attenuverter Mixer v2](https://github.com/ishkabbible/Triple_Attenuverter_Mixer_v2) : Three precision attenuators/attenuverters
    - [Links](https://github.com/pichenettes/eurorack/tree/master/links/hardware_design) : Buffer, mixer ([Mutable Instruments - Links](https://mutable-instruments.net/modules/links/))
    - [Frames](https://github.com/pichenettes/eurorack/tree/master/frames) : Keyframer/mixer ([Mutable Instruments - Frames](https://mutable-instruments.net/modules/frames/))
    - [Shades](https://github.com/pichenettes/eurorack/tree/master/shades/hardware_design) : Attenuator/offset/mixer ([Mutable Instruments - Shades](https://mutable-instruments.net/modules/shades/))

### Audio Effects
- Eurorack

  - Reverb
    - [Clouds](https://github.com/pichenettes/eurorack/tree/master/clouds) : Texture synthesizer ([Mutable Instrument - Clouds](https://mutable-instruments.net/modules/clouds/))

### Other/Utility
- Eurorack

  - Mixer
    - [Tripple Attenuverter Mixer v2](https://github.com/ishkabbible/Triple_Attenuverter_Mixer_v2) : Three precision attenuators/attenuverters

  - Amplifier
    - [Mikrophonie](https://github.com/TomWhitwell/Mikrophonie) : 4hp contact mic pre-amp module ([Music Thing Modular - Mikrophonie](http://www.musicthing.co.uk/))

  - MIDI-to-CV
    - [Yarns](https://github.com/pichenettes/eurorack/tree/master/yarns) : MIDI interface ([Mutable Instruments - Yarns](https://mutable-instruments.net/modules/yarns/))

### Full Voice
- Eurorack

  - [Elements](https://github.com/pichenettes/eurorack/tree/master/elements) : Modal Synthesizer ([Mutable Instruments - Elements](https://mutable-instruments.net/modules/elements/))

## Standalone
- [The Klangorium](https://github.com/hexagon5un/klangorium) - Hardware and tutorials for the Hackaday / Logic Noise Klangorium demo board
