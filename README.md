# Research Paper Notes Manager

A Python desktop application for manually organizing research paper reading notes, comparing studies, tracking research limitations and potential research gaps, and exporting notes to Excel.

## Features

- Manual entry for ten research paper note sections
- Save, edit, search, and delete research paper entries
- Compare multiple papers side by side
- Track author-reported limitations and potential research gaps
- Light and dark themes
- Export notes to Excel (`.xlsx`) and CSV
- Local SQLite database storage

## Technology Stack

- Python
- Tkinter for the desktop interface
- SQLite for local data storage
- OpenPyXL for Excel export

## Requirements

- Python 3
- Tkinter, usually included with standard Windows Python installations
- OpenPyXL for Excel export

## Installation on Windows

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Install the optional Excel export dependency:

   ```powershell
   python -m pip install -r requirements.txt
   ```

4. Run the application:

   ```powershell
   python Research_Paper_Notes_Manager.py
   ```

## Data and Privacy

The application stores research entries in a local SQLite database. Keep your database backed up. Do not upload personal notes, unpublished research, or private data to a public repository.

## Project Purpose

This project was created to support a manual research paper reading and comparison workflow, particularly for students conducting academic research.

## License

Distributed under the MIT License. See the `LICENSE` file for details.
