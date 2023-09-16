# Pass-Data-From-One-Activity-to-Another-Android-Studio-Kotlin

https://github.com/SyedRaihanuzzaman/Pass-Data-From-One-Activity-to-Another-Android-Studio-Kotlin/assets/142418984/6b4a3bd9-69cd-402d-a6d8-7cbd3fed34c8

Android Pass Data Project
This project demonstrates how to pass data from one activity to another in Android.

Getting Started
Clone the repository to your local machine.
Open the project in Android Studio.
Run the project on an Android device or emulator.
How It Works
The project has two activities:

The MainActivity is the starting activity. It has a button that, when clicked, opens the SecondActivity.
The SecondActivity displays the data that was passed from the MainActivity.
The data is passed using the Intent object. The Intent object is used to start an activity and can also be used to pass data between activities.

In this project, the data is passed by calling the putExtra() method on the Intent object. The putExtra() method takes two arguments: the name of the key and the value of the key.

The key is a string that is used to identify the data. The value can be any type of data, such as a string, an integer, or an object.

In this project, the key is data and the value is a string.

When the MainActivity is clicked, it creates an Intent object and calls the putExtra() method to pass the data to the SecondActivity.

The SecondActivity receives the data in the onCreate() method. The onCreate() method is called when the activity is created.

To receive the data, the SecondActivity calls the getIntent() method. The getIntent() method returns the Intent object that was used to start the activity.

The SecondActivity can then access the data by calling the getStringExtra() method. The getStringExtra() method takes the name of the key as an argument and returns the value of the key.

In this project, the SecondActivity calls the getStringExtra() method to get the value of the data key.

Author
This project was created by [Syed Raihanuzzaman].
