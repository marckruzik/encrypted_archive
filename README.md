# Encrypted Archive

A Polyglot Notebook to find all encrypted archives on disk. It uses Everything from voidtools to list all files in real time, export the data to a CSV file via a command line in a PowerShell cell, then tests all archives with 7-zip through C# cells.
See links below to install all the necessary software.

## Installation
- install Everything v1.5a
  - https://www.voidtools.com/everything-1.5a/ or https://www.voidtools.com/downloads/
- install Everything Command Line Interface (it's another executable `es.exe`)
  - https://www.voidtools.com/downloads/#cli
  - put es.exe in the same folder than Everything v1.5a
- install 7-zip (to test if an archive has at least 1 encrypted file)
  - https://www.7-zip.org/

## VS Code installation
- install VS Code
  - https://code.visualstudio.com/
- install the VS Code extension Polyglot Notebook
  - https://code.visualstudio.com/docs/languages/polyglot

## Usage
In the notebook, there are a few hardcoded paths to software (`C:\Program Files\Something\something.exe`), replace those paths with your own.
