# ASL Numbers Classifier

	A retrained Inception V3 Model that can identity numbers in American Sign Language.
    
	Data Set : (https://www.kaggle.com/ardamavi/sign-language-digits-dataset)
        
## Description  	
Using a Machine Learning Technique called transfer learning, I trained and added an additional classification layer on top of the existing Inception-V3 model from Google, which was original trained on the ImageNet database. This gives the model the ability to classify digits in American Sign Language.

## Stretch Goals
In the future, I want to use this model to create a program that can output numbers from a person signing to a webcam. Then if i can find a large enough database of visuals to train the model on all of ASL, i want to create an ASL to text translator program, that takes video from the webcam as input and translates it to English.