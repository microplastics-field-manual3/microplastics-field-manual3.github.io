---
layout: home
permalink: /post-survey-procedures
title: "Post-survey Procedures"
excerpt: "<br>"
image:
  feature: /FK200308-SuBastianRecoveryTwilight-20200316-Ingle-5814.jpg
layout: home

---
{% include toc.html class="toc-left" h_min=2 h_max=2 %} 

Imagery collected by ROV can be either in the form of video footage or still imagery. What type of imagery is collected and annotated is dependent on the aims or hypothesis. Each has its advantages and disadvantages. Below outlines the workflow for both video and still imagery.


## Processing and annotation of video footage

The annotation of ROV imagery will vary according to survey aims and hypotheses, as well as availability of staff and time for this activity. Below we provide standards for annotating ROV imagery for fish based on stereo imagery and habitat and communities based on downward-facing stills. 

ROV based stereo-video should be treated similar to stereo-DOV footage (Goetze et al. 2019).  Where possible and in line with survey aims and hypotheses, species composition, abundance and length data for all species should be recorded. 

For studies focussing on fish or overall community composition, every fish along a transect should be measured (where possible). However, fish that occur in large schools, and are of similar size, can be attributed to binned length measurement using the Number field associated with each length in EventMeasure (or equivalent if analysed using other softwares). It is important to document the range from camera as this is likely to change between regions/ecosystems. This information is included in the standard outputs of EventMeasure and is imported by default into GlobalArchive (see below). 

There are several software packages available, but it is important the output from the analysis of data is in the same or similar formats to facilitate comparison of data between campaigns, studies, and organisations. The most commonly used annotation software is EventMeasure from SeaGIS ([https://www.seagis.com.au](https://www.seagis.com.au)). If afforded, then the EventMeasure software is recommended, unless your organisation already has an alternative established stereo-video annotation workflow (e.g. AIMS). The essential information produced by such annotation software includes three main outputs:



*   Point information
*   Length measurements
*   3-D point information

Point information is typically used to calculate abundance values, while length and 3D point information is used to calculate length and biomass metrics. EventMeasure has established queries built-in to produce typical metrics over a user defined period within the footage. Periods can be used to define the start and end transects if multiple are conducted in the same deployment. In addition, EventMeasure annotation datasets held within GlobalArchive ([http://globalarchive.org/](http://globalarchive.org/)) can be queried in a similar fashion to produce such metrics (see the manual for [GlobalArchive](https://docs.google.com/document/d/1C5t4GM9AiRWiVimmWulmOfsu0HQ4SfDSdPr5gBldOZg/edit?usp=sharing)). 

Type of fish length (e.g., fork length or total length for fish and disc length for rays) should be clearly indicated as part of the adequate annotation information for each transect/campaign. 


## Processing and annotation of downward facing still imagery

A general workflow for processing and annotating epibenthos still imagery can be found in [Williams et al. (2012)](https://paperpile.com/c/0hLaF6/7IVA). Key requirements for raw image processing and positional data are as follows:



*   It is recommended that at least one of the stereo images is in colour and enhanced following similar procedures as outlined by Bryson et al. (2016). 
*   Ideally all stereo images should be georectified similar to Williams et al. (2012). If not stereo then processing routines can be found in Morris et al. (2014).
*   Positional data should be post-processed. This could include using Simultaneous Localisation and Mapping (SLAM) as demonstrated in (Barkby et al. 2009) and (Palomer et al. 2013) for AUV imagery. 

Annotation of individual images can be done using a number of annotation software tools. Examples include, Transect Measure, BenthoBox, Coral Point Count, CoralNet and Squidle+. For national consistency Squidle+ ([http://squidle.org](http://squidle.org)) is recommended as it is free and allows for different approaches in image subsampling (such as a spatially balanced selection), which is important to minimise spatial autocorrelation and influence inferences from data (Monk et al. unpublished data), as well as stratified and random point count distribution on images. Squidle+ will also automatically import the ROV data once it is linked to a data portal (such as IMAS data repository)  making it ready for analysis. Squidle+ also has tools for exploring survey data as well as analysis. In addition, it supports multiple annotation schemes, and will provide consistency through translation between schemes, which is an important point that differentiates Squidle+.

There are three approaches recommended for annotating imagery from ROVs:



*   Annotation of individual images
*   Annotation of photomosaics
*   Extracting structural complexity from orthomosaics

Annotation of individual images or photomosaics can be undertaken using three methods:



*   <span style="text-decoration:underline;">Full assemblage scoring of imagery</span> across space and time. It is important to note that this is a time-consuming process, requiring a lot of replicate images to be scored to enable sufficient power to detect biologically meaningful change as most morphospecies cover &lt; 10 % of an image. This approach appears to be good for delineating bioregional and cross-shelf patterns at a morphospecies (Monk et al. unpublished data) and CATAMI (Althaus et al. 2015) level (Monk et al. 2016, James et al. 2017). This approach will no doubt be effective in choosing an initial suite of indicators for national level monitoring and reporting. 

    As a general guideline, and dependent on the survey question, we recommend that 25 random points per image from at least 50 images per transect are a good starting point for recording most morphospecies present within images (based on Perkins et al. 2016). It is important to note that the properties of the organism themselves will also influence the number of points/images to score. Obviously morphospecies that are less abundant require more effort, but also the 'clumpiness' of species will affect the scoring effort needed (Perkins et al. 2016). (Van Rein et al. 2011) and Perkins et al.  (2016) suggest that, while a higher number of points per image can increase the detection rate of more organisms within an image, increasing the number of scored images using fewer points is likely to have a similar (or greater) effect. Ideally, increasing both the number of images scored and the number of points scored within an image would result in greater power (Roelfsema et al. 2006), but preference is usually for increasing the number of images (Perkins et al. 2016). Unfortunately, the adoption of this approach is likely to result in substantial increases in processing time and thus cost. 

*   <span style="text-decoration:underline;">Targeted scoring of indicators or proxies </span>(such as grouping fine level morphospecies into broader level CATAMI classes; Monk et al. unpublished data). This approach has been shown to work very well at an indicator morphospecies level for detecting change at a regional level (e.g. AUV imagery used by Perkins et al. 2017) as well as for detecting invasive species trends (Whitfield et al. 2007). Since this approach requires substantially less effort to score each image, more images (i.e. often all images) can be scored and, thus, increasing statistical power. The drawback is that narrower understanding of the environment is produced.
*   <span style="text-decoration:underline;">Automated analysis of imagery</span> potentially provides a cost-effective alternative to annotating imagery from ROVs. It is important to note that automated imagery analysis is a relatively new, and largely developmental, way of annotating images. Despite this, some studies suggest that coral and macroalgae can be reliably identified using automated image analysis (Table 4.1 in Chapter 4 AUV).
*   The last approach to annotating ROV imagery involves the extraction of 3D structural information from stereo images using structure from motion techniques (Marcon 2014). This approach works particularly well for sessile species to track changes in growth form through time at a fine scale (Price et al. 2019). It also has application for vertical structure such as reef walls or artificial structures (Robert et al. 2017)


## Data curation and quality control

Data quality control at both the collection and annotation stage is critical. For fish datasets we suggest that the same protocols outlined in section 5.7.3 in Chapter 5 (benthic stereo-BRUVs) be followed, whereby strict training of new annotators is undertaken and thorough checks of species IDs are done by trained taxonomists. It is crucial to include the salary or in-kind contribution of taxonomists into project budgets. For epibenthic sessile communities we recommend that the same protocols outlined in section 4.6.3 in Chapter 4 (AUV) be followed, with, most importantly, the annotation schema needs to be consistent between studies. Where possible morphospecies and associated CATAMI parent classes should be used _[Recommended]_. An initial morphospecies catalogue for southeastern shelf waters is currently held and maintained at the Institute for Marine and Antarctic Studies (IMAS) (contact Assoc. Prof. Neville Barrett or Dr Jacquomo Monk). Clearly, other annotation schemas are available and can be applied. Where existing protocols prevent the adoption of this approach the alternative schema must be mapped to CATAMI so that comparisons can be made with previous studies or between regions. Translations between schema can be readily applied within Squidle+. The quality control of all annotations of epibenthic sessile organisms undertaken by novice scorers should be assessed against an experienced analyst or machine learning algorithm (e.g. using confusion matrices; see Figure 4.4 in Chapter 4). Similarly, all datasets annotated by multiple people, even skilled scorers, should be tested for observer bias. If there are significant differences among annotators it is important to correct discrepancies. This can be done by re-examining the images to ensure an agreement can be reached between annotators. Alternatively, if an agreement cannot be reached, then the miss-classified item could be potentially grouped into a higher level CATAMI class.


## Data release

Many national marine observing programs (for example IMOS through the Australian Ocean Data Network (AODN), or the Marine Geoscience Data System (MGDS) in the USA) routinely store imagery online in an openly accessible location. [Squidle+](http://squidle.org) is a centralised online platform for standardised analysis and annotation of georeferenced imagery and video. Squidle+ operates based on flexible distributed data storage facilities (i.e. imagery can be stored anywhere in an openly accessible online location) to reduce data duplication and inconsistencies, and provides a flexible annotation system with the capability to translate between different annotation schemes.

Following the steps listed below will ensure the timely release of imagery and associated annotation data in a standardised, highly discoverable format.



1. Create a metadata record describing the data collection. Provide as much detail as possible on the deployment (either directly in the metadata record itself, or in the form of attached field sheets as .csv, .txt or similar). Details of minimum metadata requirements are provided in the On-board Data Storage section above. Publish metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:
*   If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 
*   Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit). Note that user registration is required, but this is free and immediate.

    	Lodging metadata with AODN in advance of annotation data being available is an important step in documenting the methods and location of acquired imagery and enhancing future discoverability of the data.

2. Upload raw imagery from the survey to a secure, publicly accessible online repository ([contact AODN](mailto:info@aodn.org.au) if you require assistance in locating a suitable repository).
3. Create a [Squidle+](http://squidle.org) campaign as soon as possible after imagery is uploaded, choose the most appropriate annotation schema, and commence annotation of imagery.
4. Add links to the location of the Squidle+ campaign to the previously published metadata record. You may also wish to attach or link a copy of the annotation data directly to the record.
5. Produce a technical or post-survey report documenting the purpose of the survey, sampling design, sampling locations, sampling equipment specifications, annotation schema (e.g. morphospecies, CATAMI, etc.), and any challenges or limitations encountered. Provide links to this report in all associated metadata _[Recommended]_ 


## Data analysis

The breadth of research questions precludes any detailed advice on the analysis of data from ROV transects. However, one common attribute of the image-based data that will have to be considered for all analyses is spatial proximity. The closeness of images, within and sometimes between transects (for example if triangle or clover-leaf transect designs or subsets of longer transects are used), means that image data are unlikely to be independent (due to spatial autocorrelation). Yet, this is an assumption that many statistical methods rely upon. The failure to meet this assumption means that the inferences from the statistical analysis may be: (i) over-confident, e.g. having a p-value that is too small; (ii) biased, i.e. the estimates do not reflect the truth; (iii) both, or; (iv) no effect. Obviously, the fourth category is what a researcher hopes for, but it is improbable and must be validated. However, if it is known that the study organism exhibits particularly low autocorrelation then the analysis need not consider it explicitly. 

Methods to analyse data, accounting for autocorrelation are available. These include geostatistical models (Foster et al. 2014). However, in certain situations subsampling images will help (Mitchell et al. 2017), but not necessarily alleviate completely. Further, if the study is for a broad area, where transects are small and are well-separated, then amalgamating data to transect level may also be appropriate. The issues of spatial auto-correlation should also be considered if longer transects are being broken up into smaller sections for analysis (as is commonly done in the oil and gas sector).

Some effort should be made to estimate sources of error inherent in navigational (USBL) systems (and/or other geo-referencing methods) and understand how these errors affect the overall target parameter estimation and variability (see Karpov 2006, Rattray et al., 2017, Mitchell et al. 2017). 
