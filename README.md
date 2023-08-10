# log_wrapper

- [logger](https://github.com/Bungeefan/logger)

## Getting Started

``` dart
logD("This is a debug message");

logBoxD("This is a debug message");

logStackD("This is a debug message", error, stackTrace);
```
Instead of a string message, you can also pass other objects like List, Map or Set.

## Output

![Output](https://github.com/flutter-packagist/log_wrapper/blob/main/image/output.png)

## Log level

You can log with different levels:

``` dart
logV("Trace log");

logD("Debug log");

logI("Info log");

logW("Warning log");

logE("Error log", error: 'Test Error', stackTrace: stackTrace);

logN("Network log");
```