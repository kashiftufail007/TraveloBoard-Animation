# TraveloBoard-Animation:thumbsup::heart:

<p align="center">
  <img width="300"  src="https://user-images.githubusercontent.com/34978760/63293334-57530700-c2e1-11e9-8878-0fc9e8dfea9c.gif">
</p>


## Project Detail :heart::slightly_smiling_face: :relaxed:

### Animation Code :heart::slightly_smiling_face: 
##### frombottom :relaxed:

```xml
<?xml version="1.0" encoding="utf-8"?>
<set xmlns:android="http://schemas.android.com/apk/res/android">

    <translate
        android:fromYDelta="100%p"
        android:toYDelta="0%p"
        android:duration="800"
        />

    <alpha
        android:fromAlpha="0.0"
        android:toAlpha="1.0"
        android:duration="1300"
        />

</set>
```


##### fromtop :relaxed:

```xml
  <translate
        android:fromYDelta="-100%p"
        android:toYDelta="0%p"
        android:duration="800"
        />

    <alpha
        android:fromAlpha="0.0"
        android:toAlpha="1.0"
        android:duration="1300"
        />
```
#### Java Animated Code :writing_hand:

```java
 bgone.animate().scaleX(2).scaleY(2).setDuration(5000).start();

        btnjoin.startAnimation(frombottom);

        textView2.startAnimation(fromtop);

        editText2.startAnimation(fromtop);
        editText5.startAnimation(fromtop);
        editText3.startAnimation(fromtop);
        editText7.startAnimation(fromtop);
 ```             


### Author

### Muhammad Kashif  :heart:

* [GitHub Profile](https://github.com/kashiftufail007)
* [Facebook Profile](https://www.facebook.com/KashifCache)
* [LinkedIn Profile](https://www.linkedin.com/in/muhammad-kashif007/)

### License

Copyright © 2019-2020, [Muhammad Kashif](https://github.com/kashiftufail007).
Released under the [MIT License](LICENSE).

[More Projects ](https://github.com/kashiftufail007?tab=repositories)  :muscle: :muscle: :muscle:




