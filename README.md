## usage


get [merl brdf database](https://www.merl.com/brdf/) and put the whole **BRDFDatabese** folder as below.

```
.
├── BRDFDatabase
│	├── brdfs/
│	├── code/
│	├── Copyright_Notice.txt
│	└── Readme.txt
└── CMakeLists.txt
```

To build the sample reader provided by merl (BRDFDatabase/code/BRDFRead.cpp), just `cmake` and `make sample`.

## Reference

1. Wojciech Matusik, Hanspeter Pfister, Matt Brand, and Leonard McMillan. 2003. A data-driven reflectance model. ACM Trans. Graph. 22, 3 (July 2003), 759–769. DOI:https://doi.org/10.1145/882262.882343
