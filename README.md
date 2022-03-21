<b>Exploratory Lab 1</b>

![alt text](https://github.com/emilyec/exploratory-lab-2/blob/969d1c3b89991fdb0ee3973f5ae679c581035bbb/screenshot.PNG "Screenshot")

Link to map: <a href="https://emilyec.github.io/exploratory-lab-2/herbarium-web" target="_blank">Explore Map</a>

<b>Reflective analysis</b>

My goal for this task was to create an interactive map to explore the current distribution of Garry oak ecosystem on the landscape. Garry oak ecosystems are not well mapped in general, and by combining two datasets from the BC Conservation Data Centre which show the ‘known occurrences’ of the two primary Garry oak vegetation communities, this map provides a useful resource for researchers to better understand remnant Garry oak habitat in British Columbia.
The purpose of the map is to aid in exploratory research with my supervisor, lab mates, committee members and stakeholders/titleholders. This map will help visualize potential sites for field visits and provide an invaluable visual aid for discussions with committee members and consultations with First Nation titleholders. The addition of the BC Parks, Ecological Reserves, and Protected Areas layer provides important context for the conservation threat to Garry oak ecosystems. Very few remnant patches are protected by reserves (I calculated only 8 square kilometers from the overlap of the layers in this map) which is important for developing conservation strategies and understanding the persistence of certain habitat patches over time.

The design of the map is intended to be both functional and aesthetic (<a href="https://github.com/emilyec/exploratory-lab/blob/6ffab5e2f115196b0acb7a16b5ebcdd25eeea22c/style.json">Mapbox Studio JSON style file</a>). I chose a satellite imagery basemap and customized the style in MapBox studio. The imagery is important for assessing Garry oak habitat patches and evaluating the structure of the ecosystem (e.g., openness, dominant species). The points of interest, roads, and natural features are useful for understanding the larger landscape context and the potential accessibility of habitat patches. I also enabled the 3D terrain function in MapBox to allow the user to shift perspective and view the topography. This is another piece of useful context when evaluating Garry oak ecosystems.

For the tilesets, I selected colours that would stand out from the basemap but also reflect the natural palette of Garry oak meadow grasses and wildflowers. I created a decorative title for the map, while choosing a san serif font with a scale hierarchy for the labels for ease of reading/scaling.  I customized the colours of all of the place labels to be consistent with natural toned colour scheme and to reflect the subject of the map. 

In terms of functionality, I styled the layers with changing scale in mind. I imagine that the audience will want to zoom in on specific Garry oak patches, so I faded the fill of the polygons as the user zooms in so that they can see the imagery underneath the polygon. In addition, I customized the stroke so that as the user zooms in, it changes to a dashed pattern to give an indication of the uncertainty of the patch dimensions. I also faded the Protected Areas layer slightly with zoom but left enough colour so that when the user is zoomed in close, they know whether the polygon(s) they are looking at are within a protected area or not without having to zoom out for context.

I shared an early version of this map with a lab mate for review. I got some great comments on the symbology (using the dashed line to suggest uncertainty) and the polygon colours which I adjusted to make slightly brighter than they originally were. The biggest help was double-checking the formatting/layout on a different computer. I made major changes after the review when I realized that I had formatted the map for my screen and it was not displaying properly on other computers. I also realized that I had to upload and specifically point to the custom font files that I used as they were only displaying locally at first.

I hope to build upon this draft of the map and add more data as I get it. I also hope to improve the functionality of the map and add some more sophisticated features like a toggle to turn on/off layers and pop-ups that display select attributes when a polygon is clicked. I also thought it would be nice to have the ability to <a href="https://docs.mapbox.com/mapbox-gl-js/example/flyto/" target="_blank">'fly'</a> to certain regions. The starting scale of the map is fairly large due to the distribution of the polygons and while I like seeing the entire scope when opening the map, it is a bit difficult to navigate when zoomed in. Defining regions like ‘Greater Victoria’ and ‘Gulf Islands’ would help the user navigate the map more easily and in a more curated way. 
