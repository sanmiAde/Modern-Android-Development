# Modern Android Development

- **Gradle**
    - [Kotlin DSL](https://docs.gradle.org/current/userguide/kotlin_dsl.html)
    - [Gradle Versions Plugin](https://github.com/ben-manes/gradle-versions-plugin)
- **Build Variants**
    - [Build Types](https://developer.android.com/studio/build/build-variants#product-flavors)
    - [Product Flavors](https://developer.android.com/studio/build/build-variants#product-flavors)
- **Code Style**
    - [detekt](https://github.com/detekt/detekt)
    - [ktlint](https://github.com/pinterest/ktlint) / [Ktlint Gradle](https://github.com/JLLeitschuh/ktlint-gradle)
    - [Spotless](https://github.com/diffplug/spotless)
    - [Lint Checks](https://developer.android.com/studio/write/lint)
    - [Git Hooks](https://githooks.com/)
- **Documentation**
    - [KDoc](https://kotlinlang.org/docs/reference/kotlin-doc.html)
    - [dokka](https://github.com/Kotlin/dokka)
- **Architecture**
    - **Application Architecture**
        - [Jetpack Guide](https://developer.android.com/jetpack/docs/guide)
        - [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
    - **Module Architecture**
        - Single Module
        - Multi Module
            - Layer Modules
            - (Dynamic) Feature Modules
            - Utility Modules
    - **Presentation Architecture**
        - MVP
        - MVVM
        - MVI
    - **Navigation Architecture**
        - Single Activity
        - Flow Based Activities
- **Design**
    - **Layout Design**
        - [Use ConstraintLayout](https://developer.android.com/training/multiscreen/screensizes#ConstraintLayout)
        - [Avoid hard-coded layout sizes](https://developer.android.com/training/multiscreen/screensizes#TaskUseWrapMatchPar)
        - [Create alternative layouts](https://developer.android.com/training/multiscreen/screensizes#alternative-layouts)
        - [Use the smallest width qualifier](https://developer.android.com/training/multiscreen/screensizes#TaskUseSWQuali)
        - [Use the available width qualifier](https://developer.android.com/training/multiscreen/screensizes#available-width)
        - [Add orientation qualifiers](https://developer.android.com/training/multiscreen/screensizes#TaskUseOriQuali)
        - [Modularize UI components with fragments](https://developer.android.com/training/multiscreen/screensizes#fragments)
    - **Material Theming**
        - [Color](https://material.io/design/color/)
            - [Dark Theme](https://material.io/design/color/dark-theme.html)
        - [Typography](https://material.io/design/typography/)
        - [Shape](https://material.io/design/shape/)
        - [Motion](https://material.io/design/motion/)
- **Libraries**
    - **AndroidX**
        - **Architecture Components**
            - [View Binding](https://developer.android.com/topic/libraries/view-binding)
            - [Data Binding](https://developer.android.com/topic/libraries/data-binding)
            - [Lifecycle](https://developer.android.com/topic/libraries/architecture/lifecycle)
            - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
            - [Paging](https://developer.android.com/topic/libraries/architecture/paging)
            - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
            - [Work Manager](https://developer.android.com/topic/libraries/architecture/workmanager)
        - [Navigation](https://developer.android.com/guide/navigation)
        - [CameraX](https://developer.android.com/training/camerax)
    - **Dependency Injection / Service Locator**
        - [Dagger](https://github.com/google/dagger)
        - [Koin](https://github.com/InsertKoinIO/koin)
    - **Utilities**
        - **Extension**
            - [Splitties](https://github.com/LouisCAD/Splitties)
        - **Time**
            - [ThreeTenABP](https://github.com/JakeWharton/ThreeTenABP)
            - [Klock](https://github.com/korlibs/klock)
        - **Validation**
            - [EasyValidation](https://github.com/wajahatkarim3/EasyValidation)
            - [VValidator](https://github.com/afollestad/vvalidator) (BETA)
        - **Permissions**
            - [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)
            - [Assent](https://github.com/afollestad/assent)
        - **Biometrics**
            - [Assure](https://github.com/afollestad/assure)
        - **Deep Link**
            - [DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch)
        - **Localization**
            - [Android Localization](https://github.com/akexorcist/Android-Localization)
        - **Activity Result**
            - [Inline Activity Result](https://github.com/afollestad/inline-activity-result)
    - **Network**
        - [Retrofit](https://github.com/square/retrofit)
        - [OkHttp](https://github.com/square/okhttp)
    - **Reactivity / Thread Management**
        - [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)
        - [RxJava](https://github.com/ReactiveX/RxJava)
    - **Serialization**
        - [Gson](https://github.com/google/gson)
        - [Moshi](https://github.com/square/moshi)
        - [Kotlin Serialization](https://github.com/Kotlin/kotlinx.serialization)
    - **Persistence**
        - [Room](https://developer.android.com/topic/libraries/architecture/room)
        - [SQLDelight](https://github.com/cashapp/sqldelight)
        - [Realm](https://github.com/realm/realm-java)
        - [ObjectBox](https://objectbox.io/)
        - [Paper](https://github.com/pilgr/Paper)
        - [Shared Preferences](https://developer.android.com/training/data-storage/shared-preferences)
            - [Rxkprefs](https://github.com/afollestad/rxkprefs)
            - [Splitties → Preferences](https://github.com/LouisCAD/Splitties/tree/master/modules/preferences)
            - [Only](https://github.com/skydoves/Only)
            - [Secure-preferences](https://github.com/scottyab/secure-preferences)
    - **Repository**
        - [Store](https://github.com/dropbox/Store) (alpha)
    - **Image Loading**
        - [Glide](https://github.com/bumptech/glide)
        - [Coil](https://github.com/coil-kt/coil)
    - **UI**
        - **Recycler View**
            - [Epoxy](https://github.com/airbnb/epoxy)
            - [Recyclical](https://github.com/afollestad/recyclical)
            - [Square Cycler](https://github.com/square/cycler) (Under development)
        - [Paris](https://github.com/airbnb/paris)
        - [Cyanea](https://github.com/jaredrummler/Cyanea)
        - [FlexboxLayout](https://github.com/google/flexbox-layout)
        - [Material Dialogs](https://github.com/afollestad/material-dialogs)
        - [Lottie](https://github.com/airbnb/lottie-android) / [LottieFiles](https://lottiefiles.com/)
        - [ExoPlayer](https://github.com/google/ExoPlayer)
    - **Logging**
        - [Timber](https://github.com/JakeWharton/timber)
    - **Debugging**
        - [Stetho](https://github.com/facebook/stetho)
        - [Flipper](https://github.com/facebook/flipper)
        - [Chucker](https://github.com/ChuckerTeam/chucker)
        - [LeakCanary](https://github.com/square/leakcanary)
        - [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database)
    - **Testing**
        - [JUnit5](https://github.com/junit-team/junit5)
        - [Robolectric](https://github.com/robolectric/robolectric)
        - [Mockito](https://github.com/mockito/mockito)
        - [MockK](https://github.com/mockk/mockk)
        - [Espresso](https://developer.android.com/training/testing/espresso)
        - [Truth](https://github.com/google/truth)
        - [Kluent](https://github.com/MarkusAmshove/Kluent)
        - [JaCoCo](https://github.com/jacoco/jacoco)
- **Tools**
    - **Crash Reporting & Analytics**
        - [Firebase](https://firebase.google.com/)
        - [Mixpanel](https://mixpanel.com/)
        - [Countly](https://count.ly/)
        - [Flurry](https://www.flurry.com/)
    - **CI / CD**
        - [Github Actions](https://github.com/features/actions)
        - [CircleCI](https://circleci.com/)
        - [Travis CI](https://travis-ci.org/)
        - [Bitrise](https://www.bitrise.io/)
        - [Jenkins](https://www.jenkins.io/)
