# PyData NYC2015

## Song Matching and IDing by Analyzing and Hashing Audio Fingerprints

_The content is BSD licensed._

### Sound and human hearing

Pressure waves propagating through air and impinging on eardrums are interpreted by the human brain as sound. Two main characteristics of sound are pitch and loudness. Pitch corresponds to the sound frequency expressed in Hertz [Hz] and loudness is related to the sound power per unit area, but is more commonly noted as the sound intensity relative to a reference value and measured in decibels [dB].

 Humans normally hear frequencies between 20 Hz and 20,000 Hz. The upper limit decreases with age and the hearing range for men worsens more quickly than the hearing range for women. The highest frequency that a normal middle-aged adult can hear is around 12-14 kHz.

Sound loudness is measured on a logarithmic scale in decibels of sound pressure level, dB SPL, and the reference value in air is 20 micropascals. A typical study room noise level is at 40 dB and noise produced by a jackhammer is about 90 dB. This means that the jackhammer is approximately 310 times louder than the study room.

Human voice and music are rarely composed of tones having single frequencies. Usually, a tone is made of a base frequency, called the fundamental frequency, and higher harmonics, which are whole number multiples of the fundamental frequency. The timbre of a steady tone is determined by the relative intensities of each harmonic.

Using short time Fourier transform, we can examine frequency and its intensity as it varies with time in a 3 second saxophone riff, and produce a visual representation shown bellow called a spectrogram. In a spectrogram, the X axis shows time sampling points and the Y axis corresponds to the sound intensities at discrete frequencies. In this sound clip there are 10 tones played, each with the fundamental frequency and harmonics, and combined they produce that unique saxophone sound.

### Short time Fourier transform - STFT
