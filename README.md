# adult-integers

Adult integers are those that colloquially refer to adult themes.

```{python}
import random

adult_integer_list = [
  13, # unlucky
  14, 88, 311, # racism/hate
  187, # murder
  420, # cannabis
  666, # the devil
  69, 169, 269, 369, 469, 569, 669, 769, 869, 969, # nice
  690, 691, 692, 693, 694, 695, 696, 697, 698, 699, # nice, contd.
  4, 40, 44, 400, 440, 444, # tetraphboia
  911, 999, # emergency
]

if random.randint(0, 999) in adult_integer_list:
  print("That's an adult integer!")
 ```
 
## References

- https://www.adl.org/hate-symbols
