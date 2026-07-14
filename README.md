Project 1 — Quote of the Day App

What it covers:

Dart basics, null safety, const/final
StatelessWidget + StatefulWidget
BLoC (Loading, Loaded, Error states)
Dio API call + fromJson model
FutureBuilder concept via BLoC
ListView, Cards, Pull to refresh
Public/private fields and keys
Error handling + retry button

API used: https://zenquotes.io/api/random — free, no key needed.

What the App Does

Fetches a random quote from real API on launch
Shows Loading → Quote → Error states
Save quotes to a list (BLoC state management)
Saved count badge in AppBar (buildWhen targeted rebuild)
Retry button on error
New quote button
