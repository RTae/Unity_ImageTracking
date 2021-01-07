
# Unity Image Tracking with AR Foundation

Implement Image Tracking with Augmented Reality by use AR Foundation from Unity


## Requirement

- Unity : 2019.4.17f1 or Higher

- AR Foundation : 2.1.10 (Recommend) or Higher

- AR Subsystems : 2.1.3 (Recommend) or Higher

- ARCore XR Pugin : 2.1.12 (Recommend) or Higher (ARKit XR Plugin for IOS)


## How to use

1) Clone this repository

2) Add this project in Unity Hub

3) Open this Project

4) You will see assets folder that contain content of this project and we will focus on three folders.

- First, Images folder. It contain image that you want to track (as reference) and ReferenceImageLibary

- Second, Prefab folder. It contain prefab that you want to be model

- Third, Scripts folder. It contain script of this project and you can custom this script to have better performance or functionality

5) Go to folder Images and click at ReferenceImageLibary. Look at Inspector tab

6) This's contain images that you want to track. Click at "Add images" to add more image to track.

7) You will see select button, it use for select image that you want track. Text field "Name", it use for configure a name of image and it should be same as prefab name. You need to set the specify size for your track image by yourself. I can't tell you what is perfect size for your image.

8) In the Hierarchy tab, you will see "AR Session Origin" Click it and look at Inspector tab

9) Look at Muti Image Tracking, you will see drop down tab that name is "Placeable Prefabs" click it and it will allow you to configure a size. it mean number of model you want to track (be sure your prefab name should be same as image name that you want to track)

10) Last, you need to configure max nunmber of moving images in AR Track Image Manager (It's up to your project and device that you use can handle). Done !!!


## How to build (Android)
1) Follow this link [Youtube](https://www.youtube.com/watch?v=0mpsiO2lCx0)
2) You need to make sure Gradle is support with your AR Foundation by follow this link [Click](https://developers.google.com/ar/develop/unity/android-11-build)
3) Build

## Reference
[AR Foundation Manual](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@4.1/manual/index.html)
[More example](https://github.com/Unity-Technologies/arfoundation-samples)