# pyPrepSpec
Python wrapper for Keith Horne's PrepSpec software


If you are looking to highlight a shell session command sequence as it looks to the user (with prompts, not just as contents of a hypothetical script file), then the right identifier to use at the moment is console:

```console
foo@bar:~$ gfortran -O3 -fno-automatic -ffixed-line-length-132 -mcmodel=medium -o prepspec_test.exe prepspec.for misc.for -L/data/jvhs1/star-2018A/lib `pgplot_link`
```
