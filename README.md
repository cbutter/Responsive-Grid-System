# THIS IS A 12-COLUMN RESPONSIVE GRID SYSTEM

GETTING STARTED

Wrap blocks of content in an element with class="container" to restrict your layout to a max-width of 1480px (default) or class="container full" for full-width.

Give elements inside your container a .box class and then additional classes that will determine their width at three different breakpoints (Defaults: XS=320px, S=480px, M=768px, L=1024px, XL=1280px).

Class names start with either 'XL', 'L', 'M', 'S' or 'XS' followed by a '-' and a number between 1 and 12. Numbers correspond to the number of columns out of 12 that the box element's width will span. For instance, an element having the class of .L-6 would span half of its container at a large window size because 6 is half of 12. 

An element with a class of M-4 would span a third of the width in medium sized windows because 4 is one third of 12.

To make an element with a width of 25% of its container at large (L) window sizes, 50% of its container at medium (M) window sizes and 100% of its container at small (S) window sizes, you would write: class="box l-4 m-6 s-12". Becuse an 'XL' and 'XS' state weren't defined they would default to the values used for 'L' and 'S' respectively.

To make an element with a width of 50% regardless of the winow size you only need to add one class for the large (L) window size: class="box L-6"

Add an .XS-hide, .S-hide, .M-hide, .L-hide or XL-hide class. to hide an element at extra-small (XS), small (S), medium (M), large (L) or extra-large (XL) window sizes.

CREDIT: design.craigbutterworth.com
