# vr-unit

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An A-Frame VR experience visualizing the scale of data storage units, from a single bit to a Quettabyte.

## Demo

- [bit-GB / ビットからギガバイト](https://code4fukui.github.io/vr-unit/)
- [GB-EB / キロバイトからエクサバイト](https://code4fukui.github.io/vr-unit/#2)
- [PB-QB / エクサバイトからクエタバイト](https://code4fukui.github.io/vr-unit/#7)

## Features

- **3D Visualization**: Represents 12 data units (bit, byte, kbyte... Qbyte) as a series of progressively larger cubes.
- **Scalable Views**: Uses URL hash parameters (`#0`, `#2`, `#7`) to "zoom out," making the immense scale of larger units comprehensible.
- **VR & Desktop Ready**: View in an immersive VR environment or on a standard desktop browser.
- **Lightweight**: Built with A-Frame and vanilla JavaScript, requiring no installation.

## How to View

1.  **Open a Demo Link**: Click one of the links above to launch the experience.
2.  **Navigate**:
    -   On a desktop, click and drag to look around.
    -   In a VR headset, open the URL in a WebVR-compatible browser for an immersive experience.
3.  **Change the Scale**: Modify the number in the URL hash (e.g., `.../vr-unit/#7`) to change the viewing scale. The number acts as a power of 10 divisor, effectively zooming the camera out to fit the larger units in the frame.

## Technical Note

The visualization uses a simplified progression to represent scale: the size doubles from `bit` to `byte`, and then increases by a factor of 10 for each subsequent SI prefix (kilo, mega, giga, etc.).

## License

This project is licensed under the MIT License.