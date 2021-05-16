# Kera Lua (Unity Package)

This repo contains [KeraLua](https://github.com/NLua/KeraLua) as a Unity package.
This repo is only for the convenience of using Kera Lua within the [Unity game engine](https://unity.com/).

## Usage

## Short Instructions

To use this project, you can download the latest tagged release OR clone locally as a Git submodule -- either way, into your Unity project.
Once it's there, simply add the Unity package as a local package.

## More Detailed Instructions

To use this project, ensure you already have a version of Unity downloaded with a Unity project open.

1. Download this project's tagged latest release, or clone this repo as a Git submodule.
2. Ensure the Kera Lua (Unity package) files are within your Unity project folder structure (either _in_ or _alongside_ your `Assets/` folder)
3. In your Unity project, open the Unity Package Manager from the `Window > Package Manager` menu.
4. In the package manager, add the `+` button and choose "Add package from disk...".
5. Browse for the `package.json` file, and click Open on it.

After the above steps, Unity should now import your package.

Once Unity finishes compiling, you should be able to reference KeraLua code in your C# scripts, including both inside and outside of AssemblyDefinition-contained code!

## Contributing
Check out the [original Kera Lua repo](https://github.com/NLua/KeraLua) if you wish to contribute!

## Suggestions & Feedback
If you have any suggestions or issues using the package in Unity, feel free to leave an issue.
