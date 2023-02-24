# thesis_scripts

This is a repository that contains all scripts necessary to build Scott Koeneman's Biostatistics PhD Thesis for the University of Iowa.
All that is contained in this repository is free to be used as a template for your own thesis or other projects if you are so inclined.

The root directory contains .tex files necessary to construct the body of the document. The file "Thesis.tex" is the main file that is
compiled, and this file relies on all other .tex files being in the same directory so that they can be included in the document. Figures
are expected to be in the "figures" directory.

Of interest also may be the uithesis12.sty file, which is a standardized style file handed down from graduate student to graduate student
that helps format dissertations in a manner that is acceptable to the graduate college. Additionally, the .gitignore file is designed to ignore
extraneous files generated by Latex that do not need to be tracked, and also ensures binary files such as pdfs that can be generated from
scripts in the repository are not tracked so as to save space.

The "scripts" directory contains R and Julia scripts to generate all of the results presented in the thesis. These scripts tend to
write output to the "data" and "figures" directories.

The "data" directory contains generated dumps of .csv files that are used to construct tables in the .tex files, as well as data used
in applications.

The "figures" directory is empty on the remote repository so as to not track changes to binary files, but if the scripts are run,
then .pdf images will be placed here.
