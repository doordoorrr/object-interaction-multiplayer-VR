# object-interaction-multiplayer-VR
this project indludes a Unity project that is a networked VR multiplayer object interaction template game.

- unity editor version: Unity-2022.3
- Meta XR all-in-one SDK v65
- Meta XR interaction SDK OVR Samples v65

Details:
- project uses 3D render pipeline
- build settings have already been configured sich that the build app can run on the oculus quest devices
- change company name and product name under player settings
- fetaures an object interaction rig:  
  - grabbable and respawnable ball
  - sliding scroll bar with color options that determine the ball's color
  - ![image](https://github.com/user-attachments/assets/bf207e30-98b4-4d42-aeee-1f3b988afba6)
  - networking details:
  - UI that has two options: host and client/join
  - each button determines two things:
    - clicking host produces a unqiue Room code that client can use to access the host's session
      and  the default xr rig transforms into the network player prefab avatar 
    - join/client, which uitilizes the interactable "enter text" box that is used to enter     
     one's Room code
    - once the client's connection is sucessful to the host's session the client will have a   
      networked avatar as well
- utilizes untiy's relay service (untiy provides connectivity through a universal Relay server acting as a proxy)


