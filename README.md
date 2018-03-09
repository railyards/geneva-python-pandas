# Module: Working with Data Using Pandas

## Meta-Information

*   Module Maintainer: Lachlan Deer (`@lachlandeer`)
*   Course: [SWC Geneva](https://lachlandeer.github.io/2018-03-08-geneva/)

## Contents

This repository contains a relatively quick introduction to the Python library Pandas using a dataset on US state employment numbers.
Pandas is the default library for data-wrangling in Python and has fast become a competitor to R's libraries like `dplyr` and `data.table.`

Contents of these modules will be taught at the 2017 edition of 'Programming Practices for Research in Economics' at the University of Zurich.

In this set of modules (aimed at a roughly 3/4 day schedule) we introduce

1.  Pandas Objects
2.  How to import and export data to/from python using pandas
3.  How to concatenate/append/merge data sets together
4.  How to index and select rows and columns of data
5.  Performing simple operations on data using ufuncs
6.  Ways to handle missing data
7.  The benefits of hierachical indexing
8.  Aggregate functions and the application of the split-apply-combine paradigm

In additon, the aptly named `XX-downloadingDataAPI` demonstrates how the use the BLS API to download all the data series utilized in these modules.
To keep things easy and reproducible, the data we use are stored in `notebooks/data`, and any output data we produce will be stored in `notebooks/out_data

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

`
