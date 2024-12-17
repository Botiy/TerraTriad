# TerraTriad
  ### Our goal is to get an offered grade (Megajánlott jegy a célunk)
  ## Group members and their neptun-codes: Fébert Tamás(UQ8MSF), Jakab Martin(FX6A7J), Horváth Botond(TRYLVW)
  We have chosen the Airbus Ship Detection challenge where, the goal is to locate ships in images, and put an aligned bounding box segment around the ships you locate. Many images do not contain ships, and those that do may contain multiple ships. Ships within and across images may differ in size (sometimes significantly) and be located in open sea, at docks, marinas, etc. 
  ### Milestone 1 - The name of the notebook, which needs running: 
  AirbusShipDetection.ipynb
  
  Authorization requires a kaggle json file - in our project this file is also present.
  
  ### Milestone 2 - The notebook, which should be run to perform the training(along with every required preparation step):
  Keras_solution.ipynb
  
  Authorization requires a kaggle json file, same as is the first milestone. 

  Environment: To run this notebook, we have used google colab environment(with the L4 GPU model) and tensorflow.keras. (the colab pro subscription is required for this operation, because there was not enough RAM and GPU initially on the free plan)
  
  We used hyperparameter-optimization to choose the best parameters for the training (to reach the highest IoU score) and trained the network with those parameters for 50 epochs with 100 step sizes. (It took approximately 4 hours on the L4 GPU.)
  
  The model has a high (0.6809) IoU score, but its f1 score is low, as it was not the objective during the optimization. We tested it on some images, where it was not predicting the ships well, but the no-ship images were correctly predicted.
  
  We did use AI sometimes (ChatGPT and the embedded Gemini in google colab), mostly to correct code parts or discover what we were doing wrong.
  
  The documentation of our project can be found in the following pdf( or between the files in this repository): [Documentation](Documentation_TerraTriad.pdf)
  The presentation version of the project is now available in the repository and also here: [Presentation](Airbus_Ship_Detection.pptx)
 
