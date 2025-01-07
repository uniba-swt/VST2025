Test-to-Code Trace Links via Program Mutation
----

This repository includes the evaluation artifact for the paper "Recovering Test-to-Code Trace Links via Program Mutation" as submitted to the VST Workshop 2025, Montreal, Canada.

- Folder "PIT Output" includes the raw xml-output from applying the PIT default set of mutation operators to the four projects. 
- Folder "False Negative Analysis" includes a csv-file with all links not detected by Mut4T (without call depth filtering)
- Folder "TCTracer Overlap" includes two csv-files, comparing the overlap between false negatives, and false positives for commons-io, commons-lang and JFreeChart
