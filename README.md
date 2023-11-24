### Medic-101 Application

The main purpose of this application is to provide a simple interface for elderly members to respond quickly when either facing a medical emergency or sustaining an injury for which the medical attention goes beyond the scope of their immediate knowledge. Medic101 combines multiple medical services into the same place for convenience and ease. The main object of this app is to be simple and easy to use, so the target audience may have less trouble navigating its functions, and their peers or doctors can track their progress through the notes modality.

The main hub of the app consists of 6 large buttons with the functions: 1) providing basic medical information, 2) a GoogleMap GPS tracker function that highlights nearby hospitals, 3) a symptoms tracker, 4) an emergency call button, 5) a camera to take pictures and document injuries, and 6) a settings function to change the user’s emergency number. 

![alt text](https://github.com/sunni426/EC327-FinalProject/blob/main/Medic101_Interface.png?raw=true)
# Components 
## 1) Symptom Notes Tracker
This feature functions like a notes application and allows the user to track any symptoms. The motivation behind creating this feature arises from realistic situations where it is not possible to go to the doctor immediately. It is also important to note that for most injuries that are not life threatening, the patient does not go to the doctor immediately or at times the doctor does not attend the patient immediately thus it becomes important to note down 
## 2) Emergency Call Button
This feature is a button that, if granted permission by user, calls an emergency contact on their phone. The user can open the settings button and change the emergency contact number that is called.
## 3) Map Services
Users can access this feature to search for nearby hospitals and find accessible route options there. First, users will be prompted to turn on their location in System Settings to enable GPS signals (location settings will pop up automatically). The GoogleMap, customized through Google Cloud Platform, will zoom in 72.5% to the user’s local area. Nearby medical centers are highlighted in red for them to quickly find best routes there. The user’s location is updated every 0.2 seconds; if the user’s location changes up to 10 meters, the map will zoom to re-center the user’s location, and markers are placed at each location change.
## 4) Basic Medical Information
	The purpose of this feature is to allow users to learn about any common household injuries that they may sustain. An important detail to note is that this feature is not for immediate danger prevention or treatment. If users are significantly hurt, they should not try to help themselves using this, and should instead call their emergency contact and or emergency services. For example, if a user has a bruise or a light burn, they would be able to peruse this section of the application to learn more about how they could prevent unnecessary pain.
## 5) Symptoms Visual Camera Feature
	The camera feature allows users to use the camera from within the Medic 101 app. The purpose of allowing users to utilize the camera from within the app would be to increase ease of access for the target audience(the elderly), especially when using a complex and disorganized structure within a phone may be too difficult for them to do. The main purpose of this feature, much like the symptom notes tracker, is to give patients the ability to track their injuries over time, and give any physicians a visual representation of the progression of the damaged area.
## 6) Settings
	This feature, like all settings within apps, allows users to change their personal information, such as their emergency contact. 

# Backend & Frontend; GUI, Processing
Android Studio was used to develop this application, using Java with SDK 32 and an emulator of Google’s Pixel 2. Android Studio is the official integrated development environment(IDE) for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. It is available for download on Windows, macOS and Linux based operating systems. Our application is interfaced on an Android mobile device. Since we used android studio, it provided us with a variety of pre-built UI components such as structured layout objects and UI controls that allowed us to build the graphical user interface for our app. We were able to make changes to an existing XML file inorder to control the user interface. We also learnt that Android applications use classes in the Java language to implement various aspects of Graphical User Interface (GUI) functionality. 

EC327 Final Project
- Project Lead
- * Eliott Dinfotan

- Spec Lead
- * Sunni Lin

- Interface Lead
- * Ismail Sufi

- Tech Lead
- * Aryan Gupta

- Docs Lead
- * Jason Calalang
