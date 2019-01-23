# An-efficient-safe-screening-rule-for-sparse-logistic-regression
An efficient safe screening rule for sparse logistic regression

In this repository, we propose an implementation to solve the sparse logistic regression using SLEP package with safe screening rules.

Examples on synthetic dataset are presented in example_100.m. Examples on Leumekia dataset are presented in leu.m.

This package has the following requirements:
1.Matlab R2018b
2.SLEP package (https://github.com/jiayuzhou/SLEP)
3.Libsvm package (https://www.csie.ntu.edu.tw/~cjlin/libsvm/)
4.Leukemia dataset (https://web.stanford.edu/~hastie/CASI_files/DATA/leukemia.html, download the leukemia_big.csv)

Before you running the code in this package, you may first need to mex the files in SLEP and Libsvm.

You need to put 'SLEP' and 'Libsvm' in the folder 'lib' of this package, and the extracted data file in the 'dataset' folder of this package.

After the procedure above, you can run the command:
>>run example_100.m
or:
>>run leu.m
The results are stored in example_100.mat or leu.mat correspondingly.
If you want to visulize the results, run the command:
>>load('example_100.mat')
or:
>>load('leu.mat')
and then:
>>run draw.m
in your matlab software.
