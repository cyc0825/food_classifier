# EECS 442 Final Project: food_classifier

### Introduction
The study used a dataset of food images, which were labeled with their corresponding food types. The VGG, KNN and Inception V3 algorithms were trained on this dataset, and their performance was evaluated on a separate test set. The results of the study showed that both algorithms were able to accurately classify the food types in the dataset, with Inception V3 achieving better performance than VGG and KNN. However, all three algorithms demonstrated good performance and can be used for food type classification. Overall, this study demonstrates the potential of using VGG for food type classification, and highlights the importance of using appropriate algorithms for this task.

### Implemented Methods
- [ ] K-Nearest Neighbors (KNN): 80% write by ourselves and 20% modify from [EECS 442 Fall 2022 HW3](https://www.eecs.umich.edu/courses/eecs442-ahowens/fa22/psets/ps3.pdf)
- [x] Visual Geometry Group (We use miniVGG): Partially write by ourselves, partially modify from [EECS 442 Fall 2022 HW5](https://www.eecs.umich.edu/courses/eecs442-ahowens/fa22/psets/ps5.pdf)
- [x] InceptionV3: Based on the approach from [Maharsh's approach](https://github.com/MaharshSuryawala/Food-Image-Recognition#about-the-project)

### Expected Results
| Methods     | Accuracy |
| :------     | -------: |
| KNN         | N/A      |
| VGG         | 56%      |
| InceptionV3 | 70%      |
