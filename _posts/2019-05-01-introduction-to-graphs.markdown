---
layout: post
title: "Introduction to graph"
---

This post will give you a introduction about tensors in tensorflow. Tensorflow is a framework used to process tensors. But, what is a tensor?

Tensor, as defined in the tensorflow webpage, is a generalization of vector and matrices to highers dimensions. Tensorflow represents a tensor by a n-dimensional arrays of base datatypes.

As an example, the following code creates three tensor. The first one is a 1D dimensional tensor, the second one is a 2D dimensional tensors and the third one creates a 3D tensor.

{% highlight python %}

from __future__ import absolute_import
from __future__ import division
from __future__ import print_function

import numpy as np
import tensorflow as tf
{% endhighlight %}


 
