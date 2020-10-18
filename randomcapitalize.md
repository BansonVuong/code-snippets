---
title: random_capitalize
tags: string,intermediate
---

Decapitalizes the first letter of a string.

- Capitalize the first letter of each word in the string.

```py
import random
def rand_capitalize(sentence):
    new_sentence = ""
    for letter in sentence.lower():
        new_sentence += letter if random.randint(0,1) == 0 else letter.upper() #This randomly decides if the letter should be upper or lowercase
    return new_sentence
```

```py
rand_capitalize('The quick brown fox jumped over the lazy dog') #THE quiCk BrOwN fOx jUMpEd OVEr tHe lAzY dOg
```
