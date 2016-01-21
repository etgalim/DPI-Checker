# DPI Checker

This is a supper simple app that will show you what drawable bucket the android system is using for a selected sevice.

**Why have something like this?**

While devices have hardware PPI rating given by the actual pixel count on the screen in relation to the screen size, device vendors can set there custom DPI rating for screens in the Android system.

Using **adb shell getprop ro.sf.lcd_density** or **adb shell dumpsys display** will show the system DPI rating.

Some devices fall between 2 different drawable buckets and the system decide whether to upscal or downscale a drawable image.

With **DPI Checker** you'll see what the system choose for the particular device the app runs on.

Use, share and enjoy :)

--------

P.S.
I'm a UX designer, go easy on me and be nice.


