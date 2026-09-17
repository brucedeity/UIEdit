# UIEdit: Perfect World (Angelica Engine) UI Editor

UIEdit is a WYSIWYG UI editor for the Angelica Engine, used by games such as Perfect World. It allows interface files to be previewed and edited visually.

## Features

- **WYSIWYG editing**: design and preview UI layouts in real time.
- **Drag-and-drop editing**: position, resize, and align buttons, panels, sliders, text boxes, and other UI components.
- **Real-time preview**: preview interfaces at different resolutions and aspect ratios.
- **Component-based design**: customize UI elements with support for animations, transitions, and event bindings.
- **Theme and style management**: create and apply consistent fonts, colors, and textures.
- **Multilingual support**: manage text and dynamic content for multiple languages.

## Angelica Engine Integration

- **Seamless workflow**: work directly with Angelica Engine interface and texture resources.
- **Script bindings**: connect UI elements to game scripts.
- **Reusable layouts**: save and reuse UI layouts for menus, HUDs, and dialogs.

## Developer Tools

- **Hierarchy and layers**: organize UI elements with clear layering and grouping.
- **Event support**: define mouse, touch, and controller interactions.
- **Debugging tools**: inspect collision boxes, anchors, and layout constraints.

## Use Cases

- Main menus, pause screens, and settings panels.
- Game HUDs, health bars, minimaps, and scoreboards.
- Dialogs, inventories, and custom interface screens.
- Custom tools and mod development.

## Download

Visit the [Releases](https://github.com/brucedeity/UIEdit/releases) page to download the latest version.

Requirements: Windows 7 or later and .NET Framework 4.8.

## Build

The project uses GitHub Actions for automated builds. Pushing to the `master` branch triggers the workflow.

Local builds require:

- Visual Studio 2019 or later, or MSBuild.
- .NET Framework 4.8 Developer Pack.
- NuGet.

Build the `Release|x86` configuration because the project uses the 32-bit native `FreeImage.dll` dependency.

## Acknowledgements

- Original author: [pdev](https://github.com/perfectdev/UIEdit).
- Improvements by slug © 2020.
- Contributions and maintenance by [brucedeity](https://github.com/brucedeity).
- Chinese localization by [lzw981731](https://github.com/lzw981731).
