
Published with permission of Kluwer Academic Publishers, Dordrecht,
Boston, London
 
 
------------------------------------------------------------------------
Space Science Reviews 60: 283-307,1992.
Copyright 1992 Kluwer Academic Publishers. Printed in Belgium.
------------------------------------------------------------------------
 
 
              THE PLASMA INSTRUMENTATION FOR THE GALILEO MISSION
 
 
    L. A. FRANK, K. L. ACKERSON, J. A. LEE, M. R. ENGLISH, and G. L.
    PICKETT
 
 
     Department of Physics and Astronomy, The University of Iowa, Iowa
                                City, IA 52242, U.S.A
                                 [FRANKETAL1992]
 
 
Abstract. The plasma instrumentation (PLS) for the Galileo Mission
comprises a nested set of four spherical-plate electrostatic analyzers
and three miniature, magnetic mass spectrometers. The three-dimensional
velocity distributions of positive ions and electrons, separately, are
determined for the energy-per-unit charge (E/Q) range of 0.9 V to 52 kV.
A large fraction of the 47 pi-steradian solid angle for charged particle
velocity vectors is sampled by means of the fan-shaped field-of-view of
160 deg, multiple sensors, and the rotation of the spacecraft spinning
section. The fields-of-view of the three mass spectrometers are
respectively directed perpendicular and nearly parallel and
anti-parallel to the spin axis of the spacecraft.  These mass
spectrometers are used to identify the composition of the positive ion
plasmas, e.g., H+, O+, Na+, and S+, in the Jovian magnetosphere. The
energy range of these three mass spectrometers is dependent upon the
species. The maximum temporal resolutions of the instrument for
determining the energy (E/Q) spectra of charged particles and mass (M/Q)
composition of positive ion plasmas are 0.5 s.  Three-dimensional
velocity distributions of electrons and positive ions require a minimum
sampling time of 20 s, which is slightly longer than the spacecraft
rotation period. The two instrument microprocessors provide the
capability of inflight implementation of operational modes by
ground-command that are tailored for specific plasma regimes, e.g.,
magnetosheath, plasma sheet, cold and hot tori, and satellite wakes, and
that can be improved upon as acquired knowledge increases during the
tour of the Jovian magnetosphere.  Because the instrument is
specifically designed for measurements in the environs of Jupiter with
the advantages of previous surveys with the Voyager spacecraft, first
determinations of many plasma phenomena can be expected. These
observational objectives include field-aligned currents,
three-dimensional ion bulk flows, pickup ions from the Galilean
satellites, the spatial distribution of plasmas throughout most of the
magnetosphere and including the magnetotail, and ion and electron flows
to and from the Jovian ionosphere.
 
 
1. Introduction
 
 
Although the first direct detection of the presence of plasmas in the
vicinity of Io's orbit was reported by Frank et al. (1976) with
measurements from the plasma analyzer on Pioneer 10, the first
definitive measurements of Jovian magnetospheric plasmas were acquired
during the Voyager flybys. The Voyager plasma observations were used to
define the required capabilities for the Galileo plasma instrumentation.
Briefly we summarize here the plasma domains of the Jovian
magnetosphere. This information is largely taken from the review by
Belcher (1983). For more recent work the reader is referred to further
analysis of the torus ions (Bagenal, 1985; Bagenal et al., 1985), the
torus electrons (Sittler and Strobel, 1987), and the middle
magnetosphere (Sands and McNutt, 1988). Measurements of medium-energy
charged particles, E approx. > 30 keV, are summarized by Krimigis and
Roelof (1983).
 
The heart of the Jovian magnetosphere is the great torus of plasmas that
encompasses the orbit of Io. This torus is fed by the ionization of
neutral gases from Io's atmosphere and may respond to the sporadic
injection of gases from this moon's volcanic activity. The composition
of the ion plasmas in this torus is rich in heavy ions, e.g.,
S+, O+, S2+, O2+, and Na+. The plasma torus is divided into two regimes,
cold torus inside Io's orbit and a hot torus at greater Jovicentric
distances. The maximum ion densities, ~ 3000 cm**-3, are located near
Io's orbit. The ion temperature decreases severely from ~ 40 eV at 6
RJ (Jovian radii) to ~ 1 eV at 5 RJ. This temperature decrease is due to
radiative cooling. Ion temperatures in the hot torus at radial distances
~ 6 to 8 RJ are in the range of 40 to 100 eV. The electron temperatures
can be described in terms of a two-temperature Maxwellian distribution,
i.e., a cold and hot distribution. At the inner edge of the torus the
electron temperatures decrease to ~ 0.5 eV with decreasing radial
distances whereas the cold electron temperatures beyond ~ 6 RJ are
typically ~ 10 to 100 eV. Characteristic temperatures of the hot
electron velocity distributions are ~ 1 keV and the number densities are
less than those for the cold electrons. The torus plasmas corotate with
the planet. The corresponding corotational energy of an S+ ion is 960
eV at equatorial radial distance 6 RJ. The deflection of plasma bulk
flow near the Io flux tube is consistent with that expected for
incompressible flow around a cylinder and is evidence for an Alfven wave
associated with the plasma flow past Io. The estimated current in the Io
flux tube is ~ 3 x 10**6 A, presumably carried in large part by
electrons.
 
At distances beyond the plasma torus, > 10 RJ, a plasma sheet extends to
the dayside magnetopause. At 15 RJ the typical thickness of the plasma
sheet is ~ 2 RJ. These plasmas are observed to corotate more-or-less
rigidly with Jupiter's rotational motion to radial distances of about 20
RJ. At distances of 20 to 40 RJ this azimuthal bulk speed of the plasma
is less than that expected from rigid corotation by factors of 2 or
 more. Beyond 40 RJ the plasmas are again observed to rigidly corotate
 at frequent times as inferred from measurements with the
medium-energy charged particle detector. The corotational energy of an
S+ ion at 40 RJ is 43 keV. Whereas the density of the hot electrons is
only ~ 1% of the total density at 8 RJ, the hot electron density is
similar to that for the cold electrons at 40 RJ. Ion temperatures are
also higher in the plasma sheet relative to those in the torus, ~ 20 to
40 keV at radial distances 30 to 100 RJ.  Plasma densities in the plasma
sheet are ~1 to 10 cm**-3 at 10 to 20 RJ and vary from ~10**-3 to 1
cm**-3 at larger radial distances. Above and below the plasma sheet the
densities can be as low as 10**-5 to 10**-4 cm**-3.
 
Beyond radial distances of 130 R, in the dawn side of the Jovian
magnetosphere the ion bulk flows become generally anti-sunward with a
strong component along directions that are radially outward from the
planet. This region was detected with the medium-energy charged particle
detector and is called the magnetospheric wind.
 
 
2. Advantages of the Galileo Plasma Measurements
 
 
The Galileo Mission advantages for plasma investigations in the Jovian
magnetosphere are (1) the spinning section of the spacecraft, (2) an
instrument microprocessor to restructure the instrument operation by
ground command, and (3) a series of orbits that allow close flybys of
the Galilean satellites, a survey of the Jovian magnetotail, and a
substantial local-time survey of the magnetosphere. The spinning section
of the spacecraft provides the important capability for a suitably
designed instrument to view the entire 47 pi-steradian solid angle for
particle velocity vectors at the spacecraft position.  The instrument
microprocessor can be used to tailor the operation of the plasma
instrument for the most effective measurements in each of the diverse
plasma regimes of the magnetosphere and its environs, e.g.,
magnetosheath, plasma sheet, satellite wake or flux tube, or
magnetospheric wind. Targeted encounters with the satellites and a tour
of the magnetosphere and magnetotail offer exceptional opportunities for
studies of most of the important plasma regions and their temporal
responses to variations of Iogenic and solar wind plasmas, and the
interactions of magnetospheric plasmas with the satellites.
 
The Galileo plasma instrumentation (PLS) is substantially more capable
for measurements of the Jovian plasmas than those of the Pioneer and
Voyager spacecraft because it is specifically designed for this purpose.
The basic advantages are in the performance areas of (1) extended energy
range, (2) coverage of the angular distributions of plasmas, (3) angular
resolution, (4) temporal resolution, and (5) ion composition.
 
The energy-per-unit charge ranges of the Pioneer and Voyager plasma
instruments are 100 to 4800 V and 10 to 5920 V, respectively. The
corresponding range of the Galileo plasma analyzer is 0.9 to 52000 V.
This extended energy range spans the important energy gap between 5920
and 30000 V in the combined performances for the Voyager plasma
instrument and medium-energy particle detectors. The 47 pi-steradian
solid angle for particle velocity vectors at the spacecraft position is
sampled adequately to provide determinations of the three-dimensional
velocity distributions for positive ions and electrons. Thus such
important plasma parameters as field-aligned currents, cross-field
currents, plasma bulk flow velocities, heat fluxes, and free energy are
to be determined for the first time with the Galileo instrument. The
angular resolution is sufficient to provide definitive measurements of
the above plasma parameters. Temporal resolutions for obtaining electron
and positive ion spectra are about 200s for the Pioneer analyzer (ions
only) and about 100s for the Voyager Faraday cups. The corresponding
temporal resolution for the Galileo plasma analyzer is about 0.5s;
complete three-dimensional velocity distributions for positive ions
and electrons can be telemetered once each 20s.  These improved temporal
resolutions are particularly important during the brief encounters with
the satellites and the traversals of plasma boundaries such as those of
the plasma sheet and current sheet in the middle and outer
magnetospheres.
 
Three miniature mass spectrometers which are positioned at the exit
apertures of the electrostatic analyzers in the Galileo instrument
provide determinations of the positive ion composition. The Voyager
determinations of ion composition from E/Q spectra are model-dependent
and are possible when the Mach number of the corotational flow is
greater than 5 or 6. This method is acceptable generally near the Io
orbit but as the Jovian radial distance increases, ion thermal speeds
rapidly increase and prevent decisive identification of ion species. The
Galileo mass spectrometers provide a direct determination of ion
composition, specifically the mass-per-unit charge.
 
In addition to the above performance features, the Galileo plasma
analyzer can be operated flexibly via electronic reconfiguration by
ground command. The operational configuration of energy-per-unit charge
(E/Q) passbands, mass-per-unit specific plasma region. The temporal
resolution for a given measurement can also be selected. The Galileo
plasma analyzer is equipped with sufficient onboard hardware and
software to implement automated beam capture modes for ion velocity
distributions and for determination of ion composition.
 
 
3. Several Anticipated Scientific Results
 
 
The capabilities of the Galileo plasma instrumentation are demonstrated
here by application to several plasma regimes in the Jovian
magnetosphere.
 
As the Galileo spacecraft crosses the plasma sheet in the middle and
outer magnetospheres the magnitudes of field-aligned and cross-field
currents are determined.  Their values and location are correlated with
the position of the current sheet as found with the magnetometer. The
motions of the plasma sheet are directly determined from the
three-dimensional bulk flow vector and the azimuthal component is
separated from the radial outflow or inflow. Angular distributions and
ion compositions are examined in order to discern the contributions of
electrons and ions from the ionosphere, the solar wind via the
magnetosheath, and Io in the inner magnetosphere. Thus the formation and
dynamics of the plasma sheet can be understood. The mechanism for the
unusual heating of plasma with increasing radial distance is expected to
be identified.
 
The encounters with the Galilean satellites offer exciting opportunities
for observing plasma phenomena. Examination of the ion velocity
distributions in the wakes of these satellites is used to determine the
mechanism for ion loss from these bodies. The effectiveness of
ion pickup by the magnetospheric plasma flow is derived from the
signatures in the velocity distributions of these ions. The mass
spectrometers are used to identify the major ions produced in the
vicinity of the satellite. For Io these ions include O+, S+, and SO2+,
and for icy satellites perhaps H+, C+, and H2O+ can be found. Such
measurements give the rate of mass loss from each satellite.
Perturbations of the plasma flow can be identified in terms of the
conductivity of the satellite. During the closest satellite encounters
it is possible that a magnetopause or ionopause is detected, thus
providing further information concerning the magnetic and atmospheric
properties of that body. If the flyby of the satellite is polar,
detection of strong field-aligned currents to and away from the Jovian
ionosphere might be expected. Field-aligned acceleration of ions and
electrons by electrostatic double layers or anomalous resistivity is
possible. The relative contributions of the various Galilean satellites
for providing the ions in the plasma torus and sheet are assessed during
the encounters.
 
The substantial periods of time that the Galileo spacecraft is located
in the plasma sheet offer the unique opportunity to view the responses
of the Jovian magnetosphere to the volcanic activity on Io. If specific
Io volcanic eruptions can be identified with temporal fluctuations in
densities, composition, and motions of the plasma sheet, remarkable
advances in our knowledge of the transport of mass and momentum in the
Jovian magnetosphere are envisioned.
 
Simultaneous observations of three-dimensional plasma velocity
distributions and of plasma waves with the Galileo spacecraft allow the
first studies of wave-particle interactions in the wide-ranging types of
plasmas in the Jovian magnetosphere. A discussion of measurements of
plasma waves during the Voyager encounters has been given by Gurnett and
Scarf (1983). For example, the velocity distributions of ions can be
examined to determine whether or not resonant acceleration by
ion-cyclotron waves is an important mechanism for ion heating in the
torus and plasma sheet. Further the amplitudes of broadband
electrostatic noise can be compared with plasma velocity distributions
to determine the importance of the anomalous resistivity in plasma
heating. Free-energy sources, e.g., ring distributions in the electron
velocity distributions, for the generation of electron cyclotron or
upper hybrid waves may be identified and related to the wave amplitudes
observed with the plasma wave instrument. In general the direct
measurement of the plasma density and other parameters gives the growth,
propagation and resonance conditions for plasma waves in wave-particle
interactions. Thus the mechanisms for providing Jupiter with intense
radio sources and particle precipitation into the auroral ionosphere
can be further understood.
 
The existence of the magnetospheric wind at radial distances > 130 RJ in
the dawn sector of the magnetosphere offers exciting goals for the orbit
into the distant magnetotail. The origins of this wind are unknown. It
is possible that the magnetospheric wind develops near the Alfven point,
where the corotational speed is equal to the Alfven speed. The actual
position must be determined from considerations of the tangential
stress balance (cf. Vasyliunas, 1983). Thus magnetic bubbles could be
slung radially outwards into the magnetotail. The low pressures in the
magnetotail would produce super-Alfvenic radial outflow. On the other
hand, the outflow wind might be thermally powered by the hot plasma in
the plasma sheet inside the Alfven point. A third possibility is that
the magnetospheric wind is the signature of reconnection of magnetotail
lines in a convection pattern controlled by dayside magnetic merging
rates.  The response of the magnetotail to fluctuating internal plasmas,
e.g., Iogenic plasmas, or to a varying solar wind are unknown. In the
magnetotail characterized by spectacular, explosive activity or a mere
quiescent outflow of plasmas? The exploratory orbit into the magnetotail
will indeed answer many questions concerning the origins and dynamics of
this immense and little understood plasma region.
 
 
4. Overview of the Plasma Instrument
 
 
The instrument is divided into two analyzers, A and B. Each
electrostatic analyzer comprises three 70 deg. spherical-segment plates.
The outer and inner plates are grounded and the center plate is supplied
with a programmed series of voltages to effect analyses of the energy
spectra of electrons (E) and positive ions (P). The inner and outer
channels between the plates are the positive ion and electron analyzers,
respectively. A charged particle successfully passes through the channel
on the basis of its energy-per-unit charge (E/Q). Continuous-channel
electron multipliers, or Spiraltrons, are employed as sensors and are
positioned at the exit apertures of the electrostatic analyzers. Charged
particles arrive at positions at the exit aperture according to their
direction of arrival at the entrance aperture. The analyzers are mounted
on the instrument (magnetometer) boom of the spacecraft such that
charged particles moving perpendicular to the spacecraft spin axis
arrive at sensors 4E and 4P, and particles generally moving parallel and
antiparallel to the spin axis are detected  with sensor pairs 7E, 7P
and 1E, 1P, respectively.  Thus the fan-shaped fields-of-view are
divided into segments by the use of multiple sensors. Rotation of the
spacecraft spinning section allows coverage of almost the entire unit
sphere and angular distributions are obtained by electronically
sectoring the sensor responses as a function of spacecraft rotation
angle. The angular sampling of electron velocity distributions is
similar. The instrument is placed at a sufficient distance out along the
boom to avoid obstruction of the fields-of-view by the large dish
antenna of the spacecraft.
 
Three miniature mass spectrometers are included in the instrument for
determining the composition, i.e., mass-per-unit charge (M/Q), of the
positive ion plasmas. Two of these mass spectrometers are positioned at
the exit aperture of electrostatic analyzer B, the third spectrometer is
in analyzer A. Each of these mass spectrometers is equipped with two
Spiraltrons as sensors and an electromagnet. One of these sensors is
placed behind the electromagnet such that it accepts ions not deflected
by the gap magnetic field. These 'integral flux' sensors are shown as
1MI, 2MI, and 3MI. The second sensor in each mass spectrometer is
displaced from the undeflected path and accepts ions with M/Q values
that are a function of the gap magnetic field. These 'differential flux'
sensors are 1MD, 2MD, and 3MD. A programmed series of currents is fed to
the electromagnet. If the polar angle is taken as 0 deg. in the
direction of the spacecraft spin axis, then the fields-of-view are 11
deg. to 38 deg., 87 deg. to 93 deg., and 142 deg. to 169 deg. for
spectrometers 1, 2, and 3, respectively.
 
The aperture cover serves two purposes. Prior to and during launch the
cover in its closed position prevents contamination of the sensors from
dust and condensable vapors. After the launch sequence, the cover is
opened and is employed to tailor the fields-of-view of the sensors
viewing at small angles to the spin axis of the spacecraft. The
corresponding obstructions are identified as shapers.
 
 
5. Design of the Instrumentation
 
 
5.1. ELECTROSTATIC ANALYZER
 
 
The spherical-segment analyzer plates are precision-machined from solid
blocks of magnesium. The radii of the inner and outer surfaces,
respectively, of the four electrostatic analyzers are 9.68 and 9.95,
10.08 and 10.36, 11.77 and 12.10, and 12.23 and 12.57 cm. These plates
are concentric. Thus the analyzer constant C ~ 18.2, where E/Q = CV and
is the plate voltage. The angle from the center of the entrance aperture
to the exit aperture of the analyzer is 70 deg. as referenced to the
common center of curvature. Each of the concave surfaces within the
analyzers has been machined with 140 saw-tooth serrations. The interior
surfaces of the analyzer plates have been also electrodeposited with
platinum black over gold electroplate. The two latter measures are taken
in order to suppress the scattering of ultraviolet radiation and charged
particles within the analyzers into the sensors. The entrance aperture
is 60 deg. wide. Because the entrance aperture is wide in order to
provide good angular coverage in spacecraft latitude, the fields-of-view
shapers are used on the protective cover to limit excessive spreading in
the azimuthal direction for the polar sensors. The center plate of each
analyzer pair is supplied with voltages ranging from 0.05 to 2880 V in
order to provide energy (E/Q) spectra of positive ion and electron
intensities. The E/Q range is 0.9 eV q**-1 to 53 keV q**-1. There are 64
plate voltages that cover this energy range in logarithmically equal
increments. The averaged full-width at half maximum responses (FWHM) of
the ion and electron passbands are equal, DELTA E/E = 0.11. The range
and sequence of plate voltages can be selected by ground command.
 
A total of seven sensors are used for the two electron analyzers, and
seven for the two positive ion analyzers. These continuous channel
multipliers are Spiraltrons, model SEM 4211 with 1-mm diameter apertures
and model SEM 4213 with 3-mm diameter apertures, manufactured by Galileo
Electro-Optics Corporation. Entrance apertures of
these sensors are positioned at a distance 16 mm from the exit aperture
of their respective electrostatic analyzers. The Spiraltrons with larger
apertures are used for the two ion sensors that view closest to the spin
axis of the spacecraft, i.e., the polar sensors, in order to offset the
reduced projected area of the entrance aperture. The sensors are
screened for stability by operation for ~2 x 10**9 accumulated counts at
a gain > 10**8. Grounded mesh screens are mounted in front of the
entrance apertures of the sensors to shield the sensor post-acceleration
electric fields for the prevention of the collection of secondary
charged particles produced in the interior of the instrument. The
post-acceleration voltage for the ion sensors is approximately the bias
voltage, and about +150 V for the electron sensors. The nominal gain of
the Spiraltrons is 5 x 10**7 to 3 x 10**8 in the saturated pulse counting
mode. The output charge is collected by small plates and the collection
efficiency is improved by a potential difference of about 120 V for the
electron sensors and 200 V for the ion sensors. This charge is received
by hybrid amplifiers and discriminators manufactured by AMPTEK Inc.,
model A101. The threshold for these amplifiers was conservatively set at
4 x 10**6 electrons. The high voltage for sensor bias is programmable by
ground command in 32 increments spanning the range 2200 to 3800 V in
order to maximize the operating lifetime of the sensors against
degradation by using the minimum charge per pulse. The pulse pair
resolution of the amplifier/discriminator is nominally 250 ns (4 mHz),
and about 1.4 micro-second (700 kHz) after modification for use in the
instrument.
 
 
5.2. MINIATURE MASS SPECTROMETERS
 
 
Three miniature mass spectrometers are included in the plasma
instrument, one spectrometer in analyzer A and two spectrometers in
analyzer B. After passage through the electrostatic analyzer the
positive ions enter two collimating slits. The dimensions of the first
slit are 11.1 x 0.15 mm and for the second slit, 8.5 x 0.15 mm. These
two slits are separated by 9.5 mm. The paths of the positive ions are
then deflected according to their M/Q by the magnetic field in the gap
of a small electromagnet. The gap dimension is 3.0 mm and the length and
width of the pole pieces are 9.9 and 4.0 mm, respectively. The magnet
core is fabricated from a material similar to HY MU 80 and wound with
about 5000 turns of 332-gauge silver wire. Overlapped sheets of
Permalloy 80 with thickness 0.010 inch are used to encase the plasma
instrument to reduce the maximum stray field to 16 nanotesla (nT) at a
distance of 1 m. The mass of the electromagnet is 150 g. The
electromagnet is supplied with a programmed series of 64 currents
ranging from 0.6 to 105 mA. The sequence of current values can be
controlled by ground command. The corresponding range of gap magnetic
fields is 0.0014 to 0.225 T. The ions are detected with two Spiraltrons,
one Spiraltron (integral) with a 1-mm aperture for undeflected ions, and
one Spiraltron (differential) with a 3-mm aperture that is offset from
the path for undeflected ions. The magnet is non-focusing and the 3-mm
aperture Spiraltron is used to achieve approximately equal geometric
factors for the differential and integral channels. The sensor apertures
are positioned at a distance 20.1 mm from the exit face of the
electromagnet. A slit with width 0.76 mm is placed in front of each of
the two Spiraltrons. The centers of these slits are separated by 3.30
mm. The Spiraltrons are operated in a similar manner as previously
described for the sensors for the electrostatic analyzers.
 
At higher mass channels (larger current) H2+ and OH+ are deflected
sufficiently to be detected with the differential sensor.  The M/Q value
for the integral sensor is taken at a fraction 0.5 of the undeflected
responses. For a given current step of the mass spectrometer, the
averaged FWHM for the three mass spectrometers in terms of ion energy is
DELTA E/E = 0.06. In general the differential channel is used for the
detection of trace fluxes of light ions and the integral channel for
abundant heavy ions in the Jovian magnetosphere. The mass resolutions of
the mass spectrometers are M/DELTA M = 4.1 at full-width at 50%
responses (FWHM) for the differential sensors (MD) and M/DELTA M ~ 2 for
the integral sensors (MI). This resolution has been chosen to allow
identification of the species H+, H2+ (He++), He+, O++, O+, Na+, S+, and
K+ with the MD sensors and H+, H2+ (He++), O++, O+, S+, and SO2+ with
the MI sensors. The E/Q ranges vary with the M/Q of the ion species,
e.g., for the MD sensors, 0.9 V to 20 keV for H+, 0.9 V to 3 kV for O+,
and 0.9 V to 800 V for S+. For the MI sensors, these ranges are 10 V to
52 kV for H+, 0.9 V to 52 kV for O+, and 0.9 V to 14 kV for S+. The mass
spectrometers cannot distinguish between two ions with the same M/Q,
e.g., O+ and S++. The mass spectrometers are designed in part with the
criterion that corotating SO2+ (M/Q = 64 amu, E/Q ~ 2 kV) can be
identified at Io's orbit.
 
 
5.3. GEOMETRIC FACTORS
 
 
A summary of the latitudinal coverage, energy resolutions, and geometric
factors of each of the twenty sensors in the plasma instrument is given
in Table I. The averaged geometric factors for the electron and positive
ion sensors of the electrostatic analyzers and the positive ion sensors
of the mass spectrometers are 3.4 x 10**-5, 6.4 x 10**-5, and
3.2 x 10**-6 cm**2 sr eV eV**-1 , respectively.
 
These values are computed by comprehensive ray tracing of trajectories
through the electrostatic and magnetic analyzers and with the nominal
entrance area of the sensor.  In practice both the efficiency and this
area vary with individual sensors and final values of the geometric
factors are derived from laboratory measurements and inflight responses
in an isotropic plasma such as that in the plasma sheet during Earth1
encounter. These geometric factors are tailored to provide effective
measurements of both the dense plasmas in the torus and the sparse
plasmas of the outer Jovian magnetosphere.
 
The maximum responses of a single sensor to several representative
plasmas are shown as functions of the plasma temperature, bulk flow
speed V, and species. The bulk speed of 100 km s**-1 has been chosen as
scale-wise representative for the corotational speeds in the torus. The
densities of all the plasmas are each assumed to be 1 cm**-3. For
example, if the density of S+ ions is 1000 cm**-3, V is 100 km s**-1, and
the temperature kT is 100 eV, the maximum responses of the ion sensors
of the electrostatic analyzer (P) and of the ion sensors of the mass
spectrometers (M) are 4 x 10**6 and 2 x 10**5 counts s**-1, respectively,
when viewing in the bulk flow direction. The geometric factor of the ion
sensor (P) is sized such that these responses are somewhat above the
saturation values for the sensor/amplifier, ~10**6 counts s**-1. The ion
sensors in the mass spectrometers are employed to extend the dynamic
range of these ion measurements to the larger ion densities by means of
their lesser geometric factors. On the other hand, the large geometric
factor of the ion sensors for the electrostatic analyzers provides the
capability of the determining densities of hot (~ tens of keV),
isotropic ions as low as 10**-3 to 10**-2 cm**-3 in the outer regions of
the magnetosphere. Thus the combined geometric factors of the
electrostatic analyzers and mass spectrometers accommodate a large range
of ion densities. If the electron densities in the center of the plasma
torus are 3000 cm**-3, then the maximum responses for the electron
sensors are ~2 x 10**5 and 6 x 10**5 counts s**-1 for electron temperatures
kT = 1 and 10 eV, respectively. For an electron temperature of 10 keV in
the outer magnetosphere, densities as low as 10**-4 to 10**-3 cm**-3 can be
well determined.
 
 
                                      TABLE I
                        Galileo PLS performance parameters
 
------------------------------------------------------------------------
Sensor       Polar angle         Energy resolution,   Geomagnetic factor
             coverage, theta     DELTA E/E at FWHM    cm**2 sr eV
                                        eV**-1
------------------------------------------------------------------------
Electrons        Energy range: 0.9 V < E/Q < 52 kV
 
1E            14 deg-41 deg             0.14             1.9 x 10**-5
2E            38 deg-62 deg             0.12             3.7 x 10**-5
3E            58 deg-80 deg             0.10             4.1 x 10**-5
4E            81 deg-102 deg            0.08             5.0 x 10**-5
SE           100 deg-122 deg            0.10             4.1 x 10** 5
6E           121 deg-146 deg            0.12             3.6 x 10**-5
             142 deg-171 deg            0.14             1.3 x 10**-5
 
Positive ions    Energy range: 0.9 V < E/Q < 52 kV
 
1P^a           9 deg-41 deg             0.15             9.8 x 10**-5
2P            35 deg-59 deg             0.12             3.5 x 10**-5
3P            62 deg-84 deg             0.09             4.1 x 10**-5
4P            78 deg-99 deg             0.07             5.0 x 10**-5
5P            97 deg-119 deg            0.09             4.0 x 10**-5
6P           118 deg-141 deg            0.11             3.6 x 10**-5
7P^a         136 deg-166 deg            0.15             1.5 x 10**-5
 
Ion composition
   Energy range: species dependent
 
   Differential (D) sensor: 0.9 V to 20 kV (H+)
                            0.9 V to 800 V (S+)
             Resolves: H+, H2, He+, O+, Na+, S+, K+ with M/DELTA M = 4.1
 
       Integral (I) sensor: 10 V to 52 kV (H+)
                            0.9 V to 14 kV (S+)
             Resolves: H+, H2+, He+, O+, S+, SO2+ with M/DELTA M  ~2.0
 
1MD^a, 1MI    11 deg-38 deg             0.03             2.4 x 10**-6
2MD^a, 2MI    87 deg-93 deg             0.03             4.7 x 10**-6
3MD^a, 3MI   142 deg-169 deg            0.03             2.4 x 10**-6
------------------------------------------------------------------------
^a 3-mm entrance diameter, others are 1 mm. ^b Preliminary values based
upon ray tracing (see text).
 
Considerable attention in the design of the instrument was directed
toward minimizing the sensor responses to the intense fluxes of
energetic electrons in the inner Jovian magnetosphere. The Spiraltrons
are shielded in all directions by a minimum of 2.5 g cm**-2 equivalent of
aluminum. This corresponds to an electron range of ~5 MeV.  In addition
the Spiraltrons used for ion sensors are operated at a sufficiently low
voltage that two or more initial secondary electrons at their entrance
apertures are necessary to yield an electron pulse above the
discriminator level of the amplifiers. This mode of operation reduces
the sensor efficiency for the detection of ions by 50% (+/- 10%), with a
corresponding decrease in the geometric factors cited in Table I. Such
operation of the sensors at bias voltages ~2400 V allows
discrimination against detection of penetrating electrons. The
omnidirectional geometric factors for detection of penetrating, > 5 MeV
electrons are ~10**-4 cm**2 for the ion sensors with 1-mm apertures, and
~10**-3 cm**2 for the 3-mm ion sensors (see Table I). The corresponding
geometric factors for the Spiraltrons used in the electron analyzers are
~10**-3 cm**2. At the orbit of Io the electron intensities with E > 5 MeV
are ~2 x 10**7 cm**-2 s**-1 (Van Allen, 1976). Thus the background
counting rates are ~2 x 10**3, 2 x 10**4, and 2 x 10**4 counts s**-1 for the
1-mm ion sensors, the 3-mm ion sensors, and the 1-mm electron sensors,
respectively. For comparison, the sensor responses in the direction of
flow (S+, 1000 cm**-3, 50 eV, 100 km s**-1) are ~5 x 10**6 counts s**-1 for
the ion channels of the electrostatic analyzer and ~3 x 10**5 counts
s**-1 for the sensors in the mass spectrometer. The analyzer responses to
electrons (e-, 1000 cm**-3, 50 eV) are expected to be ~6 x 10**5 counts
s**-1. The corresponding S/N ratios are 2500, 150 (I), and 15 (D), and 30
for the ion sensors, mass spectrometer sensors, and electron sensors,
respectively.
 
At larger radial distances, > 20 R,, the intensities of electrons with
E > 5 MeV are typically < 10**3-10**4 cm**-2 s**-1 within and near the
plasma sheet (Baker and Van Allen, 1976). The corresponding maximum
background rates are then < 1 and 10 counts s**-1 for the 1-mm positive
ion and electron sensors, respectively. For these maximum rates, the
densities for which S/N = 1 for an isotropic, H+ plasma are 3 x 10**-3
cm**-3 at kT = 10 keV and 5 x 10**-3 cm**-3 for electrons at 1 keV. The
corresponding densities for the mass spectrometer sensors are ~ 0.1
cm**-3 (I) and 1 cm**-3 (D). These above examples for H+ give the most
pessimistic values because we have assumed worst-case background rates
and because the ion plasmas are partially corotating. The S/N ratios
will be typically larger by factors of ~ 10 to 100.
 
The spacecraft potential is expected to be important at the lower energy
range of the analyzer. A quantitative assessment of anticipated
spacecraft potentials is given by the Voyager plasma measurements. In
the outer magnetosphere, typical Voyager spacecraft potentials were
positive in the range of several volts to 10 V (Scudder et al., 1981).
Because the plasmas are generally hot, temperatures ~ keV, in the
outer magnetosphere the plasma measurements should not be greatly
impaired. On the other hand, in the highest density regions of the Io
torus, Voyager spacecraft potentials were negative with magnitudes up to
25 V (Sittler and Strobel, 1987). In this region electron temperatures
are tens of eV or less and the observations of thermal electron plasmas
may be precluded if the Galileo spacecraft potential is similar. The
energy range of the Galileo plasma instrument is sufficient to determine
this spacecraft potential. Determination of the magnitude of the
potential will have to await the in-situ observations. The potentials
along the boom on which the plasma instrument is mounted and those of
the spacecraft body will also affect the trajectories of low-energy
particles as viewed by the plasma analyzer. This effect will have to be
modeled in detail in order to determine the deflections of the' observed
angular distributions as a function of the particle energy.
 
 
5.4. INSTRUMENT ELECTRONICS
 
 
The plasma instrument is divided into two analyzer systems A and B. This
configuration of the instrument has been chosen in order to reduce the
number of possible single-point failures that could result
in the total loss of the scientific objectives. Each analyzer is
equipped with a set of electrostatic analyzer plates, at least one
miniature mass spectrometer, and a partial set of the sensors for the
measurements of the three-dimensional velocity distributions of positive
ions and electrons. A dedicated plate voltage supply, magnet current
supply, and sensor bias voltage supply are provided for each analyzer.
Each sensor is serviced by a 16-bit accumulator. The electronics for
both analyzers are controlled from the instrument bus.
 
The reduction of single-point failures of the instrument proved to be
considerably more difficult for the data handling and control subsystem
(DHCS). There are two separate buses, A and B, that can singly operate
the two analyzers. Similarly there are two RCA 1802 microprocessors, 1
and 2 that are each equipped with 4 kbytes of read-only memory (ROM) and
4 kbytes of read/write memory (RAM). Two bus adapters, alpha and beta,
couple the microprocessors with the command data system (CDS) of the
spacecraft. The instrument is operated with one bus adapter, one
microprocessor, and one bus. The bus separator/selector allows the use
of any combination of these electronic elements, e.g., bus adapter
alpha, processor 2, and instrument bus A. This configuration for the
DHCS is set via a hardware bus command (HBC) that transfers the
necessary information in the address portion of the packet header from
the spacecraft CDS. The HBC is executed regardless of which processor
and bus adapter are currently selected. If the currently selected bus
adapter fails, the HBC can be used to select the other bus adapter.
 
Each of the two microprocessors is provided with identical I/O
electronics that include an analog-to-digital (ADC) converter (model
AD571, Analog Devices, Inc.), three digital-to-analog (DAC) converters,
and a digital status input port. A 16-input multiplexor is used with the
ADC to monitor voltages within the instrument. The DACs provide the
control voltages for the programmable high voltage (plate and bias) and
current (electromagnet) supplies.
 
Two low-voltage power supplies, A and B, are included within the plasma
instrument.  By means of a power distribution system, failure of a
single low voltage supply does not result in the loss of the DHCS or
instrument bus. Analyzer A or B becomes inoperable with the failure of
the one of the low-voltage power supplies, A or B. A power switching
circuit that is controlled by ground command is used to select the
analyzer to be operated with the functioning low-voltage power supply.
The replacement and supplemental heaters are used for thermal control
during the mission. The latch for releasing the protective cover over
the instrument aperture is a one-shot redundant device with two
electrically fired, black powder Unidynamics bellows actuators.
 
 
5.5. MASS, SIZE, AND POWER
 
 
The overall dimensions of the plasma instrument are 8.00 x 15.00 inch
(mounting surface) and 13.68 inch (height). The total mass is 13.2 kg,
of which 0.33 kg is used for magnetic shielding and 3.57 kg is invested
in radiation shielding of the sensors and electronics with tantalum. The
average power, without heaters, is dependent upon the electronic
configuration of the instrument and is in the range of 6.5 to 10.7 W.
 
 
6. Inflight Operation of the Instrument
 
 
The operating modes of the plasma instrument are designed to accommodate
the diverse plasmas in the Jovian magnetosphere. We provide here a brief
introduction to those capabilities. The instrument cycle time is 243
seconds and is subdivided into 12 equal intervals, or instrument spin
modes. Each spin mode is a separate instrument operations and data
collection cycle. The duration of a spin mode is 20.3 s and thus
slightly longer than the range of anticipated  rotation periods for the
spacecraft spinning section, 18.3 to 19.8 s.  By ground command the
plasma instrument can be configured to sample a combination of a given
set of sensors, a range of energy passbands, a range of mass channels,
and a set of angular sectors as the fields-of-view rotate. The
operations of analyzers A and B can be programmed independently.
Limitations of these analyzers are imposed by the minimum dwell time for
the energy passbands and mass channels of 8.3 ms, a service time of 1 ms
for the processing of the contents of a count accumulator, and the
telemetry rate  allocated to the instrument of 612 bits s**-1 (72 sensor
samples s**-1 plus overhead). Each sample of sensor responses is
quasi-logarithmically compressed into an 8-bit word. Internal buffers
can allow rapid bursts of < 1500 measurements to be trickled into the
telemetry stream.
 
Consider the measurement cycle time of the plasma instrument if onboard
software were not available to improve the operational efficiency. If
all energy passbands, mass channels, and sensors were sampled in each of
16 angular sectors, then the time for this complete plasma measurement
(1.3 x 10**6 samples) would be 5.1 hours. Such instrument operation is
ineffective and wasteful of the capabilities for obtaining plasma
parameters, e.g., individual 64-point energy or mass spectra in 0.5 s.
Thus the spin modes are each designed to obtain a specific type of
plasma measurement during one spacecraft rotation, e.g., a
three-dimensional velocity distribution, high angular and energy
resolutions of an ion beam, and the mass composition of an ion beam. A
spin mode is constructed of nested control loops. These loops control
(1) the number of angular sectors sampled during a spacecraft rotation,
(2) the number of energy pass-bands or mass channels in a sector, (3)
the duration of an energy passband or mass channel, (4) the readout of
the selected sensors, (5) the sequence of energy passbands, and (6) the
sequence of mass channels. Four sequencing tables are used to determine
the operation of the instrument during a spin mode: (1) sensor, (2) mass
channel, (3) energy passband, and (4) angular sector. The angular
sectors are referenced to a fixed position on the celestial sphere by
means of information from the spacecraft attitude control system.
Instrument software is available for five basic types of spin modes.
Default values for the sequence tables are also included in read-only
memory in the instrument processor in lieu of values from ground
commands. We briefly illustrate below the capabilities of the various
spin modes.
 
     Spin mode 1. Survey of positive ion and electron velocity
     distributions. All electron, ion, and integral ion sensors
     (spectrometers) are sampled. The number of angular sectors, the
     energy range, and the number of energy passbands are selected by
     ground command. The product of the numbers of passbands and angular
     sectors is 64. For example, the responses of all of the above
     sensors for 64 passbands sampled in a single angular sector of 45
     deg can be telemetered each spacecraft spin period. Alternately
     16 passbands (every fourth passband) in each of our 90 deg-sectors
     can be telemetered during a single rotation period in order to
     obtain the principal features of the three-dimensional velocity
     distributions of positive ions and electrons once each 20.3 s.
 
     Spin mode 2. Determination of the velocity distribution of a
     positive ion beam. Electron and ion sensors corresponding to those
     nearest the direction of the ion beam are selected. These sensors
     and the spacecraft rotation angle for the beam are determined with
     measurements from a preceding spin mode 1. The rapid energy scans
     in the direction of the beam are limited to the energy range of the
     beam as determined during spin mode 1. For example, during one
     spacecraft rotation, energy passbands 8 through 23 can be sampled
     with three sensors for positive ions and two or three sensors for
     electrons for each of five contiguous 22.5 deg. sectors in the
     direction of the beam. Two electron sensors are used for analyzers
     and B, with the exception of three for analyzer B if the beam is
     nearly perpendicular to the spacecraft spin axis. Again angular
     size of the sectors and the number of energy passbands can be
     selected by ground command.
 
     Spin mode 3. Survey of ion composition. Mass spectrometers 1 and 2
     are sampled for a selected range of gap magnetic fields. During one
     spacecraft rotation a single energy passband of the electrostatic
     analyzer is used and the gap magnetic fields are incremented over a
     selected series of values. Thus for a given energy passband and a
     single spacecraft rotation it is possible to sample the entire M/Q
     range in 64 current steps in each of four 90 deg-sectors.
 
     Spin mode 4. Survey of ion composition. This spin mode is identical
     to spin mode 3 with the exception that mass spectrometer 3 replaces
     1.
 
     Spin mode 5. Determination of the composition of an ion beam. The
     mass spectrometer with direction of field-of-view nearest to that
     of the ion beam is chosen on the basis of previous measurements
     with spin mode 1. The energy passband and angular sectors for the
     ion beam are similarly identified. For example, during one
     spacecraft rotation in the plasma sheet or torus of the Jovian
     magnetosphere full coverage of the M/Q range in 64 channels can be
     sampled in each of five contiguous 22.5 sectors.
 
The instrument cycles for analyzers A and B are each selected as a
sequence of 12 spin modes. The order of the spin modes and their
operating parameters such as energy and mass ranges, angular resolution,
etc., are controlled by the sequence tables. As an example, a sequence
of spin modes during an instrument cycle for analyzer A can be 1, 1, 2,
1, 1, 5, 1, 1, 4, 1, 1, 3. Thus the various operating modes of the
plasma instrument can be implemented and cycled automatically with
minimal demand for command uplinks to the Galileo spacecraft. Major
command sequences are used to restructure the spin modes and their
sequencing for special events such as the close encounters with the
Galilean satellites and the exploratory survey into the distant
magnetotail.
 
 
Acknowledgements
 
 
At The University of Iowa L. A. Frank is principal investigator and K.
L. Ackerson is a co-investigator for the plasma investigation. The other
co-investigators are F. V. Coroniti of the University of California at
Los Angeles and V. M. Vasyliunas of the Max-Planck-Institut fur
Aeronomie, Lindau, Germany. E. C. Stone of the California Institute of
Technology is a co-investigator whose responsibility is the Heavy Ion
Composition (HIC) investigation which employs a separate instrument on
the Galileo Orbiter. The authors wish to express their appreciation to
the following personnel of the Jet Propulsion Laboratory for their
assistance in the implementation of the plasma instrumentation: J. R.
Casani, W. G. Fawcett, H. W. Eyerly, C. M. Yeates, M. S.  Spehalski, W.
J. O'Neil, R. F. Ebbett, and T. V. Johnson. This research was supported
in part at The University of Iowa by the Jet Propulsion Laboratory under
contract 958778.
 
 
References
 
Bagenal, F.: 1985, 'Plasma Conditions Inside lo's Orbit: Voyager
     Measurements', J. Geophys. Res. 90, 311.
 
Bagenal, F., McNutt, R. L., Jr., Belcher, J. W., Bridge, H. S., and
     Sullivan, J. D.: 1985, 'Revised Ion Temperatures for Voyager Plasma
     Measurements in the Io Plasma Torus', J. Geophys. Res. 90, 1755.
 
Baker, D. N. and Van Allen, J. A.: 1976, 'Energetic Electrons in the
     Jovian Magnetosphere', J. Geophys Res. 81, 617.
 
Belcher, J. W.: 1983, in A. J. Dessler (ed.), 'The Low-Energy Plasma in
     the Jovian Magnetosphere', Physics of the Jovian Magnetosphere,
     Cambridge University Press, Cambridge, p. 68.
 
Frank, L.A., Ackerson, K.L., Wolfe, J.H., and Mihalov, J.D.:
     1976,'0bservations of Plasmas in the Jovian Magnetosphere', J.
     Geophys. Res. 81, 457.
 
Gurnett, D. A. and Scarf, F. L.: 1983, in A. J. Dessler (ed.), 'Plasma
     Waves in the Jovian Magnetosphere', Physics of the Jovian
     Magnetosphere, Cambridge University Press, Cambridge, p. 285.
 
Krimigis, S. M. and Roelof, E. C.: 1983, in A. J. Dessler (ed.),
     'Low-Energy Particle Population', Physics of the Jovian
     Magnetosphere, Cambridge University Press, Cambridge., p. 106.
 
Sands, M. R. and McNutt, R. L., Jr.: 1988, 'Plasma Bulk Flow in
     Jupiter's Dayside Middle Magnetosphere', J. Geophys. Res. 93, 8502.
 
Scudder, J. D., Sittler, E. C., Jr., and Bridge, H. S.: 1981, 'A Survey
     of the Plasma Electron Environment of Jupiter: A View from
     Voyager', J. Geophys. Res. 86, 8517.
 
Sittler, E. C. and Strobel, D. F.: 1987, 'Io Plasma Torus Electrons:
     Voyager 1', J. Geophys. Res. 92, 5741.
 
Van Allen, J. A.: 1976, in T. Gehrels (ed.), 'High-Energy Particles in
     the Jovian Magnetosphere', Jupiter, University of Arizona Press,
     Tucson, p. 928.
 
Vasyliunas, V. M.: 1983, in A. J. Dessler (ed.), 'Plasma Distribution
     and Flow', Physics of the Jovian Magnetosphere, Cambridge
     University Press, Cambridge, p. 395.

        