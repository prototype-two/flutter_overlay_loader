Flutter Overlay Loader for your project

## Purpose
This package was made to make it easy to implement a loader where the entire background of the app goes dark and a loader appears while running an async function.

## Usage
```dart
final loggedIn = await overlayLoader(
  context: context,
  asyncFunction: () {
    return authUserStore.loginFacebook();
  },
  opacity: .8
);
```
