#BetterNSLog

This simple library (full of preprocessor magic), shadows NSLog and adds a "debug" NSLog command, called DLog.

Import **BetterNSLog.h** where you need it, and you're good to go.

This...

    NSLog(format,...)

...prints:

    [APPNAME] DESIRED_OUTPUT

And

This...

    DLog(format,...)

...prints:

    [APPNAME][source_file:line_number][function] DESIRED_OUTPUT

where **mt** stands for **main thread**.

##Updates

**v1.1**

- BetterNSLog now supports asl_log

##Warning

**DLog** doesn't print anything when **DEBUG** flag is not set!

##License

BetterNSLog is available under the MIT license. See the LICENSE file for more info.
