# Gameplay Feedbacks - Demo Project

## Features Demos

The *Demos_Features/Maps* folder contains a variety of demo levels that showcase different aspects of the **Gameplay Feedbacks** framework. Each demo is designed to highlight specific features and functionalities, allowing users to understand how to implement and customize feedbacks in their own projects. These demos are listed in the following subsections, along with a brief description of their purpose and features.

### Core

#### Broadcast Demo

Map name: **Demo_Broadcast**

This demo shows the use of the **Gameplay Feedbacks Subsystem** in order to broadcast feedback events throughout a level. It showcases how to send and receive feedback events between different actors in the scene, allowing for dynamic interactions and responses based on gameplay tags. Feedback players will react to broadcast events with a random deviation in their start time, in order to create a more organic and natural feel to the feedbacks.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_broadcast.mp4" controls="controls" style="max-width: 730px;"></video>

#### Tag Dispatcher Demo

Map name: **Demo_Tag_Dispatcher**

This demo shows the use of the **Tag Dispatcher Feedback** in order to create a chain of feedback events.

#### Tickables Demo

Map name: **Demo_Tickables**

This demo shows the use of tickable feedbacks to create smooth transitions and animations. Feedbacks are applied to _Transform_ and _Light Component_ properties by means of curve assets, built-in tweens, custom easing function and custom impulse functions.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_tickables.mp4" controls="controls" style="max-width: 730px;"></video>

### Camera

#### Camera Demo

Map name: **Demo_Camera**

This demo shows how to use feedbacks to control camera properties or post process. Additionally it shows how to implement camera shake effects by means of an Unreal Engine _Camera Shake_ asset.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_camera.mp4" controls="controls" style="max-width: 730px;"></video>

### Post Process

#### Post Process Demo

Map name: **Demo_PostProcess**

This demo shows how to use  and manage various post-processing effects using the Gameplay Feedbacks framework.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_postprocess.mp4" controls="controls" style="max-width: 730px;"></video>

### Transform

#### LookAt Demo

Map name: **Demo_LookAt**

This demo shows how to use the **LookAt Feedback** and **Actor Look At Feedback** to make a Component or Actor look at a target location. It also uses the **Gameplay Feedbacks Subsystem** to broadcast feedback events to multiple actors in the scene, allowing for synchronized behavior.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_lookat.mp4" controls="controls" style="max-width: 730px;"></video>

### Vfx

#### Simple Niagara System Demo

Map name: **Demo_SimpleNiagara**

This demo shows how to use the **Simple Niagara Feedback** to spawn visual effects in the scene. Spawns are triggered as single effect, multiple and synchronized effects and fire-and-forget effects.

<video src="https://marcosecchi.github.io/gameplay_feedbacks_docs/videos/demo_simpleniagara.mp4" controls="controls" style="max-width: 730px;"></video>

#### Niagara System Demo

Map name: **Demo_Niagara**

This demo shows how to use the **Niagara Feedback** to modify user-defined Niagara System properties through tickables.

### UI

#### UMG Demo

Map name: **Demo_UMG**

This demo shows how to use feedbacks to control User Interface elements in the scene.


