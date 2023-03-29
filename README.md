# MT1004-Linear Algera Height-Prediction-For-Projectile-Motion-Simulation
![ezgif-4-fdc4c6088561](https://user-images.githubusercontent.com/84980384/143990691-ea896efc-3b30-462b-b21d-d88debb16e2a.gif)

# Project Demo
[​Video​](https://mohsinalimirxa.wixsite.com/experience/projectilemotion)

# Description
We created a model that predicts the height of a ball based on the velocity input provided by the user. We tested this model extensively using Polynomial Regression to ensure its accuracy and reliability. To make it more fun, we developed a simulation of this model in a popular sports game called Cricket.

The simulation works by taking velocity as input and predicting the height using a simple formula that we derived by equating Potential Energy and Kinetic Energy. The formula is easy to understand:

height = (1/(2 * g)) * velocity^2

In this formula, "g" represents the acceleration due to gravity. We used this formula to predict the height of a cricket ball after it has been hit. We hope that our simulation helps you understand how these concepts can be applied in real-world scenarios. Have fun playing the game!
# Getting Sarted
## Dependencies ##
* Windows 10/Mac OS/Linux.

## Installing ##
* Made in Octave.
* Made in C#.
* Need all files in LA project for implementing in octave.
* Need all files in gamefiles for running the cricket game.
## Exexuting program ##
* Once all files are download, just compile and run the program.
## Octave ##
### Files  ###
The file 'grp - Copy.dat' contains the dataset.

![Screenshot 2021-11-27 122447](https://user-images.githubusercontent.com/84980384/143986600-ae1980ec-9871-475a-a461-83f3705bef0d.png)

 File 'theta.dat' contain values of weights of thetas for model.
![Screenshot 2021-11-30 093940](https://user-images.githubusercontent.com/84980384/143986649-9405f76f-cb7c-4351-be72-3f13164b7b01.png)

### Code ###
The code contains

![Screenshot 2021-11-30 094202](https://user-images.githubusercontent.com/84980384/143986912-e24fa362-7d79-47b7-9aa0-398f8174541e.png)

![Screenshot 2021-11-30 094228](https://user-images.githubusercontent.com/84980384/143986883-dd6a008c-f9ba-4c11-8569-2f99bedb8f23.png)

### Accuracy  ###
*  Formula vs trained data\.
We used "height formula" as mentioned earlier in the description to summarize the results between the Trained Data and the Data accurately retrieved from the Formula. The derivation comes from the fact that Kinetic energy equals to the Potential Energy.

![WhatsApp Image 2021-11-28 at 8 38 09 AM](https://user-images.githubusercontent.com/84980384/143987336-2de1d1ba-f633-473b-a782-fca98fb4b03f.jpeg)
*  Formula vs Given dataset\.

![WhatsApp Image 2021-11-28 at 8 38 26 AM (1)](https://user-images.githubusercontent.com/84980384/143987513-f8a052df-ef00-49ab-8363-b838395372a8.jpeg)

* Dataset vs Trained data\

![WhatsApp Image 2021-11-28 at 8 37 54 AM](https://user-images.githubusercontent.com/84980384/143987602-6abf23de-2cb5-4380-8f46-ccb439a48992.jpeg)
## Known Issues ##
* The model must contain more dataset values.
* We chose to ignore drag and frictional force. 
## Game ##
The game ask you to enter velocty and it shows predicted vs original height on that value of velocty.

![image](https://user-images.githubusercontent.com/84980384/143987941-629857a5-7ec4-49c6-ae26-094f0f5eed58.png)

![Screenshot 2021-11-30 095322](https://user-images.githubusercontent.com/84980384/143987836-9fd84d60-ee8f-4834-ae10-87ffd6467d08.png)
# Authors
1. Ahmed Aleem\
   ahmadaleem13@gmail.com\
   [​LinkedIn​](https://www.linkedin.com/in/ahmad-aleem-45a2251bb/)
2. Mohsin Ali Mirza\
   Mohsinalimirxa@gmail.com\
   [​LinkedIn​](https://www.linkedin.com/in/mohsin-ali-mirza-63878620a/)
 3. ​Waleed Gul<br> 
 ​hwaleed0035@gmail.com<br> 
 ​[​LinkedIn​](https://www.linkedin.com/in/mohsin-ali-mirza-63878620a)
