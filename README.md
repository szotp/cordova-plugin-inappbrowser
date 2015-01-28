# cordova-plugin-inappbrowser

This plugin adds a customizable in app browser to your cordova application.

```
  webview.openWebView(null, null, {
    iconColor: '#FFFFFF',
    backgroundColor: '#000000',
    isPDF: false,
    url: 'http://mwaysolutions.com'
  });
```

## Installation
```
  $ cordova plugin add https://github.com/mwaylabs/cordova-plugin-inappbrowser.git
```
## Options
- All parameters are required

- iconColor: Defines the color of the icons expectes a string with a colorcode e.g. '#000000'
- backgroundColor: Defines the backgroundcolor of the bar at the bottom of the webview, expectes a string with a colorcode e.g. '#FFFFFF'
- isPDF: Defines whether to show or hide the navigation buttons (next, back, reload) expects a boolean
- url: The url of the resource to show. expects a string with a valid url

### Supported Platforms
- iOS 7+

### License
Code licensed under MIT. Docs under Apache 2. PhoneGap is a trademark of Adobe.