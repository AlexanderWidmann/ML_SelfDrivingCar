# ML_SelfDrivingCar
This repository is for university a assignment.

## The goal of this project:
  - Learn more about machine learning
  - Experiment with parameters to get the best possible alogithm
  
## The task:
  - Using the Udacity Car simulator create a self-driving car
 
## The approach:
  - Implement a working solution to test the setup
  - Start with the Keras Sequential Model to implement a first working prototype
      + Adjust parameters to test the limits of this model
  - Try to find at least 1 different algorithm to implement based on given data
  - Try to implement a reeinforcementlearning process for the car
  - Maybe combine the approaches to see, if there are possiblities for improvement
  
  - Preprocess the input
      + This step is mostly taken to reduce processing time for the model
        Most pictures include some overhead (Ex.: Sky) or different lighting so maybe try to normalize the images
  
## The data:
  - Using the Record-function of the simulator drive 3 "clean" laps (this is an arbitrary number that i chose to keep relatively small to keep the processing time shorter)
    Try this with at least 2 different tracks and train the models accordingly (More possibilities to observe how data affects the results)
    
## The tests:
  - Use the models on the tracks where the data is from
  - Use the models on different track and observe where models fail and if there are possibilities to improve
    
## Expected results:
  - Knowledge
  - At least 2 different working models
  - Detailed analysis of the results/ the models and their parameters affect the outcome
