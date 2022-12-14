# Binary-Classifer
***Challenge*** : For a given dataset of 1840 + 460 images of labled data of ***DAMAGED*** & ***UNDAMAGED CAR***.

I approched this as a normal Binary Classifier used 3 pair of ***CONVULUTION LAYER*** & ***MaxPooling layers***.

   - **Number of filters** : 16,32,64 are number of filters from first to last(third) pair of layer.
   - **Kernel size** : i have used 3 x 3 kernel size so no artifacts problem.
   - **pooling size** : 2 x 2 size maxpooling.

***Flatten Layer*** and then two ***dense layers*** to converge to a single output tensor.

if final tensor < 0.5 then its damaged car.
else not damaged.

after changeing different features and observing results I have reached a **accuracy** of **90%** and **validation accuracy** of **80%**.

Final model contains ***RMSprop optimizer*** and 3 paired layer network , 1 flattening layer , 1 drop and two dense layers with ***Data AUgumentation*** to stop overfitting.


# Trained model Links
Drive link for model files :  contains Complete model , just weights and Architecture
- [Final Model](https://drive.google.com/drive/folders/1LR_GIB5qMfYx2llIDBJOQ-vhVlH5Fohh?usp=sharing)
