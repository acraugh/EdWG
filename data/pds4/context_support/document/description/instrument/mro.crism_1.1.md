
 
Instrument Overview
===================
 
CRISM (Compact Reconnaissance Imaging Spectrometer for Mars) is a
hyperspectral imager on the MRO (Mars Reconnaissance Orbiter)
spacecraft.  MRO's objectives are to recover climate science originally
to have been conducted on the Mars Climate Orbiter (MCO), to identify
and characterize sites of possible aqueous activity to which future
landed missions may be sent, and to characterize the composition,
geology, and stratigraphy of Martian surface deposits. MRO will operate
from a sun-synchronous, near- circular (255x320 km altitude), near-polar
orbit with a mean local solar time of 3 PM.
 
CRISM's spectral range spans the ultraviolet (UV) to the mid-wave
infrared (MWIR), 362 nm to 3920 nm. The instrument utilizes a
Ritchey-Chretien telescope with a 2.12 degree field-of-view (FOV) to
focus light on the entrance slit of a dual spectrometer. Within the
spectrometer, light is split by a dichroic into VNIR
(visible-near-infrared, 362-1053 nm) and IR (infrared, 1002-3920 nm)
beams. Each beam is directed into a separate modified Offner
spectrometer that focuses a spectrally dispersed image of the slit onto
a two dimensional focal plane (FP). The IR FP is a 640 x 480 HgCdTe area
array; the VNIR FP is a 640 x 480 silicon photodiode area array. The
spectral image is contiguously sampled with a 6.55 nm spectral spacing
and an instantaneous field of view of 61.5 microradians. The Optical
Sensor Unit (OSU) can be gimbaled to take out along-track smear,
allowing long integration times that afford high signal-to-noise ratio
(SNR) at high spectral and spatial resolution. The scan motor and
encoder are controlled by a separately housed Gimbal Motor Electronics
(GME) unit. A Data Processing Unit (DPU) provides power, command and
control, and data editing and compression.
 
Scientific Objectives
=====================
 
CRISM has three major science objectives, which are implemented via key
parts of its observing strategy:
 
OBJECTIVE 1: Globally characterize crustal composition, and identify
targets that expose rocks diagnostic of past climate conditions and
habitability
 
IMPLEMENTATION:
- Acquire near-global data at reduced spatial resolution at key
  wavelengths to characterize surface composition composition (the
  multispectral survey)
- Using the multispectral survey, find and target regions for higher
  spatial resolution hyperspectral coverage
 
OBJECTIVE 2: Identify and map surface mineralogy of key targets with
high spatial and spectral resolutions and high SNR
 
IMPLEMENTATION:
- Target thousands of sites with observations that use CRISM's full
  spatial and spectral resolution
- Use along-track scanning used to take out most ground-track motion, so
  that high SNR can be obtained at high spectral and spatial resolutions
- Obtain coverage to >3600 nm to provide high sensitivity to low
  abundances of carbonates
- Obtain inflight calibration of background and responsivity to support
  radiometric accuracy
 
OBJECTIVE 3: Separate the signature of the surface from that of the
atmosphere, and characterize the spatial and temporal properties of the
atmosphere
 
IMPLEMENTATION:
- Observe each targeted site at multiple geometries to quantify
  atmospheric effects
- Acquire periodic global grids of measurements to monitor atmospheric
  conditions, and use these results to correct the multispectral survey
 
CRISM's implementation of its science strategy maps into three groups of
investigations.
 
CRISM will conduct its first group of investigations through a global,
100- 200 m/pixel, 72-wavelength survey.  Through these multispectral
survey data, global characterization of surface mineralogy to understand
Mars crustal composition will be established using a spectral parameter
approach.  The mineralogy maps will also be used to search for evidence
of aqueous activity that lacks morphologic expression and/or that is not
resolved by previous Mars-orbiting instruments.
 
CRISM's second group of investigations is implemented by high-resolution
hyperspectral mapping of hundreds to thousands of high priority targets
including candidate sedimentary deposits, volcanic regions, crustal
sections exposed in steep escarpments, and sites which exhibit evidence
for concentrations of aqueously formed minerals.
 
The final group of investigations is implemented using a systematic,
global grid of hyperspectral measurements of emission phase functions
(EPFs) acquired repetitively throughout the Martian year. EPF
measurements allow accurate determination of column abundances of water
vapor, CO, dust and ice aerosols, and their seasonal variations. At the
same time, the grid's repetitive coverage will track seasonal variations
in water content of surface material.
 
Subsystems
==========
 
CRISM consists of three boxes; the Optical Sensor Unit (OSU) which
includes the optics, gimbal, focal planes, cryocoolers and radiators,
and focal plane electronics; the Gimbal Motor Electronics (GME), which
commands and powers the gimbal motor and encoder and analyzes data from
the encoder in a feedback loop; and the Data Processing Unit (DPU),
which accepts and processes commands from the spacecraft and accepts and
processes data from the OSU and communicates it to the spacecraft. The
CRISM OSU has a one-time deployable cover that protects the instrument
optics from contamination. The cover will be opened following MRO's
aerobraking into its science orbit.
 
Light is focused by the Ritchey-Chretien on-axis telescope onto the
slit.  Following the slit is the spectrometer optics. The dichroic
reflects the VNIR, while transmitting the infrared. The two modified
Offner spectrometers disperse the light and focus it onto their
respective focal planes. Each focal plane has a dedicated electronics
board that provides the required clock signals and bias voltages, and
digitizes the video data from the focal plane. The digitized data is
transmitted through the twist capsule to the DPU. Lamps in the
spectrometer housing can illuminate each focal plane, permitting a flat
field calibration of the focal planes. The infrared focal plane is
cooled to about 110K by one of three cryocoolers (selectable by the
DPU). The three position shutter mirror, located between the telescope
and spectrometer slit, allows imaging of a scene, measurement of an
internal closed-loop controlled integrating sphere, or background
measurements.
 
The scanning subsystem consists of the Gimbal Motor Electronics (GME), a
high-resolution angular encoder, and the gimbal drive motor. The GME
contains the motor driver circuitry, and responds to a commanded profile
from the DPU. Software in the DPU implements a control algorithm,
utilizing feedback information from the 20-bit encoder to maintain
closed-looped control. The system accurately follows a programmed scan
pattern that is carefully designed to compensate for orbital motion and
to accomplish the desired scan pattern across the Martian surface.
 
The DPU receives unregulated 28 volt power from MRO and provides
regulated secondary power to CRISM, receives and processes commands from
the MRO, controls the CRISM subsystems, and acquires and formats CRISM
science and housekeeping data that is then sent to the spacecraft solid
state recorder for downlink to earth.
 
SUMMARY OF TECHNICAL ATTRIBUTES:
 
Spectral Range:  362 - 3920 nm
 
Spectral Sampling:  6.55 nm
 
Field of view: 2.12 degrees
 
Instantaneous field of view (1 pixel): 61.5 microradians
 
Swath Width from 255x320 km orbit:  9.4 to 11.9 km
 
Spatial Sampling from 255x320 km orbit:  15.7 to 19.7 m/pixel
 
IR detector temperature:  100K attainable with cryogenic cooling
 
VNIR detector temperature: heated to -60C
 
Spectrometer housing temperature:  <194K
 
SNR:  425 at 2300 nm, for a targeted observation of typical surface
materials
 
System MTF, at 9.25 cycles/mm (resolves a 40 meter spot): 0.73 VNIR, 0.4 IR
 
Gimbal Pointing:  +/- 60 degrees Along Track
 
Scan Jitter:  +/- 25 microradians
 
Spectral Full Width Half-Max:  7.9-10.1 nm VNIR, 9-19 nm IR
 
Spectral Smile (VNIR):  1.3 pixels
 
Keystone (VNIR):  < +/- 0.42 pxls
 
Spectral Smile (IR):  1.3 pixels
 
Keystone (IR):  < +/- 0.42 pxls
 
Spectral Profile, VNIR:  <<1%, 3 pixels from peak
 
Spectral Profile, IR:  Typically <2%, 3 pixels from peak
 
Out of Field Stray Light:  < 1%
 
Mass:  32.92 kg
 
Power (normal data acquisition):  45.8 W
 
Power (during internal calibrations):  47.3 W
 
Power (during cooldown w/o data collection):  44.4 W
 
Power (during standby with subsystems off):  16.1 W
 
Detectors
=========
 
VNIR:
 
The VNIR focal plane consists of a silicon photodiode detector array
indium bump-bonded to a TCM 6604A multiplexer. The focal plane consists
of 640 column x 480 rows with 27-micron elements, and the long axis
oriented in the along-slit direction. There are four quadrants each 160
columns in width.  Readout occurs one row (wavelength) at a time, and
each quadrant's output is sent to a separate analog-to-digital converter
that digitizes to 14 bits.  Component-level calibration (section 4.1)
showed that read noise is approximately 180 e-, and gain is 80 e- per
14-bit DN. Full well is approximately 780,000 e-, and response is
quasi-linear up to about 93% of full well. A bias voltage applied to the
detector assures that, even with the minimum signal and dark current,
14-bit DNs are significantly greater than zero.
 
The columns in the detector have three types of exposure to light. By
design, the 10 columns at each edge are physically masked to serve as a
reference for dark current. Inside the masked columns, another 10
columns on each side are not masked but neither are they exposed to
direct illumination through the slit. These columns measure glare from
the grating and other components internal to the spectrometer, The
central 600 columns are intended to image the slit. Due to manufacturing
and alignment tolerances, the actual dimensions of the three
illumination regions of the detector are slightly different than the
design.
 
A fixed mounted filter on the detector blocks higher orders from the
grating. By design the boundary is near 650 nm. The filter, comprised of
two distinct filter glasses, stands approximately 0.2 mm off the
detector surface. A mask at the filter boundary, consisting of a black
stripe 216 microns wide, was microlithographically placed on the filter
surface. The mask blocks scatter off the joint between the two glasses
and, although it does attenuate the scene at adjacent wavelengths,
because it is out of focus the transmission is not reduced to zero.
Spectral information is not lost, and the shadowing attenuation can be
calibrated out. By design, only 107 out of the 480 available rows have
useful amounts of light dispersed light through the slit. 363 of the
remaining 393 rows are physically masked; the 10 rows adjacent to the
107 useful rows are unmasked to provide margin for detector alignment in
the instrument.
 
The detector is mounted in a focal plane assembly. The FPA holds the
detector at the proper angle to the spectrometer housing to locate it at
the optical focal plane, and thermally isolates it from the colder
spectrometer housing while allowing translation and rotation relative to
the side of the spectrometer housing to minimize spectral smile and
keystone distortions.  The detector's temperature is thermostatically
controlled to -60C in order to maintain quantum efficiency above 900 nm.
 
The VNIR detector has a dedicated electronics board in the base of the
gimbal that provides the required clock signals and bias voltages, and
separately digitizes the video data from each quadrant of the focal
plane.  The digitized data are transmitted through a twist capsule to
the DPU. The focal plane electronics control redundant focal plane lamps
in the spectrometer housing that can illuminate the focal plane,
permitting a non- uniformity calibration. They also control one of the
two redundant lamps in the internal integrating sphere. The board
monitors its own temperature and current, shutter motor current, and
temperatures of the detector, spectrometer housing, telescope, and
baffle. Both the VNIR or IR board can control one of two redundant sets
of windings in the shutter motor; in a contingency situation in which
the shutter resists movement, both windings can be used together.
 
IR:
 
The infrared (IR) focal plane consists of a HgCdTe detector array indium
bump-bonded to a TCM 6604A multiplexer, the same as used in the VNIR
array.  The HgCdTe detector was grown on a CdTe substrate by molecular
beam epitaxy (MBE) by the Rockwell Science Company (RSC). Dimensionally,
electrically, and optically, the IR detector resembles the VNIR detector
except for differences summarized below. Read noise is slightly lower at
140 e-, but gain and full well are similar.
 
The fixed-mounted filter is a three-zone interference filter designed to
block not only higher orders from the grating, but also thermal
background to which the detector responds at wavelengths <4250 nm. Zones
1 and 2 are bandpass filters that transmit wavelengths of 1000-1810 nm
and 1580-2840 nm respectively. Zone 3, covering longer wavelengths, is a
linearly variable filter with an 80-nm bandpass and a linear variation
in center wavelength scaled to match the dispersion of the IR
spectrometer. All three zones overlap in order to eliminate leaks of
thermal background to the detector.  At the zone 1/zone 2 boundary there
is no gap in transmission, but there is a narrow gap in transmission
about 40 nm wide at the zone 2/zone 3 boundary from about 2720-2760 nm.
In addition excessive thermal background is admitted at the boundary
between zones 2 and 3, but this can be calibrated out.
 
The IR focal plane assembly is more complicated than the VNIR assembly,
due to the three times larger temperature contrast that has to be
maintained between the detector and spectrometer housing. The cryogenic
part of the FPA is mounted to a molybdenum core, and includes the
detector held at proper angle to the spectrometer housing to locate it
at the optical focal plane, as well as associated electronics. A cold
shield, blackened on the interior, limits the view to the spectrometer
housing to that necessary to admit the cone of light from the
spectrometer optics. Baffling attenuates off-axis scatter of thermal
background through the baffle's rectangular aperture. A low-emissivity
gold coating on the cold shield's outer surface limits radiative
coupling of the baffle to the spectrometer housing. The detector's
temperature is maintained at either of two setpoints, 104K or 108K,
using an active cryogenic system in order to minimize dark current. The
cryogenic portion of the FPA is thermally isolated from its retaining
ring by rigid, low thermal conductivity nextel struts. The struts resist
creep in the orientation of the cryogenic core in the face of repeated
thermal cyclings.
 
Like the VNIR board, the IR focal plane electronics board is located in
the base of the gimbal and provides clock signals and bias voltages, and
separately digitizes the video data from each quadrant of the focal
plane.  It transmits digitized data through the twist capsule to the
DPU, controls redundant focal plane lamps, controls one of the two
redundant integrated sphere lamps, and monitors its own temperature and
current, shutter motor current, and temperatures of the detector,
spectrometer housing, telescope, and cryogenic coolers. In addition the
IR board monitors the temperature of the integrating sphere and current
of the IR-controlled sphere lamp.
 
THERMAL CONTROL:
 
CRISM's thermal design is driven by several sometimes conflicting
requirements:
- maintaining the spectrometer housing at or below -75C to minimize IR
  thermal background radiation
- maintaining the VNIR detector at -60C to retain quantum efficiency at
  > 900 nm
- maintaining the IR detector at <120K to minimize dark current
- maintaining the optics near -60C to control their thermal emission at
  the longest IR wavelengths.
- maintaining the mechanical coolers above -40C for cooling efficiency
  and to prevent leakage of their He refrigerant
 
These goals are met through a combination of passive and active cooling
that create the required thermal zones.
 
There are three radiators that provide passive cooling, plus heaters on
those components where a minimum temperature must be maintained. The
largest of the three radiators, the anti-sunward radiator or
cryoradiator, faces toward the terminator from MRO's 3 PM local solar
time sun-synchronous orbit. Its purpose is to cool the spectrometer
housing. The anti-sunward radiator is constructed from an
oriented-strand composite that provides more thermal conductivity than
alternative metallic choices for radiator construction. The duck-foot
shape increases radiator area while not interfering with the spacecraft
deck when the OSU gimbals. Ribs provide mechanical rigidity. The
anti-sunward radiator is connected to the spectrometer housing by a
flexible link. Where the radiator stem passes through the gimbal base, a
polymer spacer provides thermal isolation. A trim heater on the
spectrometer housing prevents temperature from falling low enough to
cause icing of the optics or to overwhelm the heater on the VNIR
detector.
 
The optical bench is exposed on the exterior of the instrument and is
one half of the planet-facing radiator that is oriented toward Mars
during the Primary Science Phase. It cools the telescope optics to
minimize thermal emission at the longest IR wavelengths.
 
The other half of the planet-facing radiator is the plate to which the
bodies of the three mechanical coolers are thermally sunk. Its function
is to dissipate heat from the coolers. A trim heater plus a spacecraft
survival heater keep the cooler bodies above -25C during cold excursions
such as during cruise to Mars. A narrow gap between the two segments of
the planet- facing radiator maintains their distinct temperatures.
 
The IR detector is maintained below 120K by an active cooling system
that utilizes three He-charged mechanical coolers, each linked to the IR
detector by a CH4-charged cryogenic diode heat pipe (CDHP). The CDHP's
provide thermal conductivity to a cooler that is on, and thermal
isolation from a cooler that is off.
 
The coolers are the Ricor K508 model charged with 30 bars of He, and
were specially selected from the top 2% of the product line based on
high heat lift capacity and a high ratio of heat lift to current drawn.
With the cooler body near -20C approximately 700 mW of heat lift is
available. The cooler cold tip is connected to a heat pipe with a copper
braid. Each cooler draws 450-550 mA of current at 15 V to cool the
detector to 104K.
 
The heat pipe is a sealed tube containing a condenser on the cooler end,
a wick that connects the condenser with an evaporator on the detector
end, and a liquid trap on the detector end. When the cooler is off and
the detector is cold, the liquified methane is in the liquid trap and
does not circulate; the tortuosity of the wick provides low thermal
conductivity. When the cooler is powered on and the condenser end
reaches approximately 138K, the methane begins to liquefy there and is
wicked to the evaporator where it removes heat, and vapor returns to the
condenser end to continue the cycle.  After cooler turn-on, the system
reaches temperature in approximately 12 hours.
 
The heat pipes are enclosed in a shoebox-shaped cold shroud that
envelops the assembly and minimizes radiative coupling to the rest of
the instrument.  The shroud is thermally coupled by a flexible link to
the optical bench, and suspended from the warm side of the instrument
housing by Kevlar cables. The heat pipes are supported inside the shroud
by a second set of small-diameter Kevlar cables, creating a dual-nested
Kevlar cable thermal isolation/structural support system. The shroud is
gold-plated for low emissivity to minimize radiative coupling. The
assembly is baked out in vacuum prior to operation to dissipate adsorbed
water that raises emissivity of surfaces inside the shroud and
introduces parasitic losses.
 
Optics
======
 
TELESCOPE AND SPECTROMETER:
 
CRISM's optomechanical structure is all-aluminum to minimize change in
focus with temperature. Components are mounted to an optical bench,
which also serves as a Mars-facing radiator that cools the optics to
minimize IR background, and as a mount for the shutter and internal
integrating sphere.
 
Light is focused by a 100-mm aperture, and 441-mm focal length Ritchey-
Chretien on-axis telescope onto a slit. Both the primary and secondary
mirrors are coated aluminum, and are baffled to block out-of-field paths
to the slit. The secondary is mounted by a spider and obscures 29% of
the aperture. The telescope is protected by a composite baffle with
flexure mounts to the optical bench. The interior of the baffle is vaned
to attenuate off-axis scattered light. The end of the baffle is covered
by a hinged, solid-composite, one-time deployable cover. Deployment
occurs using a high-output paraffin actuator with redundant heaters. The
cover has a telltale that indicates whether the cover is closed or not.
 
The slit is 27 microns wide and 16.3 mm long and is mounted in an
assembly for fastening to the optical bench. The slit is mounted on a
76-mm radius cylindrical surface whose axis is perpendicular to the
slit, to improve focus. The slit is constructed of nickel and its
telescope facing side is gold plated, both to resist effects of heating
and to dissipate incident solar energy in the event of a direct view of
the sun. Irregularities in slit width cause along-slit variations in
system response at the percent level; the maximum irregularity is a burr
that attenuates incoming light by only 10%.
 
Following the slit is the spectrometer optics. A wedged, ZnSe dichroic
beamsplitter reflects the VNIR while transmitting the IR, each to its
own modified Offner spectrometer and focal plane assembly. The wedge
directs internal reflections in the transmitted IR light out of its
nominal path, so that the reflections can be blocked by the
order-sorting filter on the detector. The two modified Offner
spectrometers disperse the light and focus it onto their respective
focal planes. In the VNIR spectrometer M1 and M3 are prolate ellipsoids
and the grating (M2) is mounted on a spherical surface. In the IR
spectrometer M1 and M2 are spherical and M3 is a generalized asphere
approximating an oblate ellipsoid. Both spectrometers account for the
curved slit, thereby creating a flat, well-corrected slit image at the
detector. Each spectrometer also has a fold mirror after M3 that directs
the light out of plane to focus on the focal plane assembly (FPA)
mounted on the side of the spectrometer for thermal control. Nominally
each spectrometer has unity magnification, but due to manufacturing
tolerances the angular sizes of the two FOVs differ by 1.2%.
 
The diffraction gratings are an aluminized polymer manufactured by JPL
using an electron beam process. Each is dual-zone, with each zone blazed
to maximize efficiency in either the longer- or shorter-wavelength parts
of the VNIR or IR spectral range. The areas of each zone are sized to
balance SNR in their two wavelength ranges. CRISM uses the first-order
diffracted light; higher orders from the gratings are blocked by
fixed-mounted filters on the detectors.
 
CALIBRATION SUBSYSTEM:
 
CRISM has several internal calibration capabilities that allow
monitoring of bias, dark current and thermal background, detector
nonuniformity, and responsivity of the optics including the slit and
everything behind it.
 
Two parts of the calibration subsystem, a shutter and an integrating
sphere, are built into the optical bench. The shutter is an
aperture-filling vane with a polished aluminum rear surface, attached to
a 33-position stepper motor with 3-degree  steps. In its closed position
(32), the shutter enables measurement of bias, dark current, and (for
the IR detector) thermal background. At position 17 it provides a view
of the internal integrating sphere. The open position was redefined in
software to step 3 to eliminate an unanticipated reflection from the
base of the shutter. The stepper motor has no absolute position
knowledge, and instead moves between reference positions of open (3),
sphere (17), and closed (32) by counting steps. A photodiode can view a
fiducial LED when the shutter is located at positions 0, 17, or 32.
Normally the fiducial is left unpowered to eliminate stray light, but it
will be powered periodically inflight to check that the shutter has not
skipped positions.
 
The internal integrating sphere provides a smooth, near-flat field of
dispersed light as viewed by either spectrometer, that samples all of
the optics except the telescope. It is intended as the primary inflight
reference for radiometric calibration. The sphere is lined with
sandblasted aluminum and has a slightly vignetted rectangular aperture.
Illumination is provided by either of two small incandescent lamps, one
controlled by the VNIR focal plane electronics that is located in the
plane of the slit off to one side, and one that is controlled by the IR
focal plane electronics that is located orthogonal to the slit off to
one side. The VNIR-controlled bulb is the primary bulb for inflight
calibration because its orientation generates less cross-slit brightness
gradient, minimizing effects of small irreproducibilities in the
shutter's position viewing the sphere. The lamps' peak current is 115
mA, and current level can be commanded either directly (open loop) or
under closed loop control. For closed loop control, a Si photodiode
inside the sphere measures the brightness of the lamp and adjusts
current to match a brightness goal. There is one photodiode per lamp,
controlled by the same focal plane electronics. A single closed-loop
setpoint (90% of maximum) is used inflight, and each lamp runs at 2000K
at its setpoint. Convolved with the efficiency of the optics and
detectors, signal in DN/second as viewed at the detector peaks near 2200
nm. Under closed loop control, either of the sphere lamps' brightness
stabilizes in 3- 4 seconds after it is turned on, and for the same
sphere temperature, it repeatedly achieves the same current to within
one part in a thousand.
 
Each detector can also be illuminated by either of two redundant focal
plane lamps, which are mounted in the spectrometer housing and bathe the
detector with undispersed white light. The purpose of these lamps is
measure pixel- to-pixel nonuniformities in detector response, at
brightness levels that are unattainable using dispersed light from the
sphere bulbs. This is particularly important for the VNIR detector,
where <500-nm radiance from the sphere is low. All four of the bulbs are
identical to the sphere bulbs except for their mounting. The VNIR bulbs
are mounted in the spectrometer housing to directly illuminate the focal
plane. For the IR detector the cold shield prevents a direct view, so
the lamps illuminate the detector by flooding the spectrometer housing
to create indirect illumination. At either detector, lamp 2 is the
primary lamp for inflight use because its radiance field is more uniform
at any given detector row (wavelength). The lamps' currents are only
commandable directly, open loop. Multiple levels are used for inflight,
measurements in order to attain Mars- and sphere-like brightnesses at
different detector rows
 
Electronics
===========
 
SCANNING SYSTEM:
 
The scanning subsystem consists of the Gimbal Motor Electronics (GME), a
high-resolution angular encoder, the gimbal drive motor, and the OSU
base.  The GME contains the motor driver circuitry, and responds to a
commanded profile from the DPU. Software in the DPU implements a control
algorithm, utilizing feedback information from the 20-bit, 6-microradian
precision angular postion encoder to maintain closed-looped control. The
system accurately follows a programmed scan pattern that is carefully
designed to compensate for orbital motion and to accomplish the desired
scan pattern across the Martian surface.
 
DATA PROCESSING UNIT:
 
The DPU receives unregulated 28-32 volt power from MRO and provides
regulated secondary power to CRISM, receives and processes commands from
MRO, controls the CRISM subsystems, and acquires and formats CRISM
science and housekeeping data that is then sent to the spacecraft
solid-state recorder (SSR) for downlink to earth.
 
The DPU is based upon the modular stacking electronics system developed
for CONTOUR/ CRISP and several of the instruments on MESSENGER. The
  CRISM design consists of eight electronics boards, although there are
  only 4 unique board designs. Two of the board designs are closely
  based on existing MESSENGER board designs.
 
The DPU consists of a Processor System and a Power System. The Power
System consists of DC/DC converter boards with additional circuitry, one
each for the coolers, IR focal plane, VNIR focal plane, and the
remaining DPU boards.  The DPU Power Board receives primary power from
the spacecraft and distributes it through an internal stacking connector
to all boards in the Power System. An I2C serial data bus from the
Processor Board controls all functions on the Power System boards. The
I2C serial data bus and primary power distribution allow for daisy
chaining of additional Power System boards as required. Each of the
power boards also telemeters its own temperature and the currents and
voltages being supplied by it.
 
The Processor System consists of Processor Board, a Spacecraft Interface
Board, and two Focal Plane Interface Boards (one per focal plane). The
Processor System boards use Actel field-programmable-gate-array (FPGA)
signals routed to an internal stacking connector for interfaces between
boards. The Actels are programmed to implement a data bus between
boards, allowing for daisy chaining of additional Processor System
boards as required. The Processor Board controls IR and VNIR focal plane
power and cooler power via its I2C bus, and gimbal position using a
serial RS422 interface to the GME. The Spacecraft Interface board
communicates with the spacecraft via serial low-voltage differential
signal (LVDS) command and telemetry interfaces, receives spacecraft time
synchronization and side A/B selection via a hardware signal, and
transmits science data to the SSR via serial LVDS interfaces for the IR
and VNIR focal planes. The Focal Plane Interface Boards provide clock,
frame, and command data signals to the IR and VNIR focal plane
electronics under control of the Processor Board. They receive focal
plane data and perform data editing and compression. The Processor Board
generates telemetry headers for image data and passes them to the Focal
Plane Interface Boards for incorporation onto image frames before
transmission to the SSR.
 
Operational Modes
=================
 
SOFTWARE CONTROL:
 
Core functions include autonomy, spacecraft interface, basic thermal
control, and the macro system described below. Data compression is
partially derived from that in the MESSENGER/MDIS camera, whereas cooler
and gimbal control and focal plane lamp control are derived from the
CONTOUR/CRISP instrument. Features specific to CRISM include
wavelength-dependent compression, observation control, and closed loop
control of the internal integrating sphere.
 
VNIR and IR detector control:
 
Key variables in constructing observing scenarios include the following.
All are independently selectable separately for the VNIR and IR
detectors.
 
Image source. Image data may be generated using digitized output from
the detector, or using one of up to seven test patterns stored in the
focal plane electronics.
 
Frame rate. Frame rates of 1, 3.75, 5, 15, and 30 Hz are supported. The
1 Hz frame rate is used for hyperspectral measurements of the onboard
integrating sphere, because the long exposures possible at 1 Hz are
needed for appreciable SNR at the shortest VNIR wavelengths. 3.75 Hz is
used for hyperspectral measurements of Mars; this is the highest frame
rate at which the DPU electronics support onboard compression options
over the range of wavelengths imaged onto the detectors with useful SNR.
15 and 30 Hz frame rates are used for nadir-pointed multispectral
measurements that return only selected wavelengths. The 5 Hz frame rate
is not planned for use inflight, because at that rate the electronics do
not support compression of a hyperspectral wavelength selection, and it
would produce excessive along- track smear in a nadir-pointed
observation.
 
Integration time. Integration times are in increments of 1/480th of the
inverse of the frame rate. At 1 Hz, for example, available integration
times are 1/480th sec, 2/480th sec...480/480th sec, and at 15 Hz,
1/7200th sec, 2/7200th sec...480/7200th sec.
 
Compression. All CRISM data are read off the detector in 14-bit format
and are compressed real-time in hardware. Compression options, in
succession are:
- Subtraction of an offset, on a line by line basis: Offsets are set by
  uploading a data structure to the DPU.
- Multiplication by a gain, on a line by line basis, with the output in
  12- bit format. Gains are set by uploading a data structure to the
  DPU.
- Row selection: All detector rows having useful signal can be saved, or
  alternatively an arbitrary, commandable subset of rows (a wavelength
  filter) can be saved. The number of rows with useful signal is 545,
  107 in the VNIR and 438 in the IR. These are returned in hyperspectral
  measurements. The nominal number of rows for multispectral mode is 73,
  18 in the VNIR and 55 in the IR. For each detector, there are four
  wavelength filters from which to choose rapidly by command:
  hyperspectral (545 total channels), multispectral (73 total channels),
  and two sets of expanded multispectral (82 and 94 channels). New
  options are set by uploading a data structure to the DPU.
- Pixel binning: Pixels can be saved unbinned or binned 2x, 5x, or 10x
  in the spatial direction. No pixel binning in the spectral direction
  is supported.
- Optionally, conversion from 12 to 8 bits using one of eight look-up
  tables (LUTs) specified on a line by line basis: The line-by-line
  choices are set by uploading a data structure to the DPU. The LUTs are
  stored in non- volatile memory and are not uploadable
- Optionally, lossless Fast + differential pulse-code modulation (DPCM)
  compression.
 
The offsets, gains, and row-dependent LUT choices were set following
instrument calibration. Offsets were derived from measurements of bias
at different frame rates and detector temperatures, so that the minimum
14-bit DN at any frame rate over the range of expected operating
temperatures translates to a positive, non-zero value. A single,
wavelength-independent value is used for each detector.
 
Gain and LUT choices were set following determination of instrument
responsivity and estimation of signal levels and SNRs for Mars. The gain
settings were driven by four requirements: (a) 12-bit sampling near the
level of read noise so that SNR would be effectively improved by spatial
pixel binning, (b) avoiding saturation, (c) maintaining appreciable SNR
at photon-starved wavelengths, and (d) operation considerations, i.e.,
avoiding repeatedly changing settings. The driving cases are VNIR
observations of the internal integrating sphere and VNIR and IR
observations of icy regions Mars. In each case, obtaining sufficient SNR
at <600 nm or >2600 nm requires driving other wavelengths to occupy a
large part of the dynamic range of 9800 14-bit DNs. This is 4000 times
the VNIR read noise and 5000 times the IR read noise. Therefore it was
decided to use wavelength-independent gains that code the full range of
near-linear detector response into 12 bits, which maintains 12-bit
sampling at the level of the read noise in the VNIR and at 1.2 times the
read noise in the IR. The wavelength-dependent LUT choices were made to
avoid 8-bit saturation while also minimizing quantization errors at
expected signal levels in multispectral mode observing Mars.
 
Selection of the multispectral wavelength filters was a research
project.  OMEGA data were used to generate a core set of wavelengths
needed to accurately capture the centers and shapes of absorption bands
and key spectral ratios due to minerals known to be present (olivine,
pyroxene, ferric oxides, sulfates, and clays) or sought-after
(carbonates), or due to known atmospheric constituents. These were
augmented with companion wavelengths needed to subtract a leak of the
2nd order from the grating through the IR order sorting filter at
nominal wavelengths >2800 nm. The extended sets were populated using the
CRISM spectral library, to provide better characterization of known or
suspected minerals and to detect key minerals of exobiologic interest
that are not known to be present, but may be at low abundances
(nitrates, phosphates).
 
Calibration subsystem control:
 
Calibration lamps. 4095 levels are commandable in each of two lamps at
each focal plane, and in two lamps in the integrating sphere. All
settings are open-loop, meaning that current is commanded directly. For
the integrating sphere only, closed loop control is available at 4095
settings. For closed loop control, the setting refers to output from a
photodiode viewing the interior of the integrating sphere; current is
adjusted dynamically to attain the commanded photodiode output.
 
Shutter position. The stepper motor running the shutter has 33
positions, and can be commanded in two modes. It may be commanded to
move a discrete number of steps, or it may be commanded to a predefined
position (open, closed, or viewing the integrating sphere). In software,
open=3, sphere=17, and closed=32.
 
Scan system control:
 
A torque motor under software control moves the gimbal.  Pointing toward
nadir is defined as 0 degrees. The gimbal can move back and forth
between hard stops at -60 and +60 degrees.  The software also limits the
gimbal to stay within a minimum and maximum position.  These soft stop
angles are uploadable. The motor includes a relative position encoder
and an index pulse at a known position.  Until the software is commanded
to find the index, the software does not have absolute knowledge of the
gimbal's position. The software searches for the index by moving the
gimbal back and forth between the hard stops. A hard stop is recognized
via a limit switch or a motor stall condition.
 
Once per second the software computes one second's worth of angular
positions and velocities to follow over the next second. The software
tries to remove differences between the computed values and the
platform's actual position and velocity using a Proportional Integral
Derivative (PID) algorithm. The PID control parameters are uploadable.
 
The gimbal control software can be commanded into several different
modes where the tables of positions and velocities are computed in
different ways.  When the mode is off, the motor is not driven. In hold
mode, the platform is held at the current position. In slew mode, the
platform is moved to a commanded angle. In profile mode the platform's
desired angle and velocity are computed such that the spectrometer
points to a fixed target on the Martian surface as the spacecraft passes
over the target.  The platform's angle versus time is an S-shaped curve.
CRISM software stores about 1800 S- curve profiles. New or replacement
profiles can be uploaded. The upload is not the angle vs. time curve
itself, but the coefficients of a polynomial approximation of the ratio
of downtrack target distance to spacecraft altitude. Offsets or
constant-rate scans can be superimposed on top of the commanded angle.
 
Using these capabilities, typical observations include either of two
basic gimbal pointing configurations and two basic superimposed scan
patterns.  Pointing can be (1) fixed (nadir-pointed in the Primary
Science Phase, a.k.a. pushbroom) or (2) dynamic, tracking a target point
on the surface of Mars and taking out ground track motion. Two types of
superimposed scans are supported: (1) a short, 4-second duration
fixed-rate (EPF-type) scan which superimposes a constant angular
velocity scan on either of the basic pointing profiles, or (2) a long,
minutes-duration fixed-rate (target swath- type) scan. For the second
configuration, dynamic targeting, the motion of the slit projected onto
the surface is primarily a combination of gimbal movement and spacecraft
velocity with slight variations due to continuous spacecraft yawing, and
rolling in the case of off-nadir targeting.
 
The scan platform control software can be placed in a diagnostic mode by
command.  In this mode, high rate scan data replaces image data.
 
Instrument macros:
 
A macro is a sequence of commands that can be stored and then executed
later.  A macro can be any length as long as the total length of all the
macros fit into available memory. Up to 256 macros may be defined; each
macro is identified by a small integer, 0 - 255. A macro is loaded to
the instrument by placing CRISM in a learning mode to define a macro. If
a command arrives with its macro field indicating learn, the command is
added to the macro currently being constructed.  Any command that
arrives without the learn field, is executed immediately. There are
commands for running and stopping a macro. There are also special
commands for adding delays to a macro; these can be used only within a
macro. One macro can call another or can execute loops. Both calls and
loops can be nested.  Up to 64 macros can be running concurrently.
 
Several default macros are available as soon as CRISM is started, and
are used to control instrument autonomy.
 
Observation control:
 
An observation is defined as the execution of a stored sequence of
macros while the scan platform follows a desired profile.  For the
observation to be useful the spacecraft must be oriented properly and
the command sequence and scan profile started at the correct time.
Consequently, the spacecraft computer is intimately involved in
observation control.
 
Two blocks of observation data are uploaded for each target, one to the
spacecraft computer and one to CRISM. Both blocks include a unique
target identifier (target ID). The spacecraft observation data also
includes the target's latitude and longitude, an estimate of closest
approach time tCA, and an offset from tCA indicating when to start
observing.  Using orbit and target data, the spacecraft computes the
actual tCA.  As the spacecraft nears the target, it rolls to allow CRISM
to view the target and notifies CRISM.
 
The observation data uploaded to CRISM contains the target ID, a scan
profile ID, and a list of macros and time offsets between their execution.
The relative timing of the macros will vary with the target.
 
The spacecraft starts CRISM's observation by sending CRISM a command
(CRM_OBS_START) some time before tCA - dt1. The command has the target
ID, tCA, and dt1. When CRISM receives the command, it uses the target ID
to find the corresponding stored target data. The scan profile
identifier is extracted and, using tCA, the scan profile computation
begins. The first macro of the target is run (m0) at tCA - dt1. After
the first offset time elapses (dmt0), the second macro is run (m1).
This process repeats until all of the macros are run or an offset time
of 65535 seconds is encountered.  When the spacecraft sends
CRM_OBS_START command, it also prepares the SSR for receiving CRISM
images. After the last macro of the observation is run, CRISM notifies
the spacecraft so that the SSR can be closed.
 
Cooler control:
 
The CRISM coolers are operated with a modified Proportional Integral
(PI) control loop. The CRISM software calculates the error (difference
between the goal and actual cooler cold tip temperature), and applies
the control algorithm to compute a digital value commanding the cooler
level and sends the result to a digital to analog converter. The digital
value ranges from 0 to 4095 and controls how fast the cooler motor runs.
The control algorithm runs at 5 Hz.
 
The algorithm operates in two modes. If the error is above a threshold,
only the proportional (P) part of the algorithm is applied. The error is
multiplied by a gain and an offset is added. Once the error drops below
the threshold, both the proportional and integral (PI) terms are
applied. The error is added to the integrated error. Limits are placed
on both the error to add and the total integrated error.
 
Heater control:
 
The CRISM DPU controls the temperature of five zones of the instrument:
two that encompass the focal plane electronics boards in the base of the
instrument, plus the cooler bodies, the spectrometer housing, and the
VNIR detector. The heater in each zone may be commanded off, on, or
controlled by software. If a heater is being controlled by software, it
uses a goal and hysteresis commanded for that zone. Every second the
zone's temperature is compared against its limits. If the temperature is
too low, the heater will be turned on. If the temperature is too high,
the heater will be turned off.
 
Status reporting and autonomy:
 
A collection of environmental data is monitored by CRISM including
voltages, currents, and temperatures. These analog values are read every
second or more frequently. Each monitored item has a lower and upper
limit. If an item is out of limit for one cycle, but back within limits
on the subsequent cycle, a transient alarm is reported. The alarm ID
indicates the item being monitored and whether the value was too low or
too high. The values accompanying the alarm are the out of limit data
and the corresponding limit. If an item is either too high or two low
for two consecutive monitoring cycles, a persistent alarm is reported.
  For some out of limit conditions, the software will execute a macro in
  reponse to power off the subsystem that generated the alarm.
 
Data transmission:
 
CRISM data are sent via three dedicated links to the spacecraft SSR for
downlink to the ground. A low-speed link is used for the once-per-second
or less frequent reports of voltages, currents, and temperatures via the
spacecraft interface board in the DPU. These status packets also contain
the commanded software and power configuration of the instrument. The
low-speed link also transmits alarms, and can be commanded to transmit
dumps of memory contents, the onboard macro library, or a memory
checksum (the last bits of the sum of memory contents) as health and
status checks.
 
The VNIR and IR detector each have a dedicated high-speed link to the
SSR via its interface board in the DPU. Each row of an image frame is
prefaced with a line number to track its wavelength, and each image
frame is prefaced with a header containing a snapshot of the contents of
the status packet at the time of frame measurement, as well as the
spacecraft time, target ID, and gimbal position at the beginning,
middle, and end of frame integration.
 
OBSERVATION TYPES:
 
CRISM science observations use nine basic sequences of macros that
translate into different sequences of EDRs. All of the sequences use an
onboard target list for autonomous pointing and time of observations by
the spacecraft guidance and controls system. A target ID  is used to
uniquely identify a target on this list.
 
Four of the macro sequences are intended for execution while the gimbal
is tracking a target, and superimposing 11 slow scans: Full resolution
targeted observation, half resolution (long or short) targeted
observation, and atmospheric survey EPF. All follow the same basic
outline. The gimbal is first set to +60 degrees to begin the scan, which
then starts at the commanded time. During approach to the target, the
scan profile is designed to slowly sweep the optical line-of-sight (LOS)
back and forth across the target. Thus, instead of holding the target
still within the FOV, short +/- 0.3 degree scans are superimposed. These
short scans are called EPF scans.  During target over-flight (+35 to -35
degree gimbal angle), the gimbal takes a much longer sweep across the
target. It is this long central scan that differentiates the classes of
observations. The incoming EPF sequence is repeated outgoing, except in
reverse order. Four dark measurements of instrument background are
taken, marking the start and end of each group of EPF scans, effectively
bracketing the incoming and outgoing EPF scans and the central scan.
 
The character of the central scan is what differentiates the four types
of gimbaled science observations:
 
A FULL RESOLUTION TARGETED measurement utilizes CRISM's full resolution
capabilities, at the expense of a relatively large data volume. The
gimbal is first moved to the starting position of the central scan,
which depends on the scan's length. However, it is not the scan length
that is the independent variable, but rather the desired speed of the
central scan and the time available for execution. Taken together these
dictate length of the scan and the initial gimbal position. For full
resolution observations, the central scan is executed such that the LOS
scans at a rate of 1 pixel (approximated as 60 microradians) per
integration time, and crosses the target at mid-scan. The number of
integrations is selected to mostly occupy the range of gimbal angles
between +/- 35 degrees. Depending on the altitude above a particular
target, one of several choices of macros is used to mostly occupy but
not overfill this gimbal range, and the corresponding gimbal setup macro
is used. The data are taken without spatial pixel binning, and the dark
and lamp data are correspondingly taken without pixel binning. However
to conserve data volume, the EPF scans are taken with 10x pixel binning;
the gimbal scan rate for the EPFs yields approximately square pixels
projected onto the surface.
 
A HALF RESOLUTION LONG targeted measurement covers a larger area, but at
half the spatial resolution. It is intended for targets for which areal
coverage is more important than the highest possible resolution. The
gimbal is again moved to the starting position of the central scan,
which for a given scan duration is about twice the angular offset as the
full resolution targeted measurement. The LOS is scanned at a rate of 2
pixels (120 microradians) per integration time, and sufficient
integrations are executed to mostly occupy the range of gimbal angles
between +/- 35 degrees.  Depending on the altitude above a particular
target, one of several choices of macros is used to mostly occupy but
not overfill this gimbal range, and the corresponding gimbal setup macro
is used. The duration of the scan is the same as for a full resolution
targeted measurement taken from the same altitude. The data are taken
with 2x spatial pixel binning; the higher scan rate yields approximately
square pixel footprints projected onto the planet surface. The area
covered by the central scan is approximately twice that as for a full
resolution targeted measurement. The dark data are correspondingly taken
with 2x pixel binning. However to conserve data volume, the EPF scans
are taken with 10x pixel binning; the gimbal scan rate yields
approximately square pixels projected onto the surface.
 
A HALF RESOLUTION SHORT targeted measurement is a lower data volume
alternative to the two types of targeted observations just described,
intended to provide flexibility in covering more targets. The gimbal is
first moved to the starting position of the central scan, which in this
case is chosen so the scan only occupies about half the range of gimbal
angles between +/- 35 degrees. Then the LOS is scanned at a rate of 2
pixels (120 microradians) per integration time, and sufficient
integrations are executed to occupy approximately half the range of
gimbal angles between +/- 35 degrees. Depending on the altitude above a
particular target, one of several choices of macros is used, and the
corresponding gimbal setup macro is used.  The duration of data
collection over the central scan is half that of a full resolution
targeted measurement taken from the same altitude. The data are taken
with 2x spatial pixel binning; the higher scan rate yields approximately
square pixel footprints projected onto the planet surface. The area
covered by the central scan is approximately the same as that as for a
full resolution targeted measurement. The dark data are correspondingly
taken with 2x pixel binning. However to conserve data volume, the EPF
scans are taken with 10x pixel binning; the gimbal scan rate yield
approximately square pixels projected onto the surface.
 
In an EPF measurement, the central scan is replaced with another EPF
scan.  The EPFs and dark  data are all taken with 10x pixel binning. An
EPF measurement is intended to characterize the atmosphere or the
average surface properties of a kilometers-sized area, as a part of
tracking seasonal changes.
 
The multispectral survey is intended to map large areas Mars
Odyssey/THEMIS- IR scale of resolution, for two purposes: (a) to find
sites for targeted measurements, or (b) to characterize composition over
large, contiguous areas. This type of observation does not use a scan
profile, but is nadir- pointed and measures selected wavelengths at
elevated frame rates. The basic configuration is a repeating sequence of
alternating Mars-viewing and background measurement macros. The
Mars-viewing periods are constrained to be in blocks of 3 minutes so
that adequate interpolation of background is possible. CRISM spends most
of its observing time in this mode.
 
In MULTISPECTRAL SURVEY mode, the instrument is fixed pointing at nadir,
and selected wavelengths are measured at spatial resolution that is
reduced by binning pixels in the spatial direction, to manage data
volume. This mode of operation is intended to search for new targets of
interest and to provide moderate spatial and spectral resolution mapping
of surface composition.  Data are compressed to 8 bits using the LUTs
defined line by line.  Multispectral survey data and accompanying
background and lamp calibrations are taken in 10x pixel binning mode,
with 72 channels selected. Dark, lamp, and Mars data are all taken at 15
Hz, yielding 200-m effective pixels projected on Mars.
 
MULTISPECTRAL SURVEY POLAR mode differs in that data are compressed only
losslessly.
 
MULTISPECTRAL WINDOWS resemble the above multispectral survey, except
that they are taken at 30 Hz with 5x pixel binning, yielding 100-m
effective pixels projected on Mars. These data are always taken in
12-bit format.  Multispectral windows have 3 basic uses:
- Polar monitoring. Selected parts of the polar region are observed
  several times around specific periods of Ls to monitor seasonal
  changes in the polar cap.
- Ridealongs. If a High-Resolution Imaging Science Experiment (HiRISE)
  or Context Imager  (CTX) measurement is not coordinated with a CRISM
  targeted measurement, then a 15-second duration multispectral window
  with a preceding dark measurements and following lamp measurement may
  be executed, with the window centered on the center of the HiRISE or
  CTX target. This assures that science observations by either of those
  instruments are accompanied by at least a minimal CRISM observation.
- Depending on downlink availability, multispectral windows can be used
  in place of the multispectral survey for mapping selected regions of
  the planet. Because of lower SNR than in survey mode, this is only
  recommended for resolution of 100-m scale spatial heterogeneity, not
  for detection of weak bands.
 
RADIOMETRIC CALIBRATION is performed at least daily. A radiometric
calibration consists of a set of sphere measurements (with the sphere
operated closed-loop) with bracketing measurements of the ambient
background with the shutter viewing the darkened sphere. These data are
used to recover radiometric responsivity.
 
A BIAS CALIBRATION consists of a set of shutter-closed measurements at
each frame rate, at 4-5 integration times per frame rate. These data are
used to recover detector bias, i.e., the offset image with zero scene
radiance or thermal background. Bias calibration is performed at least
daily.
 
FLAT-FIELD CALIBRATION is performed at monthly intervals. A flat-field
calibration consists of a set of of a bland region of Marx with
bracketing background measurements. These data are used to recover
non-uniformity of the VNIR detector. (The integrating sphere provides
sufficient signal for this to be measured in the IR, but in the VNIR, at
wavelengths <600 nm there is insufficient signal at a single detector
element to determine non- uniformity at the desired accuracy of 0.001.)
 
A calibration source INTERCALIBRATION is performed monthly to track
long- term changes in system response. The sphere bulb controlled by the
VNIR electronics is the primary radiometric reference for CRISM. The IR-
controlled bulb is measured only monthly to monitor output of the VNIR-
controlled bulb for long-term changes.
 
Calibration
===========
 
Calibration occurred onground and continues inflight, the latter using
recurring measurements that accompany measurements of Mars (e.g.,
shutter- closed measurements and measurements of the internal
integrating sphere and focal plane lamps) as well as special
observations including star measurements. Ground calibration
characterized those attributes that are difficult to measure inflight,
such as linearity, and establishes the baseline performance of the
onboard calibration subsystem (such as the radiance field of internal
sources) that is needed to process inflight calibrations.
 
Ground calibration occurred in six stages:
(1) The VNIR and IR detectors were characterized individually at
temperature for detector-specific attributes such as bias, dark current,
and linearity.
(2) The detectors were aligned in the optical assembly for best focus
and to minimize optical distortions including spectral smile, keystone,
and rotation of the detector relative to the beam. At the same time,
data were collected to characterize the calibration subsystem and
optical performance.
(3) The integrated system was tested at temperature.
(4) Following environmental testing, calibrations not requiring
collimated light were repeated during thermal balance measurement of the
instrument.
(5) Measurements requiring collimated light were repeated.
(6) After initial delivery and integration onto the MRO spacecraft,
CRISM and the other instruments were refitted with replacement FPGAs.
Following the FPGA replacement, key calibrations were repeated.
 
Stage 1 was completed at the Optical Development Laboratory at APL.
Stages 2, 3, 5, and 6 were completed at the Optical Calibration Facility
(OCF) at APL. Observations were acquired either looking out a sapphire
window at one of several calibrated field-filling radiance sources (a
blackbody, a gold- lined integrating sphere, a Spectralon-lined
integrating sphere, and Spectralon and rare-earth oxide-doped Spectralon
plates illuminated by a halogen lamp), or through a collimator looking
at sub-pixel or extended white light or monochromatic sources, a
military resolution target, or various geologic hand samples to validate
calibration. Stage 4 was completed at APL's Space Simulation Laboratory
in a thermal vacuum chamber outfitted with a sapphire window, viewing a
blackbody or the halogen lamp-illuminated Spectralon plates. In all
cases, observations of external sources were accompanied by measurements
of the internal calibration subsystems. During stages 1 and 2 over
168,000 frames of VNIR or IR data were acquired, and during stages 3
through 6 over 946,000 frames were acquired, typically in bursts of 12
to improve photon counting statistics. Measurements were purposely taken
at a variety of frame rates and exposure times.
 
Detector alignment:
 
The final ground calibration yields wavelength limits of 362-1053 nm in
the VNIR and 1002-3920 nm in the IR, over the range of detector rows
that are included in the wavelength filters used for hypespectral
observations.  Measured dispersion is 6.55 nm/channel. Columns 0-11 of
the VNIR detector and 0-7 and 634-639 of the IR detector are physically
masked and serve as an unilluminated reference for integrity of
radiometric calibration.  Specifically, near-zero values in calibrated
data indicate correct removal of bias, thermal background, and
electronics ghosts. Columns 12-23 and 627- 639 of the VNIR detector and
8-27 of the IR detector are exposed but not directly illuminated through
the slit and measured glare from the gratings.  Columns 25-625 of the
VNIR detector and 29-632 of the IR detector measure the scene or the
internal integrating sphere. Other columns are transitional.
 
Keystone (spatial drift along a detector column) is +/- 0.4 pixels at
the edges of the detectors, with near-zero values near column 250 on
each detector.
 
The total magnitude of spectral smile (wavelength drift along a detector
row) exceeds 1 pixel, with the least variation along-slit near column
275 of the VNIR detector and column 350 of the IR detector. Thus, for
extraction of data from overlapping EPF measurements, columns 275-350
form the sweet spot on the detectors where optical distortions are
minimal.
 
Modulation transfer function and scattered light: A key requirement of
CRISM is to resolve small-scale deposits. The requirement of MTP>0.2 at
9.25 cycles/mm at the detector, required to resolve a 75-m spot on the
surface from MRO's nominal 300-km altitude, is exceeded at all
wavelengths. The smallest spot at which this requirement is met at all
wavelengths in the central 1.8 degrees of the FOV is 38 meters.
 
The point spread function falls by a factor of 100 within 3 spatial
pixels and 1000  within 10 spatial pixels. Integrating from 0.01-3
degrees outside the instrument aperture defined by the slit,
approximately 1.3% of the measured light in a given spatial pixel comes
from more than 3 spatial pixels distance and 0.1% from outside 3
degrees.
 
Spectral sampling:
 
In order to distinguish spectrally similar minerals that have different
geological implications for their environments of formation, adequate
spectral resolution is necessary. This requires not only spectral
sampling, but a sufficiently narrow full width half maximum (FWHM) of
the instrument response in the spectral direction (the slit function).
CRISM's spectral sampling is specified at <10 nm to provide
oversampling, and the instrument meets that requirement. The measured
FWHM is 8 nm in the VNIR across the FOV. In the IR it increases from 10
nm at short wavelengths to 15 nm at the longest wavelengths at the
center of the FOV, and broadens by about 2 nm to +/- 0.8 degrees from
the center of the FOV. Outside +/- 0.9 degrees from the center of the
FOV the telescope is slightly vignetted, so further degradation is
expected at extreme field angles.
 
Signal to noise ratio:
 
Extraction of mineralogically useful spectral data at high spatial and
spectral resolution requires high SNR. The internal CRISM requirement is
an SNR of 400 at 2300 nm for typical Martian materials. 2300 nm was
chosen because it approximates the wavelength of key absorption bands
due to H2O and OH in minerals, and the value of 400 is to detect 1%
depth absorption bands with confidence. SNR for a reference Martian
scene was estimated using system responsivity derived from observations
of the Spectralon plate at <2500 nm and the large-aperture blackbody at
>2000 nm. For typical Martian scendes, SNR is >100 at nearly all
wavelengths and >300 at 500-2500 nm, just exceeding the requirement at
2300 nm. Lower SNR at <450 nm and >2500 nm is a consequence of Mars's
inherently low reflectance at those wavelengths.  Effective SNR is
higher during 10x-binned multispectral mapping because of the
statistical effects of averaging multiple spatial pixels.
 
Operational Considerations
==========================
 
Like any spacecraft instrument, CRISM exhibits artifacts that require
corrections beyond the basic radiance calibration. The seven most
significant artifacts were found early enough during calibration either
to be corrected or to be characterized sufficiently to be calibrated
out.
 
First, the boundary of zones 1 and 2 of the VNIR order sorting filter is
a joint between two distinct glasses with different indices of
refraction.  When illuminated during stage 1 testing for linearity, it
was found to cause significant (>>10%) scattered light at shorter
wavelengths (<670 nm). This was correcting by replacing the VNIR focal
plane assembly with the flight spare, onto which a narrow black stripe
was painted to shadow the joint. The black stripe attenuates the light
from 610-710 nm and explains the dip in response at those wavelengths
in Figures 36 and 37.
 
Second, the linearity of both detectors was found to be extraordinarily
sensitive to the bias voltage applied. Upon discovery of this during
stage 1 testing, the voltage was modified from 5 to 4.8 V to lessen the
effect. In hindsight, and if time had allowed, there should have been a
study of several bias voltages near 4.8 V to identify the one producing
the least nonlinearity.
 
Third, CRISM's gimbal housing has a gap between two segments of its
planet facing radiator, in order to simultaneously maintain the cooler
bodies at
>248K and the spectrometer housing at <198K. During ad hoc testing for
scattered light during stage 2 (performed by walking a flashlight around
the gimbal housing with a mounted but unaligned VNIR detector), a sneak
path for undispersed light to the VNIR detector was discovered. This was
easily fixed by covering the VNIR FPA with thermal blanketing, but the
result was a heat leak from the FPA to the spectrometer housing, raising
spectrometer housing temperature to near is maximum desired value of
-75C. To remediate the heat leak, VNIR operating temperature was
modified from -20C, intended originally, to -60C.
 
Fourth, the original open position for the shutter at step 0 of 33 was
found to create a ghost image of the scene approximately 1 degree out of
the FOV in the cross-slit direction, with a magnitude 10-30% of the
primary scene.  This was remediated by a software fix, in which open was
redefined to position 3, which moves the origin of the ghost image to an
angle further from the FOV at which it is baffled by the telescope.
Secondary artifacts created by this fix are discussed in more detail
below.
 
Fifth, zone 1 of the IR order sorting filter was found to have a red
leak at
>4200 nm, beyond CRISM's nominal wavelength range but within the
>spectral
range at which the detector responds. Hence, thermal background is
unexpectedly large at 1000-1700 nm in the IR. This was discovered too
late for redesign of the filter; the main effect is decreased - but
still high - SNR at the affected wavelengths.
 
Sixth, it was intended originally that the maximum wavelength would be
4050 nm - compared to MRO's basic requirement of >=3600 nm - in order to
cover the strong carbonate band centered at 3980 nm. Due to tolerances
in the manufacturing process, the peak response of the zone 3 linearly
variable filter was mismatched to the peak required for 4050 nm light to
fall on the detector. The mismatch was greater than the 80-nm bandpass
of the filter. To maintain responsivity at >2700 nm, a long-wavelength
cutoff of 3920 nm was accepted to properly align the filter with light
dispersed from the gratings.
 
Finally, the spectrometer slit - which defines the mapping of
wavelengths to detector rows as well as the spatial FOV - is mounted on
a curved surface whose axis of curvature is parallel to the wavelength
direction. The slit assembly is fixed with pins through holes whose
diameters are oversized to provide margin for fastening the assembly.
During instrument-level vibration testing between calibration stages 3
and 4, the slit assembly shifted in the wavelength direction by the
tolerance in the hole diameters, shifting wavelength calibration by
about 15 nm in both the VNIR and IR. Although vibration testing exceeded
expected launch vibrations by about 50%, additional shifting of the slit
assembly during launch cannot be ruled out.  If this occurred, it can
easily be calibrated out using the measured positions of Martian
atmospheric gas absorptions.
 
The remaining artifacts are relatively minor and/or have straightforward
(though sometimes tedious) corrections and are discussed below.
 
Electronics effects:
 
Several attributes of the VNIR and IR detectors have to be corrected for
small differences in detector temperature between measurements of scenes
and measurements of internal calibration sources. The required precision
of knowledge of detector temperature is approximately 0.3K. Relatively
late in calibrations, it was found that raw values of temperatures
telemetered by the IR focal plane electronics (including both redundant
detector temperatures) were being perturbed by up to 2K by changes in
current loads on the board. These variations in current result from
normal operations like changing  frame rate, running lamps, or running a
cooler.
 
In practice, this artifact is corrected by calibrating it out. The large
number of ground calibration frames afforded many cases in which loads
changed while temperature remained constant, and these cases occurred
over temperatures that span the operating range. The raw telemetry value
at each frame rate is corrected to its corresponding value at 1 Hz
before conversion from digital to physical units.
 
Both detectors, but especially the VNIR detector, is subject to a weak
ghost image of any illuminated spot into its corresponding location in
every other quadrant of the detector. The cause is suspected to be that
all four quadrants share a common ground through which electrical
cross-talk occurs.  This is a small effect at the <1% level, and in
practice is removed by scaling the image of each quadrant by an
empirically determined value that is nonlinearly related to signal
level, and then subtracting the scaled quadrant image from that of every
other detector. To the uncertainties in measurement, each of the four
quadrants in a detector behaves only slightly differently. There is a
minimal effect of frame rate, but ghost magnitude is apparently
unaffected by detector temperature.
 
As mentioned previously, both detectors exhibit slightly nonlinear
response to input signal. This was characterized during stage 1 testing
by a matrix of measurements at each frame rate, in which both the level
of a well- calibrated light source and exposure time were varied. Both
types of modulation of total signal produce indistinguishable results.
Nonlinearity is well described by a logarithmic function of bias- and
ghost-corrected DN; corrections for flight scale DN by the difference in
relative responsivity from that occurring at a reference DN level. It is
critical that bias and ghost corrections be performed prior to this
correction, to eliminate negative values due to interquadrant ghosting.
Each frame rate exhibits a different nonlinear relationship of relative
responsivity and bias- and ghost corrected DN, but the 4 quadrants of
each detector are indistinguishable.
 
Shutter reproducibility:
 
In order to illuminate the spectrometer slit's full 2.12 degree FOV,
CRISM's telescope illuminates a circular region of slightly larger
diameter surrounding the slit. The base of the shutter, on the hinge
end,  just protrudes into the illuminated area. At position 0,
originally intended as the open position, the reflective rear surface of
the shutter provides the detectors an unbaffled view of the scene
approximately 1 degree from the center of the FOV in a cross-slit
direction, creating an out-of-focus ghost image of that location. Moving
the shutter through successive steps redirects the angle from which the
ghost image originates to further from the center of the FOV. At
position 3, the angle from which the ghost image originates is baffled
by the telescope, and the ghost disappears. To remediate the ghost
image, the open position of the shutter was redefined in software as
position 3.
 
At position 3 the shutter attenuates up to 10% of the light coming from
an external scene, depending on the wavelength. The short-wavelength
zone of the VNIR grating and the long-wavelength zone of the IR grating
are blocked preferentially.
 
In frames that view the integrating sphere, ratioing successive views of
the sphere (between which the shutter is moved) creates a distinctive
wavelength-dependent pattern in which brightness of the sphere is non-
repeatable by up to a few percent. This is explained by a small (0.1
degree) non-reproducibility in the angle at which the sphere is viewed
and the fact that, unlike the external scene, the spectrometer's view of
the sphere is vignetted by the sphere's aperture. With a slight shift in
shutter position, the cone of sphere light entering spectrometer optics
shifts. The filling of dual zone gratings changes slightly, decreasing
responsivity at long VNIR wavelengths and short IR wavelengths.  Also,
the shadow of the black strip on the VNIR order-sorting filter zone
boundary shifts, creating a distinctive trough and peak pattern at
detector rows 222-235.
 
Because this effect is so characteristic as a function of wavelength, it
is easily correctable. Ratios of different sphere observations during
ground calibration are used to create a multiplicative correction to a
sphere image as a function of wavelength. In flight data to be
corrected, the magnitude of the peak near VNIR row 235 is measured. The
correction is scaled to by the magnitude of the peak, and it is
multiplied by the data. The VNIR row 235 peak is used to scale the
corrections for both the VNIR and IR.
 
To the limits of measurement error, the small irreproducibility of
shutter position at the open position has no measurable effect on
external scene data.
 
IR second order leakage:
 
During stage 3 calibration in the OCF, monochromatic light was scanned
in a grid in wavelength and along-slit spatial positions to search for
out-of- band light. Out of band leakage was found in zone 3 of the IR
order sorting filter. The filter admits up to 3% of the 2nd order light
from the grating, at wavelengths 1400-1950 nm, that falls at detector
rows whose nominal wavelengths are 2800-3900 nm. The leakage peaks at a
nominal wavelength of 3400 nm. Due to the falloff of both the solar
spectrum and the Martian reflectance spectrum with increasing
wavelength, the relative magnitude of the leakage to the signal in zone
3 is exaggerated.
 
The OCF testing provided sufficient data for an empirical correction for
this effect, in which scaled values of signal at second-order
wavelengths are subtracted from first-order (nominal) wavelengths.
 
Bias levels:
 
Bias is the response of the detector to zero input signal from light or
thermal background, and includes two components.  At operating
temperatures of -60C, VNIR dark frames measure only bias. One component
is a fixed pattern that varies pixel-to-pixel +/- 25 14-bit DN's, and
has a weak columnar organization. The second component is a step
function of about 20 14-bit-DNs that occurs at some row of the detector.
The row at which this occurs moves systematically with frame integration
time.
 
The fixed-pattern component of bias depends on frame rate, differing by
about 100 14-bit DNs between frame rates. It also varies with detector
temperature and temperature of the focal plane electronics. It is
thought that the temperature dependence may be due to effects on
electronics components that are involved in applying a bias voltage to
the detector. To the limits of measurement uncertainty, the temperature
dependence itself is independent of quadrant or frame rate.
 
Inflight, the fixed pattern to the bias will be measured via dedicated
calibrations, and will be adjusted for changes in detector or focal
plane electronics temperature based on telemetered temperatures. The
step function will be modeled.
 
Bad pixels:
 
The IR detector is operated at cryogenic temperature to minimize dark
current and bias level of the detector. With increasing detector
temperature, not all pixels accrue an elevated bias level or dark
current - the latter of which adds noise due to its electron counting
statistics - at the same rate. The most susceptible pixels, within which
effective SNR or available  dynamic range are adversely impacted, are
bad pixels.
 
Sphere radiance:
 
Under closed-loop control, the brightness of either of the integrating
sphere's lamps is measured by a Si photodiode that adjusts current up or
down to reach a commandable brightness goal. The responsivity of the Si
in the photodiode is affected by temperature at >900 nm, becoming more
sensitive to light at warmer temperatures. So, as sphere temperature
increases and the Si becomes more photosensitive, the same commanded
goal requires less lamp current. The decrease in lamp current results in
a decrease in with increasing sphere temperature. Inflight, sphere
radiance is modeled based on ground calibration at different operating
temperatures, which were measured by comparing against stable external
sources (the Spectralon plate and blackbody). Output radiance at the
commanded brightness goal is calculated at every pixel of each detector
as a function of telemetered sphere temperature; there is a separate
model for each sphere bulb.
 
Detector responsivity:
 
Both the VNIR and IR detectors exhibit dependence of their spectral
responsivities on detector temperature. In the VNIR detector, the +/- 1K
thermostatic cycling of the detector heater on the timescale of minutes
affects responsivity at >900 nm by up to a few percent, due to the
temperature-dependence of Si photosensitivity at those wavelengths.
Inflight, differences in responsivity on such very short time scales
will be corrected using a function of telemetered detector temperature,
derived from VNIR ground measurements of a stable reference (the
Spectralon plate) taken as detector temperature cycled.
 
In the IR detector, the longest wavelengths (especially zone 3) exhibit
a cyclical pattern of responsivity variation as a function of
wavelength. The pattern is interpreted as Fabry-Perot fringes due to
interference by long- wavelength light that penetrates the HgCdTe
detector material which - at those wavelengths - is only a few
wavelengths thick. The pattern shifts systematically as a function of
detector temperature due to thermal expansion of the detector material.
The change in temperature required to introduce these artifacts at the
level of anticipated noise in the data is near 0.25K, and IR detector
temperature is predicted to vary by 1-2K in the course of one Mars
orbit. A model of detector IR responsivity as a function of temperature,
analogous to that for the VNIR detector, is used to calibrate out the
fringes. However it is not anticipated that the model would be accurate
enough to correct the effect to the level of noise due to its high
frequency and the problems with telemetered IR detector temperature.
Instead, the sphere will be measured repeatedly as detector temperature
changes, and the sphere used as a relatively stable reference against
which to calibrate out these effects.

        