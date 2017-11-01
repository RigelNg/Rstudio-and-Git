# Genes
Rigel  
November 1, 2017  





 The data set 'Genes' contains a single response Y (whether the leaf length for a particular plant was bigger than average) and p = 3,235 genetic markers. 
 . If Y = 1, then the leaf length is greater than average for that plant and Y = 0 otherwise. 
 . The genetic markers are coded as 1, 0.5, 0. A higher value suggests that the gene is more 'switched on'. You may treat these as continuous variables. 
 
 The Question?
 . Determine which, if any, of the genetic markers are associated with with a greater than average leaf length.


```r
library(readxl)
genes<- read_excel("C:/Users/Rigel/Desktop/Final Semester/STAT learning individual Assignment/Genes_Data_converted.xlsx")

head(genes)
```

```
## # A tibble: 6 × 3,237
##       Y   GM1   GM2   GM3   GM4   GM5   GM6   GM7   GM8   GM9  GM10  GM11
##   <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl>
## 1     1     0     0     0     1   0.5     0     0     0   0.5     1     1
## 2     2     0     0     0     1   0.5     0     0     0   0.5     1     1
## 3     3     0     0     0     1   0.5     0     0     0   0.5     1     1
## 4     4     0     0     0     1   0.5     0     0     0   0.5     1     1
## 5     5     1     0     0     1   0.5     0     0     0   0.5     1     1
## 6     6     1     0     0     1   0.5     0     0     0   0.5     1     1
## # ... with 3225 more variables: GM12 <dbl>, GM13 <dbl>, GM14 <dbl>,
## #   GM15 <dbl>, GM16 <dbl>, GM17 <dbl>, GM18 <dbl>, GM19 <dbl>,
## #   GM20 <dbl>, GM21 <dbl>, GM22 <dbl>, GM23 <dbl>, GM24 <dbl>,
## #   GM25 <dbl>, GM26 <dbl>, GM27 <dbl>, GM28 <dbl>, GM29 <dbl>,
## #   GM30 <dbl>, GM31 <dbl>, GM32 <dbl>, GM33 <dbl>, GM34 <dbl>,
## #   GM35 <dbl>, GM36 <dbl>, GM37 <dbl>, GM38 <dbl>, GM39 <dbl>,
## #   GM40 <dbl>, GM41 <dbl>, GM42 <dbl>, GM43 <dbl>, GM44 <dbl>,
## #   GM45 <dbl>, GM46 <dbl>, GM47 <dbl>, GM48 <dbl>, GM49 <dbl>,
## #   GM50 <dbl>, GM51 <dbl>, GM52 <dbl>, GM53 <dbl>, GM54 <dbl>,
## #   GM55 <dbl>, GM56 <dbl>, GM57 <dbl>, GM58 <dbl>, GM59 <dbl>,
## #   GM60 <dbl>, GM61 <dbl>, GM62 <dbl>, GM63 <dbl>, GM64 <dbl>,
## #   GM65 <dbl>, GM66 <dbl>, GM67 <dbl>, GM68 <dbl>, GM69 <dbl>,
## #   GM70 <dbl>, GM71 <dbl>, GM72 <dbl>, GM73 <dbl>, GM74 <dbl>,
## #   GM75 <dbl>, GM76 <dbl>, GM77 <dbl>, GM78 <dbl>, GM79 <dbl>,
## #   GM80 <dbl>, GM81 <dbl>, GM82 <dbl>, GM83 <dbl>, GM84 <dbl>,
## #   GM85 <dbl>, GM86 <dbl>, GM87 <dbl>, GM88 <dbl>, GM89 <dbl>,
## #   GM90 <dbl>, GM91 <dbl>, GM92 <dbl>, GM93 <dbl>, GM94 <dbl>,
## #   GM95 <dbl>, GM96 <dbl>, GM97 <dbl>, GM98 <dbl>, GM99 <dbl>,
## #   GM100 <dbl>, GM101 <dbl>, GM102 <dbl>, GM103 <dbl>, GM104 <dbl>,
## #   GM105 <dbl>, GM106 <dbl>, GM107 <dbl>, GM108 <dbl>, GM109 <dbl>,
## #   GM110 <dbl>, GM111 <dbl>, ...
```

