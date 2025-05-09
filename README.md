# fato2bit-quick
A docker build file to run fasta to 2-bit conversion without rootpermission ( G lib work around )

# Quickstart
To install simply build with the singularity recipe as follows

```
 apptainer build fato2bit-quick.sif singularity.recipe
```

To run the image

```
singularity exec fato2bit-quick.sif faToTwobit -h
```

