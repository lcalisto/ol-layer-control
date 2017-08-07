# Layer control in OpenLayers 3.x and above

Example on how to create a layer control in OpenLayers 3.x and above. This example uses _OpenLayers 4.2.0_.

This example adds a layer control to the map.


## Running the App

Just check the __index.html__ for details.

A live example in :

[__https://htmlpreview.github.io/?https://github.com/lcalisto/ol-layer-control/blob/master/index.html__](https://htmlpreview.github.io/?https://github.com/lcalisto/ol-layer-control/blob/master/index.html)

## Notes

In order to make this layer control work, make sure you add __basemap:_boolean___ and __name:_text___ to your layers object.

### To add the layer control
The main function to add the control is:
```
showLayersControl()
```

### To remove the control

Function __removeLayersControl()__ removes the layer control.
```
removeLayersControl()
```
