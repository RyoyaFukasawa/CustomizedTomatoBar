---

## Customized Version: CustomizedTomatoBar

This repository is a customized version of [TomatoBar](https://github.com/ivoronin/TomatoBar), originally created by Ilya Voronin and distributed under the MIT License.

### 🔧 Custom Modifications
- Added **individual volume control** for each sound effect (windup, ding, ticking)
- Implemented a **SwiftUI-based volume slider UI** in the settings menu
- Volume is stored persistently via `@AppStorage` (UserDefaults)
- Improved user accessibility by allowing **double-tap reset to default volume**
- [Planned] Migration to `AVAudioEngine` for full device-independent volume control (in progress)

> These changes were made to give users finer-grained control over the sound experience, especially for those who want to lower alert volumes without changing macOS system volume.

---

## License

This project remains under the original [MIT License](./LICENSE) from TomatoBar.

