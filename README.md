# MG4
## Devlog
Danika Fleck

Start() runs once when the script is enabled and sets _timer to _switchSpeed. switchSpeed is the number of seconds we want before the food item switches directions. Update() runs everyframe and checks if _timer has reached 0.0. If it has reached 0.0 the timer is reset by giving _timer the value inside of _switchSpeed again. Also within Update() the variables _up is a boolean which indicates whether the gameObject should move up or down. If _up is true then the object is translated up, if else the the object is translated down. When _timer reaches zer0, the value of _up is switched to keep the alternating translations going.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)