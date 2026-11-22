# Echoes of Elaria · Lab 8

Game Development Fundamentals, Unreal Engine 5.8. Open the Verdant Flats region to explore the forest music transition, spatial leaf and river ambience, randomized wind gusts, wind-driven music ducking and treasure pickup sounds.

## Open the project

Install Git LFS before cloning. The Lab 8 audio and gameplay changes are stored directly in Git. The project retrieves unchanged binary assets from the team’s public midterm Git LFS store.

```sh
git lfs install
git clone https://github.com/Jerrizzy001/Gaming-Foundations-Lab08.git
cd Gaming-Foundations-Lab08
git lfs pull
```

Open `DPS937_ThirdPerson.uproject` in Unreal Engine 5.8. Open the `Region01_VerdantFlats` level and press Play. Enter and leave the forest to hear the crossfade, approach the river to hear distance attenuation, and collect treasure for localized pickup feedback.

The audio manager and forest zone are in `Content/GameAssets`. Sound cues, attenuation, sound classes, the wind mix and the water actor are in `Content/audio`. Audio sources include the Wanderers Repose, Demons Realm and Essential Ambience collections and the imported coin-collect and candy-pickup recordings. Third-party assets retain their original terms.

The public checkout includes the eight Sound Waves used by the lab. The full download also includes the original audio sampler libraries.
