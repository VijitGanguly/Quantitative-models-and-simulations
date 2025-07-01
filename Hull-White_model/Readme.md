# Hull–White Model Simulations

This folder contains simulations of the Hull–White interest rate model using two approaches:

### 📘 Additive OU Process
The short rate is modeled as the sum of multiple independent mean-reverting components, each following its own Ornstein-Uhlenbeck process. This three-factor formulation effectively represents a combination of three correlated one-factor Hull–White models, offering analytical tractability and simplicity for pricing and scenario analysis.

### 📘 Extended Hull–White Model (Drift-Based)
This version introduces auxiliary mean-reverting factors that influence the drift of the short rate through a deterministic function. Unlike the additive approach, these factors are not directly added to the rate but shape its evolution indirectly, allowing for greater flexibility in modeling yield curves and enforcing rate positivity. This model is well-suited for complex instruments and calibration tasks, though it is more computationally intensive.
