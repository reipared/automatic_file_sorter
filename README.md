# Automatic File Sorter in File Explorer

## Overview

This Python script automatically organizes files in a specified directory by moving them into categorized folders based on their extensions. It currently sorts Excel (`.xlsx`), image (`.jpg`), and text (`.txt`) files into separate folders.

## Features

- Automatically creates destination folders if they do not exist.
- Moves files to their respective folders based on file extension.
- Prevents duplicate moves by checking if the file already exists in the target folder.

## Prerequisites

- Python 3.x installed on your system

## Installation

1. Clone this repository:

   ```sh
   git clone https://github.com/yourusername/Automatic-File-Sorter.git
   ```

2. Navigate to the project folder:

   ```sh
   cd Automatic-File-Sorter
   ```

## Usage

1. Modify the `path` variable in `Automatic_File_Sorter_in_File_Explorer.py` to point to your target directory.

2. Run the script:

   ```sh
   python Automatic_File_Sorter_in_File_Explorer.py
   ```

3. The script will organize files into the following folders:
   - `xlsx files/`
   - `image files/`
   - `text files/`

## Notes

- You can extend the script to support additional file types by modifying the conditional statements.
- The script currently supports `.xlsx`, `.jpg`, and `.txt` file types.
