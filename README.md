# FaceRecognition

This project contains two apps: image comparison and face recognition. They use the following libraries: openCV and face_recognition.

**Image Comparison**

The image comparison app compares if two images are the same, displays the selected photos and also sends a validation message in the console. I created a folder named "images" from where you can make the comparisons. If you want to compare different images than those I chose you can simply change the path for the images on the 4th and on the 8th line in the image_comparison.py.

**Face Recognition**

The second file is the main_video which is the face recognition app itself. This app identifies your face by checking if a photo of you is in the "Images" folder.
After running the program the IDE will open a window in which you should see the recording captured by the camera. If the app recognizes your face, it will highlight your face with a red rectangle and on the bottom line you will see the name of the corresponding image from the "Images" folder.
If the app doesn't recognise you it will display "Unknown" instead of your name.

**Using the app**

I used [Pycharm](https://www.jetbrains.com/pycharm/) for writing these scripts and I suggest running it in the same IDE. You need to add this project into Pycharm and then you can run the main_video and image_comparison by left clicking on them and then select **run** or you can use the hotkey ```CTRL+SHIFT+F10```. If you want to close the window press ```Q```.

**Pieces of advice for a more accurate detection**

If you want accurate result with the face_recognition app you should add clear photos inside the "Images" folder. Besides this you need to stay closer to the camera in order to be detected.

**Screenshots**

*Face Recognition*
![face1](https://user-images.githubusercontent.com/100527261/158456232-d5d2a41e-431b-4fe1-8702-fb1fefb33efa.PNG)
![face2](https://user-images.githubusercontent.com/100527261/158456349-81763e4c-fe5d-42a7-97ee-b08319248a2a.PNG)

*Image Comparison*
![comparison](https://user-images.githubusercontent.com/100527261/158458444-5780eb98-e157-4f8a-81c9-3f79eff68b5d.PNG)




