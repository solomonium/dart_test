# dart_define_test

Tests using `--dart-define` with Flutter and Shorebird.

To test with Flutter, run:

```sh
flutter run --dart-define=MY_VAR=HELLO
```

To test with shorebird, run:

```sh
shorebird init
shorebird release ios -- --dart-define=MY_VAR=HELLO
shorebird preview
```

You should see the same output in both cases (a white background with text reading "hello HELLO").
