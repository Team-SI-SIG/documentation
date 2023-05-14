## Input image
The image must be a geotiff (*.tif, *.tiff).

## The filters
### Closing filter
**Closing filter** performs a max then a min filter. Here you can see the differences depending on the window size :

||||
|:-:|:-:|:-:|
| ![original][1] | ![size 5][2] | ![size 11][3] |
| Original | Size 5 | Size 11 |

### Median filter
**Median filter** is used to remove noise and it perserves edges.<br/>Here you can see the differences after using the closing filter with the same window size as the median filter :

||||
|:-:|:-:|:-:|
| ![original][1] | ![size 5][4] | ![size 11][5] |
| Original | Size 5 | Size 11 |

### Median filter iteration
**Median filter iteration** : you can specify how many times you want the script to perform the median filter. For exempla you may want the script to do 5 times the median filter to remove more noise. Here are an example : 

|||
|:-|:-|
| ![1 iteration][6] | ![5 iterations][7] |
| 1 iteration | 5 iterations |

#### >>>> [Next part : Training](Training.md)


  [1]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/original_sample.png
  [2]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/grey5.png
  [3]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/grey11.png
  [4]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/gm5_5.png
  [5]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/gm_11_11.png
  [6]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/median1.png
  [7]: https://github.com/Team-SI-SIG/HistoricalMap/raw/master/img/help/median5.png
