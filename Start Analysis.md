### Fridays 

##### 1- Working directory
First, make sure you have redirected the tem files to SCRATCH


```
export TMPDIR=/scratch/alpine/$USER/tmp
```

##### 2- Set up Node for Fridays 
During our Friday tutorial time only, we can use this node by first running the following command: *sintractive*
```
sinteractive --reservation=aneq505 --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

- For other days : *aintractive*
-You can change the time to be longer

```
ainteractive --time=01:00:00 --partition=amilan --nodes=1 --ntasks=2 --qos=normal
```

##### 3- always Purge then load  
```
module purge
# then load qiime
module load qiime2/2024.10_amplicon

```

##### 4- Make folders
