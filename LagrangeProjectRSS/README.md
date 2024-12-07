# LagrangeProjectRSS
Adds Lagrange point to RSS (Real Solar System) Mod in KSP using patched conics logic.

KSP, By default, does not allow Lagrange points (without use of principia); This is simply due to orbital mechanics 101/kepler's law.

However, you can change the orbital period of bodies by modifying configurations using the period = setting under Orbit. This allows for customized orbital periods.

By changing the semi-major axis to the desired Lagrange point location and inheriting eccentricity, inclination, mean anomaly, ascending node, and argument of periapsis from the parent planet, you can create stable Lagrange points.
By Tidal locking the lagrange point, you can find good estimate of their orbital period which will give one a good estimate on fine-tuning lagrange points.

Due to KSP's built-in rotation period only showing down to hours/minutes, Further accuracy adjustment requires finetuning by hand via manually adjusting orbital period of lagranges. (Please let me know if there's a way to see orbital period of planets and moons)

This is essentially what the mod does (And Lagrange Project by LucalisIndustries at https://forum.kerbalspaceprogram.com/topic/220855-lagrange-project/).

Currently, SOI for these lagrange points are set at 2000km for planets and 500km for moons.


