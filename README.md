# USCOTS25 - `purrrfect` simulations

Materials for USCOTS 25 Posters and Beyond

## `purrrfect` is open source and hosted on GitHub

Find it at [https://github.com/yardsale8/purrrfect](https://github.com/yardsale8/purrrfect)

## `purrrfect` can be installed using `devtools`

```{R}
install_github('yardsale8/purrrfect', force = TRUE)
library(purrrfect)
```
## Important note on the Colab display bug

Current version of `IRKernel` on Colab causes a display error when displaying a `tibble` containing a list column.  Instructions on fixing this issue can be found in the included notebook.

## On displaying the presentation

The presentation mode uses the `RISE` Python library, which doesn't work with `jupyter 7.0+`.  To make this work, you can create an `conda` virtual environment for Python and R, then use `conda` to install `rise`, which will reinstall an older version of `jupyter notebook`


