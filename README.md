# Forearm Tracking For Microsoft HoloLens 2 Research Mode for Unreal Engine

![](https://github.com/Nathan-Tran/HoloLens-ResearchMode-Unreal/blob/main/docs/images/gif.gif)

## Description

An extension of the hand tracking provided by the HoloLens 2. Forearms are now tracked in world space allowing for novel experimentation with UI/UX based on forearm interaction. This solution is based on the HoloLens-ResearchMode-Unreal plugin found [here](https://github.com/microsoft/HoloLens-ResearchMode-Unreal)

## Installation

Call UpdateLatestWristTransforms() immediately after whereever your project makes it's call to the hand tracking API. For example within: FOpenXRHandTracking::UpdateDeviceLocations()

## Documenation

Links to further documentation can be found [here](https://noneuclideangeometry.com/2023/06/14/hololens-2-vision-pro-forearm-tracking-solution/)
