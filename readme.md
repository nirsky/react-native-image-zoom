# React-Native-Image-Zoom

Forked from https://github.com/ascoders/react-native-image-zoom  
Added new props:

* `onSwipeVertical` - default () => {}  
* `swipeVerticalDistanceCallback` - default 220

`onSwipeVertical` will be called when image is not zoomed and swiping up or down on distance greater than `swipeVerticalDistanceCallback`.  

This is useful when implementing dismiss gesture.