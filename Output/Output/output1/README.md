## Problems resolved :

* Solved the epsilon sampling issue
* Solved the model issue in terms on convnet layers. Converted to standalone units for conv layers and pooling layers.
* Used Xavier initialisation for the conv and output layers. We could move to more uniform approach for all layers, rather than having different for two different parts.
* Resolved the lack of difference in values of the element units by contrasting the unit block values


## Parameters and Numerical Outputs: 
* Action frequency : {0: 7854, 1: 9391, 2: 32859, 3: 8027}

* Epochs : 10000

* Max Time Steps : 400

* Epsilon decay : 0.01/100 

* Reward distribution : {2: 1153, 1: 8671, 3: 146, 4: 27, 6: 1, 5: 1}

* Grid dimensions : 10,10

* No. of fruits : 2

## Local Observations : 

* The distribution of actions can be better, by decreasing the epsilon decay. 

