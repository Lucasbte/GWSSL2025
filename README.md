# GWSSL2025
Code and data employed in the making of the article "Playback-Based Localization of Songbirds Using Multiple Recorders". Written by me, Jonathan Gallego, and Jose David López.

## ABSTRACT

The acoustic localization of wildlife can provide valuable ecological
and conservation information. However, achieving an accurate
acoustic source location within a defined area remains challenging due
to the complexities of real-life (synchronized) landscape passive acoustic
monitoring. This work presents a multilateration methodology to estimate
bird call locations based on the Gillette and Silverman algorithm,
a closed-form linear method whose implementation was simplified by the
novel Python library OpenSoundscape. We tested it by localizing playback
of a pre-recorded Grey Warbler (Gerygone igata) song at known
locations using a grid of synchronized microphones uniformly placed in
a flat open landscape. Our approach was able to locate 19 of the 20 replayed
events within 1.24 ± 0.90 meters of their real source position (in a
80 × 80 meters grid). This is the first approach to tracking birds through
synchronized audio recordings in the open field.


Keywords: Bioacoustics · Sound Source Localization · Bird Tracking ·
Microphone Arrays

Audio files can be downloaded from running the Python notebook.

## INCLUDES

~ Main Python notebook
~ .CSV files of detections and ARU coordinates
~ .DAT files of results with executions attempted