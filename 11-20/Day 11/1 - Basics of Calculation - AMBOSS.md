# Basics of Calculation
## Summary

Mathematical fundamentals are not only relevant for many exam questions: In the everyday work of most doctors, simple calculations must also be performed, such as dosage adjustments based on patient weight or kidney function. A selection of some fundamental concepts relevant for medical professionals is compiled in this chapter.
## Resolutions for Units of Measurement

Physical units can be extended by so-called prefixes (Latin: prefixes) by powers of ten.

- Powers of ten with a positive exponent: The exponent corresponds to the number of zeros following the 1.
- Powers of ten with a negative exponent: The exponent corresponds to the number of decimal places.

|Intention Symbol|Intention Name|Numerical Value|
|---|---|---|
|M|Mega-|106 = 1,000,000|
|k|Kilo-|103 = 1.000|
|h|Hecto-|102 = 100|
|d|Deci-|10−1 = 0.1|
|c|Centi-|10−2 = 0.01|
|m|Milli-|10−3 = 0.001|
|μ|Micro-|10−6 = 0.000001|
|n|Nano-|10−9 = 0.000000001|
|p|Piko-|10−12 = 0.000000000001|
|f|Femto-|10^-15 = 0.000000000000001|
## Rule of Three

### Calculating with the Rule of Three

The rule of three is a solution strategy in mathematics for rearranging simple ratio equations in two steps. It not only leads to the correct solution in many IMPP questions but is also very useful, for example, for dosage calculations in anesthesia.

- Starting equation: aX equals bY
    - Here, a and b are fixed numerical values.
    - X and Y are variables that can, for example, stand for a unit.
- Question: What corresponds to cX?
- Solution Strategy
    1. Isolate X: Divide both sides by a.
    2. Make X into cX: Multiply both sides by c.
- Result: cX corresponds to (cb / a) Y

### Calculation Examples

- Example 1
    - An athlete produces 200W of power with an efficiency of 20%. What is his total physical power output?
        - Given: 20% corresponds to 200 W.
        - Sought: How much is 100%?
        - Solution
            1. Divide both sides by 20: 1% corresponds to 10 W.
            2. Multiply both sides by 100: 100% equals 1.000 W.
- Example 2 (Special Case): Sometimes the starting equation is already in the form X equals bY, then the 1st step is unnecessary.
    - A 70 kg patient is to receive 2 mg/kg of Propofol for anesthesia induction. How many mg of Propofol need to be administered?
        - Given: 1 kg corresponds to 2 mg of Propofol.
        - Sought: How much propofol corresponds to 70 kg?
        - Solution: 1 kg × 70 equals 2 mg × 70 = 140 mg
## Vector Calculation and Pythagorean Theorem

### Vector Calculation

To describe a force, it is not enough to say how strong this force is. Equally decisive is the direction in which the force acts. The direction of a physical quantity is mathematically described using vectors.

- Definition: A vector is, simply put, a physical quantity that has a magnitude (length) and a direction.
    - Examples: force, momentum
- Addition of two vectors: When you want to add two vectors, in general, you cannot simply add the magnitudes of the vectors.
    - One arranges the vectors in such a way that they form two sides of a triangle → The third side of the triangle then corresponds to the sum vector of the two vectors.
    - For the calculation of the length of the sum vector, there are two simple special cases.
        - The angle between the vectors is 90° → Calculation using the Pythagorean theorem
        - The angle between the vectors is 120° and the vectors are of equal length → Equilateral triangle → The resultant vector is equal in length to the original vectors.

### Geometry – The Triangle

This geometric figure reappears even after school. In every triangle, the angles of the triangle add up to 180°. The geometric relationships described below also apply to vector calculus. We will focus here particularly on the right triangle and the equilateral triangle.

#### Pythagorean Theorem

In a triangle with a 90° angle (right angle), the lengths of the sides can be easily calculated using the Pythagorean theorem.

- Pythagorean theorem: In a triangle with a right angle between the sides a and b, the length of the third side c is given by: a² + b² = c²
- Calculation example: Two perpendicular velocity vectors have magnitudes of 0.8 m/s and 0.6 m/s. What is the magnitude of the total velocity?
    - Solution: 0.82 + 0.62 = 0.64 + 0.36 = 1.00 = c2 → c = 1.00 [m/s]

#### Angle Calculation

In a right-angled triangle, there is a fixed ratio between an angle and the length ratio of any two sides. However, for the calculations, we need a few vocabulary words that some may still remember from middle school:

- Hypotenuse: The longest side of the triangle, opposite the right angle.
- Adjacent side: The side that borders the angle α and the right angle
- Opposite side: The side that lies opposite angle α and is adjacent to the right angle.

The following relationships apply here:

- Sine: sin α = Opposite side/Hypotenuse
- Cosine: cos α = Adjacent side/Hypotenuse
- Tangent: tan α = Opposite side/Adjacent side

|Angle α|0°|30°|45°|60°|90°|
|---|---|---|---|---|---|
|sin(α)|0|½|½ √2|½ √3|1|
|cos(α)|1|½ √3|½ √2|½|0|
|tan(α)|0|⅓ √3|1|√3|not defined|

- Calculation example: A ladder stands 1 m away from a wall and leans against the wall at an angle of 60° to the ground. How long is the ladder?
    - Solution: The wall and the ground form a right angle. Since the ladder is opposite the right angle, it is the hypotenuse. Using the cosine (cos α = adjacent / hypotenuse or hypotenuse = adjacent / cos α), we can now calculate the length of the ladder: hypotenuse = 1 m / cos 60° = 1 m / ½ = 2 m → The ladder is 2 m long.

#### Equilateral Triangles

Another special case in which sides can be easily added is equilateral triangles: In a triangle with an angle of 60° and two equal-length sides, all angles are 60° and all sides are of equal length.

## Error Calculation

When a measurement is performed multiple times, it is very likely that the same result will not be obtained each time. Mathematically, this fact can be described with measurement errors, the mean, and the standard deviation. This allows for an assessment of how well the measurement reflects reality.

### Absolute and Relative Error

If a measured value deviates from an exact target value, the difference between the two measured values is referred to as the absolute error. The relative error indicates how large the absolute error is in comparison to the target value.

- Absolute error: Difference between the exact value and the (error-prone) measured value.
    - Δx = xexact - xmeasured
- Relative error: Quotient of absolute error and the exact value
    - δx = Δx / xexact

### Mean and Standard Deviation

Errors in the measurements make it nearly impossible to represent reality with an exact value. Therefore, one tries to estimate how large the real value approximately is (e.g., using the mean) and how much the estimate likely deviates from the real value (e.g., using the standard deviation). Usually, for this estimate, the so-called mean is used: To minimize the influence of measurement errors, several measurements are conducted, and the average (= arithmetic mean) is formed from the results.

- Mean: Average value obtained when all individual values are added together and the sum is divided by the number of individual values.
    - Example: Calculation of the average hair length of 5 medical students
        - 2 cm + 4 cm + 5 cm + 6 cm + 33 cm = 50 cm
        - 50 cm / 5 = 10 cm
        - The average length is 10 cm, the 5 medical students have hair that is on average 10 cm long.
- Harmonic mean: Reciprocal of the arithmetic mean of the reciprocals of the considered numbers.
    - Formula: Harmonic mean of two numbers a and b = 2 / [(1/a) + (1/b)]
    - Example: Harmonic mean of 3 and 6 = 2 / [(1/3) + (1/6)] = 2 / (3/6) = 2 / (1/2) = 4
- Variance: The variance is a measure of the dispersion of the measured values.
    - Sum of the squared deviations from the mean, divided by the number of values
        - Example: Variance of hair lengths of 5 medical students
            - Mean: 10 cm
            - Values: 2 cm, 4 cm, 5 cm, 6 cm, 33 cm
            - Number of values: 5
            - Variance = [(10 − 2)² + (10 − 4)² + (10 − 5)² + (10 − 6)² + (10 − 33)²] / 5 = (64 + 36 + 25 + 16 + 529)cm² / 5 = 670 / 5 = 134[cm²]
- Why is it squared?
    - If all deviations (unsquared) are simply added together, the result is always 0 and therefore not meaningfully usable.
    - Squaring gives greater weight to large deviations than to small ones.
- Problem of squaring
    - The unit of the variable is squared, making the variance counterintuitive and hard to use.
- Solution: Calculation of the standard deviation
- Standard deviation
    - (SD) = Square root of the variance
    - Describes how far the individual values are, on average, from the mean.
    - Example: Variance of hair lengths = 134 cm² → Standard deviation = √134 cm² = 11.6 cm
        - The hair lengths deviate an average of 11.6 cm from the mean!

## Gaussian Normal Distribution

The Gaussian distribution or normal distribution is a specific arrangement of measurement values or probabilities (probability distribution) that can be found in many natural processes. An example of a normally distributed variable is the Hb level.

- Important properties of the Gaussian distribution
    - Graphic representation: Gaussian curve
    - Shape: Bell-shaped and symmetrically distributed around the mean (μ)
    - Distribution of measurements
        - Half of the values lie below the mean, the other half above
        - Approximately 68% of the measurements lie within the range of ±σ (= standard deviation) around the mean (i.e., about 16% lie below or above).
        - The two inflection points of the Gaussian curve lie at a distance of ±σ from the mean.
        - About 95% of the measurements lie within ±2σ of the mean (i.e., approximately 2.5% lie below or above it).
- Application example
    - The average Hb concentration is 9.5 mmol/l with a standard deviation of 0.6 mmol/l. What is the probability that a random subject has an Hb value below 8.3 mmol/l?
    - Solution
        - 95% of the subjects have an Hb level of 9.5 mmol/l ± 2×0.6 mmol/l, which is between 8.3 and 10.7 mmol/l.
        - The Gaussian distribution is symmetric around the mean. → 2.5% of the subjects have an Hb value below 8.3 and above 10.7 mmol/l.

> [!NOTE]
> In a normal distribution, the mode, median, and arithmetic mean are identical!

## Exponential Function and Logarithm

Exponential functions are functions that carry the independent variable in the exponent. They can be used, for example, to mathematically describe growth processes (exponential growth). Logarithmic functions are the inverse functions of the exponential function, so they reverse the exponential function.

### Exponential Function

Exponential functions have a real number a as the base and the independent variable x as the exponent. They play a role in medicine, for example, in radioactive decay.

- Definition: A function of the form y = ax is called an exponential function.
    - Here, a is referred to as the base and x as the exponent.
- Special case: If the base of an exponential function is the Euler number e, the function is also called the natural exponential function or e-function and has special properties.
- Calculation rules
    - ax × ay = ax+y
    - ax × bx = (ab)x
    - (ax)y = axy
    - a−x = 1/ax
- Calculation examples
    - 105 × 106 = 11130
    - 105 × 25 = 205
    - (105)6 = 1030
    - 10−1 = 1/10 = 0.1

### Logarithm

The logarithm is the inverse function of the exponential function. In other words, the logarithm of a number y is the number x that you would need to write as the exponent to obtain y. It is needed, for example, to calculate the half-life of a radioactive decay or the pH value from a given proton concentration.

- Definition: A function of the form x = loga y is called a logarithmic function.
    - Here, a is again the base of the logarithm and corresponds to the base of the associated exponential function (y = ax)
- Example
    - Decimal logarithm: logarithm to base 10, shorthand: lg
    - Natural logarithm: logarithm to the base e, shorthand ln
- Calculation rules: Just as for the exponential function, certain calculation rules apply to the logarithm:
    - loga x + loga y = loga(xy)
    - loga xy = y loga x
    - loga a = 1
- Calculation examples
    - lg 25 + lg 4 = lg 100 = 2
    - log2 43 = 3 log2 4 = 3 × 2 = 6
    - lg 10 = 1
- Interpretation aid: If the decimal logarithm of a quotient is, for example, 2, then lg(a/b) = 2, which means (a/b) = 102 ⇔ (a/b) = 100, from this it follows that a = 100 × b.

### Radian

In physics and mathematics, the radian measure is often used instead of degrees to describe angles: Radian measure and angles are related through the unit circle. Each angle can be assigned a portion of the circumference of the circle, resulting in a dimensionless number instead of a degree measurement. Since the circumference of the unit circle is 2π, 360° corresponds to 2π, 180° to π, 90° to π/2, and so on. The conversion between radians and degrees is straightforward:

- Radian: Length of the arc subtended by the angle on the unit circle
    - Formula: φ = (π / 180°) × Angle in Degrees
        - φ = angle in rad (radian); the formula indicates how to convert an angle in degrees to an angle in rad.
    - Formula: φ = (180° / π) × angle in rad
        - φ = angle in degrees; the formula indicates how to convert an angle in radians to an angle in degrees.
- Example: On a wristwatch, the minute hand has covered a quarter of an hour (α = 90°). The hand is 1 cm long. What distance has the tip of the hand traveled during this time?
    - φ = (π / 180°) × 90° = π/2 ≈ 1.57
    - Since the length of the pointer corresponds to the radius of the unit circle, the tip of the pointer has covered a distance of about 1.57 cm.

## Circles and Spheres

The essential mathematical properties of circles and spheres are also important for calculations in medicine, for example, when calculating the cross-sectional area of a blood vessel or the volume of a tumor. Circles and spheres are characterized by their radius r, which is half of the diameter.

- Circle constant π ("Pi")
    - Required for many calculations involving circles
    - π = 3.14159...≈ 3.14 ≈ 3
- Circle
    - Area A = πr²
    - Circumference C = 2πr
- Kugel
    - Volume V = 4/3 πr3

## Review Questions on the Chapter Fundamentals of Computing
### Resolutions for Measurement Units

What unit prefixes do you know? How can, for example, the powers of ten 10^6, 10^2, 10^-2, 10^-6, 10^-9, and 10^-12 be expressed with a prefix?
- "Mega-" stands for 10^6, "Hekto-" for 10^2, "Centi" for 10^-2, "Mikro-" for 10^-6, "Nano-" for 10^-9, and "Piko-" for 10^-12.
### Rule of Three

The carbohydrate content of a 200 g bar of chocolate is about 120 g. A diabetes patient has eaten a chocolate bar of about 20 g. How can the amount of carbohydrates consumed be calculated and why can this method be applied?
- The carbohydrate content of the bar can be calculated using the rule of three because the two quantities "carbohydrate content" and "amount of chocolate" are always in the same ratio to each other. In this case, 20 g of chocolate contains 20 g / 200 g × 120 g = 12 g of carbohydrates.
The number of bacteria in a sample doubles every 10 minutes. Can the rule of three be applied here to calculate the amount of bacteria after 2 hours?
- No, because the number of bacteria and the elapsed time are not in a constant ratio to each other. If there are originally 5 bacteria, there are already 10 bacteria after 10 min, 20 bacteria after 20 min, 40 bacteria after 30 min, and 80 bacteria after 40 min. The number of bacteria grows much faster than time passes. The ratio between 20 min and 20 bacteria is 20/20 = 1, between 30 min and 40 bacteria is 30/40 = 0.75, between 40 min and 80 bacteria is 40/80 = 0.5. The ratio is therefore not constant and the rule of three cannot be applied. How the number can be calculated is taught in the section on exponential functions.
### Vector Calculation and Pythagorean Theorem

What does the Pythagorean theorem state?
- The Pythagorean theorem states that in a triangle with a right angle between sides a and b, for the third side c the following holds: c² = a² + b².
What do the terms "hypotenuse," "opposite side," and "adjacent side" refer to in a right triangle with an additional given angle α?
- The hypotenuse is always the side of the triangle opposite the right angle. The opposite side lies opposite the angle α, the adjacent side borders on the angle α and the right angle.
What relationships for side lengths apply in relation to an acute angle α in a right triangle?
- The following ratios apply in a right-angled triangle with an acute angle α: sin α = opposite side / hypotenuse, cos α = adjacent side / hypotenuse, tan α = opposite side / adjacent side.
### Error Calculation

What is the difference between absolute error and relative error?
- If a measured value deviates from an exact target value, the absolute error indicates the difference of the measured value from the exact value. The relative error sets this difference in relation to the exact value (target value - measured value / exact value).
How are the arithmetic mean and the harmonic mean calculated?
- For the arithmetic mean, all individual values are added and the sum is divided by the number of individual values. Example: The arithmetic mean of a and b is (a + b) / 2. The harmonic mean is the reciprocal of the arithmetic mean of the reciprocals of the individual values. Example: The harmonic mean of a and b is 2 / [(1/a) + (1/b)].
What is the standard deviation?
- The standard deviation is a measure of the deviation of measured values from the mean.
### Gaussian Distribution

What does a Gaussian distribution look like?
- It is a bell-shaped, symmetrical distribution of measured values around the mean (so-called normal distribution).
How much percent of the measurements lie within and outside of ±1 standard deviation, ±2 standard deviations, as well as above and below the mean?
- In a Gaussian distribution, 68% of the measured values lie within the range of ±1 standard deviation, 32% lie outside, i.e. 16% above and below respectively. 5% of the measured values lie outside the range of ±2 standard deviations, i.e. 2.5% below and above respectively, 95% lie within the range. Half of the measured values respectively lie above and below the mean, since the Gaussian distribution is symmetrical.
Which statistical measure corresponds to the distance of the inflection points from the mean?
- The standard deviation corresponds to the distance of the inflection points from the mean.
### Exponential Function and Logarithm

A fairground visitor wants to participate in two games of chance. In a raffle, he has a probability of winning a bicycle of 10^-3 (i.e., 1 ticket out of 1000 wins), and in a prize wheel, he has a probability of winning a stuffed animal of 10^-1 (i.e., 1 section out of 10 wins). He correctly considers that the probability of winning both is 10^-3 × 10^-1. Provide the solution in various notations and name the appropriate arithmetic laws!
- 10^-3 × 10^-1 = 10^-3+(-1) = 10^-4 = 1/10^4. In other words, the probability of winning both games is 1/10000 or 0.0001. The calculation is based on the following exponent laws: a^x × a^y = a^(x+y) and a^-x = 1/a^x.
The result of the following calculations is always the same – name the result and formulate the corresponding general calculation rule: a) 10^2 × 10^4 b) 2^6 × 5^6 c) (10^3)^2 d) 1/10^-6
- The problems can be solved with the rules of exponents and a bit of mental math. The result is always 10^6. a) 10^2 × 10^4 = 10^(2+4) = 10^6, the corresponding exponent rule is: a^x × a^y = a^(x + y). b) 2^6 × 5^6 = (2 × 5)^6 = 10^6 or generally formulated: a^x × b^x = (a b)^x. c) (10^3)^2 = 10^(3×2) = 10^6, the corresponding exponent rule is: (a^x)^y = a^(xy). d) 1/10^-6 = 1/(1/10^6) = 10^6 or generally formulated: a^-x = 1/a^x.
The result of the following calculations is always the same – name the result and formulate the corresponding general calculation rule: a) log_10 500 + log_10 20 b) 0.5 × log_2 (16^2) c) 5 - log_13 13
- Applying the logarithm laws, the problems can be easily solved with some mental arithmetic. The result is always 4. a) log_10 500 + log_10 20 = log_10 (500 × 20) = log_10 10000 = 4, the corresponding logarithm law is: log_a x + log_a y = log_a (x × y). b) 0.5 × log_2(16^2) = 0.5 × 2 × log_2 16 = 4, the law log_a x^y = y log_a x was applied here. c) 5 - log_13 13 = 5 - 1 = 4, generally formulated the law behind this calculation is log_a a = 1.
What is the base of the decimal logarithm? What is lg 1000?
- The decimal logarithm has base 10. lg 1000 = 3, since 1000 = 10 × 10 × 10 = 10^3.
What is the base of the natural logarithm?
- The natural logarithm has base e.
### Radian

What is the radian measure?
- The radian measure is an alternative to degrees to describe an angle. The angle is understood as an arc segment of a unit circle whose arc length corresponds to the radian measure.
How can degrees be converted to radians and vice versa?
- The angle in radians can be converted into the angle in degrees as follows: angle in radians = π / 180 × angle in degrees. Conversely, angle in degrees = 180 / π × angle in radians.
### Circles and Spheres

How are the area and circumference of a circle calculated?
- For the circle: area A = π r^2 and circumference U = 2 π r, where π is approximately 3.
How is the volume of a sphere calculated?
- The volume of a sphere is calculated by: V = 4/3 π r^3.