# Prologue-Oscillators
This directory contains three zip files. Each zip file is a collection of digital oscillators modified from Peter Allwin's work on porting of Emilie Gillet's wonderful Plaits code to Prologue. Where Peter's original work included an builtin LFO2, these versions instead implement Envelope Generators, Key Tracking, as well as including support for the main hardware LFO modulated by envelope or key tracking. 

EGandKT - these files implement either a single AR Envelope Generator or a Key Tracking. The files were built on Peter's V1.6 code base, which included a bug in the wavetable oscillators row indexing. So waveforms were not in canonical order.

M3_1.6.1a - these files implement, in a single version support for AR envelope, Key Tracking and LFO redirect all in one oscillator. These oscillators are based on Petere's 1.6.1 code, and thus correct waveform indexing.

M3fast - these files implement the samefunctionality as M3_1.6.1a, however the attack timing has been reduced by 1/5th for faster plucky envelopes, plus there is a small amount of Key Tracking with attack timing, for faster envelopes wit highere notes.
