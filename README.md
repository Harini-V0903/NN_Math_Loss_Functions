# NN_Math_Loss_Functions(NN_Math)

Introduction

A loss function measures how wrong a model’s prediction is and helps it improve during training.

Objective

Understand different loss functions
Know why and when to use them

Loss Functions

🔷 MSE (Mean Squared Error)

    What: Measures error, gives more weight to large mistakes
    
    Why: Forces model to reduce big errors
    
    Use: Regression
    
🔷 MAE (Mean Absolute Error)

      What: Measures average error equally
      
      Why: Stable and less affected by outliers
      
      Use: Regression
      
🔷 Binary Crossentropy

      What: Measures error in 2-class prediction
      
      Why: Works well with probabilities
      
      Use: Binary classification
      
🔷 Categorical Crossentropy

      What: Used for multiple classes (one-hot labels)
      
      Why: Improves correct class prediction
      
      Use: Multi-class classification
      
🔷 Sparse Categorical Crossentropy

      What: Same as above but with integer labels
      
      Why: Simpler and efficient
      
      Use: Multi-class classification
