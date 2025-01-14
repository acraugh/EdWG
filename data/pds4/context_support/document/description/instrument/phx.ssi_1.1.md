
 
  Instrument Overview
  ===================
    The Surface Stereo Imager (SSI) was designed for a resolution of
    <1 mrad/pixel, equivalent to the Viking cameras (color: 2.1 mrad/
    pixel, monochrome high-resolution: 0.7 mrad/pixel). The focal
    plane array (FPA), supplied by the Max Planck Institute for
    Aeronomy (MPAe), has heritage from the Imager for Mars Pathfinder
    (IMP) and the descent imager (DISR) on the Huygens probe. There
    there are two identical 256 x 256 pixel arrays, normally subframed
    to 248 x 256 for each eye; each field of view (FOV) is 13.88 x
    14.38. Since the SSI is a copy of IMP, it maintains the same eye
    separation of 15.0 cm, and the light path is folded by two sets of
    mirrors to bring the light to the FPA. Prior to compression, a
    single-eye SSI frame contains 248 x 256 x 12 bits, or 762 kb.
    Downlinking the data 'raw' (uncompressed) requires putting the
    12-bit data into 16-bit words by adding 4 flag-bits, resulting in
    an effective compression ratio of 0.75:1 and a 1.00 Mb image. Both
    the lossy (JPEG) and lossless (Rice) compressors efficiently
    discard these extra bits, and compression ratios refer to the
    original 12-bit/pixel image (e.g., a 762-kb full frame compressed
    at 6:1 requires 127 kb of downlink). About 100 frames are combined
    into a monochromic panorama, which brings the data volume to 76 Mb;
    instrument and packet headers add another 5% for a total of 80 Mb.
    A typical day on Mars allows the return of 30 Mb of SSI data.
    Therefore compression is an indispensable tool for the early
    mission. A 6:1 compressed panorama has few artifacts, compresses
    to 13 Mb, and is easily returned during a single sol.
 
    Information in this instrument description is taken from The MVACS
    Surface Stereo Imager on Mars Polar Lander for the Journal of
    Geophysical Research [SMITHETAL2001]. See this paper for more
    details.
 
 
  Scientific Objectives
  =====================
    The scientific goals for SSI fall into five general areas: atmospheric
    studies, topographic mapping using stereoscopic views, multispectral
    imaging normalized to a target of known reflectance, true color
    mosaics and studying the magnetic properties of airborne dust. The
    scientific objectives for SSI fall into several broad categories:
    geomorphology, mineralogy, and atmospheric studies.
    Geomorphology, as always, is governed by the choice of landing
    site. The polar layered terrain affords the rare opportunity
    to learn the stratigraphic history of this circumpolar geologic
    unit. Local landforms are likely to show fine-scale layering that
    is likely to have been depositional in origin, but later modified
    by strong winds. Unlike the Viking Landers 1 and 2 and Pathfinder
    sites, few, if any, rocks are expected. Defining the role of
    ices in the formation of the layers is a prime goal for SSI. To
    aid in the study of the layers, the camera's multispectral imaging
    mode will be used. Subtle color differences between layers
    may indicate a different ice fraction, changes in particle size, or
    composition changes. In addition to the stratigraphy we will look at
    local features to determine the topography and geology of the landing
    site, its photometric characteristics, and its homogeneity over a
    wide range of spatial scales. The SSI will also search for long
    timescale variations produced by atmospheric effects, for instance,
    aeolian modification of dune structures. In addition, it will
    observe effects resulting from the landing of the spacecraft and
    operations of the robotic arm
 
 
  Calibration
  ===========
    The improved Sweep magnet experiment (iSweep) an improved version
    of the Sweep magnet experiments flown onboard the two Mars
    Exploration Rovers (MERs) Spirit and Opportunity. The Sweep magnet
    is ring shaped and is designed to allow only non-magnetic particles
    to enter a small circular area at the center of the surface of this
    structure. The iSweeps will be used as radiometric calibration
    targets for the cameras on Phoenix, including SSI. The iSweeps will
    provide a presumably constant radiometric color reference for
    calibration of images from the landing site [LEERETAL2008].
 
    The SSI has been characterized and calibrated with respect to
    absolute responsivity, spectral response, image quality, flat
    fielding, stray light, and pointing accuracy. Possible changes in
    the SSI spatial response pattern, particularly due to dust on the
    entrance windows, require subsequent calibration from images of the
    Martian sky. There are a number of error sources that combine to
    reduce the absolute calibration accuracy of the instrument. The
    major inaccuracies are lamp drift from its calibration radiance,
    distance errors from the lamp to the spectralon, improperly
    corrected stray light, and temperature mismeasurement. SSI images
    will be calibrated by a combination of flight software (FSW) aboard
    the spacecraft and ground software (GSW) after the data have been
    downlinked.
 
 
  Operational Considerations
  ==========================
    The dust signature must be taken into account when interpreting
    calibration relative to the targets, especially later in the
    mission as dust accumulation becomes significant. For water vapor
    measurements, special care has been taken to control the temperature
    of the detector (heated to T = -20 degC) during these observations to
    reduce variations due to changes in the relative response near the
    long wavelength end of the silicon CCD response.
 
 
  Detectors
  =========
    The decision to include stereo plus the requirement for low mass led
    to a split of a single detector into left and right image areas and
    the avoidance of the extra complexity of two separate focal planes.
    Therefore there are two identical 256 x 256 pixel arrays, normally
    subframed to 248 x 256 for each eye.
 
 
  Electronics
  ===========
    There are two electronic boards housed in the Payload Electronics
    Box (PEB), where their environment is temperature controlled. The
    two boards mount to opposite sides of a thermal plate of aluminum
    that acts as a heat sink and support bracket. The detector cables
    from both the SSI and the RAC cameras connect to the CCD Readout
    Board (CRB) and the motor and auxiliary readouts connect to the
    Frame Buffer Board (FBB). The FBB interfaces to the spacecraft
    through its Payload and Attitude Control Interface (PACI) board
    with a 1-MHz serial link controlled by a Field Programmable Gate
    Array functioning as a state machine for command decoding.
 
    The camera system is controlled through a sequence of uplinked
    commands that are time tagged and stored in spacecraft RAM. The
    image command includes many optional parameters that control the
    exposure and processing. Everything from the exposure time to the
    amount and type of data compression is specified here and attached
    to the data set to be placed in the header. Subframing boundaries
    and pixel-averaging parameters can also be specified. After
    processing, the packetized images are stored in the telemetry buffer.
 
 
  Filters
  =======
    Each eye has 12 selectable filters between 440 and 1000 nm.
    Eight low-transmission filters are included for imaging the Sun
    directly at multiple wavelengths to give SSI the ability to measure
    dust opacity and potentially the water vapor content. Images of the
    Sun through low-transmission, narrowband filters will be converted
    to optical depth measurements. Filters near the 935-nm water band
    allow us to constrain water vapor concentration. Sky brightness
    scans reveal the scattering phase function of the aerosols, which
    can in turn be analyzed to provide the size distribution, index of
    refraction, and shapes of the aerosols.
 
 
  Optics
  ======
    The f/18 optics have a large depth of field, and no focusing
    mechanism is required; a mechanical shutter is avoided by using
    the frame transfer capability of the 528 x 512 CCD.
 
  Location
  ========
    For ground-based data, coordinates of the observatory
 
 
  Operational Modes
  =================
    Defining the role of ices in the formation of the layers is a
    prime goal for SSI. To aid in the study of the layers, the
    camera's multispectral imaging mode will be used. Subtle color
    differences between layers may indicate a different ice fraction,
    changes in particle size, or composition changes.
 
 
  Subsystems
  ==========
    Images taken of the lander deck and solar panels will be valuable
    as troubleshooting guides when performance of various subsystems
    degrades.
 
 
  Measured Parameters
  ===================
    The camera system is controlled through a sequence of uplinked
    commands that are time tagged and stored in spacecraft RAM. The
    image command includes many optional parameters that control the
    exposure and processing. Everything from the exposure time to the
    amount and type of data compression is specified here and attached
    to the data set to be placed in the header. Subframing boundaries
    and pixel-averaging parameters can also be specified.
 
    The color capability of the SSI will be used to take panoramic
    images in the search for evidence of aeolian sorting on the surface.
    The fundamental SSI camera product is a stereo image pair (or an
    'image cube' of pairs obtained with the same geometry but with
    different filters). By design, such a pair can be viewed directly
    to give a three-dimensional impression of a portion of the SSI
    landing site. In addition, quantitative photogrammetric processing
    is planned that will lead to several useful derived data products.
 
    SSI can acquire multispectral image cubes consisting of up to 12
    wavelengths, using the geology filters.T he band centers of the
    filters are clustered to optimize discrimination of the two most
    important mineral groups detectable by SSI. The first objective is
    to identify the crystalline ferric oxides, oxyhydroxides, and the
    poorly crystalline or nanophase ferric oxides.
 
    Views of the solar disk through narrowband, low transmission
    filters and of the sky through the regular filters give us a wealth
    of information concerning haze and cloud properties.

        