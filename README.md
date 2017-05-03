findbig
=======

A command-line utility for finding the biggest files in a directory tree.

```
usage: findbig [-h] [-v] [-f FORMAT] [-l LIMIT] [-u {k,b,g,m,t}] [-r ROUND]
               [-m MIN_SIZE]
               base_dir

Find large files in a directory

positional arguments:
  base_dir              Root dir to begin search

optional arguments:
  -h, --help            show this help message and exit

output options:
  -v, --verbose         Enable verbose output
  -f FORMAT, --format FORMAT
                        Output format
  -l LIMIT, --limit LIMIT
                        Limit result count
  -u {k,b,g,m,t}, --unit {k,b,g,m,t}
                        Convert sizes to unit
  -r ROUND, --round ROUND
                        Number of places to round to
  -m MIN_SIZE, --min-size MIN_SIZE
                        Ignore files smaller than threshold
```
