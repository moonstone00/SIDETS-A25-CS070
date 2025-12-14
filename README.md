# SIDETS-A25-CS070
Documentation and supporting assets for project review and submission purposes.

![alt_text](https://github.com/moonstone00/SIDETS-A25-CS070/blob/main/assets/logo-sdts.png?raw=true)

# **SIDETS : Smart Deposit Targeting System** 

#### Use this website to avoid calling customers carelessly.

This repository is the Capstone Project in [Asah Dicoding](https://www.dicoding.com/asah) 2025. This application helps sales to avoid contacting random customers and contact customers whoe are likely to take desposits.  

## Our Team
| Name                            | Bangkit-ID    | Path                     |
| -------------                   | ------------- | ------------------------ |
| Andreas Rameladi                | M891D5Y0219   | Machine Learning         |
| Fauzi Hendrawan                 | M891D5Y0622   | Machine Learning         |
| Muhammad Helmi Arrizal          | R891D5Y1289   | React & Back-End with AI |
| Muhammad Ghifani Ikhsan         | R891D5Y1279   | React & Back-End with AI |
| Wahyu Hidayat                   | R891D5Y1949   | React & Back-End with AI |

## Usage
### How to use this website:
  #### Sales:
  - Open a browser and type localhost:5173.
  - On the login screen, enter your NIP (nomor induk pegawai) and password.
  - If you don't have an account then you can't log in
  - There is no registration here because, only sales people who work at the bank.
  - After logging in, you can check the table to cantact customers.
  - Click the number to make contact.
  #### Admin:
  - Admin can register sales data via Swagger.
  - Open a browser and type http://localhost:5000/api-docs/#/
  - In the admin role there is an additional page, namely predict-nasabah.
  - 
  - The app may prompt you to provide images for a more accurate diagnosis. You can choose to either:
    - Pick from __Camera__: Use your device’s camera to take a new photo.
        - Tap on "Camera."
        - Capture the image.
        - Crop the photo if it meets the requirements.
    - Pick from __Gallery__: Select an existing photo from your device’s gallery.
        - Tap on "Gallery."
        - Browse through your photos and select the appropriate image
        - Crop the photo if it meets the requirements. 
  - Click __Mulai Diagnosa__
  - If the analysis is successful, you will be taken to a result page.

### How to see the predict history
  - Open App
  - If you are not __logged in__, you will see the login screen:
    - Enter your email and password. 
    - If you do not have an account, tap on "Daftar Disini" and follow the prompts to register. 
    - Once you have entered your credentials, tap "Masuk"
  - If you are already __logged in__, you will be taken directly to the main screen of the app.
  - Click __History__ on Bottom Navigation.
  - That'll be show the history what you've predicted before.

## About
- Predicts customers who are likely to subscribe to deposit products using Machine Learning
- Helps the sales team prioritize customers for calls and follow-up actions
- Presents data visualizations in the form of charts and tables
- Provides an interactive dashboard to monitor prediction results and statistics
  
## 📸 Screenshots
||||
|:----------------------------------------:|:-----------------------------------------:|:-----------------------------------------: |
| ![](../splash.png) | ![](../onboarding.png) | ![](../login.png) |
| ![](../home.png) | ![](../diagnose.png) | ![](../result.png) |

## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously.
- [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) -  oOservable data holder class.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
    - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes.
    - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
    - [Data Store](https://developer.android.com/topic/libraries/architecture/datastore) - Data storage solution that allows you to store key-value pairs or typed objects with protocol buffers.
- [Dependency Injection](https://developer.android.com/training/dependency-injection) - A technique widely used in programming and well suited to Android development.
- [Retrofit](https://square.github.io/retrofit/) - A type-safe HTTP client for Android and Java.
- [GSON](https://github.com/google/gson) - A modern JSON library for Kotlin and Java.
- [GSON Converter](https://github.com/square/retrofit/tree/master/retrofit-converters/gson) - A Converter which uses GSON for serialization to and from JSON.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
- [Splash API Android](https://developer.android.com/develop/ui/views/launch/splash-screen) - The elements of the splash screen are defined by XML resource files in the Android manifest file. 
- [uCrop](https://github.com/Yalantis/uCrop) - Provide an ultimate and flexible image cropping experience.
- [CameraX](https://developer.android.com/jetpack/androidx/releases/camera) - An addition to Jetpack that makes it easier to add camera capabilities to your app.

## Contact
Visit:
- [fathanmaulgit's](https://github.com/fathanmaul)
- [rubenalexanderrr git's](https://github.com/rubenalexanderrr)
