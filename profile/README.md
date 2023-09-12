![image](https://github.com/Pico-Developer/.github/blob/main/images/logo.png)

# PICO Developer
Welcome to PICO Developer! This is PICO's offcial repository for open-source samples covering the use of basic SDK features, rendering effects, performance display, interaction examples, etc. These samples aim to help you quickly get started on app development for PICO VR headsets with Unity, Unreal, Native, and WebXR. We will continue to maintain and update the samples for a better development experience.

For more information, visit the [PICO Developer Platform](https://developer.pico-interactive.com/).

## SDK & Resources

<table>
    <thead>
        <tr>
            <th>Platform</th>
            <th>SDK</th>
            <th>Documentation</th>
            <th>API Reference</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=1>Unity</td>
            <td><a href="https://developer-global.pico-interactive.com/resources/#sdk">PICO Unity Integration SDK</a></td>
            <td><a href="https://developer-global.pico-interactive.com/document/unity">Documentation</a></td>
            <td>
                <a href="https://developer-global.pico-interactive.com/reference/unity/latest/">API reference</a></td>
            </td>
        </tr>
        <tr>
            <td rowspan=2>Unreal</td>
            <td><a href="https://developer-global.pico-interactive.com/resources/#sdk">PICO Unreal Integration SDK</a></td>
            <td><a href="https://developer-global.pico-interactive.com/document/unreal">Documentation</a></td>
            <td>/</td>
        </tr>
        <tr>
            <td><a href="https://developer-global.pico-interactive.com/docs/native/en/13158/openxr-mobile-sdk-overview/#introduction-to-openxr">PICO Unreal OpenXR Plugin</a></td>
            <td>
                <a href="https://developer-global.pico-interactive.com/document/unreal-openxr/">Documentation</a>
            </td>
        </tr>
        <tr>
            <td rowspan=2>Native</td>
            <td><a href="https://developer-global.pico-interactive.com/resources/#sdk">PICO OpenXR SDK</a></td>
            <td><a href="https://developer-global.pico-interactive.com/document/native/">Documentation</a></td>
            <td>/</td>
        </tr>
        <tr>
            <td><a href="https://developer-global.pico-interactive.com/sdk?deviceId=1&platformId=3&itemId=16">Android Native XR SDK</a></td>
            <td>/</td>
            <td><a href="https://pdocor.pico-interactive.com/reference/native/xr/2.0.1/">API Reference</a>
            </td>
        </tr>
        <tr>
            <td rowspan=1>Web</td>
            <td>
              <ul>
                <li>WebXR SDK (coming soon)</li>
                <li><a href="https://github.com/Pico-Developer/awesome-webxr-development">Awesome WebXR Development</a></li>
              </ul>
            </td>
            <td colspan=2>
              <ul>
                <li>Documentation (coming soon)</li>
                <li><a href="https://developer-cn.pico-interactive.com/document/web/introduce-xr/">中文文档</a></li>
              </ul>
            </td>
        </tr>
    </tbody>
</table>

# Unity Sample
The **Unity Sample** includes samples for app development using the Unity Engine and the PICO Unity Integration SDK. "Unity 2020.3 LTS" is the version referenced in the samples while the samples can also be run on "Unity 2019.4 LTS" or later.

## Get Started
The GetStartedDemo includes the indoor and outdoor scenes. You can experience the following in the demo: changing your view, locomotion, teleportation, and switching between the indoor and outdoor scenes. For information on the demo, refer to [this article](https://developer-global.pico-interactive.com/en/document/unity/get-started-demo/).

Access the sample [here](https://github.com/Pico-Developer/Getstarted-Unity).

## Basic Sample
Basic samples cover basic features achieved through the PICO Unity Integration SDK and the Unity XR Interaction Toolkit. You need to import the above two dependencies into your project to enable the import and running of a corresponding ".unitypackage".

**Sample List**

| Feature | Description |
| -----   |    ----     |
| Controller   |  For how to use controllers and set up controller vibration. |
| UI      |  For how to interact with Unity's UI using the ray. |
| Interaction |   Includes basic interaction samples for locomotion, teleportation, object gripping, and shooting.  |

Access samples [here](https://github.com/Pico-Developer/BasicSample-Unity).

## Platform Sample
These samples show how to use PICO platform services.

Access samples [here](https://github.com/Pico-Developer/PlatformSample-Unity).

## Advanced Sample

### CarExhibition

This **CarExhibition Show** sample uses URP, Multiview environment, double resolution rendering, models from SketchFab licensed models, and a particle effect added to the scene to enhance the sense of space.

![image](https://raw.githubusercontent.com/Pico-Developer/.github/main/images/car.jpg)

Access samples [here](https://github.com/Pico-Developer/CarExhibition-Unity).


# Unreal Sample
**Unreal Sample** provides samples for app development using the Unreal Engine and the PICO Unreal Integration SDK. Samples can be run on "Unreal 4.24
" or later.


## Get Started
The **Get Started** sample sets you up to create a basic scene using the PICO Unreal Integration SDK. The sample includes the use of SDK features, the basic configurations, and a scene containing the HMD and controller settings. For instructions on how to build the scene, refer to the [Quickstart Guide](https://developer-global.pico-interactive.com/document/unreal).

**Development Environment**

| Name  | Version    |
| ----  |  ----      |
| Unreal Engine | 4.27 |
| PICO Unreal Integration SDK | ≥2.3.0 |

Access samples [here](https://github.com/Pico-Developer/Getstarted-Unreal).

## Basic Sample
Basic samples cover basic features achieved through the PICO Unreal Integration SDK.

| Feature | Description |
| -----   |    ----     |
| Controller   |  For how to use the PICO controller and set up controller vibration. |
| UI      |  For how to interact with Unity's UI using the rays. |
| Interaction |   Includes basic interaction samples for locomotion, teleportation, object gripping, and shooting.(This Sample only supports UE4.27 and above versions, because it uses the Epic recommended interaction framework as the basis)  |

Access samples [here](https://github.com/Pico-Developer/BasicSample-Unreal/).

## Platform Sample
This samples demonstrating the usage of PICO platform services.

Access samples [here](https://github.com/Pico-Developer/PlatformSample-Unreal).

# WebXR Sample

Coming soon...
