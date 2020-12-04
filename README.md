# Syringe Filters
The aim of this small project was to check if there was any difference in filtered solutions using different syringe filters.  
Different solvents (water, acetonitrile, methanol and isopropanol) were filtered using 3 different types of syringe filters (Millipore, Clarify and Minisart).  
Filtered solvents were injected in full scan mode using both negative and positive ionization modes.  
This repo contains the codes used for process the adquired data.  
  
 # Workflow 
1. Convert *.raw* files to *.mzXML* files with [Proteowizard](http://proteowizard.sourceforge.net/).    
2. Apply the code [remove_orbitrap_shoulder_peak](remove_orbitrap_shoulder_peak.Rmd) to remove background signals.    
3. Apply code [XCMS_processing](XCMS_processing.Rmd) to process the data and get and overview through a PCA.    
