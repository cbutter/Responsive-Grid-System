THIS IS A 12-COLUMN RESPONSIVE GRID SYSTEM
by Craig Butterworth

GETTING STARTED

Wrap blocks of content in an element with class="container" to restrict your layout to a max-width of 1480px (default) or class="container full" for full-width.

Give elements inside your container a .box class and then additional classes that will determine their width at three different breakpoints (Defaults: XS=320px, S=480px, M=768px, L=1024px, XL=1280px).

Class names start with 'XL', 'L', 'M', 'S' or 'XS' which identify a breakpoint followed by a '-' and a number between 1 and 12 which identifies the number of columns to span. 

An element with a class of "box L-4" would span one third of the container width (4 of 12 columns) in large views of 1024px.

An element with a class of "box M-6" would span one half of the container width (6 of 12 columns) in medium views of 768px.

An element with a class of "box S-12" would span the full container width (12 of 12 columns) width in small views of width 480px.

An element with a class of "box l-4 m-6 s12" would span 4/12 of the container width in large views of width <= 1024px, 6/12 of the container width in medium (m) views of width <= 768px and 12/12 of the container width in small (s) views of width <= 480px.

To make an element with a width of 50% regardless of the winow size you only need to add one class for the large (L) window size: class="box L-6"

Add an .XS-hide, .S-hide, .M-hide, .L-hide or XL-hide class. to hide an element at extra-small (XS), small (S), medium (M), large (L) or extra-large (XL) window sizes.
