# colorTemp-Past-Codes
Some past codes for reference

# Included a matlab file that I just tested tonight (20200409).
colorTemp.mlx might only work completely on Matlab on Windows system for some reason. I tried with Mac and Mac is acting weirdly with ginput. So to make it work, please use Windows. Haven't tested for Linux but hopefully it works.
We used Matlab because we were using the output of this file for some mathematical modelling. I think Matlab would work here as well if we are doing some modelling.

# Functionality:
Input 1: a color gradient for a map (for example: colorscale.png)   
Input 2: pic for a region of interest from the same map of input 1 for which you want to form a topical temperature map with temperature labelled (for example: scotland.png) 
Output: topical temperature map with temperature labelled for the region of interest

# To run it:
Open colorTemp.mlx. 
Run it.
When the first request that asks you to open an image, open colorscale.png in the directory.
Continue running.
The second time when it asks you to open an image, open scotland.png in the directory.
Continue running.
When a picture window pops up, click on anywhere in the ocean around scotland a few times until the picture disappears.
The file will be able to generate an ocean temperature gradiant in the sea around scotland.
