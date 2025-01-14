
 
    Instrument Host Overview
    ========================
      For most Magellan experiments, data were collected by
      instruments on the spacecraft.  Those data were then relayed
      via the telemetry system to stations of the NASA Deep Space
      Network (DSN) on the ground.  Radio Science experiments (such
      as radio occultations) required that DSN hardware also
      participate in data acquisition.  The following sections
      provide an overview first of the spacecraft and then of the
      DSN ground system as both supported Magellan science
      activities.
 
 
    Instrument Host Overview - Spacecraft
    =====================================
      The Magellan spacecraft was built by the Martin Marietta
      Corporation.  The spacecraft structure included four major
      sections: High-Gain Antenna (HGA), Forward Equipment Module
      (FEM), Spacecraft Bus (including the solar array), and the Orbit
      Insertion Stage.  Spacecraft subsystems included those for
      thermal control, power, attitude control, propulsion, command
      data and data storage, and telecommunications.
 
      Design of the Magellan spacecraft was driven by the need for a
      low-cost, high-performance vehicle.  Protoflight units that had
      been built for preflight tests or were spares from the Voyager
      spacecraft were available from storage at no cost.  These
      included the 3.7 meter diameter high-gain antenna (HGA), the
      spacecraft bus, propulsion system components, thermal control
      louvers, and much of the radio subsystem.  The stockpile of
      flight spares for the Galileo spacecraft provided Magellan's
      command and data system, tape recorders, attitude control
      processor, power subsystem and propulsion components.  Further
      elements were drawn from other projects and from NASA standard
      designs.  Only about 30% (by mass) of the Magellan spacecraft --
      primarily the radar electronics and the solar panels -- was
      especially designed for the mission.
 
      The high-gain antenna (HGA) was used as the antenna for the
      synthetic aperture radar (SAR) and as the primary antenna for
      the telecommunications system.  The HGA boresight was defined to
      be the +Z axis for the spacecraft-fixed coordinate system.
 
      The spacecraft bus was a ten sided structure containing the star
      scanner, medium-gain antenna (MGA), rocket engine modules
      (REMs), command data and data storage (CDDS) subsystem, attitude
      control monopropellant tank, and a nitrogen tank for providing
      propellant pressurization.  The solar panel array was attached
      to the bus; its rotation axis defined the +X axis for the
      spacecraft-fixed coordinate system.  The +Y axis of the
      coordinate system was in the nominal direction of the star
      scanner boresight, forming a right-hand coordinate system.
 
      The radar electronics, the reaction wheels, and various other
      spacecraft subsystem components were contained within the
      Forward Equipment Module, located between the bus and HGA.
 
      The orbit insertion stage contained a STAR-48 solid rocket motor
      (SRM) that was used to provide the impulse required to perform
      the Venus Orbit Insertion (VOI) maneuver.
 
      Thermal control of the spacecraft was accomplished by a
      combination of louvers, thermal blankets, passive coatings, and
      heat dissipating elements.  The nominal operating temperature
      for the spacecraft components was between -5 and +40 degrees
      Celsius.  The thermal control subsystem maintained these
      components at the appropriate temperatures for all orientations
      of the spacecraft orbit and sun-line and for all spacecraft
      operating modes.  Electrical power was supplied by two large
      solar panels with a total area of 12.6 square meters.  This
      array was capable of producing a minimum power of 1029 W at the
      end of the nominal mission; it could rotate about its axis to
      allow tracking of the Sun despite the changing
      Earth-Sun-spacecraft geometry during the mission.  A dedicated
      sun sensor optimized power production.  Bus voltage regulation
      was controlled by the power control unit (PCU) with a shunt
      regulator for diverting excess power from the solar arrays to
      maintain power as raw power (28-35 v), regulated power at 28 vDC
      +/-0.56 vDC, and as AC at 2.4 kHz through an inverter.  Two 30
      amp-hour, 26-cell nickel cadmium batteries provided power during
      times of solar occultation and allowed normal spacecraft
      operations independent of real-time solar illumination.  These
      batteries were sized to allow a degraded mission in the event
      that one of them failed.
 
      The attitude of the Magellan spacecraft was controlled through
      the use of reaction wheels, with monopropellant rocket motors
      being used to desaturate the reaction wheels periodically.
      During both the interplanetary cruise and the orbital portions
      of the mission, attitude reference was provided by an inertial
      reference unit (IRU), updated each orbit using celestial
      references.  During the mapping part of each orbit, the
      spacecraft was initially oriented with the HGA pointing down
      toward Venus, with the exact attitude being a function of the
      spacecraft altitude and the SAR mapping objectives.  During the
      downlink transmission part of the orbit, the spacecraft was
      oriented with the HGA slightly off the Earth-line.  The low gain
      antenna (LGA) was mounted coaxially with the HGA and did not
      require pointing since it had an omnidirectional beam pattern.
      The altimeter horn (ALTA) was mounted so that a portion of the
      fan-shaped beam nominally pointed in the nadir direction during
      the mapping part of an orbit.
 
      The Magellan propulsion subsystem consisted of two parts.  The
      first, a Star 48 SRM, provided the impulse for VOI.  Following
      that maneuver, the empty casing and parts of its support
      structure were ejected from the spacecraft.  The second part
      consisted of monopropellant hydrazine thrusters that were used
      for trajectory correction maneuvers (TCMs) during inter-
      planetary cruise, thrust vector control (TVC) during VOI, orbit
      trim maneuvers during the mapping mission, and attitude control
      when the reaction wheels were being desaturated.  The rocket
      motors were clustered in modules located on the end of outrigger
      booms in order to increase their moment arms and thus decrease
      attitude control propellant requirements.
 
      Twelve 0.9-N (Newton) and four 22-N rocket motors were used for
      attitude control, with thrust being provided by eight 445-N
      rocket motors or by the 0.9-N motors for small TCMs.  All
      engines pointed in the -Z direction, with the exception of the
      roll motors.
 
      The 0.9-N motors were used for tip-off control following
      separation of the inertial upper stage (IUS), reaction wheel
      desaturation, roll control for all times other than VOI, to back
      up any failed reaction wheels, and for small TCMs or orbit trim
      maneuvers (OTMs).  The 22-N motors were used for roll control
      during VOI.  The 445-N motors were used for controlling the
      spacecraft rotational axis during VOI, and to provide impulses
      during all propulsive maneuvers.  The monopropellant motors also
      provided the impulses needed to trim the VOI maneuver.
 
      The command, data and data storage (CDDS) system received uplink
      commands via the radio frequency subsystem (RFS) and controlled
      the spacecraft in response to those commands.  It also
      controlled the acquisition and storage of scientific data and
      sending that data, along with supplemental engineering data, to
      the RFS for downlink transmission to Earth.  The commands were
      sent to the spacecraft as time-event pairs for storage and later
      execution, and also in the form of blocks which the CDDS later
      expanded into spacecraft executable commands.  In the Venus
      orbit phase, commands for up to three days of radar operation
      were stored.  There was also a provision for receiving and
      executing discrete commands sent from the ground.  SAR data were
      stored on two multi-track digital tape records (DTRs) for later
      playback over the high-rate X-band link; there was no provision
      for real-time transmission of the SAR data.  Data storage
      capacity of the two DTRs was approximately 1.8 billion bits.
      Engineering data were normally transmitted to Earth over a
      real-time S-band link.  During those times when a real-time link
      was not possible, the engineering data were recorded on a DTR
      and played back via the X-band high-rate link with the SAR data.
      The recorded data stream was alternately switched between the
      two DTRs so that the data would not be lost during the DTR track
      change.
 
      The Magellan telecommunications subsystem contained all the
      hardware necessary to maintain communications between Earth and
      the spacecraft.  The subsystem contained the radio frequency
      subsystem, the LGA, MGA, and HGA.  The RFS performed the
      functions of carrier transponding, command detection and
      decoding, and telemetry modulation.  The spacecraft was capable
      of simultaneous X-band and S-band uplink and downlink
      operations.  The S-band operated at a transmitter power of 5 W,
      while the X-band operated at a power of 22 W.  Uplink data rates
      were 31.25 and 62.5 bps (bits per second) with downlink data
      rates of 40 bps (emergency only), 1200 bps (real-time
      engineering rate), 115.2 kbps (kilobits per second) (radar
      downlink backup), and 268.8 kbps (nominal).
 
      For more information on the Magellan spacecraft see the papers
      by [SAUNDERSETAL1990] and [SAUNDERSETAL1992].
 
 
    Instrument Host Overview - DSN
    ==============================
      The Deep Space Network is a telecommunications facility managed
      by the Jet Propulsion Laboratory of the California Institute of
      Technology for the U.S.  National Aeronautics and Space
      Administration.
 
      The primary function of the DSN is to provide two-way
      communications between the Earth and spacecraft exploring the
      solar system.  To carry out this function it is equipped with
      high-power transmitters, low-noise amplifiers and receivers, and
      appropriate monitoring and control systems.
 
      The DSN consists of three complexes situated at approximately
      equally spaced longitudinal intervals around the globe at
      Goldstone (near Barstow, California), Robledo (near Madrid,
      Spain), and Tidbinbilla (near Canberra, Australia).  Two of the
      complexes are located in the northern hemisphere while the third
      is in the southern hemisphere.
 
      The network comprises four subnets, each of which includes one
      antenna at each complex.  The four subnets are defined according
      to the properties of their respective antennas: 70-m diameter,
      standard 34-m diameter, high-efficiency 34-m diameter, and 26-m
      diameter.
 
      These DSN complexes, in conjunction with telecommunications
      subsystems onboard planetary spacecraft, constitute the major
      elements of instrumentation for radio science investigations.
 
      For more information see [ASMAR&RENZETTI1993].

        