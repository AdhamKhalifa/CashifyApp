#  Cashify

# Adham Khalifa

## Intro

Cashify is an iOS application that helps the visually-impaired know the values of cash bills by taking a picture of it and speaking it out loud. The two only requirements to use the application is to disable the silent mode and give it a camera access, in case the user wants to take pictures.

The application consists of 3 screens, Main, Contacts, and About.

[Website](https://adhamkhalifa.com/cashify/)

### Main 

is where the user taps with one finger to take a picture, or with two to insert a picture from the photo library.

### Contacts
Is where the user can add and access an emergency contact to call.

### About
Is a scene with some information about the application.


## Methods:

I designed the app using Apple Xcode and Create ML. I used 1200 images for the USD bills of 1, 5, 10, 20, 50, 100, and quarter and dime. Training has achieved a validation accuracy of 95%. However, I still believe there's room for improvement.

The app takes the picture as an input from either the Camera using CameraPicker or PhotoLibrary and processes it to predict the value of the cash bill using the ML model.

Because of the case of the target user, notifications weren't an option to fulfill that notifications/menus requirement, so I went with the tab bar as an alternative for a menu since it's fixed at the bottom of the screen and easier to guide to.



## Future Work:

I'm working on the process of improving the app to include more currencies and achieve higher accuracies and publishing it.


References:

[1] https://developer.apple.com/
[2] https://www.youtube.com/watch?v=LlZUQW3Zj9c
[3] https://github.com/L4Digital/coreml-image-classification-sample
