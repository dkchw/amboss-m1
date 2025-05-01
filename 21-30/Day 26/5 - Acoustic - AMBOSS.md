# Acoustic
## Summary

Acoustics is the science of hearing and deals with the generation, transmission, and perception of sound. Sound is a fluctuation in the density of a medium that spreads in all directions – which is why sound cannot propagate in a vacuum. The term "sound" includes not only audible sound but also ultrasound and all other forms of pressure/shock waves, such as the seismic waves resulting from an earthquake, which can be perceived as tremors/vibrations. However, for medical professionals, the primarily relevant sounds are those that are perceivable by hearing, as well as technical applications like sonography, where (ultra) sound waves are sent into a tissue and the reflected sound waves are detected to make statements about this tissue.

The most important equations of acoustics that a physician may encounter are compiled in the following sections and are illustrated through simple calculation examples. For handling, it is completely sufficient to know the respective basic formulas, which can then be easily rearranged or applied. If difficulties arise here, "Fundamentals of Calculation and Measurement" will help further. The perception of sound is described here only in terms of the physical properties of sound. Details about hearing as a function of the ear are handled under "Auditory System."
## Physical Description of Sound

The wave-like propagation of sound occurs because a sound source rhythmically exerts force on the molecules of the surrounding medium – for example, the skin of a struck drum vibrates. Through this force, the molecules begin to oscillate parallel to the direction of propagation (longitudinal oscillation), thus forming a sound wave. This results in the following characteristic properties (the focus here is on audible sound in air):

- Sound frequency: Frequency of sound. It indicates how quickly the vibrations of the sound wave repeat. The sound frequency ultimately determines the "pitch" and is independent of the medium through which the sound propagates.
    - Formula: f = c / λ
        - Unit: Hz (Hertz, 1/s)
        - f = Sound frequency, c = Propagation speed, λ = Wavelength
    - The higher the frequency, the higher the tone and the shorter the wavelength.
- Period duration: Reciprocal of the (sound) frequency
    - Formula: T = 1 / f
        - Unit: s
        - T = Period duration, f = Frequency
- Speed of sound: Propagation speed of sound
    - Formula: c = s / t
        - Unit: m/s
        - c = speed, s = distance, t = time
    - The speed of sound in air is 343 m/s
        - In comparison to light (about 300,000,000 m/s), sound is many times slower!
- Sound pressure: Fluctuation of (air) pressure, belongs to the so-called sound field quantities; the fluctuation of air pressure is ultimately the force exerted by the sound source on a certain area.
    - Formula: p = I / v
        - p = Sound pressure, I = Sound intensity, v = Sound speed
        - Unit: Pa (Pascal, N/m2)
        - Decreases with increasing distance from the sound source
- Sound intensity: "sound strength"; belongs to the so-called sound energy quantities and describes the energy of sound per area and time.
    - Formula: I = E / At (= P/A)
        - Unit: W / m2
        - E = Energy, A = Area, t = Time, P = Power
    - The sound intensity decreases with increasing distance from the sound source.
- Sound power: Power that a sound source provides to produce a sound; belongs to the so-called sound energy quantities.
    - Formula: P = I × A
        - Unit: W (Watt)
        - P = Sound Power, I = Sound Intensity, A = Area
    - The sound power is independent of the distance to the sound source.
- Sound attenuation: Sound waves become weaker as they propagate. This attenuation can be described similarly to the absorption of light:
    - Formula: I(x) = I0 × e-μx
        - I(x) = Sound intensity after interaction, I0 = original sound intensity, μ = absorption coefficient, x = distance traveled

###### Example Calculation: Speed of Sound

Sound travels through a medium at a speed of 25 m/s. How does the wavelength change when the frequency increases from 50 Hz to 150 Hz?

- Sought: Wavelength λ
- Given: Propagation speed c, frequency f
    - f = c / λ => λ = c / f
    - => λ1 = 25m/s / 50 1/s = 0.5m
    - ⇔ λ2 = 25m/s / 150 1/s = 0.17m
    - The wavelength decreases to one third when the frequency triples.
## Auditory Perception of Sound

The "audible sound" is the sound that is perceivable to the human ear based on its frequency (approximately 20–20,000 Hz) and loudness (above the hearing threshold). Since human hearing varies individually and also changes over the course of life, the limits of audibility are variable. Additionally, the perceived loudness varies with the frequency of the sound waves.

- "Volume": Is a subjectively perceived quantity, usually expressed in "Phon"
    - Isophone: Curve in a diagram of frequency (x-axis) and sound level (y-axis), where all tones are perceived as equally loud.
- Sound and the Human Ear
- Audible sound: Sound whose frequency (pitch, 20 Hz–20 kHz) and pressure (volume) are perceivable by the human ear.
    - The highest sound sensitivity is at sound frequencies of 2–5 kHz
    - Infrasound: Sound whose frequency is too low to be heard by humans (< approx. 20 Hz)
    - Ultrasound: Sound with a frequency too high to be heard by humans (> approx. 20,000 Hz)
- Sound level measurement: Since the human ear can perceive small fluctuations in sound intensity at low sound frequencies but only very large changes in sound intensity at high frequencies, it makes sense to define logarithmic sound levels. These sound level measurements are expressed in the relative, logarithmic unit "decibel." The decibel scale also allows for the correlation of the technical (i.e., absolute) quantities sound pressure, sound power, and sound intensity with the psychoacoustic (i.e., relative) quantity "loudness" in phon: It holds that at a sound frequency of 1000Hz, the numerical value in decibels corresponds to that in phon.
    - Sound pressure level
        - Formula: Lp = 20 × lg(p/p0)
            - Unit: dB (Decibel)
            - Lp = Sound Pressure Level, p = effective (i.e., perceived) Sound Pressure, p0 = reference value of Sound Pressure (= 2×10-5Pa)
        - Special case: Addition of multiple equally loud sound sources
            - Formula: Lges = Lpi + 10 × lg(n)
                - Lges = Sound pressure level total, Lpi = Sound pressure level values of individual sources, n = Number of equally loud sound sources
    - Sound power level
        - Formula: LP = 10 × lg(P/P0)
            - Unit: dB (Decibel)
            - LP = Sound Power Level, P = effective (i.e. perceived) Sound Power, P0 = reference value of Sound Power
    - Sound intensity level
        - Formula: LI = 10 × lg(I/I0)
            - Unit: dB (Decibel)
            - LI = Sound intensity level, I = effective (i.e. perceived) sound intensity, I0 = reference value of sound intensity

> [!NOTE]
> Due to the logarithmic relationship between sound level in dB and sound pressure, an increase in sound pressure level of 20dB corresponds to a difference between p and p0 by a factor of 10 (since lg(10) = 1), whereas an increase in sound intensity level of 20 dB corresponds to a difference between I and I0 equal to a factor of 100 (since lg(100) = 2)!

> [!NOTE]
> The subjectively perceived loudness is usually expressed in the unit "phon," while objective loudness such as sound pressure, sound power, and sound intensity are expressed in dB (decibels). By definition, at 1 kHz, the dB scale and the phon scale are identical!

###### Example Calculation 1: Sound Level

A patient has a hearing loss of 20 dB in the right ear. By what factor does he hear sounds louder on the left side compared to the right?

- Sought: Ratio of right/left of the sound intensity
- Given: Sound Intensity Level
    - The sound intensity level is given by LI = 10 × log(I/I0) = 20 dB
    - => 20/10 = 2 = log(I/I0)
    - ⇔ 102 = I
    - An increase in the sound intensity level of 20dB corresponds to a hearing loss factor of 100. The patient hears the sounds on the left 100 times louder than on the right.

###### Example Calculation 2: Sound Level

Two sounds with volumes of 14 dB and 5 dB are heard by a person. What is the noise exposure level for the person?

- Sought: Sound level Ltotal
- Given: Sound levels L1, L2
    - Sound levels add up. However, since the unit decibel is a logarithmic unit, this must be taken into account when adding!
    - => 14 dB = 1.4 B; 5 dB = 0.5 B
    - ⇔ 101.4 + 100.5 = 28.28
    - ⇔ log(28) = 1.45 B
    - ⇔ 14.5 dB
    - The quieter noise hardly makes a difference in addition to the louder noise!

### Sound Propagation

Sound propagates uniformly in waves. The sound waves can be reflected at surfaces (just like light, see Optics and Optical Devices) (e.g. echo), refracted, frequency-dependent scattered (dispersion), or absorbed. These phenomena of sound propagation are important because they can be utilized, as is the case in medicine, for example, with sonography, which is also known as echography.

### Impedance

Sound is transmitted through the vibrations of particles in a medium – therefore, it is obvious that sound propagates at different speeds depending on the properties of the medium. Even the temperature of air has an influence on the speed of propagation! The impedance describes this material-dependent "sound wave resistance!".

- Sound impedance: Material-dependent constant that represents the relationship between sound speed and the density of the material.
    - Formula: Z = ρ × c
        - Unit: Ns/m3
        - Z = Impedance, ρ = Density of the medium, c = Propagation velocity
    - The greater the density of a material, the higher the speed of sound is.
    - The frequency of sound does not change when transitioning between two media with different acoustic impedance
    - The greater the density difference between two tissues (i.e., the greater the acoustic impedance jump), the more sound is reflected when transitioning from one tissue to another.

> [!NOTE] Sonography
> In ultrasound imaging, sound waves are emitted by a transducer, their reflected portion is received, and for example, translated into image points (B-mode: classic grayscale image). By applying a gel to the transducer, the air gap between the transducer and the tissue to be examined is bridged, which reduces the acoustic impedance mismatch, as the gel has a similar acoustic impedance to the tissue. The resolution of the image increases with a higher sound frequency; however, due to the higher absorption of sound by the tissue, the penetration depth simultaneously decreases. Therefore, for the different examinations, the sound frequency of the device must be adjusted and, if necessary, the transducer changed.

### Resonance

A vibration that is excited from the outside (e.g., by a sound source) is a "forced" vibration. This vibration becomes stronger the closer the frequency of the vibration is to the so-called "natural frequency" of the vibrating medium/body. If there is a continuous excitation of a vibration at or near the natural frequency, resonance occurs. While this effect is desired in music (e.g., in musical instruments), resonance can also amplify the natural vibration of a system to the point of collapse. This is called the resonance catastrophe.

- Resonance (Acoustics): Oscillation of a vibrating system excited and amplified from the outside.
    - Eigenfrequency: Frequency of the oscillation that a system would exhibit due to its shape without external excitation or damping of the oscillation.
        - Resonance catastrophe: Strong increase in sound amplitude through suitable excitation (at the natural frequency) and amplification of the vibration.
        - Determination of the natural frequency of a cavity resonator: A cavity resonator is a resonance tube, e.g. a flute
            - Cavity resonator open at both ends: L = λ / 2
                - L = Length of the cavity, λ = Wavelength of the fundamental mode that produces resonance
            - Cavity resonator open at one end: L = λ / 4
                - L = length of the cavity, λ = wavelength of the fundamental mode that generates resonance

> [!NOTE] Resonance
> The hair cells in the inner ear of humans have about 100 different resonance frequencies. This allows different frequencies of a sound to be separately "represented" in the ear and also forwarded to separate fibers of the auditory pathway.

### Doppler Effect

Normally, a sound is heard by the receiver at the same frequency at which it was emitted by the sender. However, if the distance between the sound source (also known as the "sender") and the receiver changes while listening, the frequency of the received sound changes as well. This change is called the Doppler effect.

- Doppler effect: fReceiver = fSender (c ± vReceiver / c ± vSender)
    - f = frequency of sound, c = speed of sound, v = velocity of the movement of transmitter/receiver
- Movement towards each other
    - The path of sound is shortened.
    - Negative signs in the formula
    - The frequency of the sound increases → The tone is perceived as higher than when at rest.
    - Wavelength of sound decreases
- Movement away from each other
    - The path of sound is extended.
    - Positive signs in the formula
    - Frequency of sound decreases → Tone is perceived as lower than at rest
    - Wavelength of sound increases
- Example: When an ambulance is moving, the siren can be heard at different pitch levels: As the ambulance approaches, the sound is higher than when it is stationary, because the ambulance is moving in the same direction as the sound that is heard by the receiver (“it is chasing the sound waves”) – thus, the frequency of the sound increases.
    While the ambulance moves away, the sound is lower than when it is stationary, because the ambulance moves against the direction of the sound waves heard by the receiver (“it is moving away from the sound”) – thus, the frequency of the sound decreases.

> [!NOTE] Doppler Sonography
> The so-called Doppler sonography uses the Doppler effect to visualize not only the morphology of structures but also the flow behavior of blood. Depending on the direction and speed at which the blood flows, the corpuscular components of blood cause a change in the frequency sent by the ultrasound device – it is then either reflected at a higher or lower frequency. From this frequency change between the transmitted and received sound, the device can derive the flow velocity of blood. The method is particularly used in the diagnostics of vascular and heart diseases.

## Review Questions on the Chapter Acoustics
### Physical Description of Sound

What is sound?
- Sound is defined as wave-shaped density changes in a medium such as air or water. The density changes arise from directed movement of molecules of the medium, e.g. gas molecules in the air or water molecules.
How does a sound wave move?
- Sound moves in waves. Therefore, a sound wave can be described with the formula Sound frequency = propagation speed / wavelength.
What moves faster in air, sound or light?
- Light propagates faster than sound. In air, sound has a speed of about 343 m/s, light almost 300,000 km/s. The speed of sound is thus calculated like other speeds as distance traveled per time.
What is the so-called sound intensity?
- Sound intensity indicates how much energy the sound wave transports per area and time (Sound intensity = energy / (area × time)). It is therefore sometimes also called sound level. It can also be calculated from the so-called sound power: Sound intensity = sound power / area.
### Auditory Perception of Sound

When is sound audible to humans?
- For sound to be heard by humans, it must lie within the correct frequency range, i.e. between about 20–20,000 Hz. Additionally, the loudness must be above the perception threshold for sound – this varies depending on frequency.
Name and explain the three levels of sound measurement!
- The human ear can register changes in sound energy quantities (pressure, intensity, and power) differently depending on sound frequency. Therefore, a logarithmic scale, the so-called level measures, which are given in decibels (dB), is used to represent these changes. They are defined as level measure = specific factor × logarithm of the quotient of changed sound quantity and original sound quantity. The factor for sound power and sound intensity is 10, for sound pressure 20. This results in the fact that an increase of the sound pressure level by 20 dB corresponds to a difference between p and p0 by a factor of 10 (since lg(10) = 1), whereas an increase of the sound intensity level by 20 dB corresponds to a difference between I and I0 by a factor of 100 (since lg(100) = 2).
What is an isophone diagram?
- For sound to be heard by humans, it must have a minimum loudness that varies with the frequency of sound. It therefore makes sense to represent all tones that are heard equally loud on a curve in a frequency (sound level) diagram, resulting in the so-called isophone diagram.
What is represented in the unit phon and how is it related to the values in decibels?
- The loudness subjectively perceived by humans does not correspond to the objective loudness. Subjective perception is therefore described with its own unit, the "phon", the objective values in decibels. By definition, at a frequency of 1 kHz the values of both scales are identical.
### Sound Propagation

What does the physical term dispersion mean and where in the body does this phenomenon play a role?
- Dispersion means the wavelength-dependent splitting for light and frequency-dependent splitting for sound of a spectrum. In optics, dispersion leads to the separation of white light into its individual color components, forming a rainbow. The dispersion of a sound spectrum occurs analogously – but since it plays no important role for hearing sound, there is no equally vivid everyday example as with light. In the human body, dispersion occurs through the change of width and stiffness of the basilar membrane within the different areas of the cochlea in the inner ear. These cause the maximum amplitudes of sound waves with different frequencies to distribute across the various regions of the cochlea, where the corresponding frequency-selective sensory cells that convert sound into electrical impulses are located.
### Open Questions on the Chapter Acoustics

What are the three levels of measurement used for sound?

Explain what the Doppler effect is and give an example from medicine where it is applied.
