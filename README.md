# [**Unity-VRlines: Towards a Modular eXtended Reality Unity Flight Simulator**]()

[Giuseppe Di Maria](https://www.linkedin.com/in/giuseppe-di-maria-6bb5a4170/?originalSubdomain=it)\*,
[Lorenzo Stacchio](https://www.unibo.it/sitoweb/lorenzo.stacchio2)\*,
[Gustavo Marfia](https://github.com/qp-qp)<br/>

| [IFIP ICEC '23 Oral](https://icec23.cs.unibo.it/) | [paper]() | [project page](https://varlab-unibo.github.io/Unity-VRlines/)

<p align="center">
  <img src="images\aircraft.png" width="350">
</p>

```
* These authors should be considered as joint first authors.
``` 

## Abstact
Computer-aided flight simulation systems (CAFSS) make it possible to simulate flying an airplane using software and hardware. These simulations range from simple programs to intricate, full-motion simulators that often integrate physical feedback and visual clues to create realistic and affordable entertainment and pilot training. Nowadays, eXtended Reality (XR) paradigms have been integrated in CAFSS, to increase the immersiveness and realism of the experience, demonstrating positive cognitive learning effects in training procedures. 
However, no extensive results for simulator effectiveness are available to this date, considering the reach of such systems is limited by the costly hardware and unavailability of open-source software.
For this reason, we here introduce Unity-VRlines, an open-source modular virtual reality flight simulator baseline, based on the Unity game engine and the SteamVR SDK, that can be deployed in any compatible VR device. The system components and software architecture enables developers to add new flight control instructions, alter aircraft parts, and change the surrounding environment.


## Requirements
* [Unity 2021.3.21f1](https://unity.com/releases/editor/archive#download-archive-2021)
* [SteamVR v2.7.3](https://github.com/ValveSoftware/steamvr_unity_plugin/releases/tag/2.7.3) 

## Features 
* Plane the aircraft with both Keyboard and HTC-Vive in the Bologna Airport Area; 
* Camera view switch with Kinematics in VR mode;
* Guided In-Game Tutorial;

## References

The core physics module is heavily adapted from [this project](https://github.com/gasgiant/Aircraft-Physics). 

## Demo

The demo is in the ```Assets/UnityAirline/Scenes_and_Scripts/Scenes/VR_Simulator.unity```.
