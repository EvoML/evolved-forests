#Evolved Forest 

Using Genetic Programming to grow forests for regression and classification. Metafeatures are used to reduce the exploration space and aid the GP to come with the better informed forests.
Hunch is to see if GP can grow better trees than randomised generation of forests. 

Repo contains notebooks for different experiments.

## Subsampling
Currently subspacing based methods have been explored. Each tree in the GP decides which rows to keep based on simple rules. 
Eg. 
```
Feature_3 should be greater than 3 and Feature_4 < 2.
```
## Subspacing
[todo] Feature level metafeatures need to be extracted and made as primitives to be fed to GP. 

##Fitness and Selection methods being explored
 - true_probablity variance
 - Custom difficulty scores per row.
 - Lexicase Selection
 - Implicit Fitness pressure.
 - Private Holdout Fitness
 - Out of Bag Error Fitness



Multi-objective evolution and Pareto front are also being explored combining above methods.


