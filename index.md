# Data Description
There will be two data sets for the copper and stainless steel samples that are necessary to determine the adhesion strength of the nickel coating for each material’s samples. 

The first data set:
Power density of the high power laser 
Number of pulses fired for each sample 
	
Power density is a function of the location of a particular lens in the beamline and will be calculated using either a calculator or an Excel spreadsheet and the data for this is numerical. The equation used for this is well established in the field of optics and is computed with simple algebra.  This data will be input into an Excel spreadsheet alongside the number of pulses fired for each sample (which is recorded based off observation of the experiment) so that each sample is properly catalogued and so the data set may be regularly updated as experiments are carried out. The spreadsheet will be saved on a personal computer.

The second data set:
Surface wave position
Surface wave velocity
Time elapsed
VISAR beam intensity
Nickel coating adhesive strength

The second dataset is collected from an oscilloscope’s readings from the photodiode detectors set up in the VISAR beamline. Surface wave position, time elapsed, and VISAR beam intensity are directly displayed on the oscilloscope screen and will be exported as a PNG type file onto a USB drive for data processing on a computer. Due to the size of the files produced from the oscilloscope, a post-processing script written in Python will be used to allow the computer to unpack the files from the USB drive. The surface wave velocity data is produced through a native command on the oscilloscope which makes it perform a complex Fourier transform to the surface wave position readouts, resulting in a surface wave velocity plot. Like the other oscilloscope data, this plot will be saved to a USB drive and unpacked by the Python script. This data will be used to determine the nickel coating’s adhesion strength by inputting the surface wave velocity into an empirically derived correlation from literature. Aside from the images from the oscilloscope, the remainder of the data from this dataset will be numerical or plot outputs from a Python script. Ultimately all post-processed data from this dataset will be stored on a personal computer or an external hard drive.
  
How much data will be produced for each dataset?
Data Set 1: No more in quantity than on the order of MB scale since it will be a simple Excel spreadsheet.
Data Set 2: Anywhere between GB-TB depending on the number of samples examined.

# Roles and Responsibilities
DMP implementer: Grad student 1 (the author of this document) will ensure the DMP is implemented and followed throughout the entire research and data generation process.

Data manager: The PI will be the data manager. They will have the final say on all decisions regarding the data created.

Instrumentation maintenance: Grad student 1 and PhD student 1 will maintain the sensitive VISAR instrumentation, which requires frequent maintenance and recalibration. Grad student 2 will maintain the high power laser beamline instrumentation and the samples to be analyzed.

Data collection/generation: Grad students 1 & 2, PhD student 1, and undergrad students 1-3 will be responsible for data collection/generation. Grad student 1 and PhD student 1 will produce collect and process the raw data from the VISAR. Grad student 2 and undergrad students 1-3 will be responsible for recording data regarding the high power density laser beamline configuration and spallation confirmation.

Data analysis: Grad students 1 & 2, PhD student 1, and undergrad students 1-3 will perform data analysis in their respective areas. Grad student 1, PhD student 1, and undergrad student 1 will analyze the raw data produced from the VISAR. Grad student 2 and undergrad students 2 & 3 will confirm the VISAR analysis by confirming spallation occurred using optical microscopes. Analysis from both groups will be synthesized.

Data organization: Grad students 1 & 2 and PhD student 1 will be responsible for organizing the data. Data will be consolidated into an Excel (or similar software) spreadsheet. 

Quality control: The PI and PhD student 1 will act as the quality control for each step of the process for the data, from generation to analysis to archival. 

Metadata generation: Grad students 1 & 2, PhD student 1, and undergrad students 1-3 will participate in metadata generation. Grad students 1 & 2, and PhD student 1 will produce the necessary metadata relevant to their contributions to the research. Undergrad students 1-3 will assist in drafting and editing the metadata.
Software creation: Grad students 1 & 2 and PhD student 1 will be responsible for creating any software needed to process or visualize data created. 
Archiving and preservation: Grad student 1 and the PI will be responsible for determining how the data will be archived and preserved.

# Data Standards and Metadata
Grad students 1 & 2, PhD student 1, and undergrad students 1-3 will participate in metadata generation. Grad students 1 & 2, and PhD student 1 will produce the necessary metadata relevant to their contributions to the research. Undergrad students 1-3 will assist in drafting and editing the metadata.
# Storage and Security
Data will be stored on a shared Google drive, in the research team’s Box folder, and on the hard drives of Grad students 1 & 2 and PhD student 1. By having redundant data storage, it provides multiple methods to recover and access the data should one method fail or become unavailable.
# Access and Data Sharing
None of the data to be produced for this research project can be classified as sensitive or confidential, therefore it is unrestricted. Data shall be available upon request – email ian.ferguson97@gmail.com for access.
# Archiving and Preservation
Grad student 1 and the PI will be responsible for determining how the data will be archived and preserved.
