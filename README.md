# O2 Minipops

O2 Minipops is a Korg Minipops 7 rhythm box emulation for Arduino Uno-compatible boards. This fork of Jan Ostman's original code adds [MIDI beat clock](https://en.wikipedia.org/wiki/MIDI_beat_clock) synchronization support.

## Features

* Runs unmodified on any Arduino Uno-compatible board
* Tempo and pattern select CV input
* Eight drum mute inputs
* Run/stop input and clock/reset outputs
* MIDI beat clock synchronization input

## Getting Started

Load O2minipop.ino into Arduino IDE and flash it onto a Arduino Uno-compatible board. Connection schematics may be found in Jan Ostman's [blog post](https://janostman.wordpress.com/the-o2-source-code/) ([archived version](https://web.archive.org/web/20170918125855/https://janostman.wordpress.com/the-o2-source-code/)).
Schematics to connect a MIDI port may be found in a [Hackaday post](https://hackaday.com/2018/11/04/quick-and-dirty-midi-interface-with-usbasp/). Port 8 of optoisolator 6N137 connects to 5V on the Arduino, port 5 to GND, and port 6 to serial RX respectively.
MIDI beat clock synchronization works if you set the Run/Stop input (D10) to off.

## Related projects

* [Original source](https://gist.github.com/anonymous/c85c864c337501680505)
* [NANO - Minipops](https://github.com/NANOmodules/NANO-Minipops): Minipops drum machine shield for Arduino Uno
* [The Wee O3](https://github.com/mark-orion/The-Wee-O3): an ionized O2 MiniPop
* [Minipops-](https://github.com/Krustpunkhippy/Minipops-): Minipops code
* [MiniPops](https://github.com/makervan/minipops): Arduino-based drum machine PCB
* [Arduino-MiniPops](https://github.com/sgilissen/Arduino-MiniPops): Arduino MiniPops clone
* [Grains-Minipops-O2](https://github.com/emast42/Grains-Minipops-O2): Minipops O2 for Ginko Synthese Grains
* [O2shield](https://github.com/uranioEmpobrecido/O2Shield): Repository for Arduino shield (Minipops - MakeIT)

## License

See [License file](LICENSE).
