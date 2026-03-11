1. Create a simple "Hello World" application in Android Studio. Explain the purpose of the MainActivity and the activity_main.xml file.
   
   `MainActivity.kt`
   ```kotlin
   package com.example.helloworld
   import android.os.Bundle
   import androidx.appcompat.app.AppCompatActivity
   class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    }
   } ```

   `activity_main.xml`

   ```xml
   <?xml version="1.0" encoding="utf-8"?>
   <androidx.constraintlayout.widget.ConstraintLayout 
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World"
        android:textSize="24sp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent"/>
        </androidx.constraintlayout.widget.ConstraintLayout> ```
   
3. Create a login screen with EditText fields for username and password,
and a Button to submit. Include validation for empty fields.

4. Create an android application to display Alert Dialog on pressing the
Back button.

5. Create an android application which automatically notify the user when
Aeroplane mode is turned on or off using broadcast receiver.

6. Explain the Android Activity life cycle in detail. Implement a simple app that
logs the lifecycle methods (onCreate(), onStart(), onResume(), onPause(),
onStop(), onDestroy()).

7. Insert the new contents in the following resources and demonstrate their
uses in the android application
Android Resources: (Color, Theme, String, Drawable, Dimension, Image)

8. Define the following string resources in the strings.xml file for the
registration form:
• "Full Name", "Email", "Password", "Confirm Password", and "Submit".
• Use these string resources in the corresponding TextView and Button in
your layout XML.

9. Design a form with a RadioGroup for selecting the gender
(Male/Female/Other). Include a Submit button that shows the selected gender
in a TextView.

10. Create an android application to demonstrate the use of sub menu the toast
should be appeared by selecting the sub menu item

11. Create a RelativeLayout for a profile screen with:
• A Profile Image centered at the top of the screen.
• A TextView displaying the name below the profile image, aligned to the
center.
• A Button below the name, aligned to the center.

12. Design a ListView that displays a list of items. Each item should be a
simple TextView with a string from an array of names. The list should be
populated dynamically in your Activity.

13. Create an Activity that hosts a Fragment. When a button in the Activity
is clicked, pass a string value to the Fragment and display it in a TextView.

14. Create an android application using linear layout and insert 10 animals in
the list view and display the appropriate Toast.

15. Create an android application to demonstrate the Grid view and display
the images using GridLayout.

16. Create a Registration Form with the following fields:
• Username (Text Input)
• Email Address (Text Input)
• Phone Number (Text Input)
• Password (Password Input)
Submit Button (Floating Action Button)

17. Create an app that listens for ACTION_WIFI_MODE_CHANGED
using a BroadcastReceiver. Display a Toast message whenever the Wifi
mode is turned on or off.

18. Create an android application to make use of Frame Layout –
• Display the text with name
• Set the image in the frame
• Add the image to the center.
