# Android-Style
Graphic designs for Android Studio components
-
## רקע משולב

![image](https://github.com/AharonGon/Android-Style/assets/78660802/ee739470-381d-4a53-bd6f-7e44e93aef29) 

### code


```
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <!-- צור מסגרת שחורה באמצעות קווים שחורים -->
    <item>
        <shape android:shape="rectangle">
            <solid android:color="#003F51B5" />
            <corners android:radius="8dp" />
        </shape>
    </item>

    <!-- צור רקע פנימי כך שהתוכן יוכל להוצג בתוך המסגרת -->
    <item android:left="1sp" android:top="1sp" android:right="1sp" android:bottom="1sp">
        <shape android:shape="rectangle">
            <solid android:color="#00767EAC" /> <!-- זהו צבע ירוק בהיר -->
            <corners android:radius="8dp" />
        </shape>
    </item>

    <!-- שכבה נוספת עבור שילוב שני הצבעים -->
    <item android:left="2dp" android:top="2dp" android:right="2dp" android:bottom="2dp">
        <shape android:shape="rectangle">
            <gradient
                android:type="linear"
                android:startColor="#85667DFD"
                android:endColor="#C8CDE6"
                android:angle="90"/>
            <corners android:radius="6dp" />
        </shape>
    </item>
</layer-list>


```

![image](https://github.com/AharonGon/Android-Style/assets/78660802/32723ac2-9514-4c85-98f6-3a66e8ab0bee)


```
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <!-- צור מסגרת שחורה באמצעות קווים שחורים -->


    <!-- שכבה נוספת עבור שילוב שני הצבעים -->
    <item android:left="2dp" android:top="2dp" android:right="2dp" android:bottom="0dp">
        <shape android:shape="rectangle">
            <gradient
                android:type="linear"
                android:startColor="#C8CDE6"
                android:endColor="#667DFD"
                android:angle="90"/>
            <corners android:radius="20dp" />

        </shape>
    </item>
</layer-list>
```


