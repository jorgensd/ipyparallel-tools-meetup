# IPyparallel Tools meetup

You can create a compatible environment by using the [environment.yml](./environment.yml)

```bash
conda env create -f environment.yml
conda activate mpi-tutorial
```

If you do not have conda locally on your system, you can use docker:
```bash
docker run -ti -v $(pwd):/root/shared -w /root/shared -name=dxipyparallel continuumio/miniconda3
```
and follow the instructions above    