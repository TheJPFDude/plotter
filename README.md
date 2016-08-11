A project to graph out some CXS data.

For this to work, you must first get Jupyter (jupyter.org). 
You must also download the aeri_tools files located here:
(https://gitlab.ssec.wisc.edu/cphillips/aeri_tools)
Then, edit line 22, or the line that has "/Users/bchoi/Desktop/data/" 
to a directory path that contains the CXS data you want to read.

Also, you have to edit the for loop (lines 15-17) to fit the number of files
you want as well as the file names. This specific instance is for 17 files:
160201B1.CXS, 160202B1.CXS, 160203B1.CXS... and so on, all the way up to
160218B1.CXS (skipping 160212B1.CXS, because there wasn't one). 

Edit the fileName variables for your own file names, and edit the range of 
the for loop for the number of files. If you don't need to skip files, just
delete the 'if i != 12' statement on line 16.

The program is a bit slow, so running a lot of files may take some time.