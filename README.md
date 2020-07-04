
*Note:* this repo has been forked to make it a package. See changes below. It is otherwise unchanged.

Change List:

- Added a package.json
- Top level meta files have been added to suppress errors
- Added an Assembly Definition
- Specify Moment.MinAttribute to avoid conflict with UnityEngine

# Moments

**Moments** is a quick GIF replay recorder for Unity3D. It automatically records the last few seconds of gameplay and lets you save to a GIF file on demand, like the game [TowerFall Ascension](http://www.towerfall-game.com/) does.

Tested with Unity 4.6. The demo requires Unity 5+ (Personal or Pro).

## Instructions

Drop the `Moments Recorder` folder in your project and add the `Recorder` script to your camera (or select your camera and use `Component -> Miscellaneous -> Moments Recorder`).

The included demo should get you started. For more advanced features, browse the `Moments.Recorder` source code, it's heavily commented.

[Here's a preview](http://i.imgur.com/K4R8UZ0.gifv) of the output quality.

Pull requests are welcomed !

## License

Zlib (see [License.txt](LICENSE.txt))
