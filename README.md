# TiMaterialIcon
## [Google Material Design Icons](https://github.com/google/material-design-icons) for [Titanium Alloy](http://docs.appcelerator.com/platform/latest/#!/guide/Alloy_Concepts).

## Features
* Super easy to use.
* Simply pate following style into `/app/styles/app.tss` and MaterialIcons.ttf into `/app/assets/fonts/`. Now just add `mi` class to the text-based UI element and you are done.
    ```
        ".mi[platform=android]": {
            font: {
              fontFamily: "MaterialIcons"
            }
        }

        ".mi[platform=ios]": {
            font: {
              fontFamily: "Material Icons"
            }
        }
    ```
* Find icons you like from [Google Material Icons](https://www.google.com/design/icons/) and just replace space with underscore or refer to this [codepoints](https://raw.githubusercontent.com/google/material-design-icons/master/iconfont/codepoints). eg. `<Label class="mi">thumb_up</Label>`
* Scale to any size and give it any color.
* Works on Android, iOS

## Example
![Imgur](http://i.imgur.com/Z0aZOyv.png)
* [Example App](https://github.com/himalay/TiMaterialIcon/example)

## Show me how?
* Paste content of `app.tss` from [here](https://github.com/himalay/TiMaterialIcon/app.tss) to `/app/styles/app.tss`.
* Move `MaterialIcons.ttf` from [here](https://github.com/himalay/TiMaterialIcon/MaterialIcons.ttf) into `/app/assets/fonts/`.
* Find icons you want from [Google Material Icons](https://www.google.com/design/icons/) and just replace space with underscore or refer to this [codepoints](https://raw.githubusercontent.com/google/material-design-icons/master/iconfont/codepoints).
* Annnd that's it. Start useing it.
```
  <View layout="horizontal">
	 <Label class="mi">home</Label>
   <Label>I am the Google Material home icon.</Label>
  </View>
```
