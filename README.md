# Piceance-basin-model

This is a 3D model of the Piceance Basin, Colorado. Constructed by Dr. Yao Tong for her dissertation with Basin and Petroleum System Modeling Group at Stanford University. Petroleum production in the Piceance basin began in 1931 and 38 fields have been discovered and produced since then. Among the 38 fields, 21 of them produce partially or completely from basin-centered gas accumulation. The model was used to have a better understanding of the basin centered gas in Piceance Basin and to assess associated uncertainty (both parameter and spatial level) involved in basin and petroleum modeling process. 


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
  
  We'd love to hear from you if you found this useful!
