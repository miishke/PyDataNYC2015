# PyData NYC2015

## Song Matching and IDing by Analyzing and Hashing Audio Fingerprints

_The content is BSD licensed._

### Sound

Pressure waves propagating through air and impinging on eardrums are interpreted by human brain as sound. Two main characteristics of sound are pitch and loudness. Pitch corresponds to the sound frequency expressed in Hertz [Hz] and loudness is related to the sound power per unit area, but is more commonly noted as the sound intensity relative to a reference value and measured in decibels [dB].

Human voice and music are rarely composed of tones having single frequency. Usually, a tone is made of a base frequency, called the fundamental frequency, and higher harmonics, which are whole number multiples of the fundamental frequency. The musical timbre of a steady tone is determined by the relative intensities of each harmonic.

If we examine frequency and its intensity as it varies with time in a 3 second saxophone riff using short time Fourier transform (STFT), we can produce a visual representation called a spectrogram. In a spectrogram, the X axis shows time sampling points and the Y axis corresponds to the sound intensities at discrete frequencies. In this sound clip there are 10 tones played, each with the fundamental frequency and harmonics giving saxophone its unique sound. 
