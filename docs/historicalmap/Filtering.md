## Input image
The image must be a geotiff (*.tif, *.tiff).

## The filters
### Closing filter
<b>Closing filter</b> performs a max then a min filter. Here you can see the differences depending on the window size : </p><table border="0" style=" margin-top:0px; margin-bottom:0px; margin-left:0px; margin-right:0px;" cellspacing="2" cellpadding="0"><tr><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/original_sample.png"/></p></td><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/grey5.png"/></p></td><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/grey11.png"/></p></td></tr><tr><td><p align="center">Original</p></td><td><p align="center">Size 5</p></td><td><p align="center">Size 11</p></td></tr></table>

### Median filter
<b>Median filter</b> is used to remove noise and it perserves edges.<br/>Here you can see the differences after using the closing filter with the same window size as the median filter :
<table border="0" style=" margin-top:0px; margin-bottom:0px; margin-left:0px; margin-right:0px;" cellspacing="2" cellpadding="0"><tr><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/original_sample.png"/></p></td><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/gm5_5.png"/></p></td><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/gm_11_11.png"/></p></td></tr><tr><td><p align="center">Original</p></td><td><p align="center">Size 5</p></td><td><p align="center">Size 11</p></td></tr></table>


### Median filter iteration
<b>Median filter iteration</b> : you can specify how many times you want the script to perform the median filter. For exempla you may want the script to do 5 times the median filter to remove more noise. Here are an example : 
<table border="0" style=" margin-top:0px; margin-bottom:0px; margin-left:0px; margin-right:0px;" cellspacing="2" cellpadding="0"><tr><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/median1.png"/></p></td><td><p><img src="https://github.com/lennepkade/HistoricalMap/raw/master/img/help/median5.png"/></p></td></tr><tr><td><p>1 iteration</p></td><td><p>5 iterations</p></td></tr></table>

#### >>>> <a href="https://github.com/lennepkade/HistoricalMap/wiki/Training">Next part : Training</a>