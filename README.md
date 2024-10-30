# Delta-Cepheid
Code behind the project comparing observational results of three telescopes on Delta Cepheid to answer the question: How does the comparison between distances to δ Cep calculated via primary data gathered with amateur and professional equipment, and professional secondary data, indicate the impact of primary error sources when amateur astronomers embark on observation-based astronomical research?


The subject of this study, δ Cep, belongs to the category of Cepheid Variable stars (CVS), which are distinguished by their fluctuation in both diameter and temperature, leading to changes in brightness with a consistent and predictable period and amplitude (Dejoie, 2018). The methodology for observing and quantifying CVS is both time-tested and well-documented, providing a structured approach I could emulate (AAVSO, 2013). Notably, Henrietta Swan Leavitt, the founder of CVS research, identified a period-luminosity correlation, known as the Leavitt Law, which relates the absolute magnitude of Cepheid variable stars to their oscillation period (Hartman, 2018). That, in conjunction with the distance modulus, furnishes a mechanism to extrapolate a CVS’s distance from Earth.
The distance modulus formula provides a method to calculate the distance (d) to a
star using its apparent magnitude(m), the logarithmically scaled measurement of an
object’s brightness observed on earth, and absolute magnitudes (M), the logarithmically
scaled measurement of an object’s brightness at a characteristic distance of 10 parsec(pc):
𝑚−𝑀 +1 𝑑 = 10 5
Thus to experimentally compute the distance, the only value needed is that of absolute and apparent magnitude. Both values can be ascertained by collecting two weeks’ worth of data on the CVS’s apparent magnitude and plotting them on a light curve. While the apparent magnitude of the star is derived by averaging these data points, calculating the absolute magnitude requires the aforementioned Leavitt Law. Given the variable nature of the CVS's magnitude, the plotted data results in an oscillating light curve. This oscillation allows for an estimation of the CVS's period by measuring the time interval between the peaks and troughs. With this period in hand, I can then derive the absolute magnitude through the period-luminosity relationship specific to CVS.

