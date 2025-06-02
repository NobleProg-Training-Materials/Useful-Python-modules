````markdown
[Category:Python Commands]  
[Python Links]

## Getting the current time and date

The `time` module offers functions for getting the current time and date.

```python
import time
s = time.asctime()  # as string
i = time.time()     # as float
````

## Accessing web pages

The HTML code of web pages and downloadable files from the web can be accessed in a similar way as reading files:

```python
import urllib
url = 'http://www.google.com'
page = urllib.urlopen(url)
print page.read()
```

## Finding out what is in a module

The contents of any module can be examined with:

```python
print dir(name_of_module)
help(name_of_module)
```

## Creating plots

The Matplotlib library contains a wide range of possibilities for creating graphs. See the 'gallery' link on [http://matplotlib.sourceforge.net](http://matplotlib.sourceforge.net) for examples. It needs to be installed separately.

```python
from pylab import *
```

## Database access

Numpy is a library that allows operating on arrays and matrices. It needs to be installed separately. See: [http://numpy.scipy.org](http://numpy.scipy.org)

```python
import numpy
a = numpy.array([1, 2, 3, 4, 5, 6])
print a + 10, a * a
```

## Image manipulation

The Python Imaging Library (PIL) is a powerful tool for working with images (changing formats, resizing, cutting, drawing). It needs to be installed separately. See: [http://www.pythonware.com/products/pil](http://www.pythonware.com/products/pil)

```


## Python resources
[python website]([https://www.deepseek.com](https://www.python.org)

[DeeepSeek Training | NobleProg](https://www.nobleprog.es/en/python-training)
