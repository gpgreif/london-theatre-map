# London Theatres

Notes taken during development. The purpose of this project was to test out making simple visualizations with the help of ChatGPT.

1. Identifying a question or visualization
	1. Map of theatres in London (reproduce [CIM Theatre Map](https://apps.london.gov.uk/cim/index.html))
2. Finding a dataset
	1. Asked ChatGPT, it recommended the [London Data Store](https://data.london.gov.uk/)
	2. Looked through resources and downloaded theatre data from [Cultural Infrastructure Map](https://data.london.gov.uk/dataset/cultural-infrastructure-map)
3. Setting up GitHub repository
	1. Online setup
	2. Cloning repository through GitHub desktop
	3. Setup folders based on [DCL Workflow Organization](https://dcl-workflow.stanford.edu/organization.html)
	4. Moved in data and opened up Jupyter
4. Exploratory Data Analysis and Visualization
	1. Opened up Jupyter
	2. Asked ChatGPT for GeoJSON data to include in dataset, it suggests [GIS Boundary Files](https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london)from LDS
	3. Combined GIS and London Theatre data using code provided by ChatGPT
5. Creating a visualization
	1. Following the Nightingale reference, I attempted to create a mapbox visualization of the London Theatre data, with help from ChatGPT
	2. Successfully created an html file, but the mapbox visual didn't seem to load properly

LESSON: ChatGPT can be super useful, but don't use it to do things you don't understand. (see [Scott Young article on ChatGPT](https://www.scotthyoung.com/blog/2023/04/25/chatgpt-learning-obsolete/))

Second Attempt: Use Plotly instead of Mapbox
1. Creating Plotly visualization
	1. Use ChatGPT to create code for Plotly
	2. Adjust plot based on desires
2. Update GitHub repository (commit and push) using GitHub desktop

LESSON: Another example of above lesson. Was able to succeed in getting the theatres mapped as points, but couldn't include the boroughs as a choropleth.

LESSON: learn to do things the hard way (with code). So no more GitHub desktop.

##### References

[ChatGPT conversation](https://chat.openai.com/share/65782b00-6bb4-40c6-8a8a-c7a32bca9c09)

Based on
- https://studentwork.prattsi.org/infovis/visualization/art-galleries-and-museums-in-new-york-city/
- https://nightingaledvs.com/data-visualization-using-chatgpt-to-code/