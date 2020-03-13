### Some samples from the household data, we have all together 1973 clean data points:
|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education    | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:-------------|:-------|:--------------|
|   1999 |       1531 |             0 |           4 |        39 |         234848 |        704545 |         23175.3 |        78945.4 |               1 |             469696 |       352272 |                   1115530 |                1373863 | Married         | Working            | postGraduate | White  | finance       |
|   2001 |       3921 |             0 |           4 |        41 |         221212 |       1106060 |         16642.7 |        60187.4 |               1 |             331818 |       276515 |                    895909 |                1371515 | Married         | Working            | postGraduate | White  | finance       |
|   2003 |       3828 |             0 |           4 |        43 |         742424 |        981060 |         29959.1 |       112988   |               1 |             530303 |       371212 |                   2169469 |                2636136 | Married         | Working            | postGraduate | White  | finance       |
|   2005 |       1453 |             0 |           4 |        45 |         200000 |        875000 |         45581.4 |       182326   |               1 |             130000 |       400000 |                   1518000 |                2618000 | Married         | Working            | postGraduate | White  | finance       |
|   2007 |        925 |             1 |           3 |        47 |          93939 |        947848 |         76452.9 |       244156   |               1 |            3287878 |       751515 |                   5326363 |                6430151 | Married         | Working            | postGraduate | White  | finance       |
|   2009 |       1857 |             1 |           2 |        49 |          18181 |       1181818 |        128192   |       282022   |               1 |            3636363 |            0 |                   5668181 |                6464545 | Married         | Working            | postGraduate | White  | finance       |
|   2011 |       3042 |             0 |           2 |        51 |        1742424 |       1132575 |         74585.2 |       171222   |               1 |            2178030 |      1306818 |                   7222348 |                8285227 | Married         | Working            | postGraduate | White  | finance       |
|   2013 |       2245 |             0 |           2 |        53 |        4204545 |        845113 |         68821.9 |       163685   |               1 |             504545 |       420454 |                   8071045 |                8962409 | Married         | Working            | postGraduate | White  | finance       |
|   2015 |       3920 |             0 |           2 |        55 |         330303 |        198181 |         62492.4 |       151358   |               1 |            2477272 |      1651515 |                  10032954 |               10032954 | Married         | Working            | postGraduate | White  | finance       |
|   2017 |       6742 |             0 |           2 |        57 |        2386363 |             0 |         35199.8 |        88502.3 |               1 |            3977272 |      1590909 |                  12082954 |               12759090 | Married         | retired            | postGraduate | White  | otherIndustry |


|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education    | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:-------------|:-------|:--------------|
|   1999 |       5844 |             2 |           2 |        44 |           5871 |        176136 |         50105.2 |        85340.4 |               1 |             106856 |            0 |                    160284 |                 217821 | Separated       | Working            | postGraduate | White  | finance       |
|   2001 |       4520 |             2 |           2 |        46 |           1106 |        265454 |         35404.3 |        64018.8 |               1 |              82954 |       663636 |                    830651 |                 963378 | Separated       | Working            | postGraduate | White  | finance       |
|   2003 |       5443 |             0 |           2 |        49 |          37121 |        357424 |         44336.2 |        83605.4 |               1 |              26515 |            0 |                    148484 |                 275757 | Married         | Working            | postGraduate | White  | finance       |
|   2005 |       2257 |             0 |           2 |        50 |          75000 |        311000 |         64681   |       129362   |               1 |              75000 |        10000 |                    203000 |                 463000 | Married         | Working            | postGraduate | White  | finance       |
|   2007 |       5616 |             0 |           2 |        52 |          46969 |        385151 |         51094.5 |       108782   |               1 |              46969 |        56363 |                    247060 |                 716757 | Married         | Working            | postGraduate | White  | finance       |
|   2009 |       3454 |             0 |           2 |        54 |           3636 |        420000 |         50995.9 |       112191   |               1 |              18181 |         9090 |                     55454 |                 460000 | Married         | Working            | postGraduate | White  | finance       |
|   2011 |       4406 |             0 |           2 |        56 |          13068 |        339772 |         55870.8 |       128260   |               1 |               8712 |         8712 |                    101931 |                 328446 | Married         | Working            | postGraduate | White  | finance       |
|   2013 |       1973 |             0 |           2 |        58 |          33636 |        336363 |         40164.9 |        95527.3 |               1 |              16818 |        12613 |                    210227 |                 462500 | Married         | Working            | postGraduate | White  | finance       |
|   2015 |       1626 |             0 |           2 |        60 |          82575 |        371590 |         42445.8 |       102804   |               1 |              20643 |        12386 |                    181666 |                 322045 | Married         | Working            | postGraduate | White  | finance       |
|   2017 |       1355 |             0 |           2 |        62 |          23863 |        509090 |         51497.9 |       129481   |               1 |              19886 |        11931 |                    194886 |                 393750 | Married         | Working            | postGraduate | White  | otherIndustry |


|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education    | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:-------------|:-------|:--------------|
|   1999 |       4597 |             0 |           1 |        50 |            469 |         58125 |         45322.2 |        38597   |               0 |                  0 |            0 |                      2583 |                  17848 | Divorced        | Working            | postGraduate | Black  | service       |
|   2001 |       5025 |             0 |           1 |        53 |              0 |         59727 |         29251.4 |        26446.5 |               0 |                  0 |       442424 |                    453484 |                 475606 | Divorced        | Working            | postGraduate | Black  | service       |
|   2003 |       4864 |             0 |           1 |        55 |            424 |         75257 |         27971.5 |        26373.2 |               0 |                  0 |            0 |                      8909 |                  49212 | Divorced        | Working            | postGraduate | Black  | service       |
|   2005 |       6701 |             0 |           1 |        57 |           2000 |         59600 |         72130   |        72130   |               0 |                  0 |        98000 |                    130000 |                 153000 | Divorced        | Working            | postGraduate | Black  | service       |
|   2007 |       5303 |             0 |           1 |        59 |            563 |             0 |         48927.2 |        52083.8 |               0 |                  0 |        46969 |                    113290 |                 184684 | Divorced        | retired            | postGraduate | Black  | service       |
|   2009 |       4995 |             0 |           1 |        61 |            272 |           363 |         31907.9 |        35098.7 |               0 |                  0 |            0 |                     18454 |                 113909 | Divorced        | retired            | postGraduate | Black  | service       |
|   2011 |       2740 |             0 |           1 |        62 |              0 |             0 |         24795.7 |        28461.2 |               0 |                  0 |            0 |                     24393 |                  87992 | Divorced        | retired            | postGraduate | Black  | service       |
|   2013 |       6246 |             0 |           1 |        65 |            840 |             0 |         30736   |        36550.9 |               0 |                  0 |            0 |                       672 |                   5718 | Divorced        | retired            | postGraduate | Black  | service       |
|   2015 |       6032 |             0 |           1 |        67 |            330 |             0 |         32305.4 |        39122.2 |               0 |                  0 |            0 |                     16845 |                  44095 | Divorced        | retired            | postGraduate | Black  | service       |
|   2017 |       5641 |             0 |           1 |        69 |             39 |             0 |         33020   |        41510.9 |               0 |                  0 |            0 |                      7994 |                  99471 | Divorced        | retired            | postGraduate | Black  | otherIndustry |


|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education   | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:------------|:-------|:--------------|
|   1999 |       2909 |             0 |           4 |        40 |            234 |             0 |         4757.17 |       16205.1  |               0 |                  0 |            0 |                     -5401 |                  -5401 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2001 |       2925 |             0 |           4 |        42 |             39 |          1327 |         5710.38 |       20651.3  |               0 |                  0 |            0 |                     -5711 |                  -5711 | Divorced        | Working            | highSchool  | White  | service       |
|   2003 |       1552 |             0 |           4 |        44 |             42 |             0 |         3342.6  |       12606.4  |               0 |                  0 |            0 |                     -7169 |                  -7169 | Divorced        | unemployed         | highSchool  | White  | service       |
|   2005 |        902 |             1 |           5 |        46 |            574 |             0 |         3201.9  |       16009.5  |               0 |                  0 |            0 |                     -7926 |                  -7926 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2007 |       6678 |             1 |           6 |        48 |              9 |             0 |         2212.62 |       14132.2  |               0 |                  0 |            0 |                     -9384 |                  -9384 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2009 |       3070 |             1 |           7 |        50 |              4 |             0 |         2436.95 |       18764.5  |               0 |                  0 |            0 |                      1822 |                   1822 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2011 |       1197 |             0 |           7 |        52 |           1188 |             0 |         1223.09 |        9827.27 |               0 |                  0 |            0 |                      1972 |                   1972 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2013 |       3042 |             1 |           8 |        54 |              8 |             0 |         1693.22 |       16108.5  |               0 |                  0 |            0 |                        47 |                     47 | Divorced        | keepHouse          | highSchool  | White  | service       |
|   2015 |        428 |             0 |           8 |        56 |            206 |             0 |         1621.26 |       15706.9  |               0 |                  0 |            0 |                     12262 |                  12262 | Divorced        | disabled           | highSchool  | White  | service       |
|   2017 |       2619 |             1 |           9 |        58 |             11 |             0 |         3344    |       37835    |               0 |                  0 |            0 |                     18307 |                  18307 | Divorced        | disabled           | highSchool  | White  | otherIndustry |


|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education    | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:-------------|:-------|:--------------|
|   1999 |       5568 |             0 |           1 |        44 |              0 |          3170 |         6032.45 |        5137.31 |               0 |                  0 |            0 |                     -1526 |                  -1526 | Divorced        | jail               | highSchool   | Black  | manufacturing |
|   2001 |       1688 |             0 |           1 |        46 |              0 |             0 |         1468.04 |        1327.27 |               0 |                  0 |            0 |                         0 |                      0 | Divorced        | disabled           | highSchool   | Black  | manufacturing |
|   2003 |       2067 |             0 |           1 |        48 |            212 |         12727 |        15624.7  |       14731.8  |               0 |                  0 |            0 |                      2015 |                   2015 | Divorced        | Working            | college      | Black  | manufacturing |
|   2005 |       4901 |             2 |           2 |        50 |              0 |         21000 |         6541    |       13082    |               0 |                  0 |            0 |                         0 |                      0 | Married         | Working            | college      | Black  | manufacturing |
|   2007 |       1667 |             0 |           2 |        52 |              0 |         19727 |         8898.74 |       18945.7  |               0 |                  0 |            0 |                      1221 |                   1221 | Married         | Working            | college      | Black  | manufacturing |
|   2009 |       5390 |             0 |           2 |        54 |              0 |          3636 |         2652.89 |        5836.36 |               0 |                  0 |            0 |                         0 |                      0 | Married         | disabled           | highSchool   | Black  | manufacturing |
|   2011 |       3565 |             0 |           2 |        56 |              0 |         18243 |        11250.1  |       25826.2  |               0 |                  0 |            0 |                      2613 |                   2613 | Married         | unemployed         | highSchool   | Black  | manufacturing |
|   2013 |       1501 |             0 |           2 |        58 |              0 |          4460 |         7330.09 |       17433.7  |               0 |                  0 |            0 |                         0 |                      0 | Married         | retired            | highSchool   | Black  | manufacturing |
|   2015 |       2114 |             0 |           2 |        60 |              0 |          3715 |         6082.33 |       14731.5  |               0 |                  0 |            0 |                    -76795 |                 -76795 | Married         | keepHouse          | highSchool   | Black  | manufacturing |
|   2017 |       1076 |             3 |           1 |        55 |              7 |             0 |        11374.3  |       14299.1  |               0 |                  0 |            0 |                    -47719 |                 -47719 | Divorced        | keepHouse          | postGraduate | Black  | otherIndustry |


|   year |   familyID |   composition |   headCount |   ageHead |   liquidWealth |   laborIncome |   costPerPerson |   totalExpense |   participation |   investmentAmount |   annuityIRA |   wealthWithoutHomeEquity |   wealthWithHomeEquity | maritalStatus   | employmentStatus   | education   | race   | industry      |
|-------:|-----------:|--------------:|------------:|----------:|---------------:|--------------:|----------------:|---------------:|----------------:|-------------------:|-------------:|--------------------------:|-----------------------:|:----------------|:-------------------|:------------|:-------|:--------------|
|   1999 |       3907 |             0 |           6 |        34 |          11742 |         47439 |         3695.31 |        18881.8 |               0 |                  0 |            0 |                     64583 |                  64583 | neverMarried    | Working            | college     | Black  | manufacturing |
|   2001 |       1419 |             2 |           2 |        36 |              0 |         22121 |         7034.38 |        12719.7 |               0 |                  0 |            0 |                         0 |                      0 | neverMarried    | Working            | college     | Black  | manufacturing |
|   2003 |       7659 |             1 |           1 |        39 |              0 |         25454 |        21012.8  |        19812.1 |               0 |                  0 |            0 |                      5303 |                   5303 | neverMarried    | Working            | college     | Black  | manufacturing |
|   2005 |       2831 |             0 |           1 |        40 |              0 |         22000 |        16045    |        16045   |               0 |                  0 |            0 |                         0 |                      0 | neverMarried    | Working            | college     | Black  | manufacturing |
|   2007 |       4459 |             1 |           3 |        42 |              0 |         23484 |         7736.24 |        24706.1 |               0 |                  0 |            0 |                     18787 |                  18787 | neverMarried    | Working            | college     | Black  | manufacturing |
|   2009 |       2454 |             1 |           1 |        44 |              0 |         27272 |        16446.3  |        18090.9 |               0 |                  0 |            0 |                      4545 |                   4545 | Separated       | Working            | college     | Black  | manufacturing |
|   2011 |       6012 |             0 |           1 |        46 |              0 |         26136 |        22147.9  |        25422   |               0 |                  0 |            0 |                      3484 |                   3484 | Separated       | unemployed         | college     | Black  | manufacturing |
|   2013 |        175 |             0 |           1 |        48 |              0 |         20181 |        10317    |        12268.9 |               0 |                  0 |            0 |                         0 |                      0 | Divorced        | temporalLeave      | college     | Black  | manufacturing |
|   2015 |        839 |             0 |           1 |        50 |              0 |             0 |        10828.2  |        13113   |               0 |                  0 |            0 |                     -1651 |                  -1651 | Divorced        | disabled           | college     | Black  | manufacturing |
|   2017 |        130 |             0 |           1 |        52 |              0 |             0 |         9670.92 |        12157.7 |               0 |                  0 |            0 |                         0 |                      0 | Divorced        | disabled           | college     | Black  | service       |

   

# Some summary plots

Sample timeseries labor income plot (for 20 households): 

![sampleLaborIncomeTimeSeries](/Users/lee/Desktop/sampleLaborIncomeTimeSeries.png)

Average Income plot through years:

```
year
1999    58515.849468
2001    62096.450076
2003    61631.421186
2005    62050.746072
2007    60616.224024
2009    61723.606183
2011    55187.245819
2013    55558.055246
2015    51013.996452
2017    48526.321338
```

![averageIncome](/Users/lee/Desktop/averageIncome.png)

Average investmentAmount(value of stocks) plot through years:

```
year
1999    44860.393310
2001    62282.585910
2003    58126.453117
2005    55852.234668
2007    62082.949823
2009    50626.348201
2011    56326.484034
2013    72089.909782
2015    74328.152053
2017    85350.660922
```

![investmentAmount](/Users/lee/Desktop/investmentAmount.png)

Average expenditure data plot through years:

```
year
1999    32567.763675
2001    34693.636589
2003    34174.804709
2005    40804.406837
2007    41616.631510
2009    39253.224445
2011    38401.690223
2013    37231.670071
2015    36753.446087
2017    35466.241521
```

![expenditure](/Users/lee/Desktop/expenditure.png)

Average total wealth plot through years:

```
year
1999    189996.335023
2001    209022.036493
2003    215746.606690
2005    240508.410542
2007    294690.792701
2009    265977.239736
2011    264675.113533
2013    263506.552458
2015    319621.413077
2017    325448.128738
```

![wealth](/Users/lee/Desktop/wealth.png)

Average personal annuity or IRA value plot through time:

```
year
1999    31462.509377
2001    34869.478459
2003    31720.994932
2005    40220.458186
2007    50619.510897
2009    41815.880892
2011    62674.657881
2013    65190.544349
2015    78211.521034
2017    84070.374050
```

![IRA](/Users/lee/Desktop/IRA.png)

