# SearchStyle
 
|![](https://github.com/gzeinnumer/SearchStyle/blob/master/preview/preview1.jpg)|
|---|

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    tools:context=".MainActivity">

    <include layout="@layout/widget_search"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="@dimen/def_margin"
        android:layout_marginEnd="@dimen/def_margin"
        android:layout_marginBottom="@dimen/def_margin">

        <include
            android:id="@+id/ws"
            layout="@layout/widget_search_v2" />
    </LinearLayout>

</LinearLayout>
```

- [widget_search.xml](https://github.com/gzeinnumer/SearchStyle/blob/master/app/src/main/res/layout/widget_search.xml)
- [widget_search_v2.xml](https://github.com/gzeinnumer/SearchStyle/blob/master/app/src/main/res/layout/widget_search_v2.xml)

```xml
<dimen name="def_margin">16dp</dimen>
<dimen name="space">10dp</dimen>
<dimen name="def_margin_half">8dp</dimen>
<dimen name="radius">10dp</dimen>
```
```xml
<color name="black">#FF000000</color>
<color name="white">#FFFFFFFF</color>
<color name="colorText">#7b7b7b</color>
```

---

```
Copyright 2021 M. Fadli Zein
```