# Data and R markdown to replicate analyses in “Optimizing remote underwater video sampling to quantify relative abundance, richness, and corallivory rates of reef fish”.
---

This Hsu.etal_2025_dataset_README.txt file was generated on 9 Jan 2025 by Tsai-Hsuan Tony Hsu (tonytsaihsuanhsu@gmail.com / tsai-hsuan.hsu@sydney.edu.au). Knit [SamplingRUV_Hsu et al_2025.Rmd](SamplingRUV_Hsu et al_2025.Rmd) to generate html and extract R code.


1. **Author Information**

	First & corresponding author
		Name: Tsai-Hsuan Tony Hsu
		Institution: School of Life and Environmental Sciences, The University of Sydney, Sydney, NSW 2006, Australia
		email: tonytsaihsuanhsu@gmail.com / tsai-hsuan.hsu@sydeny.edu.au

	Second author
		Name: Dr. Sophie Gordon
		Institution: Australian Institute of Marine Science, Townsville, QLD 4810, Australia
 		
	Third author
		Name: Dr. Renata Ferrari 
		Institution: Australian Institute of Marine Science, Townsville, QLD 4810, Australia
		
	Fourth author
		Name: Prof. Andrew S. Hoey
		Institution: College of Science and Engineering, James Cook University, Townsville, QLD 4814, Australia
	
	Fifth author
		Name: Prof. Will F. Figueira
		Institution: School of Life and Environmental Sciences, The University of Sydney, Sydney, NSW 2006, Australia
		
		
2. **Date of data collection**: April 2021 to Jan 2022

3. **Geographic location of data collection**: Torres Strait and Great Barrier Reef, Australia, West Pacific

4. **Funding sources that supported the collection of the data**: This research was supported by the Reef Restoration and Adaptation Program, which is funded by a partnership between the Australian Government, Reef Trust, the Great Barrier Reef Foundation, and The Australian Institute of Marine Science. The research was conducted under the Great Barrier Reef Marine Park permit G21/44774.1.

5. **Recommended citation for this dataset**
Hsu T-H.T, Gordon S, Rerrari R, Hoey A.S, Figueira W.F (2025) Data and R markdown to replicate analyses in “Optimizing remote underwater video sampling to quantify relative abundance, richness, and corallivory rates of reef fish”. *Sydney eScholarship*, https://doi.org/10.25910/agvq-3f82

[Data and R markdown also available on Sydney eScholarship (https://hdl.handle.net/2123/33520) and GitHub (https://github.com/THTonyHsu/SamplingRUV.git)]


## DESCRIPTION OF THE DATA AND FILE STRUCTURE

### DATA & FILE OVERVIEW

1. **Description of dataset**

These data were generated to optimize remote underwater video sampling to quantify relative abundance, richness, and corallivory rates of reef fish.

2. **File List**

   File 1: Hsuetal_dataset_PM_Heron.csv
   File 1 description: Intensive sampling dataset of fish assemblages on RUV at Heron Island, southern GBR

   File 2: Hsuetal_dataset_PM_Chicken.csv
   File 2 description: Intensive sampling dataset of fish assemblages on RUV at Chicken reef, central GBR
  
   File 3: Hsuetal_dataset_PM_Aukane.csv
   File 3 description: Intensive sampling dataset of fish assemblages on RUV at Aukane Reef, Torres Strait

   File 4: Hsuetal_dataset_Obligate corallivorous fish.csv
   File 4 description: Species list for obligate corallivore accoding to Cole et al. (2008)

   File 5: Hsuetal_dataset_FR_Pelorus.csv
   File 5 description: Bites of obligate corallivores on RUV at Pelorus, Palm Island group
   
   File 6: Hsuetal_dataset_FR_Masig.csv
   File 6 description: Bites of obligate corallivores on RUV at Masig, Torres Strait

   File 7: Hsuetal_dataset_FR_Lizard.csv
   File 7 description: Bites of obligate corallivores on RUV at Lizard Island, northern GBR

   File 8: Hsuetal_dataset_FR_Heron.csv
   File 8 description: Bites of obligate corallivores on RUV at Heron Island, southern GBR

   File 9: Hsuetal_dataset_FR_Halfway.csv
   File 9 description: Bites of obligate corallivores on RUV at Halfway Island, Keppel Island group

   File 10: Hsuetal_dataset_FR_Davies.csv
   File 10 description: Bites of obligate corallivores on RUV at Davies Reef, central GBR

### METHODOLOGICAL INFORMATION

A detailed description of data acquisition and processing can be found in the published manuscript in Coral Reefs (xxx).


#### DATA-SPECIFIC INFORMATION


##### **Hsuetal_dataset_PM_Heron.csv**

1. Number of variables/columns: 7

2. Number of cases/rows: 3464

3. Missing data codes

    None

4. Variable List

    + Column A - Frame: video frame
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – SN: scientific name
    + Column F – Number
    + Column G – TL: total length
    
##### **Hsuetal_dataset_PM_Chicken.csv**

1. Number of variables/columns: 7

2. Number of cases/rows: 1393

3. Missing data codes

    None

4. Variable List

    + Column A - Frame: video frame
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – SN: scientific name
    + Column F – Number
    + Column G – TL: total length

##### **Hsuetal_dataset_PM_Aukane.csv**

1. Number of variables/columns: 7

2. Number of cases/rows: 1393

3. Missing data codes

    None

4. Variable List

    + Column A - Frame: video frame
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – SN: scientific name
    + Column F – Number
    + Column G – TL: total length

##### **Hsuetal_dataset_Obligate corallivorous fish.csv**

1. Number of variables/columns: 3

2. Number of cases/rows: 29

3. Missing data codes

    None

4. Variable List

    + Column A - Family
    + Column B - Genus
    + Column C - Species

##### **Hsuetal_dataset_FR_Pelorus.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 232

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual

##### **Hsuetal_dataset_FR_Masig.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 124

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual
    
##### **Hsuetal_dataset_FR_Lizard.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 503

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual

##### **Hsuetal_dataset_FR_Heron.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 515

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual

##### **Hsuetal_dataset_FR_Halfway.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 246

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual

##### **Hsuetal_dataset_FR_Davies.csv**

1. Number of variables/columns: 9

2. Number of cases/rows: 55

3. Missing data codes

    None

4. Variable List

    + Column A - Time: time on the video
    + Column B - Family
    + Column C - Genus
    + Column D – Species
    + Column E – Number
    + Column F – Activity
    + Column G – TL: total length
    + Column H – Comment
    + Column I – ID: ID for each individual
