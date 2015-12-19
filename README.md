This is a fork of [fastlane/frameit](https://github.com/fastlane/frameit).

<p align="center">
  <img src="assets/frameit.png" height="110">
</p>

- Added iPhone 4 device frame (vertical only) in `devices_frames` since Apple does not provide it
- Support frameless screenshots

## Frameless Screenshots

Sometimes, you want a mix of screenshots with frames and without frames.

By default frames will be applied. 

To have framelss, in Framefile.json, set `frame` to `false`. You will also need to set `padding` to 0 and the title to "".

    {
      "filter": "frameless",
      "frame": false,
      "padding": 0
    },


