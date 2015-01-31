## About
This is a fork of https://github.com/Famous/famous <br>
Was forked on Jan 20th 2015 from the main branch <br>
The Difference is I'm applying fixes I believe won't break anything that have yet to be added to Master along with some fixes / changes that I've implemented in my Famo.us projects.

## Pull Requests Incorporated:
Fix context container leak #599<br>
Transitionable delay fix #596<br>
Fix Accumulator: Accept arrays of arbitrary length #570<br>
Fix Matrix.set #538<br>
Matrix.multiply: Accept 2D arrays and matrices #536<br>
Vector: Always default to 0 0 0 #535<br>
fixed setVelocity all #528<br>
Draggable - Fixes and new Threshold and Autocomplete options #512<br>
Scrollview - small patches #511<br>
Transitionable: Fix doc; Make API more consistent #499<br>
Bug fixes for Scrollview and ViewSequence #407<br>

## My Changes
ElementOutput line under cleanup I add Entity.unregister(this.id);
	Should allow Surfaces to clean up.
Engine under Initialize I took out the touch move prevent default
	it's a bad work around.