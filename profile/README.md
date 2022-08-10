![image](https://github.com/Pico-Developer/.github/blob/main/images/logo.png?raw=true)

# Pico Developer
Welcome to Pico Developer! This is Pico's offcial repository for open-source samples covering the use of basic SDK features, rendering effects, performance display, interaction examples, etc. These samples aim to help you quickly get started on app development for Pico VR headsets with Unity, Unreal, Native, and WebXR. We will continue to maintain and update the samples for a better development experience.

For more information, visit the [Pico Developer Platform](https://developer.pico-interactive.com/).

## SDK & Resources

|Platform |  SDK | Documentation | API Reference|
|  ----   | ---- |      ----     |     ----     |
| Unity   | [Pico Unity Integration SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=1&itemId=12) | [Documentation](https://developer.pico-interactive.com/document/unity)|<ul><li>[XR](https://pdocor.pico-interactive.com/reference/unity/xr/2.05/)</li> <li>[Platform](https://pdocor.pico-interactive.com/reference/unity/platform/1.0/)</li></ul>|
| Unreal  | [Pico Unreal Integration SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=2&itemId=13)| [Documentation](https://developer.pico-interactive.com/document/unreal)|<ul><li>[XR](https://pdocor.pico-interactive.com/reference/unreal/xr/12832/240774/)</li> <li>[Platform](https://pdocor.pico-interactive.com/reference/unreal/platform/1.0/)</li></ul>|
| Native  | [Android Native XR SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=16)| [Documentation](https://developer.pico-interactive.com/docs/native/en/13158/android-native-xr-quickstart/#overview)|[API Reference](https://pdocor.pico-interactive.com/reference/native/xr/2.0.1/)|
| Native  | [OpenXR Mobile SDK](https://developer.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=11)| [Documentation](https://developer.pico-interactive.com/docs/native/en/13158/openxr-mobile-sdk-overview/#introduction-to-openxr)|/|

# Unity Sample
The **Unity Sample** includes samples for app development using the Unity Engine and the Pico Unity Integration SDK. "Unity 2020.3 LTS" is the version referenced in the samples while the samples can also be run on "Unity 2019.4 LTS" or later.

## Get Started
The **Get Started** sample sets you up to create a basic scene using the Pico Unity Integration SDK and the Unity XR Interaction Toolkit. The sample includes the use of SDK features, the basic configurations, and a scene containing the HMD and controller settings. For instructions on how to build the scene, refer to the [Quickstart Guide](https://developer.pico-interactive.com/document/unity).

**Development Environment**

| Name  | Version    |
| ----  |  ----      |
| Unity Editor | 2020.3.35f |
| Pico Unity Integration SDK | 2.0.5 |
| XR Interaction Toolkit | 2.1.0 |

Access the sample [here](https://github.com/Pico-Developer/Getstarted-Unity).

## Basic Sample
Basic samples cover basic features achieved through the Pico Unity Integration SDK and the Unity XR Interaction Toolkit. You need to import the above two dependencies into your project to enable the import and running of a corresponding ".unitypackage".

**Sample List**

| Feature | Description |
| -----   |    ----     |
| Controller   |  For how to use the Pico controller and set up controller vibration. |
| UI      |  For how to interact with Unity's UI using the rays. |
| Interaction |   Includes basic interaction samples for locomotion, teleportation, object gripping, and shooting.  |

Access samples [here](https://github.com/Pico-Developer/BasicSample-Unity).

## Advanced Sample

### CarExhibition

This **CarExhibition Show** sample uses URP, Multiview environment, double resolution rendering, models from SketchFab licensed models, and a particle effect added to the scene to enhance the sense of space.

Access samples [here](https://github.com/Pico-Developer/CarExhibition-Unity).


# Unreal Sample
The **Unity Sample** includes samples for app development using the Unity Engine and the Pico Unreal Integration SDK. Samples can be run on "Unreal 4.24
" or later.


## Get Started
The **Get Started** sample sets you up to create a basic scene using the Pico Unreal Integration SDK. The sample includes the use of SDK features, the basic configurations, and a scene containing the HMD and controller settings. For instructions on how to build the scene, refer to the [Quickstart Guide](https://developer-global.pico-interactive.com/document/unreal).

Access samples [here](https://github.com/Pico-Developer/Getstarted-Unreal).

## Basic Sample
Basic samples cover basic features achieved through the Pico Unreal Integration SDK.

| Feature | Description |
| -----   |    ----     |
| Controller   |  For how to use the Pico controller and set up controller vibration. |
| UI      |  For how to interact with Unity's UI using the rays. |
| Interaction |   Includes basic interaction samples for locomotion, teleportation, object gripping, and shooting.(This Sample only supports UE4.27 and above versions, because it uses the Epic recommended interaction framework as the basis)  |

Access samples [here](https://github.com/Pico-Developer/BasicSample-Unreal/).
