# Build

## To compile the latex file, run:
```bash
make
```
in the root folder, and the generated pdf file will be ``build/paper.pdf``


## To delete all the file generated during latex compilation, run:
```bash
make clean
```

# Code and Experiment
Reproducible Artifact is available [here](https://github.com/Generative-Program-Analysis/icse23-artifact-evaluation.git).

# Required LaTeX Packages
## Texlive

This document requires a full texlive distribution that can be installed by running
`apt-get install texlive-full` in the terminal. Because `texlive-full` is very
large (about 5 Gigabytes) you can also install the smaller texlive bundles and
add any missing packages manually.