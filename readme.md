Made by Diego Villaseñor with the [erv](https://github.com/diegovdc/erv) library and [wilson-tunings.echoic.space](http://wilson-tunings.echoic.space).

Layouts for a 22 tone eiksonay constant structure made by Erv Wilson. A different color is assigned to each of the  20 different tones of the eiksany. The remaining two tones are almost black.  The color scheme tries to make somewhat intuitive the relations between each tone of the eikosany, with closely related tones being similar in one way or another. The color schema is based on the CPS technique and involves the mutiplication of colors in the same fashion as factors get mutiplied to create a CPS.

A complete layout is included as well as several partial layouts that highlight different subCPS structures within the eikosany, in these partial layouts, notes that do not belong to the subCPS are almos black as well.

Color schema :

``` clj
  {#{:a :d :e} "#6c7eac"
   #{:b :d :e} "#6ca0a1"
   #{:d :e :f} "#6c6edb"
   #{:a :d :f} "#aa759f"
   #{:a :b :c} "#b7a14d"
   #{:a :b :e} "#a2747e"
   #{:c :d :e} "#4ea590"
   #{:c :e :f} "#74688f"
   #{:a :e :f} "#a250ab"
   #{:a :b :d} "#aaaa75"
   #{:b :c :d} "#7adf62"
   #{:a :c :f} "#b76f68"
   #{:b :d :f} "#aa9495"
   #{:b :c :f} "#b78d61"
   #{:a :c :e} "#747870"
   #{:b :e :f} "#a265a0"
   #{:a :c :d} "#7ab068"
   #{:a :b :f} "#ff6b75"
   #{:b :c :e} "#749869"
   #{:c :d :f} "#7a9985"}
```

The midi layout the same as the default 22ET that comes by default with the lumatone.


Special thanks to Kraig Grady for publishing the scala file and for his input with the color schema: http://anaphoria.com/Wilson1-3-7-9-11-15x3_pascal_eikosany.scl



![color codes](color-codes.png)
