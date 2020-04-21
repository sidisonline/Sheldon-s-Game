# AI-Project
This game is a little bit different version of Sheldon Cooper's Stone paper scisscor game. Here I replaced spock with thanos and lizard with snake. 

## Requirements
- Keras -> to tain the model
- Tensorflow -> for iamge processing
- OpenCV -> to use webcam

## Rules of Game
![](images/rules.png)

Scissors cuts Paper
Paper covers Rock
Rock crushes Snake
Snake poisons Thanos
Thanos smashes Scissors
Scissors decapitates Snake
Snake eats Paper
Paper disproves Thanos
Thanos vaporizes Rock
Rock crushes Scissors

## Dataset
![](images_data/thanos/1.jpg)
![](images_data/rock/1.jpg)
![](images_data/paper/1.jpg)
![](images_data/scissors/1.jpg)
![](images_data/snake/1.jpg)
![](images_data/none/1.jpg)
I created my own dataset by gathering 200 images of all gestures(
-Scissors
-Rock
-Paper 
-Thanos
-Snake
-None (for defining no movement)

## How game works
Computer selects a gesture randomly when it detects a movement and displays the results after getting to know what was human's gesture.







