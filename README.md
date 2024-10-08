# Unused Tag Cleaner

UnusedTagCleaner is a Unity Editor tool designed to help maintain a clean and efficient project structure by identifying and removing unused tags from the Tag Manager. This tool is particularly useful for larger Unity projects with multiple contributors, where managing tags can become cumbersome.

## Features

- **Comprehensive Tag Scan**: Scans all enabled scenes, assets, and prefabs, and C# script files in the project to determine which tags are in use, capturing both statically placed objects in scenes and dynamically assigned tags in scripts.
- **Configurable Scan Options**: Includes an option to extend the scan to assets and prefabs, allowing for a more thorough cleanup.
- **Identify Unused Tags**: Lists all tags that are not used in any part of the project, whether in scenes, assets, prefabs, or assigned programmatically in scripts.
- **Remove Unused Tags**: Provides an option to delete all identified unused tags with a single click, keeping your Tag Manager clean and relevant.

## Installation

1. Clone this repository or download the latest release.
2. Copy the `UnusedTagCleaner.cs` script into the `Assets/Editor` folder within your Unity project. If the folder doesn't exist, create it.

## Usage

1. Open your Unity project.
2. Navigate to `Tools > Unused Tags Remover` in the Unity menu bar to open the UnusedTagCleaner window.
3. Use the checkbox to select whether to include assets and prefabs in the scan.
4. Click on `Scan for Unused Tags` to start the scanning process. The tool will analyze all enabled scenes, assets, prefabs, and C# scripts to compile a comprehensive list of unused tags.
5. Review the list of unused tags displayed in the tool window.
6. If you decide to clean up, click on `Remove All Unused Tags` to delete them from the project.

## Contribution

Contributions to UnusedTagCleaner are welcome. Please feel free to fork the repository, make changes, and submit a pull request with your improvements.

## Bonus Script

The `Tag Usage` folder includes a supplementary script designed to analyze the usage of any remaining tags in your Unity project, providing a detailed review of how these leftover tags are employed across scenes and scripts, especially useful after a cleanup process where unused tags have been removed.

## License

Distributed under the MIT License. See `LICENSE` file for more information.

## Support

If you encounter any issues or have suggestions for improvements, please open an issue in this GitHub repository.
