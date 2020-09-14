

Travis (.com)  branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=master)](https://travis-ci.com/githubfoam/podman-travisci)  

Travis (.com) windows branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=feature_windows)](https://travis-ci.com/githubfoam/podman-travisci) 

Travis (.com) macos branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=feature_macos)](https://travis-ci.com/githubfoam/podman-travisci) 

Travis (.com) kvm qemu branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=feature_kvm)](https://travis-ci.com/githubfoam/podman-travisci) 

Travis (.com) kubernetes branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=feature_kubernetes)](https://travis-ci.com/githubfoam/podman-travisci) 

Travis (.com) minikube branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=feature_kubernetes)](https://travis-ci.com/githubfoam/podman-travisci)

Travis (.com) rootless branch:
[![Build Status](https://travis-ci.com/githubfoam/podman-travisci.svg?branch=rootless)](https://travis-ci.com/githubfoam/podman-travisci) 

~~~~
The podman driver is another kubernetes in container driver for minikube. similar to docker driver.
The podman driver is experimental, and only supported on Linux and macOS (with a remote podman server).

https://minikube.sigs.k8s.io/docs/drivers/podman/

Linux
Docker - container-based (preferred)
KVM2 - VM-based (preferred)
VirtualBox - VM
None - bare-metal
Podman - container (experimental)
https://minikube.sigs.k8s.io/docs/drivers/

Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System. Containers can either be run as root or in rootless mode
https://podman.io/getting-started/installation.html

Buildah - a tool that facilitates building OCI container images.
https://buildah.io/


Podman Machine and Boot2podman
https://podman.io/blogs/2019/01/14/podman-machine-and-boot2podman.html

Machine lets you create Podman hosts on your computer. It creates servers with Podman on them, then configures the Podman client to talk to them.
https://github.com/boot2podman/machine

skopeo is a command line utility that performs various operations on container images and image repositories.
skopeo does not require the user to be running as root to do most of its operations.
https://github.com/containers/skopeo
~~~~
