# Plant Photo App 🌱

A quick Flutter project, done with minimal dependencies.
Uses ChangeNotifier to manage app state along with a simple MaterialPage layout for different pages.
All the user data is managed by a single ChangeNotifierProvider that is accessible by all of the widgets in the project, as every element in the project currently interacts with it.



Currently the app skips actually querying device's camera to take a photo.
To do so, I'd use the image_picker package and modify the necessary podfile/xcode settings to give the project
necessary perissions to access and use the target device's camera (or simulator's gallery).

If I could go back, I would've liked to spend more on beautifying the app, and to add a simple dark mode/light mode switch to the settings tab.
Also, I definitely could make the code more readable by splitting it into multiple files.

To run, simply call 'Flutter Run' and select available destination. Tested to run on macos web and Xcode iOS simulator.
Placeholder images sourced from Unsplash.
