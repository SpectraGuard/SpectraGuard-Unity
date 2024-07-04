# SpectraGuard

An AR app for iOS built with AR Foundation Scripting API, featuring plane detection with object placement, point clouds, basic UI, a debug menu, and a world map to save and load the current state of the app locally.


## Table of Contents
- [Features](#features)
- [Dependencies](#dependencies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Build and Run](#build-and-run)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Plane Detection:** Detects horizontal and vertical planes and allows object placement on them.
- **Point Clouds:** Displays point clouds to visualize detected feature points.
- **Basic UI:** Includes a user interface for interaction and control.
- **Debug Menu:** Provides a debug menu for testing and development purposes.
- **World Map:** Saves the current state of the app locally and loads it back.

# ARWorldMap
This requires iOS 12 or above.
An ARWorldMap is an ARKit-specific feature which lets you save a scanned area. ARKit can optionally relocalize to a saved world map at a later time. This can be used to synchronize multiple devices to a common space, or for curated experiences specific to a location, such as a museum exhibition or other special installation. A world map will store most types of trackables, such as reference points and planes.

The ARWorldMapController.cs performs most of the logic in this project.

# Point Clouds
This shows just the current frame's feature points with the "AR Default Point Cloud" prefab.

# Plane Detection 
This project shows how to toggle plane detection on and off. When off, it will also hide all previously detected planes by disabling their GameObjects. See PlaneDetectionController.cs.

## Dependencies
This project primarily relies on the following packages and technologies:
- AR Foundation
- ARKit XR Plug-in
- Unity

### Prerequisites
The main branch of this repository uses AR Foundation 6.0 and is compatible with Unity 2023.2 and newer. 
To get started with this project, you'll need:
- Unity 6 (6000.0) 	6.0 (main)
- [Unity 2023.2 or later](https://unity.com/)
- [ARKit XR Plug-in](https://developer.apple.com/arkit/)
- An iOS device with ARKit support

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/your-repository.git
    ```
2. Install the required dependencies:
    ```sh
    cd your-repository
    # command to install dependencies
    ```

### Build and Run
To build and run the project on your iOS device, follow these steps:

1. Install Unity and the required dependencies as mentioned above.
2. Open the project in Unity.
3. Configure the build settings for iOS.
4. Build the project and deploy it to your iOS device.

## Usage
All scenes can be found in the `Assets/Scenes` directory. To explore and understand the code:
1. Open a scene in Unity.
2. Review the code and comments provided.
3. Modify and experiment with the code to understand how it works.

## Contributing
We welcome contributions to improve and expand this project. To contribute:
1. Fork this repository.
2. Create a new branch with your feature or bug fix.
3. Commit your changes.
4. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

If you have any questions or encounter any issues, please open an issue in this repository or contact us.

Happy coding!
