## Business Case

## Feature Engineering Approaches

## Permutation Importance plot
![permutation](https://github.com/zal-developer/Intermediate-ML/assets/119515838/b63d75e8-e67c-4f67-97f0-8539944b9f91)

## Selected feature visuals

#### Visual 1
![age bins](https://github.com/zal-developer/Intermediate-ML/assets/119515838/fa3d376a-3546-4942-a737-a4342ffa317b)
-  The age groups of 20-40 have the highest number of people who donot have metabolic syndrome while the age groups of 60-80 have the highest number of people who have metabolic syndrome.
  
#### Visual 2
![tets](https://github.com/zal-developer/Intermediate-ML/assets/119515838/84119669-0a8a-4d3b-8266-c596810f28db)
-  People with low levels of Triglycerides seem to be more associated with high levels of negative metabolic syndrome status.
## Neural Network

#### Summary

Model: "sequential_3"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_5 (Dense)             (None, 5)                 10        
                                                                 
 dense_6 (Dense)             (None, 1)                 6         
                                                                 
=================================================================
Total params: 16 (64.00 Byte)
Trainable params: 16 (64.00 Byte)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________

### Training Metrics

               precision    recall  f1-score   support

           0       0.63      1.00      0.77       316
           1       0.00      0.00      0.00       187

    accuracy                           0.63       503
   macro avg       0.31      0.50      0.39       503
weighted avg       0.39      0.63      0.48       503

### Final evaluation metrics

'loss': 0.6425641179084778,
 'accuracy': 0.628230631351471,
 'recall': 0.0,
 'precision': 0.0
