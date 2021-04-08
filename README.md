# JBJupyterCorpus by Agroskin Alexander
Task done for the JetBrains summer internship application. Small python notebook for basic `.ipynb` file analysis.

The solution itself can be found in `task.ipynb`. I've preloaded five tables for analysis, which are located in the `notebooks` directory. To load more, add their names to `notebooks/addresses.txt` and run the corresponding cell. The program has an option to pull them using `wget` (will not work on Windows).

Also included is a `languages.json` file with a dictionary for transforming language abbreviations to their names. Original file has been taken from the [cldr-localenames-modern](https://github.com/unicode-cldr/cldr-localenames-modern) repository.

All results are saved as `.csv` files in the `tables` directory.
