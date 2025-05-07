# Data Folder
This folder serves as the **main container for all datasets and their related subfolders** used in the project.
It includes:
- `unzipped/`: Contains the **unzipped versions of the IMDb datasets** (intermediate files after extraction).
- `csv/`: Contains the datasets **converted to CSV format** for easier analysis.
- `cleaned/`: Contains the **cleaned and preprocessed data** ready for SQL analysis.

**Note:** The entire `data/` folder is **excluded from Git tracking** (via `.gitignore`) to prevent large raw files from being committed to the repository. Only the `README.md` files inside each subfolder are tracked to maintain folder structure and provide documentation.
