# A brief introduction to data processing in Python

## Requirements

```
brew install python3
pip3 install jupyter pandas
```

## "Notebook-driven development"

`git clone https://github.com/hnlee/jupyter_pandas_zagaku.git`
`jupyter notebook zagaku.ipynb`

### Advantages

* Instant feedback
* Great for exploration
* Can run chunks of code
* Documented history
* Reproducible
* Github support for rendering
* Literate programming

### Disadvantages

* Version control possible, but git diff hard to read
** Recommendation is to generate .html and .py for git commits
** See: https://svds.com/jupyter-notebook-best-practices-for-data-science/
* Better suited for scripting and imperative programming

### Unit testing

* Standard Python packages: `pytest`, `nose`
* [`ipython-nose`](https://github.com/taavi/ipython_nose)

## Data processing

### "Tidy" data

1. Each variable forms a column.
2. Each observation forms a row.
3. Each type of observational unit forms a table

From [Hadley Wickham](http://vita.had.co.nz/papers/tidy-data.html)

### `pandas` Tutorial

[Cheatsheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf)

