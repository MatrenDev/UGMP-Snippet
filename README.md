# UGMP Extension

An extension that allows you to add missing natives from UGMP.

# How to add snippet?

Multiple parameteres (if the sequence of parameters does not repeat in other functions):
```
"(weatherHandlingType, weatherType, colourFilter, Float:windyness)": 
{
  "prefix": "CreateExtraWeather",
	"body": [
	"CreateExtraWeather(weatherHandlingType, weatherType, colourFilter, Float:windyness);"
	],
}
```

One parameter:
```
"ToggleFluffyClouds(enable)": 
{
  "prefix": "ToggleFluffyClouds",
	"body": [
	"ToggleFluffyClouds(enable);"
  ],
}
```

https://marketplace.visualstudio.com/items?itemName=Matren.UGMPSnip
