# TerraTriad
  ## Group members and their neptun-codes: Fébert Tamás(UQ8MSF), Jakab Martin(FX6A7J), Horváth Botond(TRYLVW)
  In our task, the goal is to locate ships in images, and put an aligned bounding box segment around the ships you locate. Many images do not contain ships, and those that do may contain multiple ships. Ships within and across images may differ in size (sometimes significantly) and be located in open sea, at docks, marinas, etc. 
  ### Milestone 1 - The name of the file, which you have to run: 
  AirbusShipDetection.ipynb
  
  Authorization requires a kaggle json file - in our project this file is also present.

  ### Milestone 2 - The EfficientLoading.ipynb contains the splitting, balancing and loading of the dataset. It uses an ImageDataGenerator for augmenting the images. 
  ### The Model.ipynb is the notebook, which contains our initial model, implementing a U-net architecture. 
  ### To evaluate the results with different metrics the Evaluation.ipynb should be ran.
  - The `Evaluation.ipynb` notebook now exclusively contains evaluation functions along with a test for these functions. These functions will be integrated into the final model and will utilize the model's output to calculate the scores.
  ### The Keras_solution.ipynb contains the training and the corrected U-net architecture along with the evaluation metrics.
  - For now it was trained for 5 epochs only, to generate weights and a keras model, but we will make a longer and more precize training.
