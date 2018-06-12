---
layout: post
title: import pip
tags: python
---

While working on some instructional Jupyter Notebooks lately, I included written instructions for installing required Python modules from PyPI using `pip`.  Some users of the notebooks were very new to Python (and programming in some cases), so the extra installation step seemed onerous.  I decided my notebooks should include code to install the required Python modules for the user, if they didn't want to run `pip` themselves.

I found a good [blog post](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/) that recommends running `pip` from within notebooks like this:

```
import sys
!{sys.executable} -m pip install package1 package2
```

Which makes a shell call to run the `pip` module in the current Python interpreter executable.  I feel that it must be more efficient to 

https://pip.pypa.io/en/stable/user_guide/#using-pip-from-your-program
