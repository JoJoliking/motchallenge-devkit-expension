# MotChallenge-devkit-expension
motchallenge-devkit is expended for MOT2020

This tool is modfied from motchallenge-devkit：https://bitbucket.org/amilan/motchallenge-devkit/src/default/

# Requirements
MATLAB

C/C++ compiler

# How to use
1.Run compile.m

2.open demo_evalMOT20.m and set the paths:

benchmarkGtDir = 'the path of your MOT2020 train datasets files;

[allMets, metsBenchmark] = evaluateTracking('c2-test.txt', 'the path of your MOT2020 test data files', benchmarkGtDir, 'MOT20');

3.Run demo_evalMOT20.m

Your can also use other .m to evaluate your other Corresponding data.
