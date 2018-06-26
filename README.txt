npm install -g @mindev/min-cli
npm install wepy-cli -g


min.config.json
{
  "compilers": {
    "babel": {
      "sourceMaps": "inline",
      "presets": [
        "env"
      ],
      "plugins": [
        "syntax-export-extensions",
        "transform-class-properties",
        "transform-decorators-legacy",
        "transform-export-extensions"
      ]
    }
  }
}

min install @minui/wxc-toast
npm install
min build
wepy build

2018-06-26
1. add wxapp-cookie-shim
npm install wxapp-cookie-shim --save
import 'wxapp-cookie-shim' --app.wpy
