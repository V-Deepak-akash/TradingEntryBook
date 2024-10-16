# Trading Entry Book

This Python application is a trading entry book designed to manage stock and option entries, deposits, and real-time portfolio tracking. It features a Tkinter-based GUI and supports graphical analysis of portfolio performance.

## Features
- Add, delete, and update deposits.
- Manage stock and option entries.
- Real-time updates of portfolio performance.
- Analyze portfolio performance with graphs.
- Export data to Excel.
- User-friendly interface for managing trading details.

## Requirements
To run this project, you need:
- Python 3.x
- Tkinter
- SQLite3
- Matplotlib
- Openpyxl (for handling Excel files)

You can install the required libraries using:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/V-Deepak-akash/TradingEntryBook
2. Navigate to the project directory:
   ```bash
   cd trading-entry-book
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the application:
   ```bash
   python main.py

## Creating an Executable (.exe) with PyInstaller
To create an executable version of this program using PyInstaller, follow these steps:

Install PyInstaller:
```bash
pip install pyinstaller
```
Run the following command to create an executable file:
```bash
pyinstaller --onefile --windowed main.py
```
This will generate an executable file in the dist folder, which can be shared and run without needing Python installed.
Requirements

## How to Use
1. Launch the application.
2. Add clients and deposit entries.
3. Add stock/option trades.
4. Analyze portfolio performance and view real-time updates.

## Contribution
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

