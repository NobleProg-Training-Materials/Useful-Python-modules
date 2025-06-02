
[Κατηγορία:Python Commands]  
[Σύνδεσμοι Python]

## Λήψη της τρέχουσας ώρας και ημερομηνίας

Το μοντέλο `time` προσφέρει συναρτήσεις για λήψη της τρέχουσας ώρας και ημερομηνίας.

```python
import time
s = time.asctime()  # ως συμβολοσειρά
i = time.time()     # ως δεκαδικός αριθμός
````

## Πρόσβαση σε ιστοσελίδες

Ο HTML κώδικας ιστοσελίδων και αρχεία από τον ιστό μπορούν να αναγνωστούν όπως τα αρχεία:

```python
import urllib
url = 'http://www.google.com'
page = urllib.urlopen(url)
print page.read()
```

## Εξερεύνηση περιεχομένων ενός module

Το περιεχόμενο οποιουδήποτε module μπορεί να εξεταστεί με:

```python
print dir(name_of_module)
help(name_of_module)
```

## Δημιουργία γραφημάτων

Η βιβλιοθήκη Matplotlib περιέχει πολλές δυνατότητες για δημιουργία γραφημάτων. Δείτε το 'gallery' στο [http://matplotlib.sourceforge.net](http://matplotlib.sourceforge.net) για παραδείγματα. Χρειάζεται ξεχωριστή εγκατάσταση.

```python
from pylab import *
```

## Πρόσβαση σε βάσεις δεδομένων

Η Numpy είναι μια βιβλιοθήκη για πράξεις με πίνακες και μήτρες. Χρειάζεται ξεχωριστή εγκατάσταση. Δείτε: [http://numpy.scipy.org](http://numpy.scipy.org)

```python
import numpy
a = numpy.array([1, 2, 3, 4, 5, 6])
print a + 10, a * a
```

## Επεξεργασία εικόνων

Η βιβλιοθήκη Python Imaging Library (PIL) είναι ισχυρό εργαλείο για εργασία με εικόνες (αλλαγή μορφής, αλλαγή μεγέθους, περικοπή, σχεδίαση). Χρειάζεται ξεχωριστή εγκατάσταση. Δείτε: [http://www.pythonware.com/products/pil](http://www.pythonware.com/products/pil)


## Πόροι για την Python

[Ιστοσελίδα Python](https://www.python.org)

[Εκπαίδευση DeepSeek | NobleProg](https://www.nobleprog.es/en/python-training)
