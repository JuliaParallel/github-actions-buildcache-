# Spack buildcache for MPI.jl CI

This repository provides a [Spack OCI buildcache](https://spack.readthedocs.io/en/latest/binary_caches.html#oci-docker-v2-registries-as-build-cache) to be used in CI of [`MPI.jl`](https://github.com/JuliaParallel/MPI.jl) and other JuliaParallel projects.
This is based on [spack/github-actions-buildcache](https://github.com/spack/github-actions-buildcache).

You can see the [list of packages](https://github.com/JuliaParallel/github-actions-buildcache/pkgs/container/github-actions-buildcache) produced by this buildcache.

If you want to have more packages in this buildcache, add them to the [`spack.yaml`](./spack.yaml) file.
