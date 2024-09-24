## Toronto_Bikeshare
In 2011, Toronto embarked on an ambitious project to enhance its urban mobility and foster a greener, more accessible cityscape. This vision gave birth to Bike Share Toronto, a system designed not just as an alternative to congested commutes but as a key part in the city's broader environmental and transportation strategy. By offering a network of easily accessible bikes, Toronto aimed to reduce car usage, lower carbon emissions, and promote healthier living. Today, this service is more than just a convenience; it's a vital part of Toronto’s commitment to sustainable urban development, demonstrating the city's dedication to a healthier, more dynamic urban environment. 


As of 2024, the accessibility of Bike Share Toronto has reached new heights, with over 800 stations around town. In a significant move to bolster this initiative, Toronto has expanded its e-bike program, transitioning from a pilot to a permanent fixture within the city's transit options. By the end of 2022, the e-bike fleet had expanded from 300 to 525, supported by 15 new e-stations. This growth is set to continue, with plans to increase the fleet to 2,000 e-bikes and add 100 more e-stations by 2025.


The purpose of this project is to analyze the bike share dataset, and to understand the impact of various factors on bike-share demand and usage in Toronto. This project is divided into three parts.

**Part 1** focuses on analyzing ridership patterns to identify key factors that influence bike-share demand in Toronto.

**Part 2** delves into station-level analysis, comparing the usage patterns of charging and regular stations, and examining their proximity to TTC stations to assess how well they are integrated with public transit.

**Part 3** involves building a chatbot using GPT-4o to answer detailed questions about the Bike Share Toronto ridership data, providing an interactive tool for exploring and understanding the dataset.

## Source Data
For my analysis, I used the following datasets:
1. Bike Share Toronto Ridership Data: This dataset includes anonymized historical ridership data from January 2019 to December 2023. The dataset is available from the City of Toronto Open Data Portal, which can be accessed here : https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/
2. Toronto Bikeways Data: The Toronto Bikeways Dataset provides detailed information on the city's cycling network, including shared and dedicated routes such as cycle tracks, bicycle lanes, neighborhood routes, multi-use trails, and signed cycling routes. The dataset is available from the City of Toronto's Open Data Portal, which can be accessed here: https://open.toronto.ca/dataset/bikeways/
3. Station Level Data: For station-level analysis and understanding e-bike distribution, I utilized datasets available from the City of Toronto Open Data Portal, accessible via GBFS (General Bikeshare Feed Specification) JSON feeds. This dataset can be accessed here: https://open.toronto.ca/dataset/bike-share-toronto/
4. TTC Subway Shapefiles: To visualize bike stations in relation to public transit infrastructure, I utilized the TTC Subway Shapefiles, accessible from the City of Toronto Open Data Portal: https://open.toronto.ca/dataset/ttc-subway-shapefiles/
5. A summarized version of the bikeways dataset, cycling-network.geojson, is also utilized to provide a concise overview of the city’s bikeways network. This dataset can be accessed here: https://open.toronto.ca/dataset/cycling-network/
6. The Toronto Ward Boundaries dataset was also used to analyze the distribution of bikeshare stations across different wards in the city. This dataset is published on City of Toronto’s Open Portal and is available here: https://open.toronto.ca/dataset/city-wards/


#### Download Data
All the folder structures and data files required for performing the analysis done in `Bikeshare_Toronto_Analysis.ipynb` and are package into a `.zip` file which can be downloaded from: [Bikeshare_Repo_Data](https://drive.google.com/drive/folders/1qUo-JQse1EKDvcAJHuVGsQ7ETDS3x0m8?usp=sharing) (Hosted on Google Drive)


## Quick Start
Once the `.zip` file is downloaded, extract all into your target directory. Open `Bikeshare_Toronto_Analysis.ipynb` and follow the step-by-step analysis detailed in the notebook.
