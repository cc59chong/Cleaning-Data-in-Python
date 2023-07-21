# Cleaning-Data-in-Python [Notes](https://github.com/cc59chong/Cleaning-Data-in-Python/blob/main/Cleaning%20Data%20in%20Python.ipynb)
You will learn how to identify, diagnose, and treat a variety of data cleaning problems in Python, ranging from simple to advanced. You will deal with improper data types, check that your data is in the correct range, handle missing data, perform record linkage, and more!
## 1 -- Common data problems
Convert data types, apply range constraints to remove future data points, and remove duplicated data points to avoid double-counting.
**Keywords**: `df.info()`, `df.describe()`, `strip()`, `pd.to_datetime`, `dt.date`, `.duplicated()`, `.sort_values()`, `.drop_duplicates()`, `.agg()`, `.reset_index()`
## 2 -- Text and categorical data problems
Learn how to fix whitespace and capitalization inconsistencies in category labels, collapse multiple categories into one, and reformat strings for consistency.
**Keywords**: `.unique()`, `.difference()`, `.isin()`, `.replace()`, `np.ihf`, `.any()`
## 3 -- Advanced data problems
In this chapter, you’ll dive into more advanced data cleaning problems, such as ensuring that weights are all written in kilograms instead of pounds. You’ll also gain invaluable skills that will help you verify that values have been added correctly and that missing values don’t negatively impact your analyses.
**Keywords**: `dt.strftime()`, `.sum(axis = 1)`, `missingno package`, `msno.matrix()`,  `dropna()`, `filln()`, `isna()`
## 4 -- Record linkage
Record linkage is a powerful technique used to merge multiple datasets together, used when values have typos or different spellings. In this chapter, you'll learn how to link records by calculating the similarity between strings—you’ll then use your new skills to join two restaurant review datasets into one clean master dataset.
**Keywords**: `Minimum edit distance `, `thefuzz package`, 'fuzz package`, `fuzz.WRatio()`, `the cutoff point`, `process.extract()`, ` recordlinkage package`, ` recordlinkage.Index()`, `indexer.block()`, `indexer.index()`, ` recordlinkage.Compare()`, `.exact()`, `.string()`, `.compute()`, `.get_level_values()`, `.append()`
