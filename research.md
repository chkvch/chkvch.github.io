---
layout: page
title: Research
permalink: /research/
---
# Sounding Saturn's Interior using Ring Seismology
<!-- ![alt text](/assets/saturn_olr.png "Saturn's fundamental oscillations in the rings"){:style="float: right;margin-right: 2px;margin-top: 2px;"}{:height='300px'} -->
![alt text](/assets/saturn_olr.png "Saturn's fundamental oscillations in the rings"){:style="float: right;"}{:height='300px'}
The interior structure of the giant planets are traditionally constrained by their gravity fields, which NASA's [Juno][juno] and [Cassini][cassini] missions measured to exquisite precision for Jupiter and Saturn respectively. Analysis of those data have [already revealed Jupiter's interior in unprecedented detail][juno_news_and_views], and similar work is underway for Saturn.

A very different dataset obtained by Cassini observations of Saturn's rings is proving to challenge our understanding of Saturn's interior as well. It has been known since the time of the [Voyagers][voyager] that the rings are studded with waves driven by resonant forcing by Saturn's moons, but Cassini observations have made it possible to identify a subset of these waves that are driven by resonances with the free oscillations of Saturn itself. The precise determination of the frequencies and number of spiral arms that Cassini scientists have been able to achieve for each of these roughly 20 waves associated with Saturn oscillations has generated an extremely well-resolved power spectrum, making it possible to do seismology of a giant planet for the first time.

This figure from [our 2019 paper][fmodes_paper] compares the locations of Lindblad (horizontal) resonances that we expect for Saturn's fundamental tones given our interior models (green/yellow bars) to the observed locations of spiral density waves that propagate toward Saturn (open symbols), the signature of waves caused by perturbations inside the rings. We used our Saturn models to confirm that Saturn's fundamental tones are the origin of the vast majority of these waves. Then we leveraged the fact that these frequencies are modulated by Saturn's rotation to measure Saturn's bulk rotation rate, a quantity which has been notoriously tough to determine through other means. For a more thorough discussion and background, see this excellent [blog post][emilyl_blog] from Emily Lakdawalla at [The Planetary Society][planetaryorg].

# Helium rain in Jupiter and Saturn
The mesmerizing flows in the atmospheres of the gas giants are well known, but beneath the surface things get even stranger. Whereas the plasma in the interior of the Sun can be understood to a fair approximation as an ideal gas, Jupiter and Saturn are cold and dense enough that the matter in their deep interiors takes the form of fluid metallic hydrogen, a highly conductive and yet free-flowing material believed to be the medium for the generation of Jupiter and Saturn's strong magnetic fields.

There is a curious phenomenon predicted to accompany the transition from ordinary molecular hydrogen to fluid metallic hydrogen at around a million times atmospheric pressure: the phase separation of helium, the second most abundant constituent of these planets and the universe at large. Much like cloud or fog formation in our own atmosphere is driven by the condensation of water vapor in air cooled below its dew point, a fraction of the helium mixed into the liquid metallic hydrogen deep in a gas giant tends to separate from the mixture. If the microscopic pockets of helium-rich material manage to grow large enough (around a millimeter in size) by atomic diffusion, then helium-rich droplets can rain out of the otherwise well-mixed medium.

![alt text](/assets/saturn800.gif "Helium rainout over the lifetime of Saturn"){:style="float: left;margin:0 20px 0 0"}{:height='300px'}
This figure is a simulation of how the helium distribution inside Saturn may have evolved over the history of the solar system. The initially uniform mixture of hydrogen and helium accreted from the protosolar nebula eventually differentiates as a result of the planet's incessant cooling driven by its contraction. We think this helium rain is a significant power source for Saturn, where well-mixed models have historically failed to predict Saturn's large observed intrinsic luminosity. In [our 2016 paper][jupiter_paper] we built similar models for helium rain in the evolution of Jupiter. From these simulations we estimated the degree to which helium rain inhibits convection in favor of double-diffusive convection, and derived constraints on the hydrogen-helium phase diagram such that the helium depletion from Jupiter's surface is consistent with the 1998 _in situ_ measurement by the Galileo Entry Probe.


# Trapping of mixed modes as a clock for red clump stars
A star the mass of the Sun will eventually exhaust the hydrogen available for nuclear fusion at its center, reorganizing itself into a red giant that will spend of order a hundred million years fusing hydrogen in a shell. Once this fusion has produced a degenerate, nearly pure helium core of sufficient mass to trigger fusion of helium by the triple-alpha process, the star will undergo helium core flashes before settling into quiescent core helium burning as a red clump star.

Red giants generally support mixed modes, in which acoustic overtone (p-)modes with high amplitudes in the star's convective envelope tend to undergo degenerate mixing with internal gravity (g-)modes occupying the star's stably stratified helium core. For a star that undergoes the helium core flash, the high-gravity degenerate core present at the onset of the helium core flash produces an abrupt abundance transition from nearly pure helium to the protostellar hydrogen-helium mixture. This transition produces a formidable feature in the Brunt-Väisälä frequency, tending to trap g-modes on one side or another of the transition. The frequencies of the g-modes are accordingly changed, producing a quite complicated spectrum of mixed modes observable by the [_Kepler_][kepler] or [_CoRoT_][corot] spacecraft.

![alt text](/assets/perspac_clump.png "Diffusion and nuclear fusion erode the sharp H-He transition in young red clump stars"){:width='700px'}

The figure here shows the complexity of the spectrum of dipole (_l_=1) mixed modes at early times on the red clump, where g-dominated mixed modes (those with the highest mode inertia _E_) deviate dramatically from the asymptotic expectation for the g-mode period spacing of ~250 s. Over some tens of millions of years, the combination of atomic diffusion at the density interface and the reestablishment of hydrogen shell fusion act to erode this steep barrier to g-mode propagation, relaxing the period spacings of g-dominated mixed modes back to the asymptotic prediction. The variance in period spacings observed for stars like these can thus differentiate between young and evolved clump stars, in spite of their having similar luminosities, surface gravities, and effective temperatures.

[juno]: https://www.nasa.gov/mission_pages/juno/main/index.html
[cassini]: https://solarsystem.nasa.gov/missions/cassini/overview/
[voyager]: https://voyager.jpl.nasa.gov/
[juno_news_and_views]: https://www.nature.com/articles/d41586-018-02612-y
[fmodes_paper]: http://adsabs.harvard.edu/abs/2019ApJ...871....1M
[jupiter_paper]: http://adsabs.harvard.edu/abs/2016ApJ...832..113M
[emilyl_blog]: http://www.planetary.org/blogs/emily-lakdawalla/2018/how-long-is-a-day-on-saturn.html
[corot]: http://sci.esa.int/corot/
[kepler]: https://www.nasa.gov/mission_pages/kepler/main/index.html
[planetaryorg]: http://planetary.org/
