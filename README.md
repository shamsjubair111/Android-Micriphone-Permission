# Android-Micriphone-Permission

Step 1: Add Permission in AndroidManifest.xml
Open your AndroidManifest.xml file and add the following permission inside the <manifest> tag:

Step 2: Request Runtime Permission in Your Activity
In your main activity, you'll need to check and request permission for using the microphone.

Check if the permission is granted.
If not, request the permission.


Add the following import statement at the top of your MainActivity.java file:

Copy code
import android.Manifest;

Make sure to declare MICROPHONE_PERMISSION_CODE at the beginning of the MainActivity class.
