
 
  INSTRUMENT: VISUAL AND INFRARED MAPPING SPECTROMETER
  SPACECRAFT: CASSINI
 
  Instrument Overview
  ===================
 
  This section is intended to give the reader a broad overview of the
technical aspects of the VIMS instrument (Brown et al 2005). It is not
intended to be a detailed technical description nor a complete
operator's manual. For a detailed technical description, the reader is
directed to papers in the open literature (Miller et al 1996, Reininger
et al 1994).
 
  VIMS-V is a multispectral imager covering the spectral range from 0.30
to 1.05 micrometers. VIMS-V is equipped with a frame transfer CCD matrix
detector on which spatial and spectral information is simultaneously
stored. The CCD is passively cooled in the range -20/+40 degrees C.
Radiation collected from VIMS-V telescope is focused onto the
spectrometer slit. The slit image is spectrally dispersed by a
diffraction grating and then imaged on the CCD: thus, on each CCD column
a monochromatic image of the slit is recorded. On-chip summing of pixels
allows implementation of a large number of operating modes for different
observing conditions.
 
  The maximum capabilities of VIMS-V are a spectral resolution of 1.46
nm and a spatial resolution of .167 millirads while in the
high-resolution mode of operation. On-chip summing of 5 spectral x 3
spatial pixels enables the normal mode of operation whereby VIMS-V
achieves a spectral resolution of 7.3 nm and a spatial resolution of .5
millirads. The total field of view of the instrument is 2.4 deg x 2.4
deg, although matching with the IR channel imposes the use of a 1.8 deg
x 1.8 deg FOV. In table 1 are listed the main characteristics of the
instrument.
 
  VIMS-V is composed of two modules, the optical head and the electronic
assemblies, housed in separate boxes. The VIMS-V optical head consists
of two units: a scanning telescope and a grating spectrometer, ideally
joined at the telescope focal plane where the spectrometer entrance slit
is located.  The telescope mirrors are mounted on an optical bench that
also holds the spectrometer. In fact, the optical bench is the reference
plane for the whole instrument.
 
  The telescope primary mirror is mounted on a scan unit that
accomplishes two specific tasks: a) pointing and b) scanning. The
scanning capability enables the .5 millirads IFOV of the nominal mode of
operation by a two-step motion of the primary mirror during each
integration time; images are produced by scanning across the object
target in the down track direction (push-broom technique). The pointing
capability is used to image selected target regions in a range about 1.8
degrees around the optical axis, and to observe the Sun, through the
solar port, during in-flight radiometric calibration.
 
  An in-flight calibration unit is located at the entrance of the
telescope.  The unit consists of: a) two LEDs for a two-point
calibration of the spectral dispersion and b) a solar port for direct
solar imaging and hence for radiometric calibration. Because the remote
sensing pallet is body-mounted to the spacecraft, to image the Sun the
spacecraft is reoriented to form a 20 deg angle with the boresight
direction of the instrument and the instrument scan mirror needs to be
moved to an angle of 4.8 degrees from boresight. Under these conditions
light from the Sun passes through a cutout in the instrument baffle and
then through a prism that attenuates the solar radiation and redirects
it towards the telescope primary mirror. Due to budget constraints, the
high-resolution mode was been implemented and tested, but not
calibrated. Calibration will be accomplished during the cruise phase to
Saturn.
 
  The VIMS infrared channel is the culmination of an effort by the NASA
Jet Propulsion Laboratory in collaboration with the French and Italian
space agencies to develop an improved imaging spectrometer for use in
spacecraft studies of planetary surfaces and atmospheres. This
collaboration resulted in several similar instruments optimized for
different planetary targets, most notably the OMEGA instrument, the Mars
Observer VIMS, and the CRAF VIMS. Mars Observer VIMS and CRAF VIMS are
Cassini VIMS most immediate forebears, but changes made in the VIMS
instrument design in response to NASA's demands to reduce the cost of
the strawman Cassini VIMS resulted in a substantial heritage from
Galileo NIMS. Despite that heritage, which goes so far as to include
parts from the Galileo NIMS engineering model, Cassini VIMS is a
substantial step beyond NIMS in the evolution of visual and infrared
imaging spectrometers.
 
  The major differences between the Cassini VIMS and the Galileo NIMS
lie in the incorporation of a separate visual channel using a
frame-transfer, silicon CCD detector with separate foreoptics and
analog/control electronics, the inclusion of a radically improved
infrared detector with improved order sorting and thermal background
rejection, an improved infrared focal plane cooler design, an improved
main electronics design, a two-dimensional, voice-coil-actuator-driven,
scanning secondary mirror in the infrared foreoptics, a fixed, triply
blazed grating in the infrared, a redundant 16 megabit buffer, and a
redundant, lossless, hardware data compressor using a unique compression
algorithm developed by Yves Langevin. These improvements result in an
instrument with substantially greater capability for planetary imaging
spectroscopy--so much so that Cassini VIMS is the most capable and
complex imaging spectrometer presently flying on a NASA planetary
spacecraft.
 
  The IR channel optics that was successfully deployed as of August 15,
1999, some 50 hours before the time of closest approach during the
Cassini Earth Swingby. The visual and IR channels are mounted to a
palette that holds them in optical alignment and helps to thermally
isolate the instrument from the Cassini spacecraft.  Thermal isolation
is particularly important for the infrared channel because thermal
background radiation from the IR spectrometer, combined with shot noise
from leakage current in the InSb photodiodes of the 256 element linear
array detector of the IR channel are the chief sources of noise in
measurements obtained with the IR channel. The nominal operating
temperature for the IR focal plane is 55-60 K and for the IR foreoptics
and spectrometer optics 120 K.
 
  The Cassini VIMS instrument is mounted on the Cassini spacecraft by
means of a palette (called the Remote Sensing Palette or RSP) on which
are also mounted the Cassini Imaging Science Subsystem (ISS), the
Composite Infrared Spectrometer (CIRS), and the Ultraviolet Imaging
Spectrometer (UVIS). Mounting of all the Cassini remote sensing
instruments on a common palette allows relatively precise boresight
alignment of the four instruments, enhancing synergy between the 4
instruments.
 
  Science Objectives
  ==================
 
  The VIMS science investigation is focused on the study of the Saturn
system and on objects that Cassini encountered during it's cruise to
Saturn. The Cassini trajectory uses gravity assists from Venus, Earth
and Jupiter to eventually get the Cassini spacecraft to Saturn, so
additional opportunities for scientific study of planetary bodies
present themselves well ahead of the Cassini Saturn orbital insertion
maneuver.
 
  The Saturn System provides a unique challenge for VIMS.
VIMS's capability to acquire the full range of visual-near-infrared
wavelengths in two-dimensional maps over a wide variety of illumination
and emission angles enables a diverse investigation of chemical,
dynamical, and geophysical phenomena. Important targets for VIMS include
the surface and atmosphere of Titan, the cloud-rich atmosphere of
Saturn, Saturn's rings, and a plethora of icy moons. Observations of
both the day and night sides of these objects should lead to increased
insights into various phenomena involving both reflection and emission
of radiation.  Occultations of the Sun and stars by these objects should
provide new insights into the nature of tenuous stratospheric hazes on
Saturn and Titan, the structure of faint rings, and atmospheric
composition.
 
  Calibration Description
  =======================
 
  The main VIMS ground calibration took place at the Jet Propulsion Lab
during the months of January and February 1996. The detailed plan for
the VIMS ground calibration evolved over a period of approximately 4
years, being completed in mid 1995, roughly 6 months before the actual
measurements were to commence. The time frame for the ground calibration
was driven by the planned delivery date of the fully integrated VIMS
instrument in the September-October period, 1996. Because the VIMS
Visual Channel was not completed at the time of the main calibration,
only the IR channel was calibrated. The Visual channel was calibrated
separately at Officine Galileo (Firenze, Italy) (the instrument
provider), in the spring of 1996, and later a small number of
operational/performance tests were carried out in late summer of 1996
after the Visual and IR channels were integrated at JPL. As a result
of the slip in the schedule for the delivery of the Visual Channel,
a substantial recalibration of the instrument has been undertaken while
the VIMS is in route to Saturn. The details of the efforts to calibrate
the VIMS instrument in flight appear later in this document.
 
  The main ground calibration of the IR channel was carried out in 6
separate areas: radiometric/flat field response, geometric,
polarimetric, spectral, and solar port response. In the early phases of
the genesis of the VIMS ground calibration plan, measurement of VIMS
stray light rejection performance was also envisioned, but practical
difficulties in performing those measurements under vacuum and at the
operational temperatures required necessitated elimination the
ground based measurements in favor of measurements in flight. Those
measurements are discussed later in this document.
 
  The actual measurements were carried out in the JPL thermal vacuum
testing facility in the largest thermal vacuum tank available. The
in-flight thermal environment for VIMS was simulated by cooling the
interior surfaces of the thermal vacuum tank with liquid N2, and
providing a cold target that filled the fields of view of both the
visual and infrared channel's passive coolers with a high emissivity
surface cooled to 4 K.  In retrospect, the thermal environment of the
JPL thermal vacuum tank and the cold target was quite accurate because
the temperatures of the instruments optics and focal planes in flight
are within a few K of those measured while the instrument was in the
test environment. Described in more detail below are the main results of
Each of the major calibration tests listed above. For more information
on the VIMS calibration during the galilean satellites flyby, see McCord
et al 2004.
 
  RADIOMETRIC CALIBRATION
 
  VIMS IR Channel
 
  The radiometric response of the VIMS IR channel was carried out before
launch in the thermal vacuum facility at the Jet Propulsion Laboratory.
A team of scientists, supported by the instrument engineering team at
JPL, designed and carried out these measurements. The team members
responsible are Thomas B. McCord (lead), Robert Brown, Angioletta
Coradini, Vittorio Formisano, and Ralf Jaumann. Also contributing were
Giancarlo Bellucci, Bonnie Buratti, Frank Trauthan, Charles Hibbitts and
Gary Hansen. Two sessions were conducted, one in January and the other
in July of 1996.  In-flight calibration efforts were conducted during
the Venus, Earth and Jupiter flybys and for two star observations.  A
workshop was held in Hawaii in February 2001 to review the information
obtained. Additional people contributing post launch were Kevin Baines,
Roger Clark, and Robert Nelson. More information on the calibration test
and data results can be found in Coradini et al 2004.
 
  The equipment facility during the ground calibration included a JPL
thermal vacuum chamber cooled by liquid nitrogen and containing the
instrument, which viewed the outside through a window with known optical
transmission.  A reflecting collimator fed light from several sources to
the instrument.  The calibrated sources were a glow bar and a tungsten
lamp and their energy delivered to the instrument was controlled by
adjustable iris diaphragms at the exit of the lamps. The light sources
and delivery system were covered to eliminate outside light and, during
the first session, the tent was purged with dry nitrogen to reduce the
effects of the atmosphere gas absorptions (mainly CO2 and H20).
Measurements were made at several instrument and focal plane
temperatures, but most measurements were made with the focal plane
temperature in the range 60.7 to 61.69 K.  Data were acquired at several
light levels and integration times, including zero.
 
  The characteristics of the instrument that were explored were dark
current (detector thermal carrier generation and electronic off-sets),
background signal (mostly thermal radiation from the chamber window and
from outside), linearity of response, ratio of responses at the two gain
states, performance of the detector for two different bias levels, and
overall radiometric response over the spectral range. The instrument was
determined to be linear within the measurement error to detector
saturation. The dark current, background, gain ratios and behavior at
different bias are reasonable, stable and as expected. The overall
spectral responsivity was most difficult to calibrate due to several
factors, including an unexpected and unknown (at the time) change in a
light source during the calibration effort. This effort has been
enhanced during in-flight calibration efforts and the responsivity
calibration seems to be converging.
 
  In-flight calibrations were conducted at Venus only for the visual
channel because the cooler cover was not yet removed from the IR channel
radiator.  The entire instrument calibration was tested at the
Earth-Moon (for the Moon only) and the Jupiter fly-bys and for two star
observations. The data are still being analyzed at this writing for the
in-flight calibrations, but the general result so far is to further
refine the calibrations and to gain better understanding of the
instrument performance, which remains as expected.
 
  One interesting characteristic experienced is the difficulty of
achieving precise and stable calibration for sources smaller than the
spectrometer slit width (sub-pixel sources). This is because the
effective spectral resolution of the spectrometer and the exact location
of the source image on the detectors depend on the size of the source
and its exact location in the focal plane. Thus, it will be difficult to
precisely predict radiometric performance for sub-pixel sources.
Nevertheless, for sources that fill the slit, the instrument behavior is
normal and as expected. The spectro-radiometric response function as
currently known is given in figure 6.1. Improvements and changes are
expected with time and more analysis. Thus, the reader is referred to
the VIMS Planetary Data System (PDS) archive for appropriate
calibrations to be used with flight data.
 
  VIMS Visual Channel
 
  The VIMS visual channel was constructed and calibrated in Italy, at
Officine Galileo (Firenze, Italy). The VIMS-V was has been calibrated in
two phase: 1) at the Officine Galileo (Firenze, Italy) premises, prior
to the integration with the infrared channel; 2) at JPL after the
integration on the remote sensing palette.  The activity carried out at
JPL was mainly devoted to geometric measurements; that is, co-alignment
of the two channels and measurement of the relative radiometric response.
Furthermore, the instrument spatial response (measurement of the image
quality through the instrument Modulation Transfer Function and Point
Spread Function) were evaluated as part of the Full Functional Tests
performed at Officine Galileo (Firenze, Italy) prior to the calibration
activity.
 
  VIMS-V was placed inside a vacuum chamber equipped with a thermally
stabilized radiator connected to the CCD and capable of keeping the CCD
at a temperature in the range -20/+40 deg C under a residual pressure of
lower than 10-4 mbar. The chamber has a window (TVC window) with
transparency better than 0.9 throughout the entire spectral range.
VIMS-V was mounted on two computer-controlled rotating tables for fine
positioning around azimuthal and elevation angles. Two lamps were used
to cover the full spectral range: a Xenon lamp for the range 0.3 - 0.4
microns, and a Tungsten lamp between 0.4 and 1.035 microns. The lamp
with its housing, which includes a condenser and a diffusing screen to
improve light uniformity, was positioned at the input slit of a
Jobin-Yvon HR640 monochromator capable of better than 0.05 nm resolution
(band width at half height) over the VIMS-V spectral range. The
monochromator output was then used to illuminate a slit, pinhole or test
targets (corresponding to a specific type of test) placed at the focus
of an off-axis collimator. The collimated beam was fed to the instrument
inside the vacuum chamber.  Unfortunately, the collimated beam has as
unknown spectral irradiance; thus, we had to devise a method to measure
it. This was achieved using a beam splitter, of known optical
properties, placed in the optical path at 45 deg C in front of the
chamber window. The reflected portion of the beam was collected by a
calibrated photodiode to monitor the irradiance output of the light
source set up. An additional calibrated photodiode was placed every 50
nm (or 50 monochrometor steps) directly in front of the collimator to
have direct calibration at the collimator aperture.
 
  With the available collimator only 1/6th of the full VIMS-V FOV could
be instantaneously illuminated, thus a time consuming procedure was
implemented to repeat a full spectral sweep (0.3 to 1.05 microns in 1 nm
steps) to cover the field of view of the instrument.  The radiometric
calibration of VIMS-V was as follows. The Unit Response of the
instrument is defined as the output in Digital Numbers when the
instrument entrance pupil is fed with a light beam of 1 W per square cm,
and this beam is collected entirely into a single spectel and into a
unit solid angle, for an integration time of 1 s. This quantity was
directly measured along with its dependence on wavelength. The spectral
calibration was performed in order to evaluate the spectrally weighted
center of each channel as well as the spectral width. The spectral width
of each Spectel is of 5 times 1.46 nm = 7.33 nm.  For a detailed
discussion on the calibration see Capaccioni et al. (1998).
 
  We note that the radiometric transfer function obtained at OG during
on ground calibration of VIMS-V when applied to the Moon and Venus
illuminated side is insufficient to remove instrumental effects.
Moreover two problems are apparent: a shift in wavelengths of about two
nominal pixels and an inadequate removal of instrumental effects,
particularly at short wavelengths. So we measured a new unit response
function using the Venus and Moon data in the following way.
 
  We use an Apollo 16 landing site telescopic reflectance spectrum
(McCord and Adams, 1973) on a bright area on the Moon surface. This
choice is supported by the fact that Apollo 16 landing site is on the
lunar highlands where the albedo is particularly high.
 
  GEOMETRIC CALIBRATION
 
  For VIMS, the primary data product is, for each resolved pixel of a
given target, the determination of both the pixel position and the full
spectrum from 0.35 to 5.2 microns. To build such spectral images, for
each picture element of any given 64 x 64 frame, the viewing direction
of each of its 352 contiguous spectral elements (spectels) must be
known. Thus, the prime goal of the geometric calibration of VIMS was to
determine the relative viewing directions of all 96 VIMS-V and 256
VIMS-IR spectels within the full VIMS Field of View (FOV), in a frame to
be referenced to the Cassini spacecraft.
 
  A complexity originates from the basic difference in the way the
spectral images are obtained by the two channels: VIMS-V operates in a
push-broom mode, acquiring an entire cross-track line simultaneously
spread over its spectral dimension (from 0.35 to 1.0 microns) along the
second dimension of its CCD detector. The second spatial dimension is
acquired either using the S/C drift or the scanning of the VIMS-V
telescope secondary mirror.  VIMS-IR uses only a linear array detector,
thus it acquires one pixel only spread over its spectral dimension (from
0.85 to 5.2 microns). The cross-track spatial dimension is acquired by
scanning the telescope secondary mirror (whiskbroom mode), while the
along track dimension is acquired (as for VIMS-V) using either
spacecraft drift or scanning the IR telescope's secondary mirror in two
dimensions. With two distinct scanning mechanisms, telescopes, and
spectrometers, the boresight alignment and the Instantaneous Fields Of
View (IFOV) within the full FOV are not identical by design, and in
principle, wavelength dependent. The geometric calibration is thus
intimately coupled to the determination of these spectral registration
effects.
 
  Due to the late delivery of VIMS-V, the ground geometric calibration
was performed in steps: the in-depth geometric calibration of VIMS-IR
was performed first, prior to the integration with VIMS-V, followed by
the geometric calibration of VIMS-V after its integration. After
integration, a large misalignment was observed, requiring a global
mechanical realignment of both the IR and V channels (out of the
calibration chamber), followed by a few final control measurements (back
to the calibration chamber) prior to integration with the Cassini
spacecraft.  Some in-flight calibrations were performed to assess the
actual geometrical characteristics of both channels, when the instrument
had reached its proper in-flight thermal regime, late during the cruise
towards Jupiter.
 
  During the ground calibration, VIMS was mounted on a fixed platform,
thermally controlled and under vacuum. A collimator and optical bench
assembly was constructed outside of the thermal-vacuum chamber, and
viewed through a large window. For the geometric calibration, we chose
to image with VIMS, two types of targets, both mounted on an X-Y stage
to allow coverage of the entire VIMS FOV. In the target projector plane,
one VIMS pixel (0.5 mrad) corresponded to ~ 1 mm. To cover the entire
VIMS FOV, the target was 64 mm in size, and the stage was moved by steps
of 0.1 mm (1/10 VIMS pixels). The first type of target consisted of
linear blades to measure potential spectral registration effects by
analyzing for each spectel the pixel response while the blade was moved
across the pixel. The other target placed in the projector focal plane
consisted of an opaque metallic target with a grid of sub-pixel sized
pinholes (0.1 mm in diameter) evenly spaced, and back-illuminated by a
tungsten lamp. The complete calibration data products are in the form of
tables, one for each spectral channel, giving the viewing direction of
each VIMS pixel. Below we summarize some of the main results.
 
  The IFOVs of both channels were very accurately measured. Averaged
over all wavelengths within a given channel, IFOVIR = 0.495 +/- 0.003
mrad, and IFOVVIS = 0.506 +/- 0.003 mrad. Although the differences look
small (~ 2 %), they result in a relative VIMS-VIS/VIMS-IR misalignment
over the entire 64-pixel FOV that is larger than one pixel, requiring a
thorough geometric re-sampling of all image cubes larger than 32 pixels.
Prior to launch, the last geometric measurement showed a boresight
alignment between VIMS-V and VIMS-IR of better than 0.3 pixels at all
wavelengths.  Images coincide independent of wavelength to within < 0.5
pixel in frames up to 12 x 12 pixels.
 
  The first measurements in flight were performed using both channels to
observe the Moon during the Cassini Earth-Moon fly-by (08/18/1999).
Those showed a boresight misalignment of VIMS-IR with respect to VIMS-V
(-1 pixels, +2 pixels). Because the VIMS-IR had not reached its nominal
thermal regime during the Earth-Moon flyby, it was concluded that at
least part of misalignment was the result of thermal gradients in the IR
channel that would lessen as the Cassini spacecraft moved farther from
the Sun and the IR channel cooled. A recent calibration using the
Pleiades cluster and the star Fomalhaut (late March, 2001) showed
boresight offsets of (-1,0) pixels. The Pleiades observation shows the
misalignment variation within the FOV, as illustrated in Figure 8
showing the various stars in the visual (blue pixels, averaged over the
first 30 VIS spectels) and the near IR (red pixels, averaged over the
first 40 spectels).
 
  The ground calibration yielded for most IR spectels, the VIMS FOV,
leading to spectral geometric 'distortion' maps. For images up to 32 x
32 pixels, all spectral images coincide to better than 1/3 pixel Larger
discrepancies appear in the bottom right and top left corners of the
frame, where spectral misalignments up to half a pixel are present. This
is illustrated in the Figure 9, scaled in mrad, for three IR wavelengths
(spectels 103, 150 and 206, at 0.98 microns, 1.75 and 2.68 microns, in
red, blue and green respectively), enlarging the four corners and the
center of the FOV geometric spectral responses.
 
  Finally, the spectral registration effects measured for the IR
spectels were demonstrated very low, as illustrated in the figure: the
huge sensitivity of the measurements allow detection of effects at a
scale smaller than 1/10 pixel. With this resolution, the larger effects
we see between contiguous spectels actually amount for 1/10 px, and in
fact result from atmospheric contributions during the calibration
(variation of H2O and CO2 features). The only large-scale effect present
(black curve) has a very low frequency (at the scale of the entire
spectral range), and likely results from optical aberrations within the
IR spectrometer. It is both smooth and small enough to minimize the risk
of misinterpreting potential large optical contrasts in the observed
scene in terms of false spectral signatures.
 
  SPECTRAL CALIBRATION
 
  The goals of the spectral calibration of VIMS were to measure the
spectral response of each VIMS spectral channel to determine the central
wavelength and spectral profile of each detector, and its spectral
stability as a function of temperature and spatial position within the
field of view of the instrument. To achieve this, the tests included: 1)
scanning a nearly monochromatic line (using a calibrated grating
monochrometer) over the VIMS wavelength range to map the spectral
profile of each VIMS detector, 2) transmission spectra of materials with
sharp absorption bands, and 3) measuring reflectance spectra of minerals
and other targets with VIMS.
 
  The monochrometer scans were useful for a single position in the full
VIMS field of view because the relatively large field of view of the
VIMS could not be covered with the narrow exit slit of the
monochrometer, and small shifts in wavelength were observed in the
monochrometer as a function of distance along the slit. This results
because a change in direction along the slit results in a slight change
in the field position in VIMS that corresponds to an angular movement.
Such changes require a change in the light path through the
monochrometer with a corresponding change in the effect output
wavelength of the monochrometer. Thus the monochrometer tests were done
on axis only.  The monochrometer was typically scanned at 1 nm
increments to map out the profile of each VIMS spectral bandpass.
 
  Calibrated transmission filters consisting of a mylar sheet displaying
sharp absorption bands in the 1-3.5 micron region, with broader features
at longer wavelengths, and Corning glass filters containing rare-earth
elements which give sharp absorption features in the visual and
near-infrared wavelength regions, and broader absorptions at longer
wavelengths were used to cover the full VIMS field of view. Because of
their uniformity and stability, the filters were used to determine the
stability of the VIMS wavelength response as a function of spatial
position, temperature, and time (because two tests were done over a
period of about 6 months).
 
  To measure VIMS response to real targets with spectral features, a set
of minerals and other materials were assembled into a spectral target
and measured in reflectance. Because the calibration geometry was
optimized for other tests, the setup for reflectance measurements was
not ideal, so these tests are more qualitative. The light source used to
illuminate the samples was set up at relatively large angles to the
normal to the surface of the highly scattering surface of the spectral
target, the exact viewing geometry is difficult to assess. Furthermore,
only vertical samples could be measured, so it was not possible to
measure the reflectance of unconstrained, loose particulate samples.
Measurements were made of rocks and solid samples that typically had
large grains, thus the absorption bands were deep and saturated, but the
spectra of these rocks are quite identifiable with the VIMS.
 
  The spectral calibration tests showed that VIMS is a remarkable
instrument, producing spectra comparable in quality to specialized
laboratory spectrometers. The large spectral range of the VIMS, ~0.2 to
5.1 microns includes the region of increasing thermal emission at room
temperature making the light reflected from the sample difficult to
separate from the background thermal emission. The spectral range of
VIMS is greater than the spectral output any single convenient
laboratory light source, so tests were often done multiple times with
different light sources.
 
  Spectral calibration of VIMS occurred in three separate steps. The
Visual channel was calibrated separately in Italy prior to integration
with the IR channel at JPL. The IR channel was calibrated in the thermal
vacuum tests at JPL January 28 to February 5, 1996. The integrated
instrument was further tested at the JPL thermal vacuum facility July
16-17, 1996. This final test was limited and only included filter
transmission and mineral target tests.
 
  The spectral calibration resulted in a specification of the wavelength
position and bandpass of each VIMS spectral channel across the
instrument field of view and as a function of temperature. The VIMS-IR
spectral response is identical across the full field of view to within
about a nanometer (nm) over the temperature range tested.  The VIMS-IR
sampling interval is about 16 nm in the IR, thus a 1-nm shift is a small
fraction is < 7% of the sampling interval. The VIMS-V has a sampling
interval of ~7 nm and tests show stability to better than about 0.3 nm.
 
  POLARIMETRIC CALIBRATION
 
  The VIMS instrument contains no specific polarimetric capability, such
as filters or grids, but the design of the grating spectrometer makes it
inevitable that the instrument's response will be linearly polarized to
some extent. The purpose of the polarimetric calibrations was to
characterize this sensitivity, so that its effect on the accuracy of
spectra obtained for both polarized and non-polarized targets in the
Saturn system can be assessed. In general, spacecraft pointing
constraints will determine the roll attitude of the ORS instruments
during targeted observations, leaving little opportunity for
observations at multiple roll orientations.
 
  Measurements for the polarization characterization of the VIMS IR
channel were carried out in the 10 ft thermal-vacuum tank in Bldg 144 at
JPL, during Jan 17-20, 1996.  A target projector was set up with a 26 mm
diameter IR linear polarizing filter at the focal plane of a collimator.
The target was illuminated by the 1-inch output aperture of an
integrating sphere, producing a polarized image of the exit aperture of
the sphere at the VIMS focal plane. The polarizer consisted of a ZnSe
substrate with a deposited aluminum wire grid, and its polarization
efficiency is documented from 2.5 microns to beyond 10 microns.  The
average single-polarizer throughput is 38%, while the maximum
cross-polarized throughput over the 2.5- to 5.0 microns range is 1.5%.
No data on the filter transmission were available below 2.5 microns. A
calibrated tungsten source with a Teflon-coated sphere provided adequate
SNR out to about 2.5 microns, while a glowbar source with a gold
integrating sphere provided adequate SNR at all wavelengths beyond 1.5
midrons.
 
  Measurements were made at 5 spatial positions of the source in the
target plane, on boresight and near the 4 corners of the VIMS field. For
each source position, measurements were made at 7 settings of the
polarizer, at 30 degs intervals between +90 degs and -90 degs, followed
by a sequence of background measurements with the shutter on the light
source closed.  Only the VIMS IR channel was available for these
measurements.  Three cubes per measurement were co-added and
background-subtraction spectra were extracted both for a central spot in
the image of the source and for a larger region which included the full
output aperture of the sphere.  This was accomplished at each
orientation of the polarizer and for each source position.
 
  SOLAR PORT CALIBRATION
 
  The Solar Calibration Port (henceforth cal port) was installed within
the VIMS IR telescope in order to permit the instrument to obtain a
strongly attenuated spectrum of the sun during the Cassini mission,
which would in turn facilitate reduction of VIMS spectra to an accurate
scale of relative reflectance. The cal port is pointed at an angle
offset by 20 degrees from the instrument boresight towards the -Z
direction, aligned with the UVIS solar occultation port. Attenuation of
the incident solar beam by a factor of approx. 2.5 x 10-7 is achieved by
(i) the small aperture of the cal port, compared to the main beam and
(ii) a series of one 70 degs and five 90 degs reflections from
right-angle prisms made of ZnSe. Most of the incident flux is returned
out of the entrance aperture by internal reflection in the prisms. The
beam exiting the cal port is focussed by the IR telescope optics onto
the VIMS-IR entrance slit, and then enters the spectrometer in the
normal way. But because the cal port aperture samples only a portion
(~0.3%) of the full instrument aperture, the collimated beam illuminates
only a small part of the diffraction grating. The optical design ensures
that this region overlaps the short- and medium-wavelength blaze regions
on the grating, in the ratio 1:3. The solar port does not illuminate the
long-wavelength blaze.
 
  The predicted throughput of the stack of prisms varies smoothly from
1.35 x 10-4 at 0.85 microns to 1.09 x 10-4 at 3.0 microns and 1.04 x
10-4 at 5.0 microns, for radiation linearly polarized in a plane
perpendicular to the plane containing the incident and exit beams and to
the rulings on the VIMS diffraction grating. The transmission of the
orthogonal polarization is less than 1.0 x 10-7.  The output spectrum of
a target seen through the cal port differs from that produced by the
same source seen on the instrument boresight due to a combination of
polarization and partial illumination of the grating blazes. The purpose
of the solar cal port calibrations is to establish the ratio of the
spectrum of an unpolarized broadband source as seen through the cal port
to that of the same source on the instrument boresight.
 
  The simulated solar source used for the calibration runs was a
high-power xenon lamp, illuminating a large, white, teflon-coated
integrating sphere.  The output of the sphere illuminated a 1 mrad
diameter circular aperture in the focal plane of the calibration
projector (equal to the angular size of the sun at 9 AU), after a 90
degs reflection from an aluminum plate. One side of this plate was
polished and oriented for specular reflection of the high-intensity beam
onto the target for the cal port runs, while the other was sand-blasted
to provide diffuse reflected illumination of the target for the
boresight runs.
 
  All measurements were made on July 12, 1996, in the 10 ft
thermal-vacuum chamber at JPL. Inside the tank, a deployable
periscope-like arrangement with two aluminum mirrors was used to
redirect the input beam into the cal port's entrance aperture. The input
signal to VIMS thus experienced identical atmospheric paths, with the
same number of reflections, for both cal port and boresight runs. Only
the IR channel was available for these runs; the VIS channel was
calibrated separately at Officine Galileo (Firenze, Italy). For each
observation multiple 8 x 8 image cubes were taken, centered manually
on the image of the target.
 
  A total of 100 separate solar port image cubes were background
subtracted and averaged in sets of 10, and all pixels co-added to
produce spectra.  Twenty boresight cubes were processed in identical
fashion. Figure 10 shows the average boresight and solar port spectra,
at the DN levels originally recorded. The resulting ratio spectrum is
displayed in Fig. 15, normalized to an average value of unity. Data for
9 channels at the three filter segment boundaries have been interpolated
in both plots.
 
  The ratio spectrum shows that the cal port sensitivity is relatively
low shortward of IR channel 50 (1.7 microns), increases rapidly between
channels 50 and 70 to a peak at channel 80 (2.2 microns), and then
declines smoothly at longer wavelengths. Oscillations near 2.7 and 4.3
microns are due to imperfect cancellation of CO2 absorption features in
the raw spectra. The high-frequency structure beyond of 4.0 microns is
an artifact of the array readout.
 
  The decline in sensitivity of the cal port relative to the main
aperture at longer wavelengths is attributable to the lack of
illumination of the long-wavelength grating blaze, and to the increasing
polarization sensitivity of the IR channel beyond 3 microns (see Sec
7.1.5). The steep drop shortward of 2 microns is, on the other hand,
unexplained. Neither the ZnSe prisms nor the several aluminum
reflections seem to be capable of causing this effect.  Additional
experiments showed no indication of a misalignment in the projector
illumination pattern. Previous calibration runs on June 26, 1996, which
did not use the external Al plate, did not achieve sufficient SNR at the
longest wavelengths. Nevertheless, these earlier results are not
consistent with the final runs at short wavelengths, for reasons that
are presently unknown. Thus, the solar port ratio spectrum in Fig. 15
must be considered provisional, and subject to revision on the basis of
in-flight experience.
 
  Viewed through the IR solar cal port, images of a circular target are
noticeably elongated. FWHM dimensions are ~2.0 pixels in X, but increase
steadily from 2.8 pixels in the Z direction at 1 microns to 4.1 pixels
at 5 microns. This may be compared with FWHM sizes for the boresight
images of 1.5 x 2.2 pixels for the same target. The elongation of the
solar port images is due to diffraction at the elongated rectangular
aperture of the cal port (30 mm x 5 mm). Image centroids are fairly
stable, varying in X by at most 0.3 pixels and in Z by at most 0.2
pixels. Because of the variable size and slightly wavelength-dependent
position of the solar image, it is recommended that solar cal port
images be co-added over at least an 8 x 8 pixel region in order to
obtain a stable, well-defined spectrum. No precise information is
available from the ground calibrations on the absolute pointing of the
solar cal port, but this is believed to be within 0.5 degrees (17
pixels) of nominal and will be readily verified with in-flight
observations of the sun.

        