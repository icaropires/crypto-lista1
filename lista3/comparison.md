# Comparison between RC4 results and Salsa20

## Salsa20
|Statistical Test| P-value|
|:---------------|:------:|
|Frequency|0.350485|
|Block Frequency|0.350485|
|Cumulative Sums|0.534146|
|Runs|0.122325|
|Longest Run |0.739918|
|Rank |0.213309|
|FFT |0.911413|
|NonOverlappingTemplate |0.534146|
|OverlappingTemplate |0.739918|
|Universal |0.000000|
|ApproximateEntropy |0.000000|
|Serial |0.534146|
|LinearComplexity |0.350485|

### Frequências

BITSREAD = 10000 0s = 4983 1s = 5017
BITSREAD = 10000 0s = 5036 1s = 4964
BITSREAD = 10000 0s = 4980 1s = 5020
BITSREAD = 10000 0s = 5028 1s = 4972
BITSREAD = 10000 0s = 4939 1s = 5061
BITSREAD = 10000 0s = 4965 1s = 5035
BITSREAD = 10000 0s = 5024 1s = 4976
BITSREAD = 10000 0s = 5051 1s = 4949
BITSREAD = 10000 0s = 4937 1s = 5063
BITSREAD = 10000 0s = 5024 1s = 4976


## RC4
|Statistical Test| P-value|
|:---------------|:------:|
|Frequency|0.534146|
|Block Frequency|0.534146|
|Cumulative Sums|0.749918|
|Runs|0.911413|
|Longest Run |0.739918|
|Rank |0.534146|
|FFT |0.739918|
|NonOverlappingTemplate |0.350485|
|OverlappingTemplate |0.911413|
|Universal ||0.000000
|ApproximateEntropy |0.008879|
|Serial |0.350485|
|LinearComplexity |0.739918|

### Frequências

BITSREAD = 10000 0s = 5003 1s = 4997
BITSREAD = 10000 0s = 5000 1s = 5000
BITSREAD = 10000 0s = 5032 1s = 4968
BITSREAD = 10000 0s = 4903 1s = 5097
BITSREAD = 10000 0s = 5035 1s = 4965
BITSREAD = 10000 0s = 4988 1s = 5012
BITSREAD = 10000 0s = 5009 1s = 4991
BITSREAD = 10000 0s = 5021 1s = 4979
BITSREAD = 10000 0s = 4974 1s = 5026
BITSREAD = 10000 0s = 5038 1s = 4962
