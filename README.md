

## Data analysis

Here we analyse geolocation data. 
We depersonalise data which we get from project "Lecturers without borders" and get most of the research questions from there.

## Data collection 

1. We collect the geolocation data of human trajectories in the project from Open Humans
https://www.openhumans.org/activity/mobility-data-of-researchers/  Feel free to join the project!
We are open for researchers around the world, who would like to analyze or donate their data through openhumans.org platform.
2. We collect the data from schools and amenities around human trajectories using https://www.thedatapond.net and osmnx package


## Code for analysis of data
We also put some recent code for analysis of open and depersonalized data for functionality of "Lecturers without borders".
If you would like to collaborate with us please contact us at *networkscied at gmail.com* or *liubov.tupikina at cri-paris.org*




#### Geolocation data analysis

This is README for geo_data_analysis for Lecturers without borders project https://scied.network/how-lecturerswb-works/ .
Here we mostly do analysis of spatial dimensions of data from "Lecturers without borders" project. 
All data is depersonalized and no data files are uploaded without permissions of the owners of the information (description in process).

*Contributors* to this repository are welcome. Please write to us if you would like to work on issues, start a new repository or tell us about errors.

More information about geolocation data analysis methods can be found here:
1. https://github.com/Liyubov/data_analysis_for_social_good
(repository in collaboration with Prashant, Hugo on visualising maps, geolocation data structuring)
and here:
2. https://github.com/Liyubov/mobility_analysis 
(repository in collaboration with Bastian from openhumans.org on analysis of open mobility data) 

#### Code for simple visualisation of mobility and static data 
1. In the first notebook *analysis_human_mobility_opendata.ipynb* we analyse Individual mobility data from openhumans platform in order to apply it later to general patterns of researchers mobility data. We also apply some trajectories analysis techniques to characterize mobility trajectories.

2. We also analyze global mobility data from openflights and global mobility data https://bluehub.jrc.ec.europa.eu/migration/app/index.html?state=5cc845a97758cd17cdecd1fb (accessed June 2019)

3. In notebook *LeWiBo_on_map.ipynb* we visualise some data points from "Lectures without borders" on a map (Work in progress). We plot the countries on a map, where we have participants from "Lecturers without borders".

4. In notebook *get_schools_from_locations.ipynb* we are using open data from Openstreetmaps (OSM) to make API calls and prepare open depersonalized dataset of datapoints with certain amenities (see OSM documentation school-mapping.azurewebsites.net) for a certain location. This notebook can also be applied to analysis of other amenities on openstreetmaps with missing information, e.g. buildings with missing information etc as shown on the screenshot openstreetmap_example.png.

### Websites for data analysis:

1. https://www.batchgeo.com/
2. https://export.hotosm.org/en/v3/learn
3. https://www.openhumans.org/activity/mobility-data-of-researchers/





### Usage of code

You can us the code in notebooks for browsing the data or managing the data collected from your project. In case of any errors or issues please contact us.

### Contributing 

The project is under development and we are open for collaborations. We collaborate with mostly educational and data analysis projects in various regions and countries. If you would like to join our team of educators, data scientists and coordinators, please write to us to liubov.tupikina AT cri-paris.org

We also are using slack in our community and would be happy to include you after you fill in the registration at https://scied.network/page



