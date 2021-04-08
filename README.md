# JBJupyterCorpus by Agroskin Alexander
Task for JetBrains summer internship. Small notebook for basic jupyter notebook analysis.

The solution itself can be located in `task.ipynb`. I preloaded five tables for analysis, they are located in the `notebooks` directory. To load more, add their names to `notebooks/addresses.txt`. The program has an option to pull them using `wget` (will not work on Windows).

Also included is a `languages.json` file with a dictionary for transforming language abbreviations to their names. Original file has been taken from the [cldr-localenames-modern](https://github.com/unicode-cldr/cldr-localenames-modern) repository.

All results are saved as `.csv` files in the `tables` directory.
