# Sharing data for StackOverflow question "[Efficient random subsample of a Pandas DataFrame based on multiple columns target requirements](https://stackoverflow.com/questions/76602474/efficient-random-subsample-of-a-pandas-dataframe-based-on-multiple-columns-targe)"
Sharing landcover polygons for testing solvers.
The 

The nvis_coverages.zip contains a .csv which is a Pandas dataframe where each row is a polygon and each column is a landcover class (except the last one which holds an ID) and the data represent the km2.
Here are the requirement for each class:

```
requirements = {
    'n20': 3303.7292716545867,
    'n25': 20000.0,
    'n5': 20000.0,
    'n16': 8021.141548475252,
    'n19': 4200.447337901741,
    'n22': 6567.771622569943,
    'n6': 1379.5100180481845,
    'n11': 1817.5786788061553,
    'n13': 303.3236915947854,
    'n3': 2902.012680251818,
    'n14': 418.7979685395164,
    'n12': 129.30788772142273,
    'n31': 378.1389107682131,
    'n17': 395.1574776551615,
    'n21': 263.51311223960766,
    'n9': 75.72543827917868,
    'n24': 272.0939149493426,
    'n27': 38.19399520147138,
    'n10': 23.84553439644266,
    'n2': 221.1534108804731,
    'n18': 27.85508348775362,
    'n7': 113.37502841343009,
    'n8': 20.0,
    'n1': 33.81356577597002,
    'n29': 74.07903352835932,
    'n15': 20.0,
    'n32': 20.0,
    'n28': 20.0,
    'n4': 20.0,
    'n23': 20.0,
    'n26': 20.0,
    'n30': 20.0
}
```

ps.: Thanks Sebastian Wozny (@arpheno)!
