#### <<<< [Before : Training](Training.md)
# Classification
### What do you need ?
 - Your filtered image (got at step 1)
 - Your model (got at step 2)

### What is settable ?
#### Class number : 
It's the class you want to get the polygons for classification.
Our method use a binary step, so today you will only get the classification for an unique class (forest for example). If you want the polygon result for another class you will need to do the step 3 again.

#### Min parcel size : 
If you consider your polygons must have a minimum size, you can set it here. For example for the forest, you usually consider that they have to be more than 0,5 hectare, so we set it by default at 0,5.  
**How we calculate it ?**   
**We simply divided the default system measure by 100**. In out training set our SRID is Lambert III (EPSG 2154) so it is in meters. So 0,5 means 0,5 hectares.

### What do you get ?
You get polygons only from the selected class.