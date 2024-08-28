make_convolution.f
-------------------
1) Added variables:
	- TORF2 	(Line 20)
	- FluxFile 	(Line 25)

2) Added a function call (Line 92)

3) Added a file inqiry to test for matched flux files (Line 96)

4) Added else statement in case the first file (created by the routing code) is not found, to look for matched flux file and if avaialble, open and read it. (Line 102-103)


initi_routine.f
----------------

Added a function or subroutine and named it 'match_grid'
Lines 27-103

- the function looks into the VIR flux directory and saves the file list as txt file (Make sure there are no additional files other than the flux files in the directory) named as 'list.txt' in the current directory. 

