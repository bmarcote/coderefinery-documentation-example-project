
# Code Refinery Documentation Example Project

Project to analyze a Excel spreadsheet file containing temperature measurements.



## Requirements

This is a Python (2.7 or 3) program that only requires `panda`.


## Usage

You can import `analyse_spreadsheet` as a Python module.

```python

import analyse_spreadsheet

# For an interactive usage
analyse_spreadsheet.main()

# For a direct usage
data = analyse_spreedsheet.get_spreadsheet_columns(file_loc, print_columns=False)
analyse_spreedsheet.mean_temperature(data)
```


