## Changes made in this version

The initialisation was changed to Kaiming. 

## Parameters and Numerical Outputs: 
* Action frequency : {0: 663379, 1: 353460, 2: 205289, 3: 228191}

* Epochs : 100000

* Max Time Steps : 400

* Epsilon decay : 0.0001/100 

* Reward distribution : {1: 94683, 3: 261, 2: 5037, 4: 16, 5: 2}

* Grid dimensions : 17,17

* No. of fruits : 1

## Local Observations : 

* The 0th action was really favoured as compared to others. Need to maybe look into it? 

## Proposed Changes to be made for the next version

* The epsilon decay factor can be worked on. 
```
eps = max(eps_end, eps_decay*eps)
```

* Looking at simpler models for the snakes for smaller grid worlds?

* Reward structure also needs to be tuned. 

* The environment also needs to be improved and tuned for better multi agent play

* Simplifying the network as well