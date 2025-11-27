JPG File Organizer

Description

This Python script automatically scans a source folder, identifies all `.jpg` image files, and moves them into a destination folder.
It also generates a log file (`moved_files_log.txt`) to record all moved files along with the timestamp of each run.
This is useful for organizing photos, backups, automation workflows, and cleaning large directories.




Libraries Used
1. os (Built-in Library)

The os module is used to interact with the operating system.
In this script, it helps with:

Accessing directory paths

Listing files inside a folder

Creating folders if they don’t already exist

2. shutil (Built-in Library)

The shutil module provides high-level file operations.
In this script, it is used to:

Move JPG files from the source folder to the destination folder

3. datetime (Built-in Library)

The datetime module is used to work with dates and timestamps.
In this script, it is used to:

Add a timestamp to the log file to record when the script was executed



Functions & Classes Explanation

Function: `move_jpg_files(source_folder, destination_folder)`

This is the main function in the program.

Parameters:

* `source_folder` — The directory containing JPG files to move
* `destination_folder` — The folder where JPG files will be transferred

What it does:

1. Creates destination folder if it doesn’t exist
2. Creates/updates a log file inside the destination folder
3. Loops through all files in the source folder
4. Checks if the file ends with `.jpg`
5. Moves each JPG file to the destination folder
6. Logs and prints each moved filename
7. Prints total files moved and location of log file



```python
class JPGFileOrganizer:
    def __init__(...):
        ...
    def move_files(self):
        ...
    def write_log(self):
        ...
```

License 



Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


If you want, I can also generate a **README.md**, **GitHub-ready project structure**, or **OOP-version of the script**.
