# winjsrocks-plugin-platform

Contains platform identification features as a plugin for the [WinJSRocks](http://winjs.rocks) MVVM Framework for WinJS apps.

# Activation
To activate, import the plugin project from npm:

``` javascript
npm install winjsrocks-plugin-platform
```

Then, register in the `WinJSRocks.Application.Instance.configure` options within the `plugins` array:

``` javascript
var WinJSRocks = require('winjsrocks');
var WinJSRocksPluginPlatform = require('winjsrocks-plugin-platform');
var app = new WinJSRocks.Application();
app.configure({
    plugins:[
      WinJSRocksPluginPlatform // Provide the Class Definition of the Plugin
    ]
  },
  function(err){
  });
```

# Features

- [Platform.js](https://github.com/bestiejs/platform.js) automatically mapped to the app `body` tag
