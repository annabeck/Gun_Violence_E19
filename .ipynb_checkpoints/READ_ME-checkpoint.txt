ZIP FILE CONTAINS:
    4 folders
    7 notebooks
    
        
        Folders contain:

            Rawdata
            - Data downloaded from Kaggle.

            Data
            - All data files generated in the notebooks

            Maps
            - Geodata on US boarders

            Figures
            - All figures generated in the notebooks

        
        Notebook descriptions:

            01 Data Prep
            - Retrieves Rawdata from the folder "Rawdata" that contain the data downloaded from Kaggle.
            - The prepared data is saved as zip csv file "Data_incidents.csv.zip" in the Data folder.

            02 US Maps
            - Loads the prepared data, "Data_incidents.csv.zip".
            - Loads geodata on US state boarders found on ArcGIS.com and saves in "Maps/states_21basic" folder, "states.shp". 
            - Prepares maps used in descriptive statistics (figure 1) and spatial kernel density plot (figure 3).
              
            03 Descriptive Stats Mass Shooting
            - Loads the prepared data, "Data_incidents.csv.zip".
            - Prepared data for the plot of development of all incidents and mass shootings over time (figure 2).
            - Retrieves relevant data used in descriptive statistics (table 1 and 2).

            04 Spatial Analysis
            - Loads the prepared data, "Data_incidents.csv.zip".
            - Generates results for mass shooting nearest neighbour (table 3), 
              G function plots (figure 4) and K function plots (figure 5)

            05 Time Clustering
            - Loads the prepared data, "Data_incidents.csv.zip".
            - Generates timelines (figure 6), kernel density plot (figure 7) and AR model results (figure 8 and table 4).


HOW TO RUN THE NOTEBOOKS:

- In each of the notebooks change the directories "os.chdir( ....)" to local folder. 
- Run the notebooks in the order given by the number in their titles. 