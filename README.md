# FaceSpace

## How does it works:

1. After installation of the application the first UI screen provides 2 buttons:  
   * Start :- This button starts the process of image capture and face detection.  
   * Enable Permission :- This button asks for the system permissions and the start button will not work until all the permissions are granted.
   
2. On pressing the “Enable Permissions” button  another window will show up  which will ask for the necessary permissions (these are need to be done only once).

3. On pressing the “Start” button new screen is shown which shows real time input from the camera.

4. In case a face is captured in the input frame of the camera a square box is formed around the face.

5.	In case multiple face are detected the screen will turn off.

## Why do we need this app:

Consider a situation  in public places  when we  are using  our mobiles and there is quite a crowd  . And in such situations sometimes we require to do use our mobiles to do some private stuff like bank transactions , send some personal messages to someone or using your login credentials to access some website or some apps etc .
In such situations we do not want others to peek in to our phones and make a note of data that we are processing.
 Another case if you are a parent/adult watching videos in your phones that contains vulgar languages or bloodshed and you do not want that your child or some other children to peek into your phones.
In such cases or any other case like this sometimes it become difficult to avoid others to peek into your phones . So keeping everything in mind we are developing an android application named “FaceSpace “ that will turn the screen off  when it detects multiple faces on the screen. It detects each face using ml kit gives it a unique id and when it detects faces with more than one id it turns the screen off using device policy manager . All this processing will go on in the background and you can use your phones in public places without any tension.
