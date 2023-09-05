# Five-Band-Audio-Equalizer
In sound recording and production studios, equalization is a widely used method. By employing an audio equalizer, we may adjust various audio frequency ranges by using linear filters. Simply put using equalizer we can adjust which frequency ranges to allow and which range to reject from the audio signal. An equalizer has ability to modify the phace,
tone and other different aspects in an audio signal.

<p align="center">
<img src="https://github.com/Moshintha20/Five-Band-Audio-Equalizer/assets/124574829/13d80db1-93dd-470e-b326-38b6df3cf771"  width="500" height="400">
</p>

In this project, we’ll use audio filters to create a
five-band graphic equalization circuit. To separate the
low, high, and mid-range frequencies of the audio
stream, it will thus contain low, high, and band-pass
filter circuits. Our circuits contains operational
amplifier-based active filters (op-amps) and has
capable of adding gains in 5 frequency bands, 
* 20 Hz - 300 Hz 
* 300 Hz - 1 kHz 
* 1 kHz - 4 kHz  
* 4 kHz - 10 kHz  
* 10 kHz - 20kHz.

The equalizer circuit is built by assembling a power supply, audio source, buffer, differential amplifier, band pass filters, controller and volume controller. The gain for the different frequency bands is controlled through variable resistors. The frequency bands are then merged to create a single audio signal, which is then sent to a power amplifier and speaker.
