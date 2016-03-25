Collection of Java classes for Android whose names and package are similar to ActionScript 3.

JASAfA uses Android classes then wraps, reorganizes, restructures it all to resemble ActionScript 3 API.

**ex:**
```
//AS3
flash.display.Graphics

//JASAfA
droid.display.Graphics
```

With the above example, the Java-class Graphics has the same functions as its ActionScript-class counterpart.

**ex:**
```
//AS3
import flash.display.Graphics;
var myGfx:Graphics = new Graphics();
myGfx.moveTo(5, 5);
myGfx.lineTo(10, 10);

//JASAfA
import droid.display.Graphics;
Graphics myGfx = new Graphics();
myGfx.moveTo(5, 5);
myGfx.lineTo(10, 10);
```