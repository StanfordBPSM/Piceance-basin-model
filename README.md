# Piceance-basin-model

This is a 3D model of the Piceance Basin, Colorado. It was constructed by Dr. Yao Tong for her dissertation with Basin and Petroleum System Modeling Group at Stanford University. Petroleum production in the Piceance basin began in 1931 and 38 fields have been discovered and produced since then. Among the 38 fields, 21 of them produce partially or completely from basin-centered gas accumulation. The model was used to have a better understanding of the basin centered gas in Piceance Basin and to assess associated uncertainty (both parameter and spatial level) involved in basin and petroleum modeling process. 

The data organization is as follows:
/cult/: all culture data, shape files for oil/gas fields in CO state, outcrops;

/data/map/: all maps used to create models, e.g., the folder topo has the files to create topo map;


you don't need them as the 1d/2d/3d/ model projects already have the maps under their directory;

/pm1d/: 5 1-d models, ExxonloveRanch#1 models(4) are in the Paleotemp paper to Basin Research; 

the MWX1 model is in Uncertainty quantificaiton/and Sensitivity Analysis paper; also used for porosity calibaration.
	
/pm2d/: 2d cross section model built based on the Y-130 cross-section from the 3D. 

NOT directly extract from 3D, 
explore 2 erosion scenarios in those 2 versions.

/pm3d/: 3D model used for thesis and AAPG Hedberg paper

/well/: contains the well list information used in this project.

/!AddiNotes/: other notes/data for the Piceance Basin model porject:

-231wells_V2015.xls: 231 PETRA well informations, plus the other USGS wells used, all well API, Name, lat-long, KB...
-CompactionCalibration: Campaction Calibration done at MWX-1 well location, with notes and discussions with Noelle

Other data/model assumptions are stored within the projects;

-The Cameo Coal Kinetics can be found at Kinetics Editor, Under 'Compositional'/'Cameo_coal', there's another 'Cameo_coal_noCO2' assumes CO2 quickly dissovled in water, just for test purpose;
-Lithologies are defined under the folder 'PBlitho' with subfolders
	
## More about Piceance Basin:
The Piceance Basin is located in northwest Colorado and was formed during the Late Cretaceous–Paleogene Laramide tectonism, which partitioned the stable Cretaceous
Interior Seaway foreland basin into a series of smaller basins. The basin is defined by reverse faults and associated anticlinal fold structures on the margins.
From the Late Cretaceous to Cenozoic, the Piceance basin transited from marine to terrestrial depositional setting as a result of the Laramide deformation and the recent
vertical regional uplift. Depositional environments varied from shallow marine, fluvial, paludal, lacustrine and terrestrial settings and formed the prolific Mesaverde petroleum system. The earliest commercial production came from a Cretaceous tight sand reservoir situated in Williams Fork Formation of the Mesaverde Group. The underlying coastal plain coals became thermally mature later in the Cenozoic and charged the adjacent Mesaverde Williams Fork Formation with natural gas.

<img src="https://github.com/StanfordBPSM/Piceance-basin-model/blob/main/figures/yao1.PNG" width="600">
(A) Map of the Piceance Basin with major uplift arch structures, green polygons indicate the Mesaverde outcrop (modified from Leibovitz, 2010). Inset map shows the state
of Colorado, USA. (B) Piceance Basin structural cross section showing asymmetry of the basin and strata from Upper Cretaceous through lower Tertiary strata based on well logs.
Color-filled gamma ray (GR) and resistivity (ILD) are shown. Key landmarks and gas fields are labeled (modified from Rogers, 2012).

<img src="https://github.com/StanfordBPSM/Piceance-basin-model/blob/main/figures/yao2.PNG" width="600">

Using this basin model, The Cretaceous Cameo Coal source rock maturation history was investigated. Given limited published calibration data, basin models were calibrated mainly with vitrinite reflectance data. The basin model predictions agree well with the measured thermal maturation data. This work contributed a regional scale 3-dimensional basin model for the study area. The model may serve as a research vehicle for further studies, such as geological scenario tests, unconventional resources characterization and other Laramide basin research. To find out more, and for references to Yao's thesis and papers, please visit bpsm.stanford.edu.
  
 We'd love to hear from you if you found this useful!
