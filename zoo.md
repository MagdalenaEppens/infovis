# A Tour Through the Visualization Zoo

To put the information to good use, we must find ways to explore, relate, and communicate the data meaningfully.
By making data more accessible and appealing, visual representations may also help engage more diverse audiences in exploration and analysis.
The challenge is that for any given data set the number of visual encodings is extremely large.
 (…) all visualizations share a common “DNA”—a set of mappings between data properties and visual attributes such as position, size, shape, and color—and that customized species of visualization might always be constructed by varying these encodings

### Time-Series Data: 
Time varying phenomena are central to many domains such as finance, science, and public policy. One often needs to compare a large number of time series simultaneously and can choose from a number of visualizations to do so. 
-	Index Charts
- Stacked Graphs
- Small Multiples
- Horizon Graphs 

### Statistical Distributions: 
Analysts often want to fit their data to statistical models, either to test hypotheses or predict future values, but an improper choice of model can lead to faulty predictions. Thus, one important use of visualizations is exploratory data analysis: gaining insight into how data is distributed to inform data transformation and modeling decisions. Common - Steam-and-Leaf Plots
- Q-Q Plots
- SPLOM
- Parallel Coordinates

### Maps: 
Many maps are based upon a cartographic projection. Other maps knowingly distort or abstract geographic features to tell a richer story or highlight specific data.
- Flow Maps: it represents the movement of a quantity in space and (implicitly) in time
- Choropleth Maps: Data is often collected and aggregated by geographical areas (...). A standard approach to communicating this data is to use a color encoding of the geographic area.
- Graduated Symbol Maps: it places symbols over an underlying map. This approach avoids confounding geographic area with data values. 
- Cartograms: A cartogram distorts the shape of geographic regions so that the area directly encodes a data variable.

### Hierarchies: 
While some data is simply a flat collection of numbers, most can be organized into natural hierarchies.
- Node-link Diagrams
- Adjacency Diagrams: rather than drawing a link between parent and child in the hierarchy, nodes are drawn as solid areas (either arcs or bars), and their placement relative to adjacent nodes reveals their position in the hierarchy.
- Enclosure Diagrams: The enclosure diagram is also space filling, (...). (...)a treemap recursively subdivides area into rectangles. As with adjacency diagrams, the size of any node in the tree is quickly revealed.

### Networks: 
A central challenge in graph visualization is computing an effective layout. Layout techniques typically seek to position closely related nodes close in the drawing; critically, unrelated nodes must also be placed far enough apart to differentiate relationships. 
- Force-directed Layouts: A common and intuitive approach to network layout is to model the graph as a physical system: nodes are charged particles that repel each other, and links are dampened springs that pull related nodes together.
- Arc Diagrams
- Matrix Views

