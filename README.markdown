## ofxOpenNI for 0.9.8
Originally from https://github.com/gameoverhack/ofxOpenNI/
and then a fork off from https://github.com/ccerhan/ofxOpenNI
* No logical changes are done. Just several method names are updated to OF098.
* Not tested for Windows or Linux. Just tested for MAC OSX 10.12 and XCode 8


Tutorial video https://www.youtube.com/watch?v=VyWLp2ZFdRQ


### Notes 
Common errors
```
ld: library not found for -lXnDDK
clang: error: linker command failed with exit code 1 (use -v to see invocation)
```
* In addtion to install instractions in the original readme file, see [this](http://stackoverflow.com/questions/33681299/apple-mach-o-linker-id-error-for-openframeworks/34559001#34559001) to fix linker error in XCode.
