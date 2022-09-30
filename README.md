# Android Development Resources


## <a name="table-of-contents"></a>Table of Contents

- [Android Development with Jetpack Compose](#android-development-with-jetpack-compose)
  -  [Topics](#android-development-with-jetpack-compose-topics)
  -  [Resources](#android-development-with-jetpack-compose-resources)
- [Android Development with View Based](#android-development-with-view-based)
  -  [Topics](#android-development-with-view-based-topics)
  -  [Resources](#android-development-with-view-based-resources)
- [Others/Good to Know Resources](#others-good-to-know)
- [Legacy Android Development using Java](#android-development-using-java)
  -  [Resources](#legacy-android-development-using-java)

## <a name="android-development-with-jetpack-compose"></a>Android Development with Jetpack Compose <sup>[Back ⇈](#table-of-contents)</sup>

Jetpack Compose is Android’s modern toolkit for building native UI. It simplifies and accelerates UI development on Android. Quickly bring your app to life with less code, powerful tools, and intuitive Kotlin APIs.

#### <a name="android-development-with-jetpack-compose-topics"></a>Topics <sup>[Back ⇈](#table-of-contents)</sup>
- Prerequisites
  - Programming Language
  -	IDE
-	Basics
    -	Hello World App
    -	Layouts
        -	LazyRows/Rows
        -	LazyColumns/Columns
        -	Box, etc
    -	App Interactions
    -	User Input/Output
    - State
    - Side Effects
      - LaunchEffect
      - SideEffects
      - DisposableEffect
    -	App Navigation using Compose Navigation
    -	Activity/Fragment Lifecycle
    -	App Architecture – MVVM pattern
    -	Networking using Retrofit
    -	Display images using Glide/Coil
    -	Data Persistence 
      -	DataStore/Shared Preferences
      -	SQLite DB (using Room)
    - Debugging
      -	Using log statements
      - Using Debugger
- Intermediate
  -	Material Design Components
  -	Notifications
  -	Services
  -	Permissions
  -	Work Manager
  -	Custom Views
  -	Animations
  -	Maps
  -	Testing
  
  ### <a name="android-development-with-jetpack-compose-resources"></a>Resources <sup>[Back ⇈](#table-of-contents)</sup>
  - Kotlin
    -	Video
        -	Udacity - https://learn.udacity.com/courses/ud9011
        -	Simplified Coding
            - Basics - https://www.youtube.com/playlist?list=PLk7v1Z2rk4hgD4teEDp2cMntnH3sR4D3D
            - OOPS - https://www.youtube.com/playlist?list=PLk7v1Z2rk4hjgFKGBxDkb0f09ugBC0xOL
        -	Official Docs - https://kotlinlang.org/docs/basic-syntax.html
        -	Learning Material by JetBrains - https://kotlinlang.org/docs/learning-materials-overview.html
        -	Java to Kotlin - https://github.com/MindorksOpenSource/from-java-to-kotlin
    -	Java to Kotlin using IDE (1-to-1 conversion)
      -	Create a Java file and write the code in Java.
      -	Press Ctrl + Alt + Shift + K or Code > Convert Java file to Kotlin File -Android Development
- Android
  - Android Basics with Compose by Google - https://developer.android.com/courses/android-basics-compose/course
  - Jetpack Compose for Android Developers for Experienced Developers by Google - https://developer.android.com/courses/jetpack-compose/course
  - Youtube
    - Stevdza San - https://www.youtube.com/c/StevdzaSan
    -	Simplified Coding (Belal Khan GDE Android)- https://www.youtube.com/c/SimplifiedcodingNetOfficial/featured
    -	Coding In Flow - https://www.youtube.com/c/CodinginFlow
    -	Coding With Mitch - https://www.youtube.com/c/CodingWithMitch/featured
    -	Philip Lackner (Good for Jetpack Compose content only and learn with caution) - https://www.youtube.com/c/PhilippLackner/featured
  - Github
    - Jetpack Compose is Awesome - https://github.com/jetpack-compose/jetpack-compose-awesome
    - Sample Apps by Google - https://github.com/android/compose-samples#jetpack-compose-samples-Video
  
## <a name="android-development-with-view-based"></a>Android Development with View Based <sup>[Back ⇈](#table-of-contents)</sup>

### <a name="android-development-with-view-based-topics"></a>Topics <sup>[Back ⇈](#table-of-contents)</sup>
- Prerequisites
  - Programming Language
  -	IDE
-	Basics
    -	Hello World App
    -	Layouts
        -	Linear Layout
        -	Relative Layout
        -	Constraint Layout
    -	View and Data Binding
    -	App Interactions
      -	Use of OnClickListeners and OnLongClickListeners
    -	User Input/Output
    - State
    - Side Effects
      - LaunchEffect
      - SideEffects
      - DisposableEffect
    -	App Navigation using Navigation Components
    -	Activity/Fragment Lifecycle
    -	App Architecture – MVVM pattern
    -	RecyclerView (Single and Multiple View Types)
    -	Networking using Retrofit
    -	Display images using Glide
      -	Data Persistence 
        -	DataStore
        -	SQLite DB (using Room)
    - Debugging
      -	Using log statements
      - Using Debugger
- Intermediate
  -	Material Design Components
  -	Notifications
  -	Services
  -	Permissions
  -	Work Manager
  -	Custom Views
  -	Animations
  -	Maps
  -	Testing

### <a name="android-development-with-view-based-resources"></a>Resources <sup>[Back ⇈](#table-of-contents)</sup>

- Kotlin (Same as above)
  -	Video
      -	Udacity - https://learn.udacity.com/courses/ud9011
      -	Simplified Coding 
        - Basics - https://www.youtube.com/playlist?list=PLk7v1Z2rk4hgD4teEDp2cMntnH3sR4D3D
        - OOPS - https://www.youtube.com/playlist?list=PLk7v1Z2rk4hjgFKGBxDkb0f09ugBC0xOL
      -	Official Docs - https://kotlinlang.org/docs/basic-syntax.html
      -	Learning Material by JetBrains - https://kotlinlang.org/docs/learning-materials-overview.html
      -	Java to Kotlin - https://github.com/MindorksOpenSource/from-java-to-kotlin
  -	Java to Kotlin using IDE (1-to-1 conversion)
    -	Create a Java file and write the code in Java.
    -	Press Ctrl + Alt + Shift + K or Code > Convert Java file to Kotlin File -Android Development
- Android
  -	Video based
    -	Udacity (Google)-Basics - https://learn.udacity.com/courses/ud9012-Advance - https://learn.udacity.com/courses/ud940
    - Google's MAD playlist - https://www.youtube.com/playlist?list=PLWz5rJ2EKKc91i2QT8qfrfKgLNlJiG1z7
    -	Simplified Coding (Belal Khan GDE Android)- https://www.youtube.com/c/SimplifiedcodingNetOfficial/featured
    -	Coding In Flow - https://www.youtube.com/c/CodinginFlow
    -	Coding With Mitch - https://www.youtube.com/c/CodingWithMitch/featured
    -	Google Android - https://www.youtube.com/playlist?list=PLlyCyjh2pUe9wv-hU4my-Nen_SvXIzxGB
  -	Text based
    -	Android Basics in Kotlin - https://developer.android.com/courses/android-basics-kotlin/course-List of all training material by Android Team (Very useful for both novice and experienced learners) - https://developer.android.com/courses

### <a name="others-good-to-know"></a>Others/Good to know <sup>[Back ⇈](#table-of-contents)</sup>
- Official Android Channel - https://www.youtube.com/c/AndroidDevelopers-Live stream/Twitch
-	Adam McNeilly (GDE Android) - https://www.youtube.com/c/AdamMcNeilly
-	Coding with Italians - https://www.youtube.com/c/CodewiththeItalians

### <a name="android-development-using-java"></a>Legacy Android Development using Java <sup>[Back ⇈](#table-of-contents)</sup>
### <a name="legacy-android-development-using-java"></a>Resources <sup>[Back ⇈](#table-of-contents)</sup>
- Udacity (Google)
  -	Basics - https://www.udacity.com/course/new-android-fundamentals--ud851
  -	Advance - https://learn.udacity.com/courses/ud855

**NOTE-** Please note that you can find a codelab for each of the lesson in the above two courses - https://codelabs.developers.google.com/?product=android 
