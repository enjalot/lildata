lil' data
=======

This tool is designed for people who work with many different data sets and are looking for an
easier way to get familiar with the dataset in front of them. 
There is only one constraint going in to the design of lil data, 
that no data going into it can have more than __100 data points__.  

lil data is a tool for exploring and getting comfortable with a dataset.
It provides many default perspectives one looks for when they first get that CSV or JSON file.


# Visualizations

* Heatmap  
  * by type
  * ![chart](/img/heatmap.jpg?raw=true)
* Distributions  
  * with only 100 items, we have quite a few pixels we can use for every object
  * easily sort each or all columns
* Parallel coordinates
  * data of this structure fits nicely into a prallel coordinates chart
  * ![chart](/img/par-coords.jpg?raw=true)
  
# Types and Schemas

Automatically determine and count the type of every data point as a 
![String](/img/types/string.jpg?raw=true),
![Int](/img/types/int.jpg?raw=true), 
![Float](/img/types/float.jpg?raw=true), 
![Boolean](/img/types/boolean.jpg?raw=true) or 
![Date](/img/types/date.jpg?raw=true).  

Each type has a color associated with it (and can be easily changed).  

JSON data is expected as an array of objects with attributes that are of the afformentioned types.  
a CSV file will be converted in to a JSON array of objects with the those types.  

The assumption that data comes in a flat format is a temporary restriction to get things underway.

# Edit

Quickly modify fields in a table format  
[edit](/img/edit.jpg?raw=true)

# Pipe

lil data is written such that the __100 data points__ can be piped in and out of it.
Being modular allows other programs to either prepare date for lil data or use it's output.  
[pipe](/img/pipe.jpg?raw=true)


## Sketches

Until the code is actually written, sketching things here:  
[Heatmap](http://tributary.io/inlet/5925299) - [Heatmap 2](http://tributary.io/inlet/5926143)
