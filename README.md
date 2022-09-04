save below as local.yml

```yml
channels:
dependencies:
  - pip:
    - "jax[cuda]"
    - --find-links https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
```

and run below command

```bash
conda env update --file local.yml 
```
