# TiMaterialIcon
## [Google Material Design Icons](https://github.com/google/material-design-icons) for [Titanium Alloy](http://docs.appcelerator.com/platform/latest/#!/guide/Alloy_Concepts).

## Features
* Super easy to use.
* Simply drop the tss file into `/app/styles/` and MaterialIcons.ttf into `/app/assets/fonts/`.
* Add Icons with a simple class name.
* Find icons you like from [Google Material Icons](https://www.google.com/design/icons/) and just prefix `mi-` to the ican name your like as a class name. eg. `<Label class="mi-favorite"/>`
* Scale to any size, give it any color.
* Works on Android, iOS
* Works with other fonts or font-icons.

## Example
![Imgur](http://i.imgur.com/RIBS4W5.png)
* [Example App](https://github.com/himalay/TiMaterialIcon/example)

## Show me how?
* Download the `app.tss` from [here](https://github.com/himalay/TiMaterialIcon/app.tss) and the `MaterialIcons.ttf` from [here](https://github.com/himalay/TiMaterialIcon/MaterialIcons.ttf).
* Place `app.tss` into `projectFolder/app/styles/` and `MaterialIcons.ttf` into `projectFolder/app/assets/fonts/`.
* Annnd that's it. Start useing it.
```
  <View layout="horizontal">
	 <Label class="mi-home"/><Label>I am the Google Material home icon.</Label>
  </View>
```
