# narbis2
9/26/25 this should be same as current production version 82. configured to load deprecated azure files from local libs.

Update Summary:

Removed deprecated JCenter repository reference in build.gradle.

Updated app-level build.gradle to use Azure Mobile Android 3.5.1 library instead of deprecated dependency.

The project is already configured (line 130) to load dependencies from the libs directory.
→ Simply create a libs/ folder and place the required .jar or .aar files inside it before compiling.
