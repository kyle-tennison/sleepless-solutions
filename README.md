# derivatives and despair

hail mary tools for engineering students when we're thoroughly screwed

### overview

really just some quality of life wrappers around `sympy`, `numpy` and `matplotlib`
that are useful for solving evil annoying problems


### installation

clone this repo and run 
```
python -m pip install .
```


### usage

```python
import despair as d


x, y, z = syms("x, y, z")

all_of_my_homework_problems_that_i_hate = [
    2*x + 4*y + z, # == 0
    2*x - 2, # == 0
    y+4, # == 0
]


x, y, z = d.solve_eoe(all_of_my_homework_problems_that_i_hate, (x, y, z))

d.splendid() #   yeah pretty splendid
```