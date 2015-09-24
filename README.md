### Manual cell counter

Plenty of automatic cell counters exist, but they aren't always reliable and often need checking, as well as failing to work on certain types of images. Hence many people simply count cells by hand. This program was motivated by trying to make *manual* cell counting as easy as possible. Using this program

- Eliminates double counting 
- Allows you to go back and review which cells were counted and which were not, to check thresholds 
- Tally 3 independent counts for multiple cell types/classes in the same image

You can save a screenshot of the image showing which cells have been marked, as well as saving a text file with the coordinates of each cell that can be loaded to modify existing counts.

The image processing toolbox is required for this program

### Usage

To use, run counter.m 

- Open a file with File -> Open image
- Select the counter by choosing one of the three coloured crosshairs
- Left click on a cell to mark it
- Right click to remove a marker
- You can only remove markers of the type currently selected e.g. To remove red markers, you need to first select the red counter
- To save a screenshot, use File -> Save image
- To save a text file with a list of points, use File -> Save points
- To resume working on an image, first open the image, then open the corresponding points file

#### Changelog

20150924 - Added 'PickableParts' fix for HG2 graphics in Matlab R2014b and newer
