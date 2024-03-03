# Lottie Animation

## Gradle

```
implementation (libs.lottie)
```
or
```
implementation ("com.airbnb.android:lottie:5.2.0")
```

## XML (URL)

```
<com.airbnb.lottie.LottieAnimationView
     android:id="@+id/animationView"
     android:layout_width="match_parent"
     android:layout_height="wrap_content"
     app:lottie_url="REPLACE_JSON_URL"
     app:lottie_autoPlay="true"
     app:lottie_loop="true"/>
```


## XML (raw)

```
<com.airbnb.lottie.LottieAnimationView
    android:id="@+id/animationView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:lottie_rawRes="@raw/animation"
    app:lottie_autoPlay="true"
    app:lottie_loop="true"/>
```
