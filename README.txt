Business Card - CSC 438 - Peter Parker

A Jetpack Compose business card inspired by the class Postcard app.

Displayed information:
- Peter Parker
- Student / Photographer
- College of Staten Island
- peter.parker@csi.cuny.edu (fictional sample address, not a verified mailbox)

Design: user-supplied illustrated Peter Parker portrait, blue background,
red card border and accents, and a light card surface. The portrait is a local
PNG drawable, so it needs no network connection.

Run: extract BusinessCard-project.zip, open its BusinessCard folder in
Android Studio, let Gradle sync, select an emulator/device, then click Run.
Android 7.0 / API 24 or newer is required. BusinessCard-debug.apk is the
matching installable debug build.

Code locations:
app/src/main/java/com/example/businesscard/MainActivity.kt - layout and colors
app/src/main/res/values/strings.xml - name, role, college, email, descriptions
app/src/main/res/drawable-nodpi/peter_parker.png - supplied portrait

GitHub currently stores the project as a ZIP archive. To update it, use
Add file > Upload files and upload the new archive under the same name.
Upload the matching APK and README.txt too, then commit the changes.
GitHub cannot directly edit individual source files inside a ZIP archive.

Validation: debug build and Android lint checks run for this update.
No coursework submission is performed.

The Friendly Neighborhood heading has been removed.

