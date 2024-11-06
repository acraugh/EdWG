
 
 
  Instrument Overview
  ===================
 
    The Mars Science Laboratory (MSL) rover carries 4 Navigation Cameras
    (Navcams). Two Navcam stereo pairs (one as a redundant backup) are
    mounted on the Remote Sensing Mast just below ChemCam. The base of
    the vertical Remote Sensing Mast is located near the front starboard
    corner of the rover. The upper Navcam pair has a boresight 1.99 m
    above the base of the rover wheels and the lower pair's
    corresponding height is 1.94 m, which are just above and below the
    Mastcam boresight of 1.97 m height. The redundant cameras are
    connected to the backup rover computer and are not expected to be
    used unless there is a problem with the primary rover computer
    and/or primary cameras. Each Navcam pair is separated by a 42.4 cm
    stereo baseline.  The primary use of the Navcams is to provide
    terrain context for mobility planning, and they also support science
    operations for selecting near field targets and robotic arm
    operations.
 
    Each Navcam consists of a detector head and an electronics box. The
    detector head houses an optical lens assembly and a Charge Coupled
    Device detector (CCD). The electronics box contains the CCD driver
    electronics, the 12-bit Analog to Digital Converter (ADC),
    camera/rover interface electronics, and a heater resistor that will
    keep the box above the minimum operating temperature of 218 K. The
    Navcams use a broadband visible filter and produce 1024 x 1024 pixel
    images.
 
    Each camera weighs 220 grams and uses approximately 2.2 Watts of power
    when the heater is not on. The MSL Navcam design is identical in design
    to the Navcams on the Mars Exploration Rovers, which are described in
    [MAKIETAL2003], with the exception of a more powerful 3.5 W heater on
    each MSL Navcam.
 
 
  Instrument Objectives
  =====================
 
    The chief objectives of the Navcams are:
 
    1) to support the operation of the rover on the surface of Mars by
    acquiring images of the terrain and landscape,
 
    2) to acquire images for support of auto-navigation, robotic arm
    operations, mobility planning (wheel sinkage and obstruction), and
    pointing of the ChemCam and Mastcam,
 
    3) to investigate the landing sites at cm/pixel resolution,
 
    4) to acquire images of the morphology of rocks and soil in order to
    provide clues about past geologic processes,
 
    5) to measure the distribution of rocks and soil around the rover as
    it moves from site to site,
 
    6) to calibrate and validate orbital remote sensing data, and
 
    7) to place rock and soil types encountered by the rover in a
    geological context.
 
 
  Calibration
  ===========
 
    The Navcams have been calibrated over the flight range of
    temperatures. They were all calibrated with respect to geometric
    flat field response, detector dark current, camera absolute
    responsivity, detector noise performance, and detector gain.
 
 
  Detectors
  =========
 
    Each Navcam uses a 1024 x 2048 pixel CCD with 12 micron-square
    pixels and a 100% optical fill factor. The CCDs operate in frame-
    transfer mode, dividing the detector into two regions. One of the
    regions is a 1204 x 1204 pixel photosensitive imaging region where
    the image is recorded. The other region is a 1204 x 1204 shielded
    storage region where the recorded image is shifted and stored during
    detector readout. It takes 5.1 msec to transfer data from the
    imaging region to the storage region, and 5.4 seconds for readout of
    data from the storage region. Each CCD includes 32 non-imaging
    pixels in the serial readout registers, which allow the monitoring
    of the CCD electronics offset and detector noise performance. The
    Navcam CCD pixels have full well capacities of approximately 170,000
    electrons and are digitized at 12 bits/ pixel. The RMS read noise
    at cold temperatures (-55 degrees C) is approximately 20 electrons,
    and the detector system has gain values of approximately 50 e-/DN,
    which results in a system with approximately 0.5 DN of RMS read
    noise.
 
    The absolute quantum efficiency (QE) of the CCDs has been measured
    between 400 and 1000 nm at four operating temperatures ranging from
    218 K and 278 K. The QE of the MSL CCDs is typical of a silicon CCD
    detector, with sensitivity peaking at 700 nm with a QE value of
    approximately 43%. The SNR of the detector system is essentially
    Poisson-limited because of its low readout noise and small dark
    current rates in the Martian operating envirionments.
 
 
  Electronics
  ===========
 
    The Navcam CCDs use a 'clocked antiblooming' readout technique,
    instead of having anti-blooming circuitry. The proper choice of
    autoexposure parameters prevent the blooming effect.
 
    The Navcams also have the capability for onboard image processing.
    The Navcams can do pixel summation in which they sum the rows and
    columns of an image, returning the results in a one-dimensional
    array of 32-bit integers whose length is the image height. These
    are very useful when the spatial content of an image has relatively
    low scene entropy and the emphasis is on the radiometry. The flight
    software (FSW) can also calculate and return the histogram of an
    image, which can be useful for atmospheric observations. Navcam
    images can be spatially downsampled to a user-specified image size
    using one of a few techniques; nearest neighbor computation of the
    mean, computation of the mean with outlier rejection, and median
    averaging. The FSW also allows the option to downlink a subframed
    region of an image so full resolution can be downlinked at a lower
    data volume. The FSW is also capable of lossy and lossless
    compression of MSL images. The rovers use a ICER wavelet image
    compressor for the lossy compression, and low complexity (LOCO) for
    lossless compression.
 
 
  Filters
  =======
 
    The Navcams use a combination of three filters (Schott OG590,
    KG5, and ND1.3) to create a red bandpass filter centered at
    650 nm and a FWHM of approximately 140 nm.
 
 
  Optics
  ======
 
    The Navcams have f/12 cameras with a 14.67 nm focal length. The
    Navcam optics are f-theta fisheye lenses with 45 degree x 45 degree
    horizontal/vertical field of view and a 67 degree diagonal field
    of view. They have an angular resolution at the center of the
    picture of 0.82 milliradians/ pixel. The field depth of the Navcams
    ranges from 0.5 m to infinity. The nominal exposure time for a
    noontime image on Mars is approximately 0.25 seconds. This time is
    50 times the frame transfer time of 5.1 ms. This ensures that the
    image signal is significantly than the image smear acquired during
    the frame transfer. The spectral range of the Navcams is 600-800
    nm.
 
 
  Location
  ========
 
    The Navcams are attached to metal brackets mounted on Remote Sensing
    Mast, just above and below the Mastcam cameras, at a wider stereo-
    pair separation than the Mastcam cameras.

        