# ERA-V2
ERA-V2-Session6-assignment
The worksheet contains the description of how the forward and back propogation works during the training process for a simple 2 input, 2 output and 2 layer Neural network

Forward Propogation:
Step 1: Calculate the output neurons ah1 and ah2 by multiplying the input i1 and i2 with w1, w2, w3 and w4 based on the network topology.
Step 2: Compute the output of activation functions ah1, ah2
Step 3: Compute the output o1 and o2 neurons of the second layer my multiplying weights w5,w6,w7 and w9 with a_h1 and a_h2 according to network topology
Step 4: Compute the output of activation functions a_o1, a_o2 
Step 5: Compute the Errors E1 and E2
Step 6: Compute the E_total by adding E1 and E2

Back propogation:
Step 1: Develop equation for the partial derivatives for E_total with respect to weights w8, w7, w6, w5
Step 2: Develop equation for the partial derivatives for E_total with respect to weights w4, w3, w2, w1 based on the substitution method provided Panel 4 and 5
Step 3: Initialize the value η the learning rate to 0.1
Step 4: Initialize the weights from w1 to w8
Step 5: Set the t1 and t2 target values to 0.5 and 0.5
Step 6: Update the formula derived from Step 1 and step 2 and update all the values in the worksheet
Step 7: Populate the vlaues for 66 epochs by dragging
Step 8: Modify the learning rate and observe the accuracy and convdrgence changing dynamically and the observations are listed below




Backward propogation:




For Learning rate = 0.1, the network does not seem to learn, even at Epoch 66, the accuracy still at 99% 
![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/9b03c34a-bc0a-4de2-83d9-7032fa7d3aca)


For Learning rate = 0.2, there is a slight improvement but much less than needed
![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/8fa2d48b-1a5c-4414-bf95-608d153f8933)
 
For Learning rate = 0.5, there seems to be a better convergence at Epoch 66 at 99.8
 ![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/ceccb9d7-5062-40b0-b877-4dec55443932)

For Learning rate = 0.8, the accuracy seems to have acheived 99.9 % at Epoch 66

![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/7cf1d476-402f-4448-ab48-5d2902f64add)

For Learning rate = 1, the accuracy is pretty good at 100% at Epoch 61

![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/3bdf7a06-c57f-4c34-899a-cb8f7fef00b1)

Learning rate = 2, the accuracy is achieved to 100 % very fast at Epoch 31 itslef

![image](https://github.com/pravinpraba-git/ERA-V2/assets/58594804/3ac4471f-d2be-4d79-a44d-fd653fe55711)
