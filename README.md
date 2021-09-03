# Compact-VG: A subset of Visual Genome

A subset of Visual Genome for object detection, and attribute - relation prediction. Randomly collected 6000 images are used to create this dataset. It contains 200 object categories, 10 predicates and 16 attributes. 

## Obj_ID.txt

List of 6000 image IDs randomly selected from Visual Genome.

## Object classes.txt

Most common 200 object categories. Each line corresponds to ImageID, x-coordinate, y-coordinate, width, height, and object class.

## Attributes.txt

16 frequent attributes of objects in the image set. Each line corresponds to ImageID, x-coordinate, y-coordinate, width, height, and attribute class.  

## Relations.txt

10 frequent predicates between subject and object. Each line corresponds to ImageID, x-coordinate (s), y-coordinate (s), width (s), height (s), x-coordinate (o), y-coordinate (o), width (o), height (o) and predicate class. 
