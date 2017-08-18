## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

:books: Same functionality. Better performance for you. :books:

Over the past few months, we've been improving Binder's architecture and infrastructure. We're retiring this repo as it will no longer be actively developed. Future development will occur under the [JupyterHub](https://github.com/jupyterhub/) organization.

* All development of the Binder technology will occur in the [binderhub repo](https://github.com/jupyterhub/binderhub)
* Documentation for *users* will occur in the [jupyterhub binder repo](https://github.com/jupyterhub/binder) 
* All conversations and chat for users will occur in the [jupyterhub binder gitter channel](https://gitter.im/jupyterhub/binder)

Thanks for updating your bookmarked links.

## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

---

# Example Binder with a Dockerfile

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-dockerfile)

A Binder-compatibible repository that contains its own `Dockerfile`.

Your `Dockerfile` just needs to extend from the [`base`](https://github.com/binder-project/binder-build-core/blob/master/images/base/Dockerfile) image for Binder.

In this example our Dockerfile installs the Julia language and  packages for use with with the Jupyter notebook. Just by adding these steps, we get a Binder that includes Julia as a kernel.
