### Fridays 

##### 1- Working directory
First, make sure you have redirected the tem files to SCRATCH


```
export TMPDIR=/scratch/alpine/$USER/tmp
```

##### 2- Set up Node for Fridays 
```
sinteractive --reservation=aneq505 --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

- For other days 
```
ainteractive --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

##### 3- always Purge 
```
module purge

module load qiime2/2024.10_amplicon

```

##### 4- Make folders
