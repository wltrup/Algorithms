# Algorithms
Here you'll find some technical essays I've written over the years that are of a more practical nature, algorithms of my own creation, some of which have actually been used in commercial software.

##### (2020) [Some Thoughts on Dynamic Quantum Clustering](https://github.com/wltrup/Algs-DQC)

A good friend of mine pointed me in the direction of a clustering algorithm called **Dynamic Quantum Clustering**, or **DQC** for short, which uses ideas from Quantum Mechanics to find the most likely cluster centers in a data set.

I read the original papers and had a few insights of my own, which I'm summarizing in this essay. I may yet write a couple of actual research papers about these insights but that's a decision I haven't made yet.

##### (2019) [Independent Concurrent Animations of Multiple Parameters](https://github.com/wltrup/Algs-Parameter-Animations)

This essay describes the mathematical steps needed to synchronize independent animations of multiple parameters, running concurrently, so as to minimize the number of function evaluations.

Check out the actual repository to see some nifty animations.

##### (2013) [Discrete Half Flux Diameter](https://github.com/wltrup/Algs-Discrete-Half-Flux-Diameter)
A colleague interested in astrophotography asked me for an algorithm to compute the _half-flux diameter_ of an image.

It turns out that the recipes commonly found on the internet are actually incorrect so I had to analyse the problem in an excruciatingly mathematical detail to devise a correct algorithm.

##### (2008) [Card Spread](https://github.com/wltrup/Algs-Card-Spread)
An algorithm to spread cards in a neat way inside of a rectangle of a given length, taking into account the _preferred overlap_, the _maximum overlap_ allowed, and a possible _gap_ surrounding the middle card.

##### (2008) [Detecting Ellipse-Ellipse Intersections](https://github.com/wltrup/Algs-Detecting-Ellipse-Ellipse-Intersections)
In this essay, I derive the mathematical basis of an algorithm to detect intersections between two arbitrarily positioned and arbitrarily oriented ellipses on the same plane.

##### (2007) [Smoothing Line Segments](https://github.com/wltrup/Algs-Smoothing-Line-Segments)
At one point, someone in the [cocoa-dev mailing list](https://lists.apple.com/mailman/listinfo/cocoa-dev) asked for an algorithm to draw a smooth curve passing through a number of given points. I solved the problem mathematically, then wrote a small application implementing the algorithm. The algorithm involves interpolating the points using [_Bezier curves_](http://en.wikipedia.org/wiki/Bézier_curve).

##### (2006) [Drawing a String Along the Diagonal of a Rectangle](https://github.com/wltrup/Algs-Drawing-a-String-Along-the-Diagonal-of-a-Rectangle)
Someone in the [cocoa-dev mailing list](https://lists.apple.com/mailman/listinfo/cocoa-dev) once asked for an algorithm to draw an arbitrary string along the diagonal of an arbitrary rectangle. I first solved the problem mathematically, then wrote an application illustrating the algorithm. My algorithm was subsequently adopted by the person who asked the question, who happens to be the author of the excellent writing tool [**Scrivener**](https://www.literatureandlatte.com/scrivener.php). Shortly thereafter, it occurred to me that another algorithm could be used. Both algorithms are described in this repository.
