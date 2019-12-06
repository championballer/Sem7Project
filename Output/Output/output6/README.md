## Changes made in this version

Network simplified. 2 fully connected layers with 512 and 256 units were removed. Conv layers are still at the same config.
Epsilon decay format was used.

## Parameters and Numerical Outputs: 
* Action frequency : {0: 287983, 1: 241773, 2: 684272, 3: 242806}

* Epochs : 100000

* Max Time Steps : 400

* Epsilon decay : 0.999(decay rate) per 100 episodes

* Reward distribution : {1: 94609, 2: 5122, 3: 258, 4: 10}

* Grid dimensions : 17,17

* No. of fruits : 1

## Local Observations : 

* Again action was overused, simply means that the agent wasn't able to learn completely, as in it didn't get a chance to explore more.


## Proposed Changes to be made for the next version

* The epsilon changed back to what it was before

* Using elu instead of relu