# Vehicle Detection (With & Without CNN)
_Project in Progress_   
The project is meant for a Vehicle Detection system
The was sourced in the form of around 17700 images of which 50% have vehicle in them and rest 50% don't have vehicle in them.

### Data:
 - The data can be found here: https://www.kaggle.com/brsdincer/vehicle-detection-image-set
 - The data is in the form of 17k images in two separate folders
 - It was converted to csv (code for that can be found in this ![file](https://github.com/SuyashVerma2311/Vehicle_Detection/blob/605d985bd5020c260c23f12b96326a458d4890c1/Vehicle_detection/vehicle_detection_without_cnn.ipynb)
 - Dataset Sample:
 ![Dataset_grid_image](https://raw.githubusercontent.com/SuyashVerma2311/Vehicle_Detection/main/informative_stuff/dataset_grid.png)
 
 
### Model without CNN
 - Not really the best model, Obviously because 3 feed-forward layers will not work for 64x64x3 Images
 - ![Model Without CNN](https://github.com/SuyashVerma2311/Vehicle_Detection/blob/605d985bd5020c260c23f12b96326a458d4890c1/Vehicle_detection/vehicle_detection_without_cnn.ipynb) (i.e. FeedForward Neural Classifier)
 - Since this model is not the way to go...   Pre-Trained Model was not saved.
