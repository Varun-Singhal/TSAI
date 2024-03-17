## Step wise recreation of calculation
1. As we understood the network, which has  weights, 2 inputs, 1 output, 2 hidden layers with 2 neurons each. We are using sigmoid activation in this usecase. 
2. We are given with initial weights, inputs and the expected outputs. We can simply specify those values in the respective columns. 
3. Next step would be calculating the values in first iteration, with simple mathematical equations. We can easily set the formula for y=mx and 1/1+(e^-x) so that we get the calculations for forward inference. For the loss, we are using loss = ((actual value - predicted value)^2)/2. And the sum of loss at both outputs is equal to the total loss. 
4. In the session we have understood and derived the partial differentiation equations for each weight. We have partially differentiated the total loss wrt each weight. 
5. We can easiy set the formula in the sheet and automate the calculation of derivatives based on other column values. 
6. After we are good with first iteration, we just need to drag those formula to other rows and are ready with the loss graph.

## Snapshot the the sheet

![Sheet Snap](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/Capture.PNG)

## Following are the Loss Graphs at various learning rates

#### Loss Graph with 0.1 learning rate
![LR 0.1 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/point1.PNG)

#### Loss Graph with 0.2 learning rate
![LR 0.2 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/point2.PNG)

#### Loss Graph with 0.5 learning rate
![LR 0.5 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/point5.PNG)

#### Loss Graph with 0.8 learning rate
![LR 0.8 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/point8.png)

#### Loss Graph with 1.0 learning rate
![LR 1.0 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/1.PNG)

#### Loss Graph with 2.0 learning rate
![LR 2.0 Loss](https://raw.githubusercontent.com/Varun-Singhal/TSAI/master/Session6/PartA/2.PNG)

