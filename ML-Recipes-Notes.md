# episode 3
1. Some features are useless (50:50)

# episode 4
Something about Pipeline
1. spam classifier
  - x-feature (input)
  - y-label(outputf(x))
  -check accuracy:
    -toolkit from sklearn
     `from sklearn.metrics import accuracy_score
     print accuracy_score(y_test, predictions)`
2. learn a function
  - model (a prototype for our algorithm)
  - use training data to adjust params of our model
  - tool tensorflow playground
  
# episode 5
-scratchy version of KNearestNeighbors
-the following is just a random algo
`def fit (self, X_train, y_train):
    pass`
`def predict(self, X_test):
    predictions=[]
    for row in X_test:
      label = random.choice(self.y_train)
      predictions.append(label)
    return predictions #predictions is a 2-d array, or a list of lists
`
-the following is the KN algo step-by-step (mostly)
  1. find the distance (Euclidean Distance)
    dist = sqrt((y2-y1)**2 + (x2-x1)**2 + ... +(n2-n1)**2) #the ultimate formula
    `from scipy.spatial import distance
    def euc(a,b): #a is the training data, b is the testing data
      return distance.euclidean(a,b) #returns the distance between a and b`
  2. con:
      slow
      hard to represent relationships between features.
      
# episode 6
train an image classifier using **TensorFlow for Poets**
1. training data: individual dirs for different types of flowers
2. Deep Learning
    no need of extracting features. Examining pixels instead
    *neuralnetwork*
3. learn tensorflow (**TF Learn**)
  **inception** one of Google's best image classifier
  then use the **retraining (Transfer Learning)** process to save time and leverage prior work
  
4. training data:
    - diversity 
    - quantity
  



    
    
    






