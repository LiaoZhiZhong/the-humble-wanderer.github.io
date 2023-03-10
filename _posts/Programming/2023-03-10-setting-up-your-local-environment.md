---
title: "Setting up your local environment"
categories:
  - Programming
---

For Python, you can save your dependencies using pip then install them again
using `pip install -r requirements.txt`.

There's an interesting move towards Hypermodern Python. Check it out [here](https://cjolowicz.github.io/posts/ ).

When updating packages using poetry, you can use the following command to 
update just one package:
```shell
poetry lock --no-update
```
Alternatively, you can use:
```shell
poetry update <package_name>
```
