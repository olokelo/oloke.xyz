---
title: "Sample Markdown"
date: 2024-08-01T00:00:00+02:00
draft: false
tags: ["markdown", "testing", "hugo"]
---

Recently I finished working on my own [Hugo](https://gohugo.io) theme. It's meant to be minimalist and high contrast. I also wrote custom CSS for syntax highlighting within Hugo.
This page is meant for testing all markdown components I might be using in the future, just to see if I didn't mess something up while modifying my theme.

You can see the results below.

## Table

| Tables   |      Are      |  Cool |
|:---------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


## Code

```python
from __future__ import print_function
import time

class Hello:

    message = "hello world"
    
    def __init__(self, user: str):
        print(f'{self.message} {user}!')
        self.user = user
    
    def get_user() -> str:
        return self.user

# these animals are nice
animals = ["rabbit", "squirrel", "flamingo"]

i = 0.0
for animal in animals:
    Hello(animal)
    time.sleep(1)
    i += 1

print('greeted ' + str(i) + ' animals!')

```

```cpp
#include <iostream>

// some function
void f(ds) {
    return 1;
}

void main(int argc, char** argv) {
    std::cout << "" << std::endl;
}

```


