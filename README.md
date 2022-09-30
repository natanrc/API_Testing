# API_Testing

Integrate API Testing code to circleCI


# Source Project :
structure file:
  - .circleci/config.yml
      Configuration file to integration Postman API with circleCI
  - Postman API Test File
  
      *) Environment setup : TechExcEnvironment.postman_environment.json
      
      *) Collection : TechExercise.postman_collection.json
      
Run POSTMAN API: 
   
         newman run "TechExercise.postman_collection.json" -e "TechExercise.postman_collection.json" -k
