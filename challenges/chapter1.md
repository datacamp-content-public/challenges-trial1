---
title: example_python_challenges
output: html_document
---

## Choose the right answer

```yaml
type: MultipleChoiceChallenge
key: 115qFYuQ4pPlifqZze0QkDORLwVufanGIfC
```

`@assignment1`
Which command explicitly imports the `pyplot` subpackage from `matplotlib`?

`@assignment2`
Assuming `matplotlib.pyplot` is imported as `plt`, which command displays the current figure?

`@assignment3`
Assuming `matplotlib.pyplot` is imported as `plt`, which command clears the current figure?

`@assignment4`


`@assignment5`


`@assignment6`


`@assignment7`


`@assignment8`


`@assignment9`


`@options1`
- `import matplotlib as pyplot`
- `import pyplot from matplotlib`
- [`import matplotlib.pyplot as plt`]
- `from pyplot import plt`
- `import pyplot as plt`

`@options2`
- `matplotlib.pyplot.show()`
- `matplotlib.show()`
- `pyplot.show()`
- `plt.show`
- [`plt.show()`]

`@options3`
- `matplotlib.pyplot.clear()`
- `plt.clear()`
- `plt.clf`
- `plt.clear`
- [`plt.clf()`]

`@options4`


`@options5`


`@options6`


`@options7`


`@options8`


`@options9`


---

## concatenating lists

```yaml
type: BlanksChallenge
key: 8a565a9166
```

`@context`


`@code1`
```{python}

```

`@code2`
```{python}

```

`@code3`
```{python}

```

`@code4`
```{python}

```

`@code5`
```{python}

```

`@code6`
```{python}

```

`@code7`
```{python}

```

`@code8`
```{python}

```

`@code9`
```{python}

```

`@pre_challenge_code`
```{python}
import dccpu.generators as g
```

`@variables`
```yaml
l1:
  - '!expr g.int_vector()'
l2:
  - '!expr g.int_vector()'
op:
  - '+'
```

`@distractors`
```yaml

```

---

## popping lists (2)

```yaml
type: OutputChallenge
key: 6258197972
```

`@context`


`@code1`
```{python}

```

`@code2`
```{python}
l1 = {{$l1}}
p = l1.pop({{n}})
print(p)
```

`@code3`
```{python}

```

`@code4`
```{python}

```

`@code5`
```{python}

```

`@code6`
```{python}

```

`@code7`
```{python}

```

`@code8`
```{python}

```

`@code9`
```{python}

```

`@pre_challenge_code`
```{python}
import dccpu.generators as g
```

`@variables`
```yaml
l1:
  - '!expr g.int_vector(size=6)'
n:
  - '!expr g.rand_int(hi=5)'
```
