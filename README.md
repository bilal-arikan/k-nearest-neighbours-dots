
| Range Demo (10.000, 1.5)                         |
| ----------------------------------- |
| ![Alt text](/SS~/SS1.gif "Gif1") |
| K-Nearest Demo (10.000, 30)                         |
| ----------------------------------- |
| ![Alt text](/SS~/SS2.gif "Gif1") |

# Unity K-Nearest Neighbours library with KDTree

Simple K-Nearest Neighbour library for Unity, using the 'Dots' technology stack (the Burst compiler and Unity's job system). It uses K-D trees to speed up queries.

It is totally free from managed allocations and can run multi-threaded. The Burst compiler heavily vectorizes the searching code.

Updated Version of the:
 `ArthurBrussee` : <https://github.com/ArthurBrussee/KNN>
 and
 `viliwonka` : <https://github.com/viliwonka/KDTree>


How to Import:
 - Add to manifest.json
```
"com.arikan.utils.knearestjobs" : "https://github.com/bilal-arikan/k-nearest-neighbours-dots.git",
```


How to Use:
 <https://github.com/ArthurBrussee/KNN>

Demo Unity Package

![Alt text](/SS~/SSDemo.PNG "Demo Import")