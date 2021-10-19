# Cristl-Project_2
The Idea behind the project was to learn about Learn the fundamentals of machine learning and deep learning and experiment with different types of models and find the ones with the highest accuracy using IMU dataset.  

The selected Human activity recognition(HMU) dataset has 3-axis accelerometer and gyroscope data bifurcated into 10 different categories:-
Class distribution: {
	Sitting in a Chair 	-> 37,144 -> 12.55%,
	Sitting in a Couch 	-> 35,344 -> 11.94%,
	Standing  		-> 31,190 -> 10.54%,
	Lying up  		-> 32,389 -> 10.94%,
	Lying side  		-> 29,984 -> 10.13%,
	Device on surface  	-> 30,000 -> 10.13%,
	Walking  		-> 27,600 -> 9.32%,
	Running  		-> 22,792 -> 7.70%,
	Walking Upstairs  	-> 24,396 -> 8.24%,
	Walking Downstairs  	-> 25,188 -> 8.51% }
Python,Tensorflow and Tensorflow-Lite are the main tools used. Tensorflow is used for creating different Deep Learning models like LSTM,BERT,GPT-3. Tensorflow-Lite is used for executing a on-device model in order to make predictions based on input data. To perform an inference with a TensorFlow Lite model, you must run it through an interpreter. The TensorFlow Lite interpreter is designed to be lean and fast.

# Aim
This project focuses on Processing real-time sensor data and deploying it on different functionality devices like Smartphones, microcontrollers for application in autonomous vehicles and Location tracking.

# Resources
Tutorials viewed-
https://youtu.be/VFEOskzhhbc

https://youtu.be/chQNuV9B-Rw

https://youtu.be/p_tpQSY1aTs

https://youtu.be/uIcqeP7MFH0

https://youtu.be/ZnukSLKEw34

https://youtu.be/DKosV_-4pdQ

Research papers reviewed-
Human activity recognition-Kaiwalya Belsare and Gauri Rasane.

Human Daily Activity Recognition Performed Using Wearable Inertial Sensors Combined With Deep Learning Algorithms-CHIH-TA YEN , (Member, IEEE), JIA-XIAN LIAO, AND YI-KAI HUANG

Real-time sensing on android-Yin Yan, Ethan Blanton, Lukasz Ziarek

Boosting Inertial-Based HAR Model with Transformers - https://sci-hub.mksa.top/10.1109/access.2021.3070646

	
Visual representation of preprocessed data-

Accelerometer-

![image](https://user-images.githubusercontent.com/78409662/137516877-6fcec505-d18f-4616-a825-cca2fed58502.png)     
![image](https://user-images.githubusercontent.com/78409662/137517024-f9b8a7e5-71d9-4110-82ea-2ee662f3cd02.png)        
![image](https://user-images.githubusercontent.com/78409662/137517167-68443155-95c4-4653-af45-1816523d8d4b.png)


Gyroscope-

![image](https://user-images.githubusercontent.com/78409662/137517433-a9d92f18-c30f-4d2f-8dbd-bde7df42b937.png)
![image](https://user-images.githubusercontent.com/78409662/137517961-a9467ba8-4dd4-4883-9c35-839aed47570f.png)
![image](https://user-images.githubusercontent.com/78409662/137518179-31afa404-5ee7-487a-b12f-0a9caeb4c4fd.png)

