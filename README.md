#BetterNSLog

This simple library shadows NSLog and adds a "debug" NSLog command, called DLog.

It's also full of preprocessor magic.

You should import **BetterNSLog.h** in your Prefix.

This...

    NSLog(format,...)

...prints:

    [APPNAME] DESIRED_OUTPUT

And

This...

    DLog(format,...)

...prints:

    [APPNAME][mt:{0,1}][source_file:line_number][function] DESIRED_OUTPUT

where **mt** stands for **main thread**.

#Warning

**DLog** doesn't print anything when **DEBUG** is not set!

#License

BetterNSLog is available under the MIT license. See the LICENSE file for more info.
