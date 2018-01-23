# react-native-heatmaps

This is an instruction on how to use my fork of [react-native-maps](https://github.com/react-community/react-native-maps) which adds possibility to draw heatmaps.

There are 2 different types of heatmaps implemented - density based and weight based. The first one is drawn with Google algorithm from their Maps Utils ([Android](https://developers.google.com/maps/documentation/android-api/utility/heatmap) and [iOS](https://developers.google.com/maps/documentation/ios-sdk/utility/heatmap)). The second one is based on my own alrogithm which unfortunately isn't perfect yet.

<p align="center">
  <img src="heatmap1.png" width="350"/>
  <img src="heatmap2.png" width="350"/>
</p>


## Installation
Soon...

## Component API
Soon...

## Example
Soon...

## Todos
* Finish this instruction.
* Fix handling points which are near the map edge in weight based algorithm.
* Add possibility to change radius when zooming in iOS for weight based algorithm.
* Add points aggregation to weight based algorithm so that it works much faster for many points.
* Get rid of apache-commons and write interpolation function yourself maybe?
