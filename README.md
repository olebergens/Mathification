# Mathification

Hi. Ich möchte in dieser Repository einige verschiedene mathematische Sätze bzw. Erkenntnisse verdeutlichen.
Es ist eigentlich alles irgendwie grafisch darstellbar. Deswegen werde ich für dieses Projekt die Programmiersprache Kotlin (https://kotlinlang.org/) in Verbindung mit Processing (https://processing.org/) und folgenden weiteren Bibliotheken benutzen:
- https://github.com/alt3r3dgd/math

Hi. I would like to illustrate some different mathematical theorems or findings in this repository.
Actually, everything can be represented graphically in some way. That's why I will use the programming language Kotlin (https://kotlinlang.org/) in combination with Processing (https://processing.org/) and the following additional libraries for this project:
- https://github.com/alt3r3dgd/math

## Inhaltsverzeichnis / Table of Contents!
1. [Ulam Spiral](#Ulam-Spiral)
2. [Mandelbrot](#Mandelbrot)
3. [Julia set](#Julia-set)
4. [Fractal Tree](#Fractal-Tree)
5. [Lorenz Attractor](#Lorenz-Attractor)
6. [Bubble sort](#Bubble-sort)
7. [Quicksort](#Quicksort)
8. [Perlin-Noise](#Perlin-Noise)
9. [Butterfly Curve](#Butterfly-Curve)

### [Ulam Spiral](https://en.wikipedia.org/wiki/Ulam_spiral)

Die Ulam-Spirale bzw. die Primzahlspirale ist eine interessante Entdeckung des polnischen Mathematikers *Stanislaw Ulam*. Die Erkenntnis welche erlangt werden konnte ist eine sehr komische Eigenschaft der Primzahlen. Die Primzahlen haben nämlich eine Tendenz in einer Spirale diagonale Linien zu bilden.

The Ulam spiral or the prime number spiral is an interesting discovery of the Polish mathematician *Stanislaw Ulam*. The discovery which could be obtained is a very strange property of prime numbers. The prime numbers have a tendency to form diagonal lines in a spiral.
 
![600x600 Ulam-Spiral](resources/ulam_spiral.png "Ulam-Spiral")


### [Mandelbrot](https://en.wikipedia.org/wiki/Mandelbrot_set)
Die Mandelbrot-Menge bezeichnet die Menge aller komplexen Zahlen c, für welche die iterative Vorschrift $$k_{n+1}$ = $z_n^2$ + c$ mit dem Startwert $z_0 = 0$ eine Folge definiert, welche endlich bleibt. Ist die Mandelbrot-Menge als geometrische Figur betrachtet, so sieht man ein Fraktal. Die Mandelbrot-Menge wurde nach Benoît Mandelbrot benannt.

The Mandelbrot set denotes the set of all complex numbers c for which the iterative rule $$k_{n+1}$ = $z_n^2$ + c$ with initial value $z_0 = 0$ defines a sequence which remains finite. If the Mandelbrot set is considered as a geometric figure, one sees a fractal. The Mandelbrot set was named after Benoît Mandelbrot.

![640x480 Mandelbrot](resources/mandelbrot.png "Mandelbrot")

### [Julia set](https://en.wikipedia.org/wiki/Julia_set)
Die Julia-Mengen welche erstmals von Gaston Julia und Pierre Fatou beschrieben wurden, sind Teilmengen der komplexen Zahlenebene. 

The Julia sets which were first described by Gaston Julia and Pierre Fatou are subsets of the complex number plane. 

![640x480 Julia](resources/julia_video.gif "Julia")

### [Fractal Tree](https://en.wikipedia.org/wiki/Fractal)
Fraktale Bäume werden durch rekursive symmetrische Verzweigungen dargestellt. Sie bilden als Fraktale Objekte der Realität ab.

Fractal trees are represented by recursive symmetric branches. As fractals they represent objects of reality.

![640x480 Fractal Tree](resources/fractaltree.png "Fractal Tree")

### [Lorenz Attractor](https://en.wikipedia.org/wiki/Lorenz_system)
Der Lorenz-Attraktor ist der Attraktor eines System von drei gekoppelten, nicht linearen Differenzialgleichungen. Formuliert wurde das System von Edward Lorenz ca. im Jahr 1963. Lorenz ging es um die Modellierung der Zustände in der Erdatmosphäre zum Zweck einer Langzeitvorhersage.

The Lorenz attractor is the attractor of a system of three coupled non-linear differential equations. The system was formulated by Edward Lorenz around 1963, who was interested in modeling the conditions in the Earth's atmosphere for the purpose of long-term prediction.

![640x480 Lorenz Attractor](resources/lorenzattractor.png "Lorenz Attractor")

### [Bubble sort](https://en.wikipedia.org/wiki/Bubble_sort)
Bubblesort ist ein Algorithmus der eine Liste von Elementen vergleichs basierend sortiert. Laufzeitkomplexität: $O($n^2)$

Bubblesort is an algorithm that sorts a list of elements based on comparison. Runtime complexity: $O($n^2)$
![640x480 Bubble sort](resources/bubblesort.gif "Bubble sort")

### [Quicksort](https://en.wikipedia.org/wiki/Quicksort)
Quicksort ist ein schneller und rekursiver Sortieralgorithmus. Er wurde ca. 1960 von *C. Antony R. Hoare* in seiner Grundform entwickelt. Im Durchschnitt führt dieser Algorithmus eine Laufzeitkomplexität von O(n*log(n)) und im schlechtesten Falle eine von O(n^2).
Im Gif wird der Quicksort-Algorithmus gezeigt mit einem Delay von 2ms für die grafische Darstellung.

Quicksort is a fast and recursive sorting algorithm. It was developed around 1960 by *C. Antony R. Hoare* in its basic form. On average, this algorithm introduces a runtime complexity of O(n*log(n)) and in the worst case one of O(n^2).
In the gif, the quicksort algorithm is shown with a delay of 2ms for the graphical representation.

![640x480 Quicksort](resources/quicksort.gif "Quicksort")

### [Perlin-Noise](https://de.wikipedia.org/wiki/Perlin-Noise)
Perlin Noise bezeichnet eine Rauschfunktion, welche auf der Basis von sogenannten pseudozufälligen Gradientenwerten an Gitterpunkten basiert. Das Prinzip geht auf Ken Perlin zurück.

Perlin Noise is a noise function based on so-called pseudorandom gradient values at grid points. The principle goes back to Ken Perlin.

![640x480 Perlin Noise Graph](resources/perlinnoisegraph.gif "Perlin Noise Graph")

Hier sieht man Perlin Noise durch das Überlagern von mehreren Frequenzen.

Here you can see fractal noise due to the superposition of several frequencies.

![640x480 Perlin Noise 2D](resources/perlinnoise2d.png "Perlin Noise 2D")

Ein häufiger Anwendungsfall für Perlin Noise ist die Erstellung eines Arts Strömungsfeld und eine gängige Methode um dies zu realisieren ist es den Rauschwert an einer bestimmten Position einen Winkel zuzuordnen.

A common use case for Perlin Noise is to create some kind of flow field, and a common way to do that is to map the noise value at a particular location to an angle.

![640x480 Perlin Noise Flow Field](resources/perlinnoiseflowfield.gif "Perlin Noise Flow Field")

### [Butterfly Curve](https://en.wikipedia.org/wiki/Butterfly_curve_(transcendental))

Die Butterfly-Kurve ist eine transzendentale Kurve in der Ebene, welche 1989 von Temple Fay von der University of Southern Mississippi entdeckt wurde.

The butterfly curve is a transcendental curve in the plane discovered in 1989 by Temple Fay of the University of Southern Mississippi.

![640x480 Butterfly Curve](resources/butterfly.gif "Butterfly Curve")
