# Hack-a-thing 1
### Katie Huang, CS 98

A basic Flutter project following their setup tutorial and first app tutorial at [Flutter docs](https://flutter.dev/docs).

## Short description of what you attempted to build
I built a simple app that generates word pairs in an infinitely scrolling list. Each word pair has a heart beside it that you can tap, and hearted word pairs are saved in a separate view that you can access at the top right of the app.

I also built upon this base app from the tutorial by changing the theme colors using the `ThemeData` widget, adding a button to delete your list of saved word pairs, and a pull-down refresher to clear out the suggested pairs and get new ones.

### References
Other than the Flutter docs, I also referenced the following for my code:
- [Pull to refresh guide](https://www.geeksforgeeks.org/flutter-implementing-pull-to-refresh/)
- [Use keys to force reload widgets](https://jelenaaa.medium.com/how-to-force-widget-to-redraw-in-flutter-2eec703bc024)
- [Button onPressed](https://googleflutter.com/flutter-button-onpressed/)

## What you learned
- I've never used React Native, so maybe it's not quite as amazing, but hot reloading is great!
- Flutter has great widgets-- the refresh and the button are perfectly styled and were so easy to insert into my code.
- I learned some Dart, and it was relatively easy to read after having learned so many other languages.
- Seems a *bit* sad but I learned how to make a local directory into a git-tracked directory using `git init`, since I had never had to do that before in any of my classes.

## What didn’t work
- The setup was quite long and painful. It took me two days between setting up Java SDK, the Flutter specifics tools, and the Android simulator.
- I had a hard time getting the simulator to run for the first time, as I got stuck on a Gradle `assembleDebug` task. A quick Google fixed this but it just stalled and I didn't know how long I had to wait.
- Changing the state of the list of saved word pairs using the delete button doesn't immediately propagate the change, since the button is a child widget to the list showing the saved pairs. If you navigate off the screen and then navigate back, you'll see that the pairs were successfully cleared. I did look around for some solutions for this but they all seemed a bit more involved than I was bargaining for.
- I think I somehow bugged out my computer's fingerprint sensor while messing with the Windows settings to get the VM acceleration to work...


