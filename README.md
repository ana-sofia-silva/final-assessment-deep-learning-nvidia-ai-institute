# final-assessment-deep-learning-nvidia-ai-institue
Final assessment for the course "Introduction to deep learning" by NVIDIA.

On this introductory course I've learned  valuable skills along the way and had a lot of fun doing it. In order to put those skills to the test I finnished the following assessment: I trained a model that is able to recognize fresh and rotten fruit. The model had a validation accuracy of `>98%`. I used some combination of transfer learning, data augmentation, and fine tuning.
## Dataset
In this exercise, I trained a model to recognize fresh and rotten fruits. The dataset comes from [Kaggle](https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification). The dataset structure is in the `data/fruits` folder. There are 6 categories of fruits: fresh apples, fresh oranges, fresh bananas, rotten apples, rotten oranges, and rotten bananas. The model required an output layer of 6 neurons to do the categorization successfully. And to compile the model I used `categorical_crossentropy`, as we have more than two categories.

