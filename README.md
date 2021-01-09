# capstone-udacity-project
    Repository for Udacity provided capstone project

# Udacity Provided Project
    In the Udacity provided project, you'll work with four datasets to complete the project. The main dataset will 
    include data on immigration to the United States, and supplementary datasets will include data on airport codes, 
    U.S. city demographics, and temperature data. You're also welcome to enrich the project with additional data 
    if you'd like to set your project apart.

# Title: Analysing the immigration data using I-94 immigration records 

## Step 1: Scope the Project and Gather Data

    As a part of this udacity provided project we will analyze the immigration data using the I-94 immigration record. 
    The I-94 record stores various    information about immigrants. It lists the traveler’s immigration category, 
    port of entry, data of entry into the United States, status expiration date and had a unique 11-digit 
    identifying number assigned to it. Its purpose was to record the traveler’s lawful admission to the United States
## Data Gathering
    I94 Immigration Data: This data comes from the US National Tourism and Trade Office. A data dictionary is included 
    in the workspace. This is where the data comes from. There's a sample file so you can take a look at the data in csv 
    format before reading it all in. You do not have to use the entire dataset, just use what you need to accomplish the 
    goal you set at the beginning of the project.
    World Temperature Data: This dataset came from Kaggle. You can read more about it here.
    U.S. City Demographic Data: This data comes from OpenSoft. You can read more about it here.
    Airport Code Table: This is a simple table of airport codes and corresponding cities. It comes from here.
    
# World Temperature Data
    Data is from a newer compilation put together by the Berkeley Earth, which is affiliated with Lawrence Berkeley 
    National Laboratory. The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 
    16 pre-existing archives. It is nicely packaged and allows for slicing into interesting subsets (for example by country). 
    They publish the source data and the code for the transformations they applied. The original dataset from 
    Kaggle includes several files (https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data). 
    But for this project, only the GlobalLandTemperaturesByCity was analyzed. The dataset provides a long period of the world’s
    temperature (from year 1743 to 2013). However, since the immigration dataset only has data in the year of 2016, the vast majority 
    of the data here seems not to be suitable.

# Airports Data
    “Airport data includes IATA airport code.An IATA airport code, also known as an IATA location identifier, 
    IATA station code or simply a location identifier, is a three-letter geocode designating many airports and metropolitan areas 
    around the world, defined by the International Air Transport Association (IATA). IATA code is used in passenger reservation, 
    ticketing and baggage-handling systems (https://en.wikipedia.org/wiki/IATA_airport_code)”. 
    It was downloaded from a public domain source (http://ourairports.com/data/)

# U.S. City Demographic Data
    This dataset contains information about the demographics of all US cities and census-designated places with a population greater 
    or equal to 65,000. This data comes from the US Census Bureau’s 2015 American Community Survey. This product uses the Census Bureau 
    Data API but is not endorsed or certified by the Census Bureau. The US City Demographics is the source of the STATE dimension in 
    the data model and grouped by State.
