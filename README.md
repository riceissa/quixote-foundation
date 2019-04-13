# Quixote Foundation

This is for Vipul Naik's Donations List Website: https://github.com/vipulnaik/donations

Specific issue: https://github.com/vipulnaik/donations/issues/97

## Instructions for getting SQL file

Go to http://quixotefoundation.org/grants/

At the bottom of the page, there should be a link that says "Download Grant List".
At the moment this links to http://hdl.handle.net/2450/11391 which redirects to https://archives.iupui.edu//handle/2450/11391 but this link might change in the future.

Click the link "View/Open" to download the XLSX file. Open this file and save as CSV, e.g. `grants.csv`.

Run the processing script to convert the CSV to SQL:

```bash
./proc.py grants.csv > out.sql
```

## License

CC0 for python and readme.

The license for the data is: "This work is licensed under the Creative Commons
Attribution 4.0 International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by/4.0/. This means the data is freely
accessible to anyone to be used and shared as they wish. The data must be
attributed to the Foundation."
