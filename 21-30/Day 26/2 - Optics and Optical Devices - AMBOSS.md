# Optics and Optical Devices
## Summary

The optics is the science of light. Light can be described as both an electromagnetic wave and as particle radiation (from photons) due to the wave-particle duality. Typically, one of the two properties predominates when light interacts with matter. The most important types of interaction include refraction and the conversion of light energy into heat (absorption), which leads to a reduction in light intensity. In particular, refraction is utilized in various optical devices such as lenses (glasses) and the light microscope to artificially enlarge objects.

Light can be perceived in different colors: White light is light that consists of all wavelengths and therefore leaves no color impression in the eye. If such a beam of white light is split into individual rays of different wavelengths (dispersion), colored light rays are created.
## Light and its Properties

### Wave-Particle Duality

Light is electromagnetic radiation that propagates in wave form while simultaneously consisting of the smallest particles, known as photons (light particles, light quanta). Depending on the situation, the properties of light as a wave or as a particle prevail. Light waves can be mathematically described by their oscillation (frequency and wavelength).

#### Speed of Light

Photons or electromagnetic waves always move at the same speed, namely at the speed of light c, which is a fundamental constant of nature. Here, c is mathematically the product of the wavelength λ and the frequency v of light. This relationship is expressed by the so-called light equation:

- Light equation: c = λ × ν
    - Unit: m/s = m × 1/s
    - c = speed of light [m/s], λ = wavelength [m], ν = frequency [Hz = 1/s]
    - Since c is always constant, the product of λ and v is also always constant: c = constant → λ × ν = constant
        - It follows that the wavelength and frequency of light are inversely proportional to each other: λ × ν = constant → λ = 1/ν or v = 1/λ
        - Accordingly, each frequency corresponds to a specific wavelength and vice versa.
- Speed of light: c ≈ 3.0 × 10^8 m/s = 300,000 km/s (measured in a vacuum)

#### Electromagnetic Spectrum

The electromagnetic spectrum is a continuum of radiation with varying wavelength (and frequency).

- Electromagnetic Spectrum
    - Microwave radiation: 0.1–30 cm
    - Infrared radiation (thermal radiation): 750 nm to 0.1 cm (corresponds to a frequency of 10^12 to 10^14 Hz)
    - Visible range: Approximately 400–750 nm
    - Ultraviolet light (UV light): 10–400 nm

##### Colorfulness

The color of light depends on its wavelength: red ≈ 750 nm, yellow ≈ 550 nm, green ≈ 500 nm, blue ≈ 460 nm, violet ≈ 400 nm. The photon energy increases with decreasing wavelength. Sunlight is white light, which contains all colors – however, these cancel each other out through additive color mixing.

- Additive Color Mixing: The perception of the human eye and the subsequent perception process in the brain cause light that contains the entire spectrum to be seen as colorless or white.
    - Blue + Red = Pink
    - Green + Blue = Turquoise
    - Green + Red = Yellow
- Monochromatic light (monochromatic = one color): Light with only one wavelength is perceived as colored.

#### Energy

The energy of a photon corresponds to the product of the constant h (Planck's constant) and the frequency of the radiation.

- Planck constant (Planck's quantum of action): h = E/v
    - Unit: Js
    - E = Energy [J], h = constant = 6.626×10-34 Js, ν = Frequency [1/s = Hz]
## Interaction between Light and Matter

Light radiation can interact with matter in various ways and is consequently influenced in different manners:

- Diffraction: Change in the direction of a beam at the edges of an obstacle with subsequent illumination of the geometric "shadow of the obstacle"
    - Example: aperture
- Reflection: Light rays are bounced back when they hit an obstacle.
    - Example: Mirror
- Refraction: Change of the direction of a ray due to a change in the propagation speed depending on the surrounding medium (see below)
    - Example: Lens
- Dispersion: Dispersion/splitting of a polychromatic light beam depending on the frequency or wavelength of the individual waves (see below)
    - Example: Prisma
- Polarization: Unordered oscillating (unpolarized) light is filtered so that it oscillates only in one plane (polarized light)
    - Example: Polarizing filter in photography
- Interference: Superposition of light waves that either amplify each other (constructive interference) or cancel each other out (destructive interference)
    - Example: Shimmering of an oil film
- Absorption: Weakening of the intensity of a light beam by converting the light energy into heat (see below)
    - Example: Absorption spectrometer

### Refraction (Light Refraction)

Light radiation spreads at a constant speed, which, however, depends on the medium through which the beam passes. The term speed of light is mostly used for the speed of a beam in a vacuum and is c0 = 299,792,458 m/s. The propagation in other media depends on how strongly the light interacts with the molecules that make up the matter. To classify the propagation speed of light through a specific medium, a refraction index is specified. When light becomes slower or faster due to the transition from one medium to another, the direction of the beam also changes. This effect is called refraction.

#### Refractive Index

The refractive index is a material property that indicates how much the speed of light propagation is altered compared to the maximum speed in a vacuum. Air has a refractive index of n = 1.0003, water has a slightly higher refractive index of n = 1.33, and quartz glass even has a refractive index of n = 1.46. Different refractive indices can also exist for individual wavelengths of light, such that the refractive index for blue light is greater in every medium than for red. The refractive index can be easily calculated:

- Formula: n = c0/c
    - n = refractive index c0 = speed of light in vacuum = 3.0 × 10^8 m/s; c = speed of light in the medium being considered

#### Refraction

Refraction is the change in the direction of a ray due to a change in the propagation speed depending on the surrounding medium and occurs at all interfaces between two materials with different refractive indices n.

- Refraction at the interface between two materials with different refractive indices
    - nMedium 2 > nMedium 1
        - Light slows down (If the frequency of light remains constant, this results in a shorter wavelength)
        - Refraction towards the vertical
        - Refraction angle < Angle of incidence
    - nMedium 1 > nMedium 2
        - Light travels faster
        - Refraction away from the perpendicular
        - Refraction angle > Angle of incidence
- Snell's Law of Refraction: Indicates how much a light beam changes its direction through refraction, thus quantifying the degree of refraction.
    - Formula: n2/n1 = sinα1/sinα2
        - n = refractive index, α1 = angle of incidence, α2 = angle of refraction

##### Example Calculation

Light that radiates through air (n = 1) strikes a water surface (n = 1.33) at an angle of 36°. Calculate the angle of refraction.

- Sought: αWater
- Given: Angle of incidence αAir, refractive index nAir, refractive index nWater
    - nAir/nWater = sinαWater/sinαAir
    - → sinαWater = sinαAir × (nAir/nWater) = sin(36) × (1/1.33) ≈ 0.59/1.33 ≈ 0.44
    - → αWater = sin-1(0.44) ≈ 26°
    - The angle of refraction is approximately 26°.

### Dispersion of Light

The effect of additive color mixing can be nullified by separating the radiation of different wavelengths from each other.

- Dispersion: "Dispersion," the splitting of a light beam into its individual components (wavelengths)
    - Cause: The wavelength-dependent speed of light causes light to be refracted to different extents at a surface and to be separated into individual monochromatic rays.
    - Example: Rainbow

### Absorption of Light

When light interacts with matter, a small part of the light is always absorbed. As a result, the intensity of the light weakens over the course of the interaction:

- Transmission: Intensity of light that remains after absorption
    - Formula: T = I/I0
        - T = transmission degree, I = intensity after interaction, I0 = intensity before interaction
        - Tges = T1 × T2
- Extinction: Extinction is sometimes also referred to as optical density and means "extinguishment."
    - Formula: E = lg(I0/I)
        - E = Extinction, I = Intensity after the interaction, I0 = Intensity before the interaction
- Lambert-Beer's Law: Describes the reduction of light intensity due to absorption losses.
    - Formula: I = I0×e−εcd => lg(I/I0) = −ε×c×d => lg(I0/I) = ε×c×d
        - Unit: W/m2
        - I = intensity after interaction, I0 = intensity before interaction, c = concentration of the absorbing substance in mol/L, ε = extinction coefficient (usually given in the unit "L/(mol×cm)"), d = path length traversed

- Irradiance: Describes the radiation power that strikes a surface.
    - Formula: E = P/A
        - Unit: W/m2
        - E = Irradiance, P = Radiant power, A = Area
- Half-value thickness: Absorption length at which the remaining intensity I is only half as large as the original intensity I0
    - Formula: lg(I/I0) = −ε × d ⇔ lg(1/2) = −ε × d
    - ⇔ lg(1) − lg(2) = −ε × d
    - ⇔ 0 − lg(2) = −ε × d
    - ⇔ lg(2) = ε × d
    - ⇔ lg(2)/ε = d
        - ε = extinction coefficient (usually expressed in the unit L/(mol×cm)), d = path length traversed

##### Example Calculation

In a photometric experiment, the concentration of a dissolved substance is to be measured using an absorption experiment. For this purpose, monochromatic light is passed through a 1 cm thick cuvette. The extinction with the dissolved substance is 1.147. The extinction coefficient is known to be 20 L/(mol×cm). Calculate the concentration of the solution.

- Sought: concentration c
- Given: Extinction E, extinction coefficient ε, d = distance
    - => lg(I0/I) = εcd and E = log(I0/I) => E = εcd
    - => c = E/εd
    - => c = 1.147 / 1 cm × 20 L/(mol×cm) = 0.05735 mol/L
## Optical Devices

The properties of light and its interaction with matter can also be utilized in a medical context. For example, in the form of optical aids such as glasses or microscopes. Both are ultimately nothing more than lenses (systems) adapted by appropriate grinding.

### Refraction at Lenses

Due to the difference in the speed of light in air and glass, light rays are refracted by lenses. The exact path of a light ray (the so-called ray path) also strongly depends on the shape of the lens. The properties of a lens can be well investigated in an optical experiment. Such an experiment consists of:

- Subject: An object that one views through a lens
    - Object size: G; Size of the object
    - Object distance: g; distance of the object measured from the center of the lens
- Linse: Transparent building element, usually made of glass
    - Types
        - Collecting lens: Convex lens
            - Beam path:
            - “Plusglass“: Focal length and refractive power are positive
            - Example: Glasses for farsightedness
        - Diverging lens: Concave lens
            - Beam path:
            - “Minus lens“: Focal length and Refractive power are negative
            - Example: Glasses for nearsightedness
        - Properties
            - Focal point (focus): The point where the refracted light rays that are parallel to the optical axis converge on the lens.
            - Focal length: f; distance from the center of the lens to the focus
        - Image size change through a lens: When viewing an object through a lens, the size of the image changes in the same ratio as the distances from the object and the image to the lens.
            - Formula: B/G = b/g
                - B = Image size, G = Object size, b = Image distance, g = Object distance
    - Lens equation: Relationship between object distance (g, i.e., the distance between the lens and the object), image distance (b, i.e., the distance between the lens and the image) and focal length (f, the distance between the lens and the focal point, which mainly depends on the lens's curvature) when observing an object through a lens with refractive power D.
        - Formula: D = 1/f = 1/g + 1/b
            - Unit: Diopters 1/m = [dpt]
            - D = Breaking force, f = Focal length, g = Object distance, b = Image distance
            - By rearranging 1/f = 1/g + 1/b, it also follows that: f = (g x b) / (g + b)
        - Observation through a combination of two lenses: When observing an object through two lenses placed one behind the other, the refractive powers of the individual lenses combine to form a total refractive power.
            - Formula: Dges = 1/fges = 1/f1 + 1/f2
                - Unit: Diopters 1/m = [dpt]
                - 1/fges = total lens power, 1/f1 = power of the first lens, 1/f2 = power of the second lens
- Image: Image produced by the object
    - Image size: B; size of the image produced by the lens
    - Image distance: b; distance of the image measured from the center of the lens

##### Example Calculation

A lens enlarges an object by 10 times when the object is 5 cm away. What is the power of this lens and what is the power of a system in which this lens is combined with a lens of double power?

- Sought: Refractive power (D) of the individual lens = 1/f1, Refractive power of both lenses combined = 1/ftotal
- Given: Magnification B/G = 10; Object distance g = 5 cm; 1/f2 = 2 × 1/f1
    - Calculation of the image distance (b)
        - It holds that: B/G = b/g
        - It follows: B/G = 10 = b / 5 cm
        - ⇔ b = 10 × 5 cm = 50 cm
    - Calculation of the breaking force (D)
        - D = 1/f = 1/g + 1/b
        - ⇔ 1/f1 = 1/5 cm + 1/50 cm ≈ 0.2/cm
        - ⇔ 1/fges = 1/f1 + 2 × 1/f1 = 0.2/cm + 0.4/cm = 0.6/cm

#### Optical Imaging Errors

Imaging errors (aberrations) are deviations from the ideal ray path in optics. Chromatic and monochromatic aberrations are distinguished.

- Chromatic Aberration: In a lens, rays of different wavelengths are refracted to different degrees (Refraction: short-wavelength light > long-wavelength light)
- Monochromatic aberrations, e.g.
    - Spherical Aberration
        - At different points on a lens, the rays are refracted to varying degrees (Refraction: edge > center)
        - The human eye compensates for spherical aberration by constricting the pupils.
    - Astigmatism, see: Refraction anomalies

### Physical Principles of Light Microscopy

To optically enlarge small structures, the resolution must be improved. For this purpose, a light microscope is often used. It generates an enlarged image by directing light through multiple lenses.

- Structure: Light is directed through several collecting lenses and the image is gradually enlarged.
    - Okular: Lens at Eye, can be viewed like a magnifying glass
        - Magnification: v = s0/f
        - v = magnification, s0 = distinct vision distance, f = focal length
    - Objective: Lens at the object, the magnification of the lens depends on the tube length
        - Magnification: v = t/f
        - v = magnification, t = tube length = distance between the focal points of the eyepiece and the objective, f = focal length
- Total magnification of the microscope
    - Formula: v = vEyepiece × vObjective => v = s0/fEyepiece × t/fObjective
        - v = magnification, s0 = distinct vision distance, f = focal length, t = optical tube length
- Light path: Path of light through a microscope
- Resolution: The smallest distance between two points that can still be perceived as separate.
    - Formula: d = λ / (n×sinα)
        - Unit: nm
        - d = smallest resolvable distance between two points, n×sinα = numerical aperture (A), n = refractive index, α = half of the microscope's opening angle, λ = wavelength of light
    - Ways to influence the resolution
        - The smaller the wavelength of the radiation used, the smaller the distance d (and the higher the resolving power)
        - The larger the refractive index n (for example, through the use of immersion solutions), the smaller the distance d (and the higher the resolution)

> [!NOTE]
> The refractive index of a microscopic arrangement can be optimized using so-called immersion solutions, which have a higher refractive index than air!

##### Example Calculation 1

- Sought: Magnification of microscope
- Given: vEyepiece = 400, t = 5 cm, fObjective = 30 mm
    - vMicroscope = vEyepiece × vObjective
    - vObjective = t/fObjective
    - ⇔ vMikroskop= (vOkular×t)/fObjektiv
    - ⇔ 400 × 5 / 3 = 667

##### Example Calculation 2

- Sought: Resolution of d
- Given: Aperture of a microscope A = 0.12; λ = 550 nm
    - d = λ/(n×sinα)
    - ⇔ d = λ/A
    - ⇔ d = 550 nm / 0.12 = 4.583 μm
## Review Questions on the Chapter Optics and Optical Devices
### Light and Its Properties

What does the so-called light equation describe?
- The light equation describes the wave aspect of light: c = λ × ν. It defines the speed of light (c) as the product of the wavelength (λ) and frequency (ν) of light. Since the speed of light is a natural constant (i.e. always the same), the product of wavelength and frequency is also always the same (λ × ν = constant), which in turn implies that wavelength and frequency are inversely proportional to each other (λ = 1/ν or ν = 1/λ).

Describe the different areas of the electromagnetic spectrum and also address the color of light!
- The electromagnetic spectrum refers to the entire range of electromagnetic radiation. Depending on the wavelength, different types of radiation with distinct frequency ranges and energies are distinguished (the larger the wavelength, the lower the frequency and energy). Especially long-wavelength radiation with a wavelength greater than 30 cm is called radio wave radiation; radiation in the range of 0.1 to 30 cm is called so-called microwave radiation. In the range between 750 nm and 0.1 cm, one speaks of infrared radiation, also known as heat radiation, because it is perceived by the body as heat. Between 400 and 750 nm, electromagnetic radiation appears as visible light. The color of the light depends on the exact wavelength of the radiation: red ≈ 750 nm, yellow ≈ 550 nm, green ≈ 500 nm, blue ≈ 460 nm, violet ≈ 400 nm. Electromagnetic radiation with even shorter wavelengths is particularly energetic and therefore potentially harmful. In the range from 10 to 400 nm, it is called UV radiation, which can cause skin cancer; at wavelengths up to about 10 pm it is called X-ray radiation, and at even shorter wavelengths gamma radiation.

How are the energy of a photon and the frequency of the radiation related?
- The energy of a photon is the product of the frequency of the radiation and the so-called Planck constant h (Planck’s quantum of action).

What is additive color mixing?
- Light consisting of only one wavelength, i.e. monochromatic light, is perceived as its respective color. When different wavelengths are added, the color perceived can be predicted using the color circle: blue and red add up to pink, green and blue add up to turquoise, and green and red add up to yellow. Additive color mixing is also the reason why light consisting of all wavelengths in the visible range is perceived as white.

### Interactions between Light and Matter

What is refraction, when does it occur, and how can it be described using the refractive index?
- Refraction refers to the change in direction of the propagation of light that occurs when light passes from one medium into another (e.g., at the interface between air and water). Refraction of light is thus a form of interaction between light and matter. When light passes from one medium into another, its propagation speed changes depending on the optical density of the medium, which can be quantified by its refractive index (n). If during this process the frequency of the light remains the same, the wavelength also changes. The greater the difference between the refractive indices of two media, the greater the refraction (change in direction). When light passes from an optically dense medium (high n) into an optically less dense medium (low n), light speeds up and bends away from the normal – the refraction angle is thus larger than the incidence angle. When light passes from an optically less dense medium (low n) into an optically dense medium (high n), light slows down and bends toward the normal – the refraction angle is thus smaller than the incidence angle.

Describe the absorption of light using the Lambert-Beer's law!
- Absorption occurs with every interaction between matter and light. Along with other effects such as reflection and scattering, radiation absorption weakens the intensity of radiation (extinction). Absorption of radiation can be calculated using Lambert-Beer's law. In its simplified form, it states that the decimal logarithm of the quotient of “intensity before absorption” divided by “intensity after absorption” corresponds to the product of the path length through the medium, concentration, and extinction coefficient.

What is meant by the half-value thickness?
- The half-value thickness refers to the path length that light must travel in a medium so that its original intensity is reduced to half. It can be calculated by dividing the decimal logarithm of 2 by the extinction coefficient.

### Optical Devices

Explain the relationship between image size and image distance of a converging lens!
- A converging lens is a convex lens that bundles the light rays incident upon it. If one does not want to construct the image geometrically, it can be calculated, since the quotient of image size to object size is always equal to the quotient of image distance to object distance.

What does it mean to wear glasses with a strength of 2 dpt?
- 2 dpt or “2 diopters” is the strength of the refractive power of the lenses. The refractive power of a lens can be calculated with the so-called “lens equation.” It states that the refractive power equals the reciprocal of the focal length of the lens. This is the sum of the reciprocals of the object distance and the image distance. The unit dpt thus corresponds to the SI unit 1/m. Glasses with a strength of 2 dpt can be used to correct farsightedness so that nearby objects can still be seen sharply. For this purpose, convex lenses are needed.

What applies to the resolution of a light microscope?
- The resolution of a microscope is the smallest distance between two points that can still be perceived as separate. It is calculated as the quotient of the wavelength of the light used divided by the aperture of the microscope. The aperture is a device parameter that can be calculated as the product of the refractive index and half the opening angle of the microscope. It becomes clear that the resolution becomes greater the smaller the wavelength of the radiation used.

Explain the working principle of an immersion liquid!
- Immersion liquids are liquids that are applied to a specimen to be examined under a microscope in order to increase the microscope’s resolution. The effect of the immersion liquid is due to the fact that the aperture and thus the resolution of a microscope are proportional to the refractive index n. Since an immersion liquid has a greater refractive index than air, its use leads to an increase in resolution.
### Open Questions on the chapter Optics and Optical Devices

What is light?

Explain what electromagnetic radiation is and what different types of radiation are included!

How can light interact with matter?

How does a rainbow occur?

How does one geometrically construct the ray path at a converging lens or at a diverging lens?

How does a light microscope work?

What is measured during an absorption measurement?
