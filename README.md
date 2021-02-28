# Digital_Symbiosis
A dimensionality reduction and probabilistic distribution of spatial data. 


## Project Description
The script is divided into three sections; preparing, analyzing, and visualizing the data. At first, the script reads a point cloud and extracts its point values (x,y,z) and colors (R,G,B). When the data frame of each room is stored, a comparison command is used in order to spot the room with the highest number of points. In order to have the same amount of points in all of the rooms’ point clouds, a padding method is implemented. Instead of downsizing the bigger point clouds, mean values are added on the smaller ones.t-distributed Stochastic Neighbor Embedding algorithm’s main parametersare the following:

* n components: The dimension of the embedded space.
* learningrate (200): The default algorithm learning rate is being used. Learn-ing rate outside the range of [10.0, 1000.0] might lead to weird, compressedrepresentation results.
* perplexity(3.0): Perplexity refers to the number of nearest neighbors that isused in order to manifold learning algorithms. Perplexity values outside therange  of  [5.0,50.0],  might  offer  significantly  different  results.  However,  the perplexity  value  in  this  research  is  3.0  due  to  the  limited  amount  of  data[32].

For  visualization  purposes  the  names  of  the  owners  of  the  rooms  are  used for labeling the data. The rooms are represented as single points. Besides the labeling, each point has a different color. The scatter-plots are both in 2D and 3D  axis.  For  a  better  understanding  of  the  results  another  set  of  2D  and  3Dscatter-plot  is  printed,  where  the  points  are  replaced  with  thumbnails  of  therooms.

A project made in collaboration with Sofia Lamda.
