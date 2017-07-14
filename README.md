# dataworldcode
Use Case for Data World: Create Treemaps Using TAS Category Dataset

The R Script included can be used to generate two treemaps, using the datasets 
available publically via api.usaspending.gov or posted in dataworld.

Instructions:
1. Download the dataset "tas_categories.csv" from data.world and save the file
2. Download the R script
3. Open R Studio
4. Open the R script file from within R studio
   
   A file can be opened by selecting 'File' > 'Open File' > Select the file location, and select open or
   by using the file open icon
5. Set the correct working directory, this will designate the location for the dataset input and graph output
   
   Go to line 25 and enter the file location following the first open parentheses in "setwd()"
   
   This should point to the folder location to which the dataset is saved
6. Execute the R script
   
   The script includes descriptive comments
   
   The script will generate two treemap files:
        
   1. Treemap of the Department of Transportation's spending by Major Object Class (classifies spending into 5 general 
      expenditure categories)
        
   2. Treemap of Department of Transportation's spending by Secondary Object Class (classifies spending into more than 
      20 detailed expenditure categories)
