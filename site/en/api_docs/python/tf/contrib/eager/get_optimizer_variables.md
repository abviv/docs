

page_type: reference
<style> table img { max-width: 100%; } </style>


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.eager.get_optimizer_variables

``` python
tf.contrib.eager.get_optimizer_variables(optimizer)
```



Defined in [`tensorflow/contrib/eager/python/saver.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.7/tensorflow/contrib/eager/python/saver.py).

Returns a list of variables for the given `tf.train.Optimizer`.

Equivalent to `optimizer.variables()`.

#### Args:

* <b>`optimizer`</b>: An instance of `tf.train.Optimizer` which has created variables
    (typically after a call to `Optimizer.minimize`).

#### Returns:

A list of variables which have been created by the `Optimizer`.