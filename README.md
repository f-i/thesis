# What's in "chapter4data" folder

For example,

"Fay18_101comb_10_5_0_0" folder contains the results for the 20%, 40%, 60% and
80% data density reduced experiments.

The folder name also gives necessary information:

F: Reference path is derived from the Fixed hotspot model;

ay18: Polygons used to constrain paleomagnetic data are from Young et al. 2019

101comb: The polygons used are PlateID 101 combined with its children, e.g.
here 108 and 109;

10: Moving window size is 10 Myr for the moving averaging method used;

5: Moving step size is 5 Myr for the moving averaging method used;

0: The picking method used is No. 0 (AMP, Age Mean Picking; see Table 2 in
chapter 3);

0: The weighting method used is No. 0 (no weighting; see Table 3 in chapter 3).


## What's in these "Fay18_?01comb_?_?_?_?" folders

For example, the "_2" folder contains all the results from the 80% data density
reduced (i.e. only 20% left) experiments; the "_4" folder contains all the
results from the 60% data density reduced (i.e. only 40% left) experiments; and
so on.


### What's in these "_2", "_4", "_6" and "_8" folders

They contain results from at least 30 experiments, where the folder names are
000, 001, 002, ... 029, and so on. Sometimes, we have more than 30 experiments,
for example, there are 1390 experiments in the "_8" folder for
"Fay18_101comb_10_5_0_0" (see Figure 4.6 in chapter 4).


#### What's in these "000", "001", ... "029" folders

For example,

000/ay18_101comb contains: Plate 101's paleomagnetic path
ay18_101comb_10_5_0_0.txt and its subfolder "10_5_simil" that contains
similarity measuring result;

000/ay18/101comb contains: Plate 101's raw paleopoles "ay18_101comb_alldat.d",
paleopoles after filtering "ay18_101comb_0_0.d" and (sub-folder
"ay18_101comb_10_5_0_0") paleopoles in each sliding window with weights and rock
types "ay18_101comb_10_5_0_0/upperAge_lowerAge.d".
