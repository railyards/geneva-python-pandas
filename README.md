# Module: Working with Data Using Pandas

## Meta-Information

*   Module Maintainer: Lachlan Deer (`@lachlandeer`)
*   Course: [SWC Geneva](https://lachlandeer.github.io/2018-03-08-geneva/)

## Contents

This repository contains a relatively quick introduction to the Python library Pandas using a dataset on US state employment numbers.
Pandas is the default library for data-wrangling in Python and has fast become a competitor to R's libraries like `dplyr` and `data.table.`

Contents of these modules will be taught at a Software Carpentry Workshop at the University of Geneva in March 2018.

The goals of the lesson are to:
1.  Introduce Pandas Objects
2.  How to import and export data to/from python using pandas
3.  How to concatenate/append/merge data sets together
4.  How to index and select rows and columns of data
5.  Performing simple operations on data using ufuncs
6.  Ways to handle missing data
7.  The benefits of hierachical indexing
8.  Aggregate functions and the application of the split-apply-combine paradigm
9.  Plotting data from pandas dataframes using matplotlib


In additon, the aptly named `XX-downloadingDataAPI` demonstrates how the use the BLS API to download all the data series utilized in these modules.
To keep things easy and reproducible, the data we use are stored in `in_data`, and any output data we produce will be stored in `out_data

## Acknowledgements

This repository borrows almost one to one from:

```
Lachlan Deer, Adrian Etter, Julian Langer & Max Winkler, 2017, Scientfic Python - Quick-ish and Dirty Pandas for Economists, Programming Practices for Research in Economics, University of Zurich
```

and borrows substance, style and motivation from:

```
Jake VanderPlas (2016), Python Data Science Handbook Essential Tools for Working with Data, O'Reilly Media.
```

at times, maybe too liberally.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />
