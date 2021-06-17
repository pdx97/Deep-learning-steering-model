### Deep Learning Steering Model 
<hr>  
<p> This was one the part 3 of the projects we did to understand how driverless vehicles work </p>

<h3> Aim of the Project </h3>
<hr>  

<ul>
     <li>Prototype to run between two white lanes </li>
     <li> Predict the correct Steering angle</li>
 </ul>

<h3>Method Used</h3>
<hr>  

<ul>
     <li>Input: images labeled with steering angle</li>
     <li>Output : Predicted steering angle</li>
</ul>

<h3> Working </h3>
<hr>  
<p> We decided to do the processing and the implementation of the deep learning learning algorithms using our laptops. A laptop, in comparison to Raspberry Pi, has better processing speed and power because of better GPUs. The laptop is used to train and test our models. It is also used to control the servo motor and dc motors via Arduino Uno. The platforms used are Arduino IDE, Tensorflow and Python.The prediction of steering angles made by the model is communicated with Arduino using Serial communication.The Arduino is responsible for giving the steering angle to the servo motor.The logic in this prototype is the same as before, but the method implemented is different. In this prototype, we let the algorithm learn how to navigate its way by feeding training data to the input layer. </p>

<h3>Prototype </h3>
<img src="https://github.com/pdx97/Deep-learning-steering-model/blob/master/Images_and_Video/CNNmodel.PNG" alt="Prototype_Image">







     
