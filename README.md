# circuit-to-controlling-servomotor-with-arduino-uno

Servomotor is dc motor with controller and some gearbox. It is very helpful to using it in the robotics prototypes.
I will discuss 2 types of using it with arduino uno:

First: connect it directly with arduino uno . You can connect it divectly on the arduino uno but olny one motor can uno run it.
![image](https://user-images.githubusercontent.com/85993776/177382479-5613fee9-d6d1-4361-b1d6-b8f8248dedd9.png)

Second: using pca9685 module access you to control multi servo motors reach to 16 motors.
![image](https://user-images.githubusercontent.com/85993776/177751835-62801ca5-3fd7-49e7-8f7d-9ce3b419d5ed.png)
(pca9685)

We connect pca9685 with arduino as follow:
![image](https://user-images.githubusercontent.com/85993776/177754773-69ddd2cc-fd22-42d1-a01b-b1cb70fc3217.png)
(we can connect other motors as first motor).

