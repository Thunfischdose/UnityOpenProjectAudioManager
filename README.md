# UnityOpenProjectAudioManager
A clone of the audio manager from unitys open-project-1 in an own package.

I really like the idea of using SerializedObject as an AudioWrapper. To be honest, I basically like it for everything... [Unite 2017 talk](https://www.youtube.com/watch?v=raQ3iHhE_Kk)

``
## This is copied source
The original code can be found [here](https://github.com/UnityTechnologies/open-project-1).
The original documentation is [here](https://github.com/UnityTechnologies/open-project-1/wiki/Audio-system).
## Usage
Add the `AudioManager` script to an empty gameobject.
Assign the `DefaultAudioMixer` located under `./Runtime/Settings/Audio` to it or make sure your own mixer has the needed channels.
Now you add some `AudioCue` script to any GameObject in your scene and add the serialized object containing the audio.
Done.

## Adjustments
 - Extracted the Audio components from the project
 - Removed DoTween dependency and LoadableAsset dependency
 
 .. many more coming
 
 ## New features
 
 .. in progress