# pyPrepSpec
Python wrapper for Keith Horne's PrepSpec software


If you are looking to highlight a shell session command sequence as it looks to the user (with prompts, not just as contents of a hypothetical script file), then the right identifier to use at the moment is console:

```console
foo@bar:~$ gfortran -O3 -fno-automatic -ffixed-line-length-132 -mcmodel=medium -o prepspec_test.exe prepspec.for misc.for -L/data/jvhs1/star-2018A/lib `pgplot_link`
```



```bash
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/data/jvhs1/star-2018A/lib
export PGPLOT_DIR=/data/jvhs1/star-2018A/lib
export PGPLOT_FONT=/data/jvhs1/star-2018A/bin/grfont.dat

alias prepspec='/data/jvhs1/prepspec/prepspec.exe'

export PS='/data/jvhs1/prepspec/'
```
