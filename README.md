# Example Binder with a Dockerfile

A Binder-compatibible repository that contains its own `Dockerfile`.

The file needs to extend from the [`base`](https://github.com/binder-project/binder/blob/master/images/base/Dockerfile) image for Binder.

In this example our Dockerfile installs the Julia language and  packages for use with with the Jupyter notebook. Just by adding these steps, we get a Binder that includes Julia as a kernel.