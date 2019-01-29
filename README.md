# GroupProject1
Group Project 1 - U of A Data Analytics Boot Camp

## Juypter Notebook directory

## Extract State Data.ipynb
    --Reads all csv files for separate states and cancers
    --Creates new combined dataframe
    --Create new columns with States, Cancer type, columns

## Extract State Averages.ipynb
    --Reads in JSON Superfund site information
    --Dataframe with Sites per state
    --Chart of Superfund per State
    
-- Read in Cancer data from csv

    --Separates data per cancer type into separate dataframes with lat/lng information
    
-- Creates subset of 4 cancertype dataframes

    --Cleans up data
    --4 dataframes with State, IncidentRates, and Superfund count per state 
    
-- Calculate Ranges between min and max incident rate

-- Create scatter plots per cancer type

    --Output scatter plot png files  
    
-- Create pearson coefficence per cancer type looking for correlation

    --Resorts data
   
## Heatmap and markers.ipynb

    --Reads in superfund JSON data for marker locations of Superfund sites
  
    --Reads in combined cancer data 
  
    --Clean up data, remove states with no data
  
    --Remove extra characters in data columns
  
    --Separate data into separate dataframes per cancer type
  
    --Create heatmaps for individual cancers
  
    --Overlay geojson county data
  
    --Create heatmap with superfund sites overlay, plus county geojson overlay
  
    --Output figures

## StateBars.ipynb

    --Read in csv file to create top 5 and bottom 5 cancer incidence
    
    --Create Charts
  
## Images Folder

    --Contains final images of State top5/bottom5 charts
  
    --Scatter plots per cancer type
  
    --Heatmaps
  
    --Heatmaps with Superfund markers
  
## Resources Folder

    --States_data folder - contains all data downloaded from cancer site, plus combined data of all states
  
    --Assorted csv files for zip code, experiments, lat/lng experiements.
  
## backup_docs

    --Assorted planning materials

## backup_ppt

    --Presentation revs assorted ppt pieces
	
