**V 1.0** - July 30th, 2026
- Initial release.
---

**V 1.1** - September 25th, 2026
- NOTE: This firmware was shipped with a batch of 5 M0SS-201's sold at Nightlife Electronics in Vancouver.
- BUG FIX: Oscillator DSP change that improves audio quality, especially on OS2 SQR and SAW waves
- BUG FIX: New patches no longer have default CC maps
- BUG FIX: Sending CC0 caused undefined behaviour
- BUG FIX: The output signal LED indicator (beside the VOL LED) now behaves nicer (doesn't flicker when certain high notes are played)
- FEATURE: ALT + ENV (matrix button) now toggles OS2 retriggering. When on, the phase of the waveform will be reset whenever the envelope is triggered
- CHANGE: The LED bar now behaves more logically, this aligns it with M0SS-101's behaviour. See the manual for further details


**V 1.2** - September 30th, 2026
- NOTE: This is the full version of the previous update, adding features that were missed in V1.1
- FEATURE: Now supports polyphonic aftertouch messages. Note that this does not mean that it polyphonic aftertouch is supported, because the 201 is a monophonic instrument. This feature translates polyphonic aftertouch messages to normal aftertouch messages.
- FEATURE: OS1 detune. Pressing WAV + OCT accesses a new hidden parameter that can be used to manually adjust OS1's pitch. It goes up and down one octave, and is not affected by the quantizer. It can be midi mapped.