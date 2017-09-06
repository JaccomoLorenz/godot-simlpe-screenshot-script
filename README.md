# Simple Screenshot Script

A simlpe script for the godot engine version 2.1 (3.0 planned) to make screenshots and save it as png file in a custom directory.

## Test Scene

There is a simple test scene "demo.tscn" where you can test the script if you want (Press F11 make screenshots).
Otherwise you can just can download/copy the screenshot.gd from the scripts folder into your project folder.

### Script variables/Settings

- Shortcut Action: The name of an action from the Input Map that should trigger the screenshot creation.
- File Prefix: An optional prefix for the filenames, you can leave it empty. 
- File Tag: At the moment you can choose between two timestamps that becomes part of the file name. 1. A simple date + time stamp or 2. A unix timestamp.
            
            Name format: Prefix_timestamp_*index 
            *The index resets every second to just differ multiple images within a second that have the same timestamp
- Output Path: The directory where you want to save your screenshots.

## License

All parts of this project that are not copyrighted or licensed by someone else are released under the MIT License - see the LICENSE.md file for details.


