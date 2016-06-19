---
layout: post
title:  "Hello World"
date:   2016-06-18 21:34:45 +0700
categories: [python, codefights]
---

I've been wanting to start a blog dedicated to my attempts/progress at coding for quite awhile now.  Finally getting around to this thanks to github offering free hosting!  This was a natural fit since the blog is really just a way for me to keep track of random coding projects, which would likely have been kept on github anyways.

Most of my projects will probably be Python based, since I'm looking to become more proficient with the overall scientific Python based libraries.  This means you can expect lots of posts related to numpy, scipy, and matplotlib.  Aside from that we'll just see where this crazy project leads!


```python
%pylab inline
```

    Populating the interactive namespace from numpy and matplotlib



```python
import matplotlib
import matplotlib.pyplot as plt
import numpy as np
```


```python
with plt.xkcd():
	
	x = np.linspace(0, 10)
	y1 = x * np.sin(x)
	y2 = x * np.cos(x)

	plt.fill(x, y1, 'red', alpha=0.4)
	plt.fill(x, y2, 'blue', alpha=0.4)
	plt.title("Hello World", fontsize = 30)
	plt.xlabel('???', fontsize = 18)
	plt.ylabel("Profit ($)", fontsize = 18)
    
plt.show()
```


![png](https://raw.githubusercontent.com/cullenhgn/cullenhgn.github.io/master/static/img/_posts/output_2_0.png)



```python

```