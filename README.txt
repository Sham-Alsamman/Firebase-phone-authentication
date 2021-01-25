README File

Firebase Phone Authentication using Firebase
 	use Firebase Authentication to sign up a user by sending an SMS message to the user's phone. The user signs up using a one-time code contained in the SMS message.
Features
	•	Ability send SMS, Also you can resend the code if SMS is not delivered on time.
	•	Easy to integrate
Constraint 
	The program is developed using android studio IDE and using kotlin language and the minimum SDK is 21 . 

How to execute the program
	1.	Open android studio then select File -> open and then navigate to the root directory of project.
	2.	Click 'OK' to open the project in Android Studio.
	3.	Run the application using the emulator or physical android device 
	4.	If you want to open the source code open “MainActivity.kt” file

How to use 

	Our interface consists of two parts (upper and lower ) 
	In the beginning the upper part is enabled and lower Is disabled 
	1.	Enter the user's phone Number( for testing enter “+1 6505553434”).
	2.	Click on “authenticate phone number” button .
	3.	The lower part will be enabled and the user will receive an SMS message with the verification code .
	4.	Enter the received verification code in the verification code filed (for testing enter “123456” ).
	5.	Click on “Verify code “ button .
	6.	a toast message will appear to indicate whether signup is successful or not 

Reference 
	https://firebase.google.com/docs/auth/android/phone-auth    

