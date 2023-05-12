#### <<<<a href="https://team-si-sig.github.io/documentation/historicalmap/en/Filtering">Before : Filtering your image</a>

## What do you need for the training ?
You just need two things :
- The **filtered image** got from the previous step
- The **training shapefile** :
You need to have a column (by default we call it 'Class') where you put the ID (and not the name) of your classification (1 for forest, 2 for water...).  
For example, if you have the forest to classify, you can draw some polygons of your forest, some polygons and fields, some of waters...  
**:warning: Think to use the same projection as your filtered image.**


## Can you explain what are classifiers, seed, split... ?
Of course ! All these parameters are adjustable and you can set them.

### Classifiers
Let's begin with the classifiers. First, GMM,KNN,RF, or SVM are acronyms, but also algorithms. These are different ways to learn and to guess in what class will be classified the pixel.

**If you don't have scikit-learn installed on your computer (aka sklearn, it's a library), you can only use GMM.**

- GMM : Gaussian Mixture Model
- KNN : K-Nearest Neighbors 
- RF : Random-Forest
- SVM : Support Vector Machine

### Split
Split is the amount of parcel used for the training. If you choose 0,5 it means and 50% of the parcel is used for training and 50% for the confusion matrix. **If split if 1 you won't have a confusion matrix.**

### Seed
The seed is used to compare the same parcel each time, so you can put the number you want in it and use it the next time if you want to compare the data.

#### >>><a href="https://team-si-sig.github.io/documentation/historicalmap/en/Classification">After : Classification</a>