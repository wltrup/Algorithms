# Algorithms
Here you'll find some technical essays I've written over the years that are of a more practical nature, algorithms of my own creation, some of which have actually been used in commercial software.

##### (2007) [Smoothing Line Segments](https://github.com/wltrup/Algs-Smoothing-Line-Segments)
At one point, someone in the [cocoa-dev mailing list](https://lists.apple.com/mailman/listinfo/cocoa-dev) asked for an algorithm to draw a smooth curve passing through a number of given points. I solved the problem mathematically, then wrote a small application implementing the algorithm. The algorithm involves interpolating the points using [_Bezier curves_](http://en.wikipedia.org/wiki/Bézier_curve).

##### (2006) [Drawing a String Along the Diagonal of a Rectangle](https://github.com/wltrup/Algs-Drawing-a-String-Along-the-Diagonal-of-a-Rectangle)
Someone in the [cocoa-dev mailing list](https://lists.apple.com/mailman/listinfo/cocoa-dev) once asked for an algorithm to draw an arbitrary string along the diagonal of an arbitrary rectangle. I first solved the problem mathematically, then wrote an application illustrating the algorithm. My algorithm was subsequently adopted by the person who asked the question, who happens to be the author of the excellent writing tool [**Scrivener**](https://www.literatureandlatte.com/scrivener.php). Shortly thereafter, it occurred to me that another algorithm could be used. Both algorithms are described in this repository.
