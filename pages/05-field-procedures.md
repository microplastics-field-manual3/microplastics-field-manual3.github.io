---
layout: home
permalink: /field-procedures
title: "Field Procedures"
excerpt: "<br>"
image:
  feature: /FK200308-SuBastianRecoveryTwilight-20200316-Ingle-5814.jpg
layout: home

---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

Many of the steps in this section are designed for smaller class ROVs and are to be managed by researchers or general marine technicians. Work-class ROVs will have their own deployment protocols based on the technical capabilities and logistic requirements for the particular ROV and associated professional  team, and these may supersede the specific steps below.


## Onboard sample acquisition


### <span style="text-decoration:underline;">Complete an on-site briefing.</span>

Prior to deployment, a deployment briefing should always be completed to ensure the operation can be completed safely. Always take a precautionary approach to risks associated with vehicle deployment. See Chapter 1 for further information about risk assessments.


### <span style="text-decoration:underline;">Set up and test the ROV system. </span>

Allow sufficient time during survey mobilisation to undertake system checks, calibrations and testing of equipment and account for unforeseen problems; in most cases it will be possible to complete all system setup and tests within half a day. The conduct of pre-start checks should be noted in the trip log and any test failures specifically recorded for later-reference. Detailed settings for each component should be made using relevant operations manuals (e.g. USBL operations manual etc.).


#### Acoustic tracking setup



*   Set position of GPS receiver. _Differential GPS is mandatory for repeat site monitoring._
*   Measure offsets of USBL transceiver head to GPS receiver and put offsets into navigation systems.
*   Deploy USBL transceiver (e.g. pole or vessel mounted).
*   USBL calibration dockside is a good idea as well to verify that range and bearing (and depth if estimated by USBL) are within expected tolerances. Understanding the selection and recording of filtering/smoothing settings of the USBL system should also be noted.


#### On-deck tests should include, but not limited to, the following checks:



*   on-board data storage
*   on-board power (if fitted)
*   cameras 
*   tether management system (including assessing for nicks in tether)
*   strobe lighting 
*   thrusters (assessing for fouling and operation)
*   Manipulator arm(s) and sample container(s) (if fitted)
*   all blanking plugs are installed
*   crane and associated shackles are working order
*   check all seals/o-rings and blanking plugs are good working order
*   check all surface communications


#### Wet testing should include checks of the following:



*   Thrusters (including all directions)
*   USBL and internal navigation (e.g. compass and avoidance sonar)
*   cameras and strobes
*   avoidance/scanning sonar (if fitted)
*   through-water communications


### <span style="text-decoration:underline;">Conduct ROV transects</span>


#### Pre-deployment



*   Transects should only be undertaken in areas where the substratum is known, preferably in the form of multibeam mapping, so as to avoid entrapment and potential loss of ROV. <span style="text-decoration:underline;">Do not deploy blind</span>, as this increases the risk of equipment loss and damage, as well as unnecessary impact on potentially vulnerable ecosystems.
*   Once final transect locations have been determined, provide the locations of the transects (usually in ESRI shapefile format or start and end waypoints) and associated multibeam maps (in geotif format) to the ROV crew responsible for piloting missions. Cross-check the uploaded transect corresponds to the correct area on the geotif (i.e. ensure the geographic coordinates are defined for all spatial data).
*   Discuss the desired target location and the feasibility of deploying at that location. Main items to take into account are:
    *   Terrain. To minimise the risk of a deployment in highly rugose seafloor (e.g. walls) it is recommended that transects should be conducted up or along walls. Also consider the water visibility. If there are any large ridges, boulders, drop-offs, etc. along the proposed transect with minimal forward vision (&lt; 10 m) there may not be a large margin for avoidance.
    *   Currents/weather/sea state. During the transect, the USBL display will show the boat and ROV position, allowing the skipper and ROV pilot to discuss tracks and adjust speed if required. This can limit the manoeuvrability of the ship and depending on the direction of the prevailing wind and sea, is not always possible on a particular heading. As the sea-state and swell can affect the ships manoeuvrability when travelling at low speeds it is essential to regularly check the weather forecast to ensure the sea state is acceptable and the platform can be safely deployed and retrieved.
    *   Depth. Be aware of the depth limitations of the ROV and the length of the tether.
    *   Entanglement procedure. Discuss potential entanglement procedure (detailed below) making sure each person is familiar with their role.
*   Prepare for ROV launch and recovery on deck and ensure only essential personnel participate in its preparation and deployment.
*   Place USBL transceiver in water and ensure functionality.
*   Ensure tether is connected, turn on ROV and run all surface checks of the ROV as per manufacturer's requirements. 
*   Check camera settings (if external cameras are being used).
*   Check data sheet is ready (note site, camera numbers and memory card numbers).
*   Turn external cameras on, check there is battery and storage space available.
*   Insert cameras into housings, check that the housing is dry and that there is no sand, hair or other objects obstructing the o-rings, and ensure there is a good seal and the o-ring is not pinched.
*   Film data sheet or clapper board so that the site/location is identifiable at the beginning of the video (only needed if cameras are external to ROV).
*   Film diode, or use clapper board, or alternative device to synchronise video footage.
*   Correctly insert the deployment release pin (if using).


#### ROV deployment 



1. Vessel master must ensure the vessel is positioned at the start of the transect location.
2. Following the signal to deploy from the vessel Master, use the crane and/or A-Frame to lift and guide the ROV from the deck into the water. Or, if using a small observation class ROV signal to the deckhand to gently place the ROV in the water ensuring the thrusters are disabled or unarmed.
3. Minimise the time taken from when the ROV is let out of reach, to when it is lowered in the water, so as to reduce potential swing and impact against the vessel. As soon as the ROV enters the water pilot it below or away from the vessel to avoid drifting into or over the ROV.
4. Using appropriate software (see Pre-Survey Preparations), rapidly pilot the ROV to the seabed and at the start of transect location to avoid drifting off the starting point. 
5. Confirm imagery and positional data are being recorded where possible (e.g. recording indicators, hard drive operating).


#### ROV maneuvering



1. At the start of the transect flash lights or something similar should be used to indicate the start of the transect. This is important to be able to sync footage with a USBL track (if used) when the cameras are not integrated into the ROV.
2. The ROV should be positioned so that it is on course for the transect trajectory before the transect start-point, so that movements are stable when it reaches the start of the transect. Once the ROV is following the planned transect track the pilot can switch to ‘auto-heading’ to hold course (if available). 
3. The flight elevation of the ROV should be set (either manually or automatically) and maintained at ~ 1 m from the seafloor to facilitate a consistent field of view (i.e. ~5 m width transect for mobile organisms with this width being measurable if calibrated stereo cameras are fitted). Try to maintain a constant forward momentum of ~ 0.5-1 ms<sup>-1 </sup>(1-2 kt). Avoid stopping or chasing fish/organisms off the transect. Also avoid disturbing the substratum as sediment clouds will obscure the image (Hitchin et al. 2015). However, if elevation is too high then fish observations are likely to be reduced. These factors need to be informed by the 'survey question', camera type and performance, illumination type and output power, etc.
4. Ask the vessel's Master to follow the ROV during transects. If current/wind is too strong then the vessel may need to anchor. A sea anchor or drop/clump weight can be used to reduce the effects of vessel and tether drag, respectively. If survey designs require live-boat procedures it is more likely that operations would cease if weather conditions deteriorate too much, unless there was an alternate survey objective that could be accomplished at anchor.
5. Make sure that the tether is kept away from vessel propellers at all times. A crew member must maintain tether management at all times. Clear and uninterrupted communication between ROV pilot, tether crew and vessel master must be maintained at all times. 
6. Monitor weather forecast conditions prior to and during deployment to maintain a safe working environment. Consider aborting operations if local weather and forecast conditions are marginal. 
7. Vessel/ROV maneuvering is a nuanced topic, with most work class ROV teams having their own protocols. Importantly, planning a transect in a fashion that avoids positioning the ROV between the vessel and known entanglement risks (ledges, pinnacles, fishing gear, etc) is the most important general protocol. The goal being to avoid a situation where the vessel drags the tether into the entanglement because the vessel is typically less maneuverable and has less situational awareness of the terrain. Current direction and speed become forces that influence how easy this is to accomplish but many other factors may dictate how a team chooses to mitigate this risk. Before each transect operators should discuss with vessel master if the entrapment risks associated with the seafloor are low enough for the transect to be completed successfully.


#### ROV retrieval



1. When the transect is complete or if the transect is being aborted, advise the vessel Master of the intention to retrieve the ROV.
2. Watch for the ROV to resurface, ensuring only required personnel are near open transom. Avoid approaching the ROV looking into the sun as this increases the risks of collision.
3. Use a grapple hook to connect the lift line to the ROV for retrieval. Depending on the size of the ROV, at least three personnel should be present with hooks to avoid the ROV colliding with the vessel _[Recommended]_.
4. Shut down the ROV. (Dis)connect relevant tether or data transfer cables.
5. For the last transect of the day, if available, wash down the ROV with freshwater and unplug the USBL.
6. Raise the USBL transducer (if pole mounted) before moving the vessel to the next location.


#### Procedures for seabed entanglement or loss of communications with ROV

Potential entanglement of the ROV is always a possibility. The following procedures should be followed upon entanglement/loss:



1. Log the last known position of the ROV.
2. If the ROV appears entangled (i.e. not moving) try to maneuver the vehicle so as to be able to follow back along the tether to see if and where the tether has become snared. If the ROV is trapped under a ledge/cave, or ensnared in a fishing line or kelp, a dive team or additional ROV may be required. It may be required that the tether is disconnected from the vessel before recovery equipment is launched. In such circumstances, the tether end should  be temporally sealed and attached to surface floats which will reduce water damage to the tether.
3. Ensure the vessel is maintaining position and is not adding increased tension to entangled tether. 
4. Ensure that you check ROV thoroughly for damage before redeployment.


#### Completion of operations

Prior to any vessel movement or engine start-up, operators should check the following:



*   All equipment is clear of the water, including the USBL transducer pole.
*   ROV is shut down.
*   All gear is safely stowed.
*   All power and data cables are (dis)connected.
*   External cameras are turned off.
*   An “All Clear to Move” command is given to the vessel Master when the ROV team is satisfied it is OK for the vessel to move on.


## Onboard data processing and storage



5. Once the ROV transect is complete, it is good practice to download associated raw imagery and associated positional data. Imagery and associated positional data should be checked to ensure no failures have occurred, including but not limited to the following: 
*   Miss-timing between image capture and strobes (i.e. dark/black imagery)
*   Failure of one of the stereo cameras
*   Failure of positional logging
1. Name data files according to established conventions. File naming conventions are vital for ensuring both efficient and effective management of field data and its integration into appropriate data management repositories. It is important to note that these conventions will differ among agencies and academic institutions. Examples of stereo imagery naming conventions are provided in Chapter 5 for benthic stereo-BRUVs.
2. Ensure accurate recording of metadata. Metadata are descriptive data sources composed of information that may be used to process the images or information therein and for archiving data on data portals (Durden et al. 2016). While it is important to follow agency specific protocols for capturing metadata, it is also essential that metadata are sufficient enough in detail to satisfy conformance checks for subsequent data release via AODN. Minimum data for each transect should contain as follows:     
*   Campaign (i.e. Survey identifier)
*   Station/event number 
*   Platform
*   Latitude and longitude (WGS 1984 in decimal degrees with a minimum of 6 decimal places _[Recommend]_)
*   Altitude in m
*   Depth in m
*   Time and date stamp in UTC
*   AUV orientation (roll, pitch, heading) in degrees
*   Precision details (e.g. type of navigation system used and its associated errors) 
*   Data provenance 
3. Backup data. This is necessary to ensure all data collected in the field is safely returned and securely backed-up at host facilities, prior to quality control and public release. Onboard copies of data should be made as soon as practical following acquisition. When operating external to a network, it is recommended that all data be backed up on a RAID or a NAS that contain built-in storage redundancy in case of hard-drive failure. A duplicate copy of all data can be copied onto external hard drives for transportation back to host facilities _[Recommended]_. 